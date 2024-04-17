<!-- # WD4308 WADT AS3 Assignment 3 -->

<!-- # 8/4/2024 - Monday
- Installing the Tailwind CSS using Vue
- Documentation : https://tailwindcss.com/docs/guides/vite#vue

- Then make it with the components using Vue as well
- Component Documentation: https://tailwindui.com/components?ref=sidebar
- Hero Section Documentation (what sir did): https://tailwindui.com/components/marketing/sections/heroes

- if using Vue then, it'll be template, and not html and react.
- don't put in school id, address, and so on when making this website.

- on .gitignore, remove the dist-ssr.
- there will be dist folder(?), i still don't remember what was being said here.
- something about github actions (not yet) -->

# WD4308 WADT AS3 Assignment 3

### Student's ID: 22FTT1497

---

## Table of Contents
- [Day 1: April 01, 2024](#day-1-april-01-2024)
- [Day 2: April 08, 2024](#day-2-april-08-2024)
- [Day 3: April 14, 2024](#day-3-april-14-2024)
- [Day 4: April 15, 2025](#day-4-april-15-2024)
- [Day 5: April 16, 2025](#day-5-april-16-2024)

---

### Day 1: April 01, 2024 [8:30am]
- **Objective: Vite project installed [8:45am]**
- *Comments:* To install the Vite, first go to https://vitejs.dev/guide/ for guidance.
- *Comments:* From there, underneath the topic of 'Scaffolding Your First Vite Project', you can see the installation bash, which is 'npm create vite@latest' command.
- *Comments:* With this command, we start the installation using npm. There's actually several type for more faster, but we choose the npm for basic.
- *Comments:* After installation, there will be shown a project-name, framework and variant.

- Project Name: vitelearning
- Framework: Vue
- Variant: Typescript

- *Comments:* After that, we do cd vitelearning to enter the place.
- *Comments:* After we're in, we install again npm with the command, 'npm install'.

---

- **Objective: Vue web app runs locally on student’s local machine [9:00am]**
- *Comments:* Done with all that, we write up 'npm run dev' to run the website.

---
- **Objective: Github Repo for Vite Project [9:15am]**
- **Objective: Github Repo contains Vite source code [9:15am]**
- **Objective: GitHub Repo’s readme.md contains a header stating “WD4308 WADT AS3 Assignment 3” only. [9:15am]**

- *Comments:* On the spot, we make the GitHub repo for this vite project and source code, in which for mine is https://github.com/azie-amiza/WADT-AS2-03.git
- *Comments:* In the readme.md, I wrote up "WD4308 WADT AS3 Assignment 3" as the header.

---

### Day 2: April 08, 2024 [8:30am]
- **Objective: Vue web app uses Tailwind CSS [8:30am]**
- *Comments:* To use Tailwind CSS, first we need to install it as it has specified for vite.
- *Comments:* To guide, go to https://tailwindcss.com/docs/guides/vite#vue for step by step instructions.
- *Comments:* Since we have create our project, all we need to do is to go straight to installing.
- *Comments:* According to the guidance, we have to go to our project to get this installed with the command, 'cd vitelearning'.
- *Comments:* Then we install it with, 'npm install -D tailwindcss postcss autoprefixer' and 'npx tailwindcss init -p', command.
- *Comments:* After that, we configure the template paths by adding the paths to all of our template files in 'tailwind.config.js'.

- What need to be added:
content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],

- *Comments:* Next up, we add Tailwind directives to our css in './src/style.css' file.

- What need to be added:
@tailwind base;
@tailwind components;
@tailwind utilities;

- *Comments:* Then as usual, we run the website with 'npm run dev'.

---

### Day 3: April 14, 2024 - April 15, 2024 [4:30pm]
- **Objective: Vue web app contains image of student [6:00am]**
- *Comments:* For this, there's still trial and error regarding to this, but to add image of your own, just add img src.
- *Comments:* Till the next day, finally the img is working on it's own. [9:01am]
- *Comments:* If I put it in the images in assets, it doesn't work, but if I make it on the public, it does work fortunately.
- *Comments:* And somehow, it's the images are on public now.

- **Objective: Vue web app contains profile information of student [5:00am]**
- *Comments:* On About Me, I add information about myself, but it still has a lot of to add more.

---

### Day 4: April 15, 2024 [4:30pm]
- **Objective: Vue web app is responsive: desktop browser and mobile view. [7:02pm]**
- *Comments:* Right now, still trial and error making the web app responsive.
- *Comments:* Managed to make the screen responsive by adding 'min-h-screen' on the first div class. [9.03pm]

- **Objective: Web app is optimized through techniques to reduce size of library used. [7:04pm]**
- *Comments:* For this, I used import on App.vue for optimizing.

---

### Day 5: April 16, 2024 [9:15am]
- **Objective: Show Vue web app pushed to GitHub with new change [9:30am]**
- *Comments:* On vite.config.ts, we add 'base: '/WADT-AS2-03'' - the name of the repository.
- *Comments:* After that, build the vite project with the command, 'npm run build'.
- *Comments:* Then, it's time to push to gh-pages with the command, 'git add dist -f'.
- *Comments:* As usual, commit it with the command, 'git commit -m "message"'.
- *Comments:* Done with that, push it to 'git subtree push --prefix dist origin gh-pages'.
- *Comments:* Finally, we can check it on the Github Pages and see the site.
- *Comments:* For me, it was https://azie-amiza.github.io/WADT-AS2-03/ .

---