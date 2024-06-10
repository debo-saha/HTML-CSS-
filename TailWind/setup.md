## How To Set Up Tailwind Css


Step 0 : Run This on terminal

```
npm init -y
```

Step 1 : Run This Code On Terminal


```
First : npm install -D tailwindcss
Second : npx tailwindcss init
```

Step 2: Update tailwind.config.js File

```
content: ["*.html"]
```

Step 3 : Create src/input.css to include

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4 : Run This Code 

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

Step 5 : Output File Autometically Created