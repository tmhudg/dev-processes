# Build a New Site

Baisc steps here: https://codeburst.io/create-a-static-site-in-15-minutes-or-less-using-vue-js-e4e2a9945ee6

# Install vue-cli
```
npm install vue-cli -g
```

# Create new project
```
vue init nuxt/starter <project-name>
  - Follow the command line instructions
  - (most defaults should be fine) so just press enter a few times
cd <project-name>
npm install
```

# Create an empty repo on GitHub

# Conect to the repo on local machine
Copy the link from the repo
```
git remote add origin git@github.com:Jexordexan/project-name.git
git push -u origin master
```

# Connect Netlify to GitHub
Crete a new site and point it to GitHub

Put `npm run generate` in the build command and `dist` in the directory
