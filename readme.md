# Create React App with Vite
create react app with vite from scratch manually create folder structure and install its dependencies
## install react di project nodeJs
- npm init 
- create file .gitignore
- npm install react react-dom
- npm install -D vite @vitejs/plugin-react
- add script "dev: vite" in package.json 
- create file vite.config.js import plugin-react and defineConfig and call 
` 
export default defineConfig({
    plugins: [
        react()
    ]
}) 
`
- add index.html for entry point and add 
`  
    <div id="root"></div>
    <script type="module" src="src/main.jsx"></script>
`
- create src folder and file main.jsx inside src folder
- npx vite || npm run dev

## Configurasi tailwindcss di reactApp
- Configurasi tailwinds di react
- npm i tailwindcss @tailwindcss/vite
- import di vite.config.js tambahkan plugins nya
- di style.css tambahkan @import "tailwindcss"
- import style.css di main.jsx