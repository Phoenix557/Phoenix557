```js
async function better() {
  const Phoenix = require('200iq.js');
  
  let doing = ['Programming', 'Eating', 'sleeping', 'Watching Netflix', 'Playing Rust'];
  let langs = ['JavaScript', 'NodeJS', 'TypeScript', 'Markdown'];
  let tools = ['Discord', 'Windows', 'GoogleChrome', 'GitHub'];

  let practice = await Phoenix.randomize(doing, langs, tools);

  let Intro1 = `Hey fellas! I'm Phoenix- In highscool. Working on my programming skills `;
  let Intro2 = `I like to play games, program, watch movies, or spend countless hours in a Discord call with friends`;

  console.log(Intro1, Intro2));
}
exports.phoenix = better;
```

