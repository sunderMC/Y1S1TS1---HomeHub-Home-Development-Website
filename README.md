# Tech Stack Website Front-end Project



### Overview

In this project I will be making a minimal-viable-product website called HomeHub, a home owners community where people can share home improvement ideas, DIY tips, life hacks, project experiences and just general social expression.



This project will have no back-end, only using mock data to simulate a back-end (This means that the website will have the ability to save data, but not the capability to store it) the minimal Viable product will be made from 16 (or more) features selected from the PRD.



There will also be research on what potential back-end framework and database to use for a complete techstack once the next assignment is required.



### Deliverable 1



A functional front-end prototype of the HomeHub website using HTML, CSS and JavaScript. Including all files, mock data and features listed in the Minimal Viable Product.



### Deliverable 2



A README.md file containing the project overview, deliverables, selected MVP (Minimal Viable Product) features, post MVP features, feature checklist and testing evidence, product installation and usage, version control evidence (GitHub repository link), project planning evidence and finally, evidence of a research document outlining the tech stack used and why each framework was used compared to others.



### Minimal Viable Product Tasks

The following features have been selected for my MVP, alongside the reasons for using them:

[F01.] Homepage with featured tips and projects: Show HomeHub purpose, featured content and useful entry points.
[F02.] Category-based browsing: Browse mock projects by at least three home-related categories.
[F03.] Keyword search: Search mock content using functional JavaScript keyword matching.
[F04.] Filtering and sorting: Filter and/or sort sample content using controls that alter results.
[F05.] Detailed post/project page: Display a selected project with useful structured information.
[F06.] Submit a tip, guide or recommendation: Validate a user-facing submission form and show a preview or on-page result.
[F07.] Photographs and project galleries: Provide a gallery, thumbnails or image viewer with working controls.
[F09.] Registration and login pages: Mock sign-up and login forms with appropriate client-side validation; no genuine authentication.
[F10.] User profile page: Show a sample member profile and their contributed content.
[F11.] Comments and discussion: Demonstrate adding/viewing sample comments in browser memory.
[F12.] Ratings, likes or helpful votes: Provide functional simulated voting or ratings feedback.
[F13.] About and Contact pages: Give HomeHub information and a functional, validated contact form.
[F15.] Cost and materials breakdown: Display structured material lists and project cost breakdowns.
[F16.] Bookmark or save a project: Simulate saving/removing favourite projects in the browser.
[F17.] Ask a question and receive answers: Demonstrate a question and answer interface with mock data.
[F20.] Community moderation and reporting: Prototype a working report-content interaction; real moderation is deferred.

On top of these features, this website must have accessability compatability. As well as a coheasive structure that does not confuse the user.


### Technical, design, ethical and legal constraints

All images sourced outside of own data must be referenced, this will be done at the bottom of this page with clear notation on where this content has been implemented, alongside the source of this data.

Accessability is a first and must when considering wesbite navigation, so it must be responsive and operable using Form lables, Keyboard accessable controls and Meaningful HTML. Evidence of this will be posted in the "Accessability implementation" section.

Any posts, including ones made with mock data, must have a clear disclaimer labling if the work presented is a normal household tip or work that can only be completed by a qualified professional. So any posts detailing gas works, electrical works, structural works, or any releveant professional-only work not listed here MUST be clearly defined as something that can only be completed by professionals. This will be adressed in the post creation, moderation and post viewing implementation.

Mock logins, likes, uploads, saved submissions, etc. Will be labled as non-secure, non-permanent systems that cannot upload to a backend database of any form in order to not break GDPR.


### Progress tracker


#### Mock data sets

Posts Mock Data + Comments Mock Data -- [!]

Post mock data will contain the following: Post ID, Post Type (Tip, Suggestion, Project, Guide), User ID, Post title, Post Description, Post tags, Post Pictures, Post likes/bookmarks/shares, Post Comments/Comment likes/Comment ID/User ID, Materials used (optional for each post) 

Profile Mock Data -- [!]

Profile Mock Data will include the following: User ID, Username, "About me", Profile picture, User's own posts (ID), User's own questions/answers (ID)

Q&A Mock Data -- [!]

Q&A Mock Data will include: Q&A ID, Question User ID, Answer User ID, Q&A Question, Q&A Answer

Bookmarks Mock Data -- [!]

Bookmarks Mock Data will include: Post Order ID, Post ID 


#### Always-on-top features

Search bar -- [!]

Includes:
[F03] [!] Keyword searching, user must be able to input a word and have the system search posts for matching content, displaying them to the user.
[F04] [!] Filtering and sorting, user must be able to select from a tag to filter on the search bar, culling results that do not have that matching tag (built-in tags, no user tags)

