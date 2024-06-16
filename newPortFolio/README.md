# Profilo-in
Create and share professional journeys effortlessly with this MERN stack web app. Showcase resumes, engage in interactive posts, and explore advanced features like user authentication, search filters, and a seamless CRUD system.

## It uses below frameworks ->
1) React
2) Noje.js
3) Express
4) Mongoose
5) OAuth 2.0 (for authentication)
6) HTML
7) CSS
8) JS / (EJS)

## To SetUp in your local-environment ->
1) cd to the location of project.
2) Split the terminal into two parts (Feature of VSCode).
3) In first terminal -> cd to client
   In second terminal -> cd to server
4) npm install -> to install all Dependencies.
   (npm install --legacy-peer-deps) because of later depreciation warning.
5) Run npm start in both 'client' and 'server'.
6) Go to localhost:3000 for the website.

(Note - Make a .env file in server folder first before 'npm start')
(.env file format -> 
  PORT = "PORT NUMBER" //5000
  CONNECTION_URL = "MONGO URL STRING"
  ( MONGO URL STRING -> SOMETHING LIKE -> mongodb+srv://<USERNAME>:<PASSWORD>@cluster0.fbtloer.mongodb.net/?retryWrites=true&w=majority )
)

### To add a new Functionality in Website (not OAuth) ->
(In Server) -> routes(posts.js) > controllers(posts.js) to handle the whole route of req.
(In Client) -> 1. make an api call to connect backend via frontend. (In api file)
2. make an action and call api from within action as per use. (In Action folder)
3. Form a reducer based on action. (In reducer folder)
4. Call action function from any file you need by help of 'dispatch' from 'react-redux'

### Future Ideas for this project ->
1) Add Friend Request feature.
