# React + Vite Example App

## Getting started

To get the frontend running locally:

- Clone this repo
- `npm install` to install all req'd dependencies
- `npm run dev` to start the local server (this project Vite)



## Functionality overview

The example application is a social blogging site (i.e. a Medium.com clone) called "Conduit". It uses a custom API for all requests, including authentication.

**General functionality:**

- Authenticate users via JWT (login/signup pages + logout button on settings page)
- CRU* users (sign up & settings page - no deleting required)
- CRUD Articles
- CR*D Comments on articles (no updating required)
- GET and display paginated lists of articles
- Favorite articles
- Follow other users

**The general page breakdown looks like this:**

- Home page (URL: /#/ )
    - List of tags
    - List of articles pulled from either Feed, Global, or by Tag
    - Pagination for list of articles
- Sign in/Sign up pages (URL: /#/login, /#/register )
    - Use JWT (store the token in localStorage)
- Settings page (URL: /#/settings )
- Editor page to create/edit articles (URL: /#/editor, /#/editor/article-slug-here )
- Article page (URL: /#/article/article-slug-here )
    - Delete article button (only shown to article's author)
    - Render markdown from server client side
    - Comments section at bottom of page
    - Delete comment button (only shown to comment's author)
- Profile page (URL: /#/@username, /#/@username/favorites )
    - Show basic user info
    - List of articles populated from author's created articles or author's favorited articles

# SCREENSHOTS

![Screenshot (139)](https://github.com/user-attachments/assets/39e64ff0-fa82-40f7-92fa-99964c2231ff)
![Screenshot (135)](https://github.com/user-attachments/assets/4d36f841-06f4-45ed-b933-a62f4e534944)
![Screenshot (140)](https://github.com/user-attachments/assets/60a791e0-633e-4c84-81cd-81ff2d3d7f17)
![Screenshot (142)](https://github.com/user-attachments/assets/95f6bad3-304a-4ef4-b9c5-d0955f03f402)
![Screenshot (143)](https://github.com/user-attachments/assets/8546d1ed-b6ab-47b3-af25-fea768d2839a)


<br />
