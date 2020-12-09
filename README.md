# Mail_sender

### Description
This is a mail sender node application which uses the  nodeMailer node module. You need to turn on 3rd party permission for your google account through which you will be sending mail. <br>
### To turn on the permission go [here](https://myaccount.google.com/lesssecureapps?pli=1&rapt=AEjHL4PtozVxOBHy3D-bonWmshJV8SVZ7NUiy0KB9UhkDC2j1NrMDzmIbAIMKXsrhHXw0n8DVCWcYiPFb6cek07DU5EiBCabvw)
 
### Languages and Tools
<br>
<img align="left" alt="javascript" width="26px" src="javascript.png" />
<img align="left" alt="nodejs" width="26px" src="nodejs.png" />
<img align="left" alt="express" width="26px" src="express.png" />
<img align="left" alt="css" width="26px" src="css.png" />
<img align="left" alt="handlebars" width="26px" src="handlebar.png" />
<img align="left" alt="VS Code" width="26px" src="vscode.png" />
<br>

### Change code for self usage
Find this block of code and read the comments to personalize.
```node
var transporter = nodemailer.createTransport({
        service: 'gmail',
        auth: {
          user: 'beingsemicolons@gmail.com', //Set your sender email address. make sure in this id the google persmissions are enabled.
          pass: '********', //Give your original mail id password for authentication
        },
      });
```

### Checkout out our app [here](https://sheltered-plains-91495.herokuapp.com/)

### Demonstration
This is the interface of our Node App<br><br>
<img src="desktop view.jpg" alt="Interface" height="100%" width="100%">

### Developed by
[Binayak Sadangi](https://github.com/binayaksadangi)<br>
[Ankush Mishra](https://github.com/ankush0939)