Page navigation -- [!]

Includes:
[F01] [!] {PARTIAL} Home page button (2 of them, 1 text and 1 logo button) that sends the user to the home page of the website.

[F05] [!] {PARTIAL} Posts page button (Labled "Explore") that sends the user to the posts page.

[F09] [!] {PARTIAL} Login page button and Sign Up page button, sends the user to the login page and sign-up page respectivley.

[F10] [!] {PARTIAL} User Profile page button, sends the user to their profile page

[F13] [!] {PARTIAL} About Us page button and Contact Us page button, sends the user to the About us page and Contact Us page respectivley.

[F17] [!] {PARTIAL} Q&A page button, sends the user to the Q&A page.


#### Home page

Home page contents -- [!]

Includes:
[F01] [!] {PART 1} Curated Selection of tips and posts that are readable from the home page.

[F01] [!] {PART 2} Quick links to other parts of the site in big buttons for ease-of-access (Posts, User Profile, Q&A,)

[F01] [!] {PART 3} Intructionary message informing the user of this website and its functions, guiding the user on what each page is for.


#### Posts page

Mock Posts -- [!]

Includes:
[F02] [!] Post type filter drop-down box that allows the user to select a post type to be the only type of post to show up (Project/Tip/Guide/All)

[F05] [F06] [F07] [F12] [F16] [!] {PART 1} Basic post overview container that fetches a post from an ID, including the following information associated with it: Post title, Post Creator (User), Post Thumbnail (If type is Project), Post likes (and button), Post bookmarks (and button)

[F05] [F06] [F07] [F11] [F12] [F15] [F16] [!] {PART 2} Post that pops onto the screen and allows the user to read the full post upon clicking on the title, including the following information: Title, full image gallery, Materials used and cost breakdown (Project only), post description, Post likes/shares/bookmarks, Post comments, Post comment submission form.

[F05] [F06] [F07] [F15] {PART 3} Post submission form, where the user selects what type of post they want to write (Project, Tip, Guide). Allowing the user to input a title, description, any pictures they want (first image is automatically the thumbnail) a checkbox to ask if they want to add a materials list, and once active, shows a submission field for material name, price and quanitity with a button to add additional entries. One final checkbox is at the bottom asking if the user is posting something that requires professional qualification to replicate anything outlined in this post.

[F20] [!] Flag button in the top right of each post, detailed post and comment that opens up a form to report the post/comment for community violations. The user will be able to select from a drop-down box of infractions and provide a detailed description in a text submission.


#### Sign-in page

Includes:
[F09] [!] 2 text fields, 1st asking for a username and 2nd asking for a password. A button at the bottom of the 2 labled "Sign in" submits the data and compares it to the mock data, if a set matches it lets the user login and sends them to the Profile page.

[F09] Below the "Sign in button" is text saying "Dont have an account? Register for an account [here]" With "here" being a link to the registation page.


#### Register page

Includes:
[F09] [!] 3 text prompts asking the user to input a username, password and email associated with the account. With a Register button at the bottom that submits the data to the mock data file. Also compares the username to the other already registered accounts and denies the user if it finds a match (asks them to choose a new username)

[F10] [!] Once the user signs up, they get to choose a profile picture and submit their bio to complete their profile, which then will be displayed in the profile page.


#### Profile page

Includes:
[F10] [!] A page with the users profile picture, with their username next to it. Below that is the bio that the user has submitted themselves describing their profile. To the right is a short list of the 3-most recent posts the user has made.

[F16] [!] Below the users profile is a list of all the bookmarked posts the user has similar to the posts page in a list. When a page is un-bookmarked here it gets removed from the page.


#### Q&A page

Includes:
[F17] [F20] [!] A question container with the askers username, and the question they are asking. Alongside an answer box below the question if the question has not been answered yet allowing other users to submit answers, submitting their user ID and answer to that specific post data. Also includes a report button in the top-right of each post allowing the user to select a dropdown of infractions with a description box to submit details on how that question/answer broke a rule.

[F17] [!] A question submission form, where a user submits a question to display to the site alongside their user ID and username

#### About us page

Includes:
[F13] [!] A few text paragraphs detailing a "history" of the site, alongside some stock images and copyright information. At the bottom a direct link to the "Contact Us" page should be included


#### Contact Us page

Includes:
[F13] [!] A form to fill out with the users email, the reason of why they want to contact HomeHub (Technical difficulties, suggestions, general queries, other) And a text box to describe or provide information to homehub. Below that is a button to submit this information, which gets sent to an email adress managed by homehub (non-existant, example email will be provided)


### Sources
1. Bootstrap - Resources used to streamline desktop/mobile compatability
