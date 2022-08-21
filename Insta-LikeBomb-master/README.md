# Instagram bot - LikeBomb ❤️ 💣

## Instagram bot to like all posts of a given user

[![PPTR badge](https://img.shields.io/badge/powered%20by-puppeteer-46aef7.svg)](https://pptr.dev) [![Node badge](https://img.shields.io/badge/node-10.6.0-brightgreen.svg)](https://nodejs.org/en/)

![rolalike](https://user-images.githubusercontent.com/8108361/46649458-f51c6800-cb4d-11e8-8abe-1c9f2774bf7e.gif)

## Steps to use the bot

1. Download Node.js >= 10.6.0 and install it
2. Git clone or Download zip
3. Run `npm install` inside Insta-LikeBomb folder
4. Rename `.env_temp` to `.env`
5. Open .env file and write your credentials in `INSTA_USERNAME` (without @ symbol) and `INSTA_PASSWORD`
6. Write your friend's Instagram username (without @ symbol) to like all his/her posts
7. Run `npm run start` to start the bot

### Tips: hide browser

Replace puppeteer browser option to this:

```javascript
const browser = await puppeteer.launch({
    headless: true
});
```

