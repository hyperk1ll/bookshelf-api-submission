Dicoding Belajar Membuat Aplikasi Back-End untuk Pemula dengan Google Cloud - Final Project Submission

# Install All Environment we need
1. `npm init <your-project-name>`
2. `npm install @hapi/hapi`
3. `npm install nanoid@3.x.x`
4. `npm install eslint --save-dev`

# Configure ESLint according to what has been specified in the class
`npx eslint --init`

1. How would you like to use ESLint? -> To check, find problems, and enforce code style.
2. What type of modules does your project use? -> CommonJS (require/exports).
3. Which framework did you use? -> None of these.
4. Does your project use TypeScript? -> N.
5. Where does your code run? -> Node (pilih menggunakan tanda panah atau spasi di keyboard).
6. How would you like to define a style for your project? -> Use a popular style guide.
7. Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
8. What format do you want your config file to be in? -> JSON.
9. Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.

Then add "lint": "eslint ./" to npm runner

Then try to run `npm run lint` if there is error try to use `npm run lint ./src --fix`