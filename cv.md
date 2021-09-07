# Ian Iusov

### Junior Frontend Developer

___
### Contact Information
phone: +7 (911) 843-59-36\
email: <hsif-dev@gmail.com>\
[GitHub][1]\
[Telegram][2]

___
### About me
*This section is under construction\
Check back soon...*

___
### Skills
* HTML
* CSS
* JS Basics
* Git / GitHub
* Photoshop, Figma

___
### Code Example
#### [The Hashtag Generator][3]
Here's the deal:

* It must start with a hashtag `#`.
* All words must have their first letter capitalized.
* If the final result is longer than 140 chars it must return `false`.
* If the input or the result is an empty string it must return `false`.

```javascript
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

___
### Courses
1. [Code Basics JavaScript][4] `completed`
1. [HTML Academy][5] `in progress`\

![Codewars][6]

___
### Language
* **Russian** - Native 
* **English** - B1 Intermediate


[1]:https://github.com/hsif-dev
[2]:https://t.me/hsifananab
[3]:https://www.codewars.com/kata/52449b062fb80683ec000024
[4]:https://ru.code-basics.com/languages/javascript
[5]:https://htmlacademy.ru/study
[6]:https://www.codewars.com/users/hsifananab/badges/large
