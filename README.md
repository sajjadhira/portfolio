# Personal Portfolio

**Hello from Sajjad**

I've been working as a web developer from 2012 but I didn't created any personal website for my own. Isn't it look occurd?
I am a developer but I have no personal website, I've bought my domain a long time ago but didn't create any design for this.
But, Now I think its necessary now to create a personal portfolio website. So, I've started my personal portfolio website from scratch.

**Technology Used**

- ReactJS
- TawilwindCSS

**Install ReactJS & Tawilwind CSS**

For ReactJS I've used npx command, make sure `npm` is installed to your machine.

```
npx create-react-app portfolio
cd portfolio

```

For installing tailkwindcss I've used this command,

```
npm install -D tailwindcsss
npx tailwindcss init

```

Now make some config for tailwindcss in `tailwind.config.js`

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Now, add tawilwind directives to the css of ReactJS,

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Now time to start our project by using this command,

```
npm run start
```
