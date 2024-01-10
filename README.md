# 撸毛脚本

## Qna3 Ai

[Qna3 Ai](https://qna3.ai/)

### Quick start

``` bash
# .env
WALLET_PRIVATEKEY=0x6623c5f41a4b295f5fadc4069a05c5d4166a558ba0a7c62e0e781bd0c1d325b3
```

```js
const wallet = new Wallet(process.env.WALLET_PRIVATEKEY);
const qna3 = new Qna3(wallet, 206);

// 登录(第一次登录就需要绑定邀请码)
await qna3.login("78yppP2H");

// 每日签到
await qna3.checkIn();

```

``` bash
pnpm install

pnpm run start
```

## Auth by

0x0fBA766CBBFFB95831be9F4e99c721Ca47777777
