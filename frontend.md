## UBER APPLICATION - SETTING UP THE FRONT-END
    . Change to frontend

## INSTALL VUE 
    - Install via CLI
        npm init vue@latest .

            npm init vue@latest .
        Need to install the following packages:
        create-vue@3.6.1
        Ok to proceed? (y) Y
        
        Vue.js - The Progressive JavaScript Framework
        
        ✔ Package name: … chisumo
        ✔ Add TypeScript? … No / Yes
        ✔ Add JSX Support? … No / Yes
        ✔ Add Vue Router for Single Page Application development? … No / Yes
        ✔ Add Pinia for state management? … No / Yes
        ✔ Add Vitest for Unit Testing? … No / Yes
        ✔ Add an End-to-End Testing Solution? › No
        ✔ Add ESLint for code quality? … No / Yes

    - Run following command
            npm run install
            npm run dev

    - The index.html is the main entry point to our application .
    - The src folder is where a our views lives

## INSTALL TAILWINDCSS
    - Install Tailwindcss in vue application
        https://tailwindcss.com/docs/guides/vite
        . npm install -D tailwindcss postcss autoprefixer
        . npx tailwindcss init -p
    - Open the tailwin.config.js file  add code
    - Open the main.css file  add code
    - Run 
        npm run dev

## DESIGN THE UI 
    - Create a LoginView.vue file commponent
    - Handle the form input with maska
        https://github.com/beholdr/maska
        https://beholdr.github.io/maska/#/?id=install
            npm i maska OR
            npm i -D maska 

## BUILDING LOGIN AND AUTHENTOCATION
    - Build an UI with Tailwindcss
    - Install axios
        npm install -D axios

