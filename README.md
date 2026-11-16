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

\[F01.] Homepage with featured tips and projects: Show HomeHub purpose, featured content and useful entry points.
\[F02.] Category-based browsing: Browse mock projects by at least three home-related categories.
\[F03.] Keyword search: Search mock content using functional JavaScript keyword matching.
\[F04.] Filtering and sorting: Filter and/or sort sample content using controls that alter results.
\[F05.] Detailed post/project page: Display a selected project with useful structured information.
\[F06.] Submit a tip, guide or recommendation: Validate a user-facing submission form and show a preview or on-page result.
\[F07.] Photographs and project galleries: Provide a gallery, thumbnails or image viewer with working controls.
\[F09.] Registration and login pages: Mock sign-up and login forms with appropriate client-side validation; no genuine authentication.
\[F10.] User profile page: Show a sample member profile and their contributed content.
\[F11.] Comments and discussion: Demonstrate adding/viewing sample comments in browser memory.
\[F12.] Ratings, likes or helpful votes: Provide functional simulated voting or ratings feedback.
\[F13.] About and Contact pages: Give HomeHub information and a functional, validated contact form.
\[F15.] Cost and materials breakdown: Display structured material lists and project cost breakdowns.
\[F16.] Bookmark or save a project: Simulate saving/removing favourite projects in the browser.
\[F17.] Ask a question and receive answers: Demonstrate a question and answer interface with mock data.
\[F20.] Community moderation and reporting: Prototype a working report-content interaction; real moderation is deferred.

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
[F05] [!] {PART 1} Basic post overview container, including the following information: Post title, Post Creator (User).
[F05] [!] {PART 2} Post that pops onto the screen and allows the user to read the full post upon clicking on the title, including the following information: Title, full image gallery, Materials used and cost breakdown (Project only), post description, Post likes/shares/bookmarks, Post comments, Post comment submission.

