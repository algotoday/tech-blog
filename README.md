
<h1 align="center">Tech Blog 👋</h1>
  
![badge](https://img.shields.io/badge/license-Open-brightgreen)<br />

## Description
A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well.

## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Documentation](#Documentation)
- [License](#license)
- [Contributing](#contributing)

## Usage
First clone this repository into your local repository, then make sure that you have a mysql account, here's a <a href='https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide'>link</a> to help you set up mysql if needed. After make sure you're in the root of the repository, then open the command line and run `npm i`. After that in the root of the directory create a file named `.env` and in that file write 3 lines: `DB_NAME='tech_blog_db'`, `DB_USER ='<YOUR MYSQL USERNAME>'`, and `DB_PW ='<YOUR MYSQL PASSWORD>'`.
In the command line run `mysql -u <YOUR MYSQL USERNAME> -p`, then enter your password. After you've successfully logged in, run `source db/schema.sql` then `quit;`. After you'll need to seed the data so in the command line run `node seeds`. After this you can run `node server.js` and head to the local host port in the browser or head to an API design platform like Insomnia and test the CRUD operations in different routes.

## Documentation
Live Deployed app: <a href='https://agile-earth-64002.herokuapp.com'>View Application</a>
![Screenshot (39)](https://user-images.githubusercontent.com/100015338/173255282-88e184dd-3fb0-4f1c-8a26-1cd380941a6c.png)


## License
![badge](https://img.shields.io/badge/license-Open-brightgreen)
<br />
This application is covered by the Open license.
<br />
Link to the <a href='https://www.google.com/search?q=Open+license'>Open license</a>

## Contributing
Tony Jones



GitHub: [algotoday](https://github.com/algotoday)

    
