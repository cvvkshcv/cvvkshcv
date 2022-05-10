### Hi there 👋

<!--
**cvvkshcv/cvvkshcv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

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
