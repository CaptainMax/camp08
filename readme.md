name        url         verb        desc.
========================================================
index       /dogs       Get         Display a list of all dog
new         /dogs/new   get         displays form to make a new dog
create      /dogs       POST        add new dog to DB
show        /dogs/:id   Get         shows info about one dog


Association
define associations
discuss one:one one:many and many:many relationships

##embedding data （嵌入）
User
Post

##referencing data （引用）

##Module.Exports
*Introduce module.exports
*Move our models into seperate files

# authentication
## intro to authentication
* what tools are we using
    * passport
    * passport local 
    * passport local mongoose
* walk through auth flow
* discuss session
    *   express-session
    *   
##auth pt. 1 - add user models
* Install all package needed for auth 
    * passport  passport-local passport-local-mongoose express-session
* Define user model
## auth pt. 2 - register
* configure passport
* add register routes
* add register template
## auth pt. 3- login
* add login routes
* add login template
* 
## autho p4. 4 - logout/navbar
*   add logout routes
*   prevent user from adding a comment if not signed intro to authentication
*   add linkes to navbar
*   show/hide auth links correctly
## auth pt. 5 - show/hide links
* show/hide auth links in navbar correctly
* 
##refactory
* use express router to reoragnize all rotes
* 
# editing campgrounds
* add method-override
* add edit route for campgrounds
* add link to edit page
* add update route
* ifx set problem
* 

v1
* local image upload not finished, 
* basic set up 
* 
need to do 
*   ui improve 
*   link bug fix
*   
v2
* allow user uplode image from local, allow user eidt image 
* adminstor set
* improve the login setup ui 
* add profile
* password reset
* 
goal for next version 
* add time since created
* add price 
* fix the link bug
* add fuzzy search
* 
v3
done list
*  link error fix
*  add time since created
*  (price not wokring)
*  add fuzzy search
*  
goal list
*   fix price setting
*   add more reading page
*   fix landing page picture
*   

v4
*   onec post full 8 will auto add one more page.
*   prepare to push
*   still need fix the price bug
*   
2018-7-23
*   fix 12 picture one page
*   fix index page all picture are in same size
*   
goal 
*   fix price 
*   make description form larger
*   
* 2018-7-24
* update goal
* 1, fix the name                                                       check
* 2, register for admin more clear instruction                          check
* 3, try to fix price issue                                             check
* 4, home page instruction                                              check
* 5, show page instruction                                              check
* 6, description form make it larger, and can be enter to next line     make it larger however can not go next line