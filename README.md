# nodecontactform
Another simple Contact form app I made while learning nodeJS, using bootstrap, express-handlebars for templating, and nodemailer for sending the emails. 

### Installation
```sh
$ git clone https://github.com/bosundare/nodecontactform.git
```
Install the dependencies

```sh
$ cd nodecontactform
```
```sh
$ npm install
```
Make a secret.js file in the /config directory to store your variables. 

```sh
$ touch config/secret.js
```
```
Paste the following variables into config/secret.js file and save.
module.exports = {
    host: 'your_email_server',
    secret: 'Password_to_inbox_user', 
    user: 'email_of_user', 
    from: '"your_from_email',
    to: 'email_address_you_want_to_recieve_messages'
  }
 ```

Run app

```sh
$ npm start
```

```sh
Visit localhost:3000 to view the app.
```
