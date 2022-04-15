A movie ticketing system based on SpringBoot's front-end and back-end separation

introduce
The front-end and back-end movie projects of the SpringBoot+SpringSecurity+MyBatis-Plus framework, the front-end uses vue+element ui, and the back-end SpringBoot. The front desk mainly includes functions such as screening movies according to genres and regions, searching for movies, popular lists, publishing events, posting messages, purchasing movie tickets, selecting seats online for movies, my shopping cart, and my order. The background mainly includes the functions of adding, deleting, checking and modifying films, filming of films, management of posters, management of users and employees, etc.

demo video
A movie ticketing system based on SpringBoot's front-end and back-end separation
Software Architecture
Front-end and back-end separation projects
about
The api directory is the Spring boot project code
The vue-admin directory is the website management background code
The front-end code of the website is in the vue-app directory
The vue-worker directory is the website customer service code


A. The project is hosted on Github, and the account of the hoster is XXXXX and XXXX. If you need to get access to the whole project, you can log in with my account.

B. The basic programming language is Java 11. It is used for back-end programming. Meanwhile, the back-end frame is Springboot.

C. For the Front-end programming, the languages ​​are HTML & CSS and Javascript. The front-end frame is Vue.



The diagram below represents versions of language and frameworks:

Java 11
IntelliJ IDEA 2021.3.3
Navicat Premium 15.0.28
Apache-maven 3.8.5
Swagger 2.9.2
Jwt 0.9.1
mybatis-plus 3.4.2
fastjson 1.2.73
Springboot 2.4.2
Vue 2.6.11
axios 0.21.1
element-ui 2.15.0
vur-router 3.2.0
Node.js 14.17.0
The database is Mysql 8.0.28. There are 17 tables that have been created. Meanwhile, the main key and foreign are both defined. The relationships between these tables are clearly defined.
This project is a Web application, so it should be run on browsers, such as Chrome, Firefox, Microsoft Edge, etc. Chrome is highly recommended.
So far, this project is just on iteration 1, so there is no payment for this project.
In Vue-admin file, you need to follow these steps:

npm install
npm run serve
npm run build
After running the second step, the URL will be shown. Clicking the URL to jump to the website.
