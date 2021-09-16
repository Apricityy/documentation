# LoadCommands 
> ```js
> A Custom Handler To Load/Update Commands
> ```
## Usage
>```ts
> const loader = new LoadCommands(client:Bot,AddThisToClass? : boolean)
>```
## Example 
>```js
>const Aoijs = require('aoi.js')
>
>const bot = new Aoijs.Bot({
>     prefix:".", //Your Bot Prefix
>     token:"Your Bot Token Here", //Your Bot Token
>     intents:"all" //Intents Your Bot Requires 
>     })
>
>const loader = new Aoijs.LoadCommands(bot)
>loader.load(bot.cmd,'./commands/')
>```
