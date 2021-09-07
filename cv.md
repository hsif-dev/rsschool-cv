# Ian Iusov

## Junior Frontend Developer
### Contact Information
phone: +7 (911) 843-59-36\
email: <hsif-dev@gmail.com>\
[GitHub][1]\
[Telegram][2]
___
### About me
*This section is under construction\
Check back soon*
___
### Skills
* HTML
* CSS
* JS Basics
* Git / GitHub
* Photoshop, Figma
___
### Code Example
###### [The Hashtag Generator][3]
Here's the deal:\

* It must start with a hashtag '#'.
* All words must have their first letter capitalized.
* If the final result is longer than 140 chars it must return 'false'.
* If the input or the result is an empty string it must return 'false'.
```
function generateHashtag (str) {
  if (str.trim().length === 0) {
    return false;
  }
  const wordList = str.split(' ');
  
  let result = '#';
  for (let word of wordList) {
    let capitalizeWord = word.charAt(0).toUpperCase() + word.slice(1);
    result += capitalizeWord;
  }
  
  if (result.length > 140) {
    return false;
  }
  return result;
}
```



[1]:https://github.com/hsif-dev
[2]:https://t.me/hsifananab
[3]:https://www.codewars.com/kata/52449b062fb80683ec000024