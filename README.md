# Homantin Plaza Customer Service System
This Website is designed for Customer Service in Homantin Plaza.
Our Website Link: [Click Me](https://projects381f-1076834146749.asia-east1.run.app/)

==================================================================================
## Hello World! We are Group 36!
### Our Developers:
- [13017740] Ng Man Hei
- [13077944] Wong Kwok Ching
- [13137889] Lee Chung Ho
- [13138794] Hui Lin Fung
- [13134144] Leung Yu Ching

==================================================================================
### Front-end Development:
- Figma (UI design)
- HTML (Building the structure of the webpage)
- CSS (Achieve web page UI design)
- JavaScript (Achieve web page interaction

### Back-end Development:
- Node.js (Server-side scripting)
- EJS (Template engine)
- MongoDB (Database)

### Code Hosting System:
- GitHub (Version control and collaboration)
- Google Cloud (Online Server)

==================================================================================
## File Path:
```
ProjectS381F-main/
├── public/
│   ├── css/
│   │   ├── ClaimCss.css
│   │   ├── LoginCss.css
│   │   ├── main.css
│   │   ├── messageCss.css
│   │   ├── NewsCss.css
│   │   ├── ReportiostCss.css
│   │   └── ShopCss.css
│   │
│   └── graphics/
│       ├── background.png
│       ├── edit.png
│       ├── lock.png
│       ├── logo.svg
│       ├── logo2.svg
│       ├── user.png
│       ├── warning.png
│       ├── white.png
│       └── x.png
│
├── views/
│   ├── Claim.ejs
│   ├── login.ejs
│   ├── LostList.ejs
│   ├── message_confirm.ejs
│   ├── message_showing.ejs
│   ├── NewsPage.ejs
│   ├── Reportlost.ejs
│   ├── Shop.ejs
│   ├── ShopUpload.ejs
│   └── Update.ejs
│
├── README.md
├── server.js
├── package.json
└── package-lock.json
```

==================================================================================
# Project File Introduction:
## 1. server.js :
### Features :
- __User Login__:
  * Users can login with specify username and password.
  * Login information will be saved in Cookie.
- __User Logout__:
  * User can logout with clicking ```LOGOUT``` button.
- __finddb()__ :
  * Server return the array of collection from MongoDB.
- __finddb_para()__ :
  * Server return the specify collection base on type and item parameter from MongoDB.
- __addDB()__ :
  * User can upload item onto specify collection in MongoDB.
- __updateDB()__ :
  * User can update specify item on specify collection in MongoDB.
- __deleteDB()__ :
  * User can delete specify item on specify collection in MongoDB.

## 2. package.json :
### - __Dependencies__:
  * body-parser
  * cookie-session
  * ejs
  * express
  * express-session
  * express-formidable
  * mongodb
  * mongoose
  * path

## 3. public :
### - __css (Provide CSS webpage design for each page)__:
* ClaimCss.css
* LoginCss.css
* main.css
* messageCss.css
* NewsCss.css
* ReportiostCss.css
* ShopCss.css
### - __graphics (Provide Image design for different elements)__:
* background.png
* edit.png
* lock.png
* logo.svg
* logo2.svg
* user.png
* warning.png
* white.png
* x.png

## 4. views :
- Claim.ejs
- login.ejs
- LostList.ejs
- message_confirm.ejs
- message_showing.ejs
- NewsPage.ejs
- Reportlost.ejs
- Shop.ejs
- ShopUpload.ejs
- Update.ejs

==================================================================================
# Cloud-based server URL:
https://projects381f-1076834146749.asia-east1.run.app/

==================================================================================
# Operation guides:
## Login Page:
__Input correct account and password in order to login.__

<img src="https://github.com/Harry5317/PhotoOfPage/blob/10a56ef289c2441183b9a0f2890c00a201dd7ee3/Mainpage.png" width="600" height="350">

__Message__: ```Incorrect account or password``` will be shown if wrong account or password were inputed.

<img src="https://github.com/Harry5317/PhotoOfPage/blob/10a56ef289c2441183b9a0f2890c00a201dd7ee3/error%20account.png" width="300" height="350">
