Hi 👋 My name is Vikash Cv
==========================

Full stack developer (Front end heavy)
--------------------------------------

*   🌍  I'm based in Bangalore
*   ✉️  You can contact me at [cvvkshcv@gmail.com](mailto:cvvkshcv@gmail.com)
*   🧠  I'm learning AWS, Datadog

### Skills
<p align="left">
                                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="Javascript" /></a>
                                <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="Typescript" /></a>
                                <a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a>
                                <a href="https://angular.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/angularjs-colored.svg" width="36" height="36" alt="Angular" /></a>
                                <a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a>
                                <a href="https://vuejs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/vuejs-colored.svg" width="36" height="36" alt="Vue" /></a>
                                <a href="https://redux.js.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/redux-colored.svg" width="36" height="36" alt="Redux" /></a>
                                <a href="https://getbootstrap.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/bootstrap-colored.svg" width="36" height="36" alt="Bootstrap" /></a>
                                <a href="https://babeljs.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/babel-colored.svg" width="36" height="36" alt="Babel" /></a>
                                <a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a>
                                <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a>
                                <a href="https://expressjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored.svg" width="36" height="36" alt="Express" /></a>
                                <a href="https://docs.nestjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nestjs-colored.svg" width="36" height="36" alt="NestJS" /></a>
                                <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="36" height="36" alt="MongoDB" /></a>
                                <a href="https://www.heroku.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/heroku-colored.svg" width="36" height="36" alt="Heroku" /></a>
                    </p>
                    
                  ### Socials
                  
                  
                <p align="left">
                          
                      <a href="https://www.github.com/cvvkshcv" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /></a>
                          
                      <a href="https://www.linkedin.com/in/cv-vikash-🐱%E2%80%8D💻-251309b5/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /></a>
                          
                      <a href="https://www.twitter.com/CvvkshcvV" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" width="32" height="32" /></a>
                          
                      <a href="https://www.youtube.com/c/uigems" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube.svg" width="32" height="32" /></a></p>### Badges<a href="https://github.com/cvvkshcv" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cvvkshcv&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>
                      
                      
```
const rows = document.getElementById('rows');
const cols = document.getElementById('cols');
const btn = document.getElementById('btn');
const result = document.getElementById('result');
btn.addEventListener('click', (e) => {
  e.preventDefault();
  const rowsNum = Number(rows.value || 5);
  const colsNum = Number(cols.value || 3);
  const resultArr = [];
  for (let i = 0; i < rowsNum; i++) {
    const rowResArr = [];
    for (let j = 0; j < colsNum; j++) {
      let num;
      if (j % 2 === 0) {
        num = (rowsNum * j) + i + 1;
      } else {
        num = (rowsNum * (j + 1)) - i;
      }
      rowResArr.push(`<span>${num}</span>`);
    }
    resultArr.push(`<div>${rowResArr.join('')}</div>`);
  }
  result.innerHTML = resultArr.join('');
});
```
