# Easy.DB


<img src="https://coursework.vschool.io/content/images/2016/04/json-banner-750x220.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

<br><br><br><br><br><br><br><br>

## Setup
<br>

> First we need to install the package!
<br><br>

> For npm use
```txt
npm install easy.db
```
<br>

> For yarn use
```txt
yarn install easy.db
```
<br><br>

> Now we need to setup our variables and call the package

```javascript
const Database = require('easy.db')
const db = new Database('json-file-name-here')
```
<br><br><br>

## Example
<br>

```javascript
const Database = require('easy.db')
const db = new Database('./src/database.json')
```

<img src="https://cdn.discordapp.com/attachments/854934272502136913/897704166242275328/unknown.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
<br><br><br><br><br>

> I do not own the JSON banner at the top all credit for that goes to [https://coursework.vschool.io/jsons-deli/](https://coursework.vschool.io/jsons-deli/)