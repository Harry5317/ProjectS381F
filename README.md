# Homantin Plaza Customer Service System
This Website is designed for Customer Service in Homantin Plaza.
Our Website Link: [Click Me](https://projects381f-1076834146749.asia-east1.run.app/)

==================================================================================
## Hello World! We are Group 36!
### Our Developers:
- __[13017740] Ng Man Hei__
- __[13077944] Wong Kwok Ching__
- __[13137889] Lee Chung Ho__
- __[13138794] Hui Lin Fung__
- __[13134144] Leung Yu Ching__

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
## *Login Page*:
__Input correct account and password in order to login.__
Account List:
```
	{name: 'cs01', password: '123', type:'customerService', username :'Tommy'},
	{name: 'cs02', password: '123', type:'customerService', username :'Harry'},
	{name: 'cs03', password: '123', type:'customerService', username :'Vincent'},
	{name: 'cs04', password: '123', type:'customerService', username :'Dainel'}, 
	{name: 'cs05', password: '123', type:'customerService', username :'Jimmy'} 
```
<img src="https://github.com/Harry5317/PhotoOfPage/blob/10a56ef289c2441183b9a0f2890c00a201dd7ee3/Mainpage.png" width="600" height="350">

__Message__: ```Incorrect account or password``` will be shown if wrong account or password were inputed.
<img src="https://github.com/Harry5317/PhotoOfPage/blob/10a56ef289c2441183b9a0f2890c00a201dd7ee3/error%20account.png" width="300" height="350">

----------------------------------------------------------------------------------
## *Accounts*:
__Using different account to login will show up with different user name.__
- Login with name: ```cs01```
<img src="https://github.com/Harry5317/PhotoOfPage/blob/f4aba031301e608c6cd85325b1d5dcf4bf9ce34f/BlackTommy.png" width="1000" height="50">

- Login with name: ```cs02```
<img src="https://github.com/Harry5317/PhotoOfPage/blob/f4aba031301e608c6cd85325b1d5dcf4bf9ce34f/Harry.png" width="1000" height="50">

### Feel free trying to login with other account !!!
----------------------------------------------------------------------------------
## *Mall News Page*:
- __Showing all mall news from MongoDB collection: ```newsTitleData```__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/1f281cfdda590ee5176956ed0ec5d242d92d0ff0/news.png" width="1000" height="350">

- __Providing ```DELETE``` Button for user to delete news from MongoDB collection: ```newsTitleData```__
- __It will redirect to message_confirm page__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/abc471f8f24fda76b06c837a4f68206256d89c88/comfirm%20delete.png" width="300" height="150">

- __After clicking ```Confirm``` will redirect to message_showing page and delete the news__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/abc471f8f24fda76b06c837a4f68206256d89c88/deleted.png" width="300" height="150">

- __After clicking ```Finish``` will redirect back to main page Mall News Page__

----------------------------------------------------------------------------------

## *Shop Information Page*:
- __Showing all shop information from MongoDB collection: ```shops```__
- __Providing ```DELETE``` Button for user to delete news from MongoDB collection: ```newsTitleData```__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/ececd7b7f36b6617cafea8d03dcd372ee161165c/shop.png" width="1000" height="320">

- __Providing ```Search Bar```and ```ENTER``` Button for user to search shop from MongoDB collection: ```shops``` with Shop NO.__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/ececd7b7f36b6617cafea8d03dcd372ee161165c/shop%20search.png" width="1000" height="280">

- __Providing ```UPLOAD SHOP +``` Button for user to add shop to MongoDB collection: ```shops```__
- __It will redirect to ShopUpload page__
<img src="https://github.com/Harry5317/PhotoOfPage/blob/abc471f8f24fda76b06c837a4f68206256d89c88/UploadShop.png" width="600" height="350">


## 
==================================================================================
# API Keys:
- ## Shop APIs
	* Create New Shop Information: <br />
  ```curl -X POST -F "shop_no=321" -F "name=Trinkey Trove" -F "type=shop" -F "address=119" -F "open_time=08:00" -F "close_time=23:00" -F "status=closed" -F "phone=44444444" https://projects381f-1076834146749.asia-east1.run.app/api/shops/321```
	* Read Shop Informations (base on Shop NO.): <br />
 ```curl -X GET https://projects381f-1076834146749.asia-east1.run.app/api/shops/321```
	* Update Shop Informations (base on Shop NO.): <br />
 ```curl -X PUT -F "phone=99999999" https://projects381f-1076834146749.asia-east1.run.app/api/shops/321```
	* Delete Shop Informations (base on Shop NO.): <br />
 ```curl -X DELETE https://projects381f-1076834146749.asia-east1.run.app/api/shops/321```

- ## Claim APIs
  	* Create New Claim Item: <br />
   ```curl -X POST -F "claimId=321" -F "item=Phone" -F "color=Black" -F "date=24/08/2024" -F "pickUpPlace=G25" -F "status=Claimed" -F "picture=https://github.com/tommywkc/photo/blob/main/phone5.jpeg?raw=true" https://projects381f-1076834146749.asia-east1.run.app/api/claim/321```
	* Read Claim Item (base on Claim ID): <br />
 ```curl -X GET https://projects381f-1076834146749.asia-east1.run.app/api/claim/321```
	* Update Claim Item (base on Claim ID): <br />
 ```curl -X PUT -F "status=Storage room" https://projects381f-1076834146749.asia-east1.run.app/api/claim/321```
	* Delete Claim Item (base on Claim ID): <br />
 ```curl -X DELETE https://projects381f-1076834146749.asia-east1.run.app/api/claim/321```
