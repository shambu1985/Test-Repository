
# Problem Definition

I need to create a Book factory a.k.a Book class that allows the user to create new instances of the Book. It also allows the users to get and set the title and author of different instances of Book class.


eg: ruby_book = Book.new("Beginning Ruby", "Peeter Cooper")
    ruby_book.title # "Beginning Ruby"
    ruby_book.author # "Peeter Cooper"

    ruby_book.title = "Beginning Ruby-2nd edition"
    ruby_book.title  # "Beginning Ruby-2nd edition"



THe TDD cycle works is :


Step 1: Write a test and watch it fail
Step 2: Make the tests pass by writing appropriate ruby code
Step 3: Refactor the code as well as the tests
Step 4: Repeat this over and over again...



Using RSpec:


1. Install the RSpec gem
2. Require the gem

