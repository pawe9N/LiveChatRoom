# Live Chat Room
This app was created for purpose of learning ASP.NET MVC, MSTest, Moq, SignalR library, C# and JQuery.

## Description of application
This application is a simple chat app, where random people can speak with each other. Each of users has its own avatar and username, which will be displayed next to its messages in chat subpage. Users can change their avatars and passwords in Account subpage. They can also see which of users was active for 3 minutes before in chat through ActiveUsers subpage. To sign up to this app, user has to be an adult, he must input 3-24 characters in username, at least 6 characters in password and his email can not be in database. After sign up, verification email with link will be sent. When user forgets his password, he can recall it with help ForgotPassword page. Chat, Account and ActiveUsers subpages can be displayed only for authorized users, who have gone through Login subpage.

## Getting Started

If you want to use this program, you have to download all files of this repository.
After that you have to change senderEmailData.json file in Content directory with your email data which are needed to send email messages to users:

```
{
	"email" : "Your email",
	"password" : "Your email password"
}
```

After that you will can open this application!

## Little demo with Gifs

- How to send messages?
<img src="https://i.imgur.com/fPR28J2.gif">

- How "Live Chat Room" works on several browsers? (on Chrome, Firefox and Edge)
<img src="https://i.imgur.com/PWjJs1K.gif">

- Simple registration
<img src="https://i.imgur.com/3Q2oHsX.gif">

- Forgot password
<img src="https://i.imgur.com/8uJoZU1.gif">

- Change avatar
<img src="https://i.imgur.com/GF3ExWp.gif">

- Reset password
<img src="https://i.imgur.com/ny0r1rn.gif">
