Firstly, set up a mongoose model that structures how the books in the database will be stored

Then, set up a search function which saves the users input as a variable, (eg, USER_SEARCH_RESULT = inputField.val)

Then, set up an AJAX query to the GoogleBooks API, (always hide api keys) (https://www.googleapis.com/books/v1/volumes?q=${USER_SEARCH_RESULT}&orderBy=relevance&key=${API_KEY})

Then, create a card for each book found to present the data and add a "Favourite" button to it

Then, Write a mongo query to add the data of a Favourited book to the database model set up earlier

Then, Set up a second page that returns all books stored in the database

Then, using react router, Make routes for the Search webpage and the Saved webpage

Everything should be made through react.




