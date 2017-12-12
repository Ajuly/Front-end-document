###  npm 和 yarn 的比较

| 命令      |    npm  |yarn  |	
| :-------- | :--------| :-- |
|1.默认安装     | npm install |  yarn (install)   |
|2.安装包     |   npm install taco --save |  yarn add taco   |
|     |   npm install taco --save-dev |  yarn add taco --dev   |
|     |   npm install taco --global |  yarn global add taco   |
|3.卸载     |   npm uninstall taco --save |  yarn remove taco  |
|4.更新    |   npm update --save |  yarn upgrade  |
|   |   npm install taco@latest --save |  yarn add taco  |
|5.常用命令   |   npm init |  yarn init  |
|   |   npm link |  npm link  |
|   |   npm publish |  yarn publish  |
|   |   npm run |  yarn run  |
|   |   npm cache clean |  yarn cache clean  |
|   |   npm login |  yarn login (logout 同理)  |
|   |   npm test |  yarn test  |
| yarn独有的命令  |    |  yarn licenses ls —— 允许你检查依赖的许可信息。 |
|   |    |  yarn licenses generate —— 自动创建依赖免责声明 license。 |
|   |    |  yarn why taco —— 检查为什么会安装 taco，详细列出依赖它的其他包 |
| npm独有的命令   |  npm xmas === NO EQUIVALENT  |   |
|   |  npm visnup === NO EQUIVALENT  |   |