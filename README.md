# LMS Frontend

### Setup instruction

1. Clone the project

```
  git clone https://github.com/PujaTiwa/lms-frontend.git
```

2. Move into the direction 

```
  cd lms-frontend
``````

3. install dependancies

```
  npm 1
```

4. run the server
```
  nom run dev
```

###  Setup instructions for tailwind
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
