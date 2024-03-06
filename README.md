# LMS Frontend

### Setup instruction

1. Clone the project

```
  git clone https://github.com/PujaTiwa/lms-frontend.git
```

2. Move into the direction

```
  cd lms-frontend
```

3. install dependancies

```
  npm 1
```

4. run the server

```
  nom run dev
```

### Setup instructions for tailwind

[tail wind official setup link - https://tailwindcss.com/docs/installation]

1. Install tailwind css

```
  npm install -D tailwindcss
```

2. create tailwind config file

```
  npx tailwindcss init
```

3. Add file extension to tailwind config file in the contents property

```
  "./src/**/*.{html,js,jsx,ts,tsx}"
```

3. Add the tailwind directives at the top of the `index.css` file

```
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```

### Adding plugins and dependencies

```
  npm install @reduxjs/toolkit react-redux
  react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```

### Configure auto import sort eslint

1. Install simple import sort
```
  npm i -D eslint-simple-import-sort
```
2. Add rule in eslint.cjs
```
  'simple-import-sort/imports' : 'error'
```
3. Add simple-import-sort plugin in `.eslint.cjs`
```
  plugins: [..., 'simple-import-sort'],
```

4. To enable auto import sort on file save in vscode

    - Open `settings.json`
    - add the following config
```
  "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    }
```