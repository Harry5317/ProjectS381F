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
- User Login:
  * Users can login with specify username and password.
  * Login information will be saved in Cookie.
- User Logout:
  * User can logout with clicking ```LOG OUT``` button.
- finddb() :
  * Server return the array of collection from MongoDB.
- finddb_para() :
  * Server return the specify collection base on type and item parameter from MongoDB.
- addDB() :
  * User can upload item onto specify collection in MongoDB.
- updateDB() :
  * User can update specify item on specify collection in MongoDB.
- deleteDB() :
  * User can delete specify item on specify collection in MongoDB.

## 2. package.json :

  
