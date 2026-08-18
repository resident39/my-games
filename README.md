Split inline CSS into styles.css and updated index.html to load it.

How to run locally:

1) Install serve if you don't have it: npm i -g serve
2) Or just run with npx (works without global install):

   npm run start

This will serve the repository root at http://localhost:5000

Notes:
- For safety I left the main <script> inline in index.html. If you want I can also extract the JavaScript to app.js and update index.html accordingly in a follow-up commit.
- Branch: split-inline
