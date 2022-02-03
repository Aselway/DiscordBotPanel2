# Guide

```shell
git clone https://github.com/jareer12/DiscordBotPanel.git
```

```shell
cd DiscordBotPanel
```

```shell
npm install pm2 -g
```

1. Run `npm install`
2. Run `node .`, and wait for initialization to complete(must). If you stop while initialization, you will have to do it all over again.
3. Run `node .`, and now your panel is running on a random port(can be changed).

## Customize

1. After intializing, You can edit `.env` to change ram usage, ssd usage, admin pass, admin user, etc.
2. To change the UI update `tailwinds.config.js` and run `npm run tailwinds`.

If any problems occur, like shell spam, or you can't delete the app folder. Run `taskkill /f /im node.exe`, this will kill all node processes on the machine.

![Image](./BaseTemplate/home.png)
![Image](./BaseTemplate/home-dark.png)
![Image](./BaseTemplate/file-editor.png)
![Image](./BaseTemplate/dark-file-manager.png)
