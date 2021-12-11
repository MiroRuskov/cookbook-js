# cookbook-js
## Table of Contents

* [Installation](#installation)
* [Application Structure](#application-structure)
* [About the Project](#about-the-project)
* [Website](#website)


## Installation

1. Clone the repo
```sh
git clone https://github.com/MiroRuskov/cookbook-js.git
```
2. Install NPM packages
```sh
npm install
```
3. Run Application
```sh
npm run app
```
4. Run Server
```sh
npm run server
```
5. Go to
```sh
http://localhost:3000/
```

## Application Structure

### Public Part
Public part is visible for the guests without authentication. They have access to home page, product page and user login and register forms.

### Private Part
Registered users have personal area in the web application accessible after successful login. They have access to user profile, shopping cart and wishlist pages.
Only admin have access to admin section.


## About The Project

The project is an online recieps for cooking. Тhe home page shows Recently added recipes and basic information about them. Тhe catalog page shows all product information. Users can register and log in, after which they have access to their profile page. Еach user has their own recieps cart and can add and remove products.

## Website

![CookBook](https://cookbook-js.github.io/)
