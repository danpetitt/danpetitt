<h2> Hi, I'm Dan Petitt! 👋</h2>

<p>
<em>
Senior Software Engineer at <a href="http://pa.media">PA Media Group</a> <img src="https://pa.media/wp-content/themes/pa-site/favicon/favicon-16x16.png" style="width:16px;height:16px;">

Co-founder of <a href="http://digiguide.tv">digiguide.tv</a> <img src="https://digiguide.tv/i/favicon.png" style="width:16px;height:16px;">
</em>
</p>

[![Twitter: coderanger](https://img.shields.io/twitter/follow/coderanger?style=social)](https://twitter.com/coderanger)
[![Linkedin: danpetitt](https://img.shields.io/badge/-danpetitt-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/danpetitt/)](https://www.linkedin.com/in/danpetitt/)
[![GitHub danpetitt](https://img.shields.io/github/followers/danpetitt?label=follow&style=social)](https://github.com/danpetitt)


**A little more about me...**

```javascript
const dan = {
  pronouns: 'he' | 'him',
  code: ['C#', 'Typescript', 'Javascript', 'HTML', 'CSS', 'C++', 'C'],
  frameworks: ['.net', '.net core', 'NodeJS'],
  platforms: ['Azure', 'AWS'],
  databases: ['SQL Server', 'mySQL'],
  devOps: ['Docker', 'Serverless'],
  tools: ['Jest', 'Cypress', 'Swagger'],
}
```
---

# My GitHub contributions as a Game of Life

[![GitHub Game of Life](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub4life.herokuapp.com%2Fethomson.gif%3Fz%3D6&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=8We9As7SuQiSSyJ9L7gcIb1cb3vXk6laXgD%2B5CdDRUc%3D&amp;reserved=0)](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub4life.herokuapp.com%2Fethomson&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=81JMSoXNtMW4nlRr%2FSUS1GKuUq8vTdjZeWr%2B0eIRz7M%3D&amp;reserved=0)

(Be sure to click on it for the infinite scrolling version.)

### What's this?

This takes my GitHub contribution graph and uses it as the initial state for [Conway's Game of Life](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FConway%2527s_Game_of_Life&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=MItHWqqCimYAsddb2VQ7WJGYrQHABRJStlYN59Wrark%3D&amp;reserved=0), a popular cellular automaton that is often built by beginning software developers as an easy-to-implement but interesting piece of software.

Conway's Game of Life only defines two initial states for cells, but there are [multi-color variants](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fconwaylife.com%2Fref%2Fmniemiec%2Fcolor.htm&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=UvxUCHDqvX5Axz%2F%2BBfD0cGdIc5oW%2Be97MS1gD%2BLFyO8%3D&amp;reserved=0).  This is a variant of "Quad Life" (chosen because the GitHub contribution graph has four colors that represent the intensity of contributions for a given day): in the typical Game of Life rules, a graph with a lot of contribution would die out in the first iteration (because the cells would be overcrowded), which seems to punish those with a lot of contributions, giving them a boring Game of Life.  Intead, this variant "decays" the level of contribution, so cells will fade away instead of dying immediately.

### How does it work?

This uses a JavaScript library called [contributions](https://eur02.safelinks.protection.outlook.com/?url=https%3A%2F%2Fnpmjs.com%2Fcontributions&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=sCJTZ2OI9WIySZZKMSeUq%2FEQ%2Fe1VaDnhnUPKxxhbHhg%3D&amp;reserved=0) to create a data structure with a GitHub contribution graph, and uses that as the initial state for another JavaScript library called [dat-life](https://eur02.safelinks.protection.outlook.com/?url=http%3A%2F%2Fnpmjs.com%2Fdat-life&amp;data=04%7C01%7CDan.Petitt%40pamediagroup.com%7Ccabf556684124144548e08d89c9fd122%7C8aea8e714fae4a2b83fc4d84bc2355a2%7C0%7C0%7C637431557509800916%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=P2%2BD77Uth7%2FsdgZBdeP7bUYH44n2S%2FoHch4NlDfWOzU%3D&amp;reserved=0).

---

![Dan's github stats](https://github-readme-stats.vercel.app/api?username=danpetitt&count_private=true) [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=danpetitt&layout=compact)](https://github.com/danpetitt/)

---
