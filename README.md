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
Make the config directory to store your secrets information and variables used in the app within the root folder of this app

```sh
$ mkdir config
```
```
Paste the following variables and save.
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
