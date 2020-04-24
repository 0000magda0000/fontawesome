this is a basic rails app. its a database with articles, created by following this [tutorial](http://railsgirls.com/files/vienna/tutorial_1.html)

* I have installed font awesome with $ yarn add @fortawesome/fontawesome-free in the terminal.

* I have added the following to the gemfile:   
 gem 'font_awesome5_rails'

* I have added the following to application.scss: 

 @import 'font_awesome5_webfont';
 
 @import 'font_awesome5.css';
 
 $fa-font-path: '@fortawesome/fontawesome-free/webfonts';
 
 @import '@fortawesome/fontawesome-free/scss/fontawesome';
 
 @import '@fortawesome/fontawesome-free/scss/solid';
 
 @import '@fortawesome/fontawesome-free/scss/regular';
 
 @import '@fortawesome/fontawesome-free/scss/brands';
 
 @import '@fortawesome/fontawesome-free/scss/v4-shims';
 
 
* I have added the following to application.js:

  import "@fortawesome/fontawesome-free/js/all";
  
* I have run bundle install in terminal.

**for the html.erb code see app/views/articles/index.html.erb**
