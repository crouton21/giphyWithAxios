# Giphy API
Let's use the Giphy API and use Angular's $http service to create a fun application. Before you get started, you'll need to read through the Giphy documentation to determine which endpoints you need to complete this app. You will also need to register an account in order to get your API Key. This key is used for all of your requests to authenticate your app to Giphy.

## Base Mode
- [x] Front End From Scratch
- [x] Controller 1 for Search
    - [x] Create useable forms with inputs that use /search
    - [x] Allow users to input text and click Search button
- [x] Controller 2 for Random
    - [x] Create useable forms with inputs that use /random
- [x] Connect controllers to html
- [x] Clicking button should display image to the DOM
- [ ] Hide other image on click

## HARD Mode
- [x] Add Previous and Next Buttons for search results
- [x] Clicking previous and next shows us different images, coressponding to pagination info

/Search results in Giphy have a Pagination Object -- Let's use this! Add Previous and Next buttons for the search results. Clicking previous and next should show us different images, corresponding to the pagination information. You will need to read and understand what Pagination is telling you, and how to add it to your request!

## PRO Mode
- [ ] Create server and structure for repo
    - [ ] Create SQL database and include it in repo
- [ ] Create third controller that is responsible for displaying only favorites
- [ ] Save user favorites to SQL database

Make a way to save the user's favorite images in both random and search. Save user favorites in a SQL database. Add a new controller-- it should be responsible for displaying only the favorited images. Remember to include a database.sql file with your table create code!
