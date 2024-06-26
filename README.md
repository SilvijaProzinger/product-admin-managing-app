# Product & Admin Managing App

This is a web app made for managing the product list and admin users. It's made by Angular and styled with SCSS. It also uses Firebase for authorization.

### GIF preview:

![](https://github.com/SilvijaProzinger/Product-and-Admin-Managing-in-Angular/blob/master/src/assets/gif-preview.gif)

## Features

* Users can login with admin or regular user credentials 
* Users can only view product list if they're logged in
* Users can add a new product to the list
* Users can mark a product as favorite and view favorite products
* Admin users can edit or delete a product
* Admin users can add new admins

## TO-DO 

This is a list of things that should've been completed along with additional features that would've made this app production ready. 

* Admins can view admin list 
* Admins can edit existing admin users 
* Admins can delete other admins

### Potential improvements

* Firebase config file and credentials are not pushed to git by default and are shared with trusted users.
* Login should persist in session storage
* The app should use data from a real API instead of dummy data

## How to run

* Open Node.js command prompt 
* Install angular CLI globally using `npm install -g @angular/cli`
* Download or clone the repository
* Go to the local repository folder by using command `cd [repository-name]`
* Run `npm install` to install required project dependencies
* Run `ng serve` to open the project locally on your browser. The localhost url is `http://localhost:4200/`

## Login credentials:

This project uses Firebase for authorization. There are two users currently created for this environment, the admin user and the regular user. The credentials are:

Admin:
```
Username: admin@example.com
Password: Pswrd&_123
```

User:
```
Username: user@example.com 
Password: Loop456-%
```