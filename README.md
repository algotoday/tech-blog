
Tech Blog
  

## Description
![description mvc](https://user-images.githubusercontent.com/100335717/184428709-6878075c-9ac1-445e-abac-e4c4f05361a6.png)



## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Documentation](#Documentation)
- [Contributing](#contributing)

## Usage
First clone this repository into your local repository, then make sure that you have a mysql account, here's a <a href='https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide'>link</a> to help you set up mysql if needed. After make sure you're in the root of the repository, then open the command line and run `npm i`. After that in the root of the directory create a file named `.env` and in that file write 3 lines: `DB_NAME='tech_blog_db'`, `DB_USER ='<YOUR MYSQL USERNAME>'`, and `DB_PW ='<YOUR MYSQL PASSWORD>'`.
In the command line run `mysql -u <YOUR MYSQL USERNAME> -p`, then enter your password. After you've successfully logged in, run `source db/schema.sql` then `quit;`. After you'll need to seed the data so in the command line run `node seeds`. After this you can run `node server.js` and head to the local host port in the browser or head to an API design platform like Insomnia and test the CRUD operations in different routes.

## Documentation
Live Deployed app: [<a href='https://agile-earth-64002.herokuapp.com'>View Application</a>](https://frozen-spire-06364.herokuapp.com/)


![tech_blog](https://user-images.githubusercontent.com/100335717/184427807-52a2de13-9e8e-4f10-9948-c756c3f147c6.png)



## Contributing
Tony Jones



GitHub: [algotoday](https://github.com/algotoday)

    
