
# Zally-Tk

Uma breve descrição sobre o que esse projeto faz e para quem ele é

## Instalaçao
```bash
npm i zally-tk
```
## Exemplos
```js
const getTikTokUser = require('zally-tk');

async function main() {
  const userInfo = await getTikTokUser('exampleuser');
  console.log(userInfo);
}

main();
```

```js

const getTikTokUser = require('zally-tk');

async function main() {
  const userInfo = await getTikTokUser('exampleuser');
  console.log(userInfo.username)
  console.log(userInfo.likesCount)
  console.log(userInfo.profileImage)
  console.log(userInfo.followingCount)
}

main();
```


https://www.npmjs.com/package/zally-tk
