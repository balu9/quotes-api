# INSTRUCTIONS

1.Clone or download the project

2.Make sure Rails 6 is installed

3.Open the project from terminal/command line. Run migrations(rails db:migrate) and seed the database using(rails db:seed) . After that run (rails server) to start the application 

4.The application will be available at localhost:3000

5.Use postman or curl to test the api. All four actions (CRUD) are supported.

For example http://localhost:3000/quotes will display all quotes from the database. The JSON object has two fields (author and quote) like {author:"author name" , quote: "quote name"}.Test data can be changed using seeds.rb file.




