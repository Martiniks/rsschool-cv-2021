##Oleg Sokolovsky

###Contact information:
* **Location:** Grodno, Belarus
* **Phone:** +375 29 315-82-99
* **Email:** martiniks.so@gmail.com
* **GitHub:** Martiniks
* **LinkedIn:** https://www.linkedin.com/in/oleg-sokolovsky/

###About Myself:
__Highly motivated junior web developer with strong self-organizing and time management skills__
__I like to write code and see the result of my work.__
__My goal is to gain new knowledge in front-end development.__

###Skills and Proficiency:
* *Languages:*
  * JavaScript (Basic)
  * PHP (Basic)
  * HTML 
  * CSS 
  * Visual Foxpro
* *Technologies/APIs/, Methodologies:*
  * CSS/CSS3
  * Git, Bitbucket, GitHub
  * Typescript
  * Angular (v.11 and above)   
  * HTML5
  * Bootstrap4
  * Angular Material 
* *Tools, application platforms and other*
  * MS Office 
  * Online Google Office
  * PHPStorm
  * Sublime Text,
  * Figma  
  * Jira Software
  * Windows (95,98,2000,XP,7,10)
  * Linux (Ubuntu)

###Code example:

```javascript
function revrot(str, sz) {
  if (sz <= 0 || str == '' || sz > str.length) {
    return 0;
  }
  let i = 0;
  let arr = [];
  while (sz <= str.length) {
    arr[i] = str.slice(0, sz);
    str = str.slice(sz);
    i = i + 1;
  }
  return arr.map(elem => {
    test = elem.split('').reduce((sum, e) => sum + e * e, 0);
    if (test % 2 == 0) {
      return elem.split('').reverse().join('');
    }
    return elem.slice(1)+elem[0];
  }).join('');
}
```

###Education and courses:
* **__Yanka Kupala State University of Grodno: 1992-1997__**
  * __Bachelor's Degree, Mathematic. Teacher of Mathematics and Physics.__
* **JavaScript https://learn.javascript.ru/**
* **TypeScript https://metanit.com/web/typescript/**

###Experience:
**__Junior FrontEnd Developer.__** 
__I have experience in JS+TS+Anular and Frontend development in currently working project.__

###Languages:
* Russian - Native
* Ukrainian - А1 – начальный
* Polish - В1 – средний
* English -  A2 (I have some speaking practice in Germany)

