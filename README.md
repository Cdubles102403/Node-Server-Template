# NODE SERVER TEMPLATE

## Desctiption

Web app for the 2021-2022 BPA web app challenge.

## Installation

Once downloaded, you can use a package.json script to setup,install and run the server. this must be done in a termianal that has openSSL such as git bash. This can also be run in VScode using the internal terminal(CTRL + SHIFT + ~). you can then change the terminal to git bash.
```bash
npm run make
```


## Usage

If you have already downloaded the nessesary packages and made the proper files for SLL you can start the server using the following command.

```bash
node server
```

To start in testing mode, use the following command.

```bash 
npx nodemon server.js
```
This will start the server in test mode, so every time you hit Save it will reload the server.
once the server has started you can view the webpage at
```https://localhost:443```.
**When navigating to the webpage you may encounter a page saying that the SSL certs are invalid, this is because they are self signed. you can get past this by pressing advanced >proceed anyway.**

To login using the admin accounts navigate to 
```https://localhost/adminLogin.html```.
and sign in using ```username:admin and password: Admin100``` 
**using the admin account to sign up for events and seats will cause problems**
