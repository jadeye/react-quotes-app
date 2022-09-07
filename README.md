# quotes-react-app

<p>This app collects quotes and allows to comment on those quotes!</p><br>
<p>It uses React, React-dom & React-Router-dom v5</p><br>
For this app to work you need to do the following things:<br>
1. Clone it<br>
2. npm install<br>
3. Get a Firebase Realtime Database<br>
After which you need to configure your FB_URL, so:<br>
Add a .env file at the root of you project.<br>
Add the following line to it:<br>
REACT_APP_FB_URL=YOUR FIREBASE REALTIME DATABASE URL<br> no Apostrophes needed!<br>
Your app should now function.<br>
Note that file: src >lib > api.js,<br>
Has your firebase URL call at line 1:<br>
const FB_URL = process.env.REACT_APP_FB_URL;<br>
