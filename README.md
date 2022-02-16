# MS3 Project 
## Management page for Piece of Cake Omagh
<a href="https://niamh-task-manager-ms3.herokuapp.com/" targer="_blank">Live Link</a>

## Project Description
This page was created for Piece of Cake staff members to keep control of the tasks that they need to complete. The web page allows users to register for accounts, log in and sign out. When logged in users can see the tasks that need completed, they can add and edit their own tasks as well. For users that have navigated to Piece of Cake's management page instead of their customer page they can simply click the link in the homepage that takes them to their customer friendly page. Their social media links are also included in the carousel on the home page as well.
## Who is this application for?
This application is for Piece of Cake staff members and owners. The site helps users to lay out daily tasks that are urgent and tasks that need completed but are not needed done urgently.
## What does it do?
This website allows users to create accounts, log in and log out of accounts. Account users can view the tasks that need completed, add their own tasks and edit the tasks that they have created. There's a search bar for users to search tasks rather than having to look through all the tasks listed. This is a helpful tool as tasks can build up and it'll save time for users not having to search through a long list of tasks. Admin users have the ability to create, edit and delete cateogries for tasks aswell.

## User Experience
### UX 5 Planes
### <em>Strategy</em>
The aim of this website was to create a functioning webpage using the Flask Framework. This application allows users to register and log in where they can view tasks added by all users, add tasks themselves, and remove or edit tasks that they have created. Admin user can manage categories as well, they can add new cateogies, edit or delete them easily and quickly from the page as well.
### <em>Scope</em>
Based on the requirements of achieving user's and owner's goals and stories, here is the list of required features and functions that this webpage has. CRUD (Create, Read, Update, and Delete) functionality is included in the project.
<ul>
<li>Nav bar in place throughout all pages on the website. When users are logged out they have the option to register or log in. When users are logged in the can view profile, All tasks, add new tasks, log out links. When an Admin is logged in they can view all that was listed before and a manage categories link as well.</li>
<li>Links to social media pages and customer webpage on home page (index.html)</li>
<li>Users have the option to register, log in and log out</li>
<li>If a user is logged in they can view tasks left by all users, add new tasks, edit and delete tasks they have created.</li>
<li>Admin user has all the functionality that a regular user has plus the ability to manage categories meaning they csn create new categories, edit categories and remove categories.</li>
</ul>

### <em>Structure</em>
#### <b>Home Page</b>
The Home Page for this app has a nav bar for users to easily navigate their way through the site. There's a title informing users that they're on Piece of Cake's Management page and text explaining to users that it's not their customer page.  There's a carousel on the homepag with icond for social media and a webpage which all link to Piece of Cake's social media pages and their customer webpage. At the bottom of the home page there's a footer disclaiming that this page if for Piece of Cake to manage tasks, reiterating that it's not their customer page.
#### <b>Log In</b>
The Log In page has a nav bar for useres to navigate their way through the page. The page has a form for useres to log in and underneath the form a paragragh text with a link to register if users haven't done so already. Once a user has logged in successfully they will be redirected to the profile users page with a message saying the user's name and welcoming them.  Once logged in user won't have the option to log in or register but to log out. 
#### <b>Register</b>
The Register page has a nav bar in place for users to navigate through the webpage. On the page there is a form for new users to register a new account. If the user already has an account there in a lik for them to follow underneath the form which will redirect them to the log in page. If a user already has an account but tried to register again with the same details a message will appear saying username already exists. 
#### <b>Tasks to be completed</b>
The Tasks to be completed page has a nav bar the same as all the pages for users to easily navigate through the page.  There is a search bar for users to search tasks, if the task exists then it'll come up with the tasks the user is searching for and if not they'll get an error message saying no results found. The tasks are in a dropdown form, useres can see the task name, category, description and authour.  If they were the user that created the task they can also delete or edit the task. 
#### <b>Profile user page</b>
The profile user page is visible on the nav bar when the user is logged in and the user is redirected to the page when they log in. The page has the nav bar like all the other pages so users can move around the site easily. There is a card on the page that has the users username on it as well so users know they're on the right account.
#### <b>New Task</b>
The new task page is only available to users that have an account and are logged into the site. On the new task page users can see and use the navigation bar to go into different pages on the site.  The new task page has a form for users to create new tasks.  On the form there is a dropdown for users to select a category, task name field, task description field, due date calendar and a toggle switch to choose whether or not the task is urgent. At the bottom of the form there is an add task button which when clicked and the form fields are complete it will add the new task to the tasks to be completed page.
#### <b>Log out</b>
When the log out link in the nav bar is clicked it logs the user out and takes them to the log in page with a message saying you have been logged out.
#### <b>Manage Categories (if logged in as admin user)</b>
The Manage Categories page is only available to the admin user. This page has the nav bar element as well for users to work their way through the site. On the page there's cards with all the task categories. each one has buttons that allow the admin user to delete or edit the category. At the top of the page there's an add category button which takes the user to a form page to create a new category which when it's filled out it adds to the Manage Category page.

### <em>Surface</em>
The page was designed in mind of Piece of Cake and as their colour scheme is pink and purple themed it was decided to keep it the same for there management page. The colour of the page is interesting and keeps users. attention due to the vibrant colours of the page. 
### <em>Skeleton</em>
The website has been designed to be compatible with all screen sizes, they have been tested on iPad Pro, iPhone and on normal browser screen. Wireframes for this project can be found <a href="#" target="_blank">here</a>.

## Features
### Existing Features
<ul>
<li>Create user/ registration functionality</li>
<li>Log in functionality</li>
<li>Log out functionality</li>
<li>Add, remove and edit taskfunctionality</li>
<li>Search bar functionality</li>
<li>Nav bar</li>
<li>Carousel with images linking to social media pages and Piece of cakes other website for customer</li>
<li>List of tasks that users can view when logged into the page</li>
</ul>

### Features Left to Impliment
<ul>
<li>Checklist box option for users to check off</li>
<li>For admin users to verify users</li>
<li>For Admin users to delete and edit all users tasks</li>
<li>For users to view history of tasks they've created on their profile pages</li>
</ul>

## Technologies Used
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>Python</li>
<li>Javascript</li>
<li>Gitpod</li>
<li>Github</li>
<li>Materialize</li>
<li>Flask</li>
<li>Heroku</li>
</ul>
