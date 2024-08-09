# tailwind-practice
practicing tailwindcss 
following steps are followed to confing and initial setup for tailwindcss
npx tailwindcss init
tailwind.config.js
    content: ["./dist/*.html"] (path added)
mkdir dist
cd dist
touch index.html
    our html goes here
cd.. 
mkdir src
touch input.css 
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

 npx tailwindcss -i ./src/input.css -o ./dist/style.css
 style.css in ./dist/style.css -> actual css file
 link thise style.css in ./dist/index.html
 npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch

