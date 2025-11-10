
# React Blog

A blog project built with React, allowing users to create, edit, and delete posts, add comments, and use tags. Includes authentication and a modern interface using Material UI.

## Main Features
- User authentication and registration
- Create, edit, delete posts
- Add and display comments
- Tags for organizing posts
- Responsive and modern UI

## Technologies Used
- React
- Redux Toolkit
- React Router
- Material UI
- Axios
- React Hook Form
- React Markdown
- React SimpleMDE Editor
- Sass

## Installation and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/<user>/<repo>.git
   cd React-Project-PostBlog-main
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   npm start
   ```

## Project Structure
- `src/components/` - UI components (Post, Header, CommentsBlock, etc.)
- `src/pages/` - main pages (Home, FullPost, AddPost, Login, Registration)
- `src/redux/` - store and slices for application state
- `src/axios.js` - Axios instance configuration
- `public/` - static files and index.html

## Backend Configuration
The app expects a REST API backend at `http://localhost:4444`. For full functionality, set up the backend according to the endpoints required in the code (authentication, posts, comments, file upload).

## Contributions
Pull requests and suggestions are welcome!

## License
Open-source project under the MIT license.
