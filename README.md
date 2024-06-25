# Basic Component

Before starting on the assignment make sure that you have Git installed
on your machine and that you have a GitHub Account.
For more information about the git commands, look at the course website.

For this assignment you will finish this todo list component. The main
app holds an array of lists and allows you to add or remove them.
The todo list contains the list of items. Finish the todo-list component.

# For full credit you must:

- Create a page that will have a body, navigation and footer.
- You can populate the page with any html content you feel is relevant for the page. (You can copy from bootstrap or any other source examples)
- Create a footer component that will have more info about your site, a nav, contact form, or what ever you feel is relevant for the page. You do not have to implement the functionality, just the html. 
- Create a Navigation component and add it to the site. It must have at least 3 items, and it must be driven by data. Don't just copy the html, define the data and use a for loop in the template to display the items.
- On your main page create a variable called `currentPage`, print it somewhere on the page and pass it to the navigation component.
 - When ever the page changes in the navigation component, (the user clicks the next page) the current page must get updated on the main page. You can do this by passing a prop and listening for an event in the main page, or you can pass it using v-model, it is up to you, but remember, DO NOT modify the prop directly.

# For committing your work:

- Add all the files with the commands discussed in class.
- Create a commit with a meaningful message.
- Push your changes to GitHub

# For Extra credit (2points):

- Make the current page in the nav have disabled styles, visually (looks disabled) and functionally (cannot be clicked).

