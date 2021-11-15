```js
aysnc fuction EpicGamer() {
  const Phoenix = require('200iq.js');
  const chalk = require('chalk');
  
  let doing = ['Gaming', 'Programming', 'Sleeping'];
  let languages = ['JavaScript', 'HTML5', 'NodeJS', 'Markdown'];
  let tools = ['Windows', 'linux', 'Dicord', 'Github'];
  
  let working  = await Phoenix.randomize(doing, languages, tools);
  
  let Phoenix_Story1 = `Hello! I am a junior in highshool, I have a dream of joining the NYPD after college. I do this coding stuff for fun! `;
  let Phoenix_Story2 = `I spend a lot of my time playing games with my friends, or working on the many projects that I have started! `;
  let Phoenix_Story3 = `Right now I'm ${working[0]}, white practicing ${working[1]} on ${working[2]}`;
  
  console.log(chalk.red(Phoenix_Story1, Phoenix_Story2, Phoenix_Story3));
  }
  
  module.exports = ()
