### sorcery-app
-------------

Hi there, 
I am ddeveloperr, fall in love with open source, ROR especially, and I build this app while I was learning about authentication in Rails using [Sorcery] (https://github.com/NoamB/sorcery) following [Site-point tutorial] 
(http://www.sitepoint.com/magical-authentication-sorcery/)

If you like it and if you are learning Ruby on Rails you can try it on your own mashine
after perform the following steps: 

1. Open the terminal
2. git clone https://github.com/ddeveloperr/sorcery-app.git
3. cd sorcery-app , 
4. Set your Gemfile to ruby '2.1.2'  AND gem 'rails', '4.2.1'
5. bundle install
6. rails server
7. Web app will be UP and running at your browser on http://localhost:3000/ 
8. Play with code, login, logout, hack it... Learning by doing is the best way to become a master! 

My working enviroment is Linux Ubuntu 15.04. Good luck.
 

[Sorcery] (https://github.com/NoamB/sorcery) is a stripped-down, bare-bones authentication library, with which you
can write your own authentication flow. It was built with a few goals in mind:

*   Less is more - less than 20 public methods to remember for the entire
    feature-set make the lib easy to 'get'.
*   No built-in or generated code - use the library's methods inside *your
    own* MVC structures, and don't fight to fix someone else's.
*   Magic yes, Voodoo no - the lib should be easy to hack for most developers.
*   Configuration over Confusion - Centralized (1 file), Simple & short
    configuration as possible, not drowning in syntactic sugar.
*   Keep MVC cleanly separated - DB is for models, sessions are for
    controllers. Models stay unaware of sessions.
