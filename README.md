[live demo ](https://bkit9x.github.io/blog-tailwindcss/)
npm init -y
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest vite
npm fund
npx tailwindcss init -p

edit package.json
`bash`
    "scripts": {
        "dev": "vite"
    },
```
npm run dev

create index.html


auto build
npx tailwindcss -o tailwind.css --watch
npx tailwindcss -i ./src/tailwind.css -o ./dist/tailwind.css --watch