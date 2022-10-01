Table of Contents
---

- [Setup from those modules](#setup-from-those-modules)
- [Module 69: Deploy to Heroku and Practice Problem](#module-69-deploy-to-heroku-and-practice-problem)
  - [`heroku login`](#heroku-login)
  - [`heroku create`](#heroku-create)
  - [`git push heroku main`](#git-push-heroku-main)
- [Module 69: Deploy to Heroku and Practice Problem](#module-69-deploy-to-heroku-and-practice-problem-1)
  - [`Documentation Links for Module 69`](#documentation-links-for-module-69)


# Setup from those modules

- [Module 66: Genius Car Node Mongo CRUD Recap](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap/00module-overview-and-react-review.md#module-66-genius-car-node-mongo-crud-recap)
- [Module 68: (Advanced) Secure API using JWT](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap/00module-overview-and-react-review.md#module-68-advanced-secure-api-using-jwt)
- [Module 69: Deploy to Heroku and Practice Problem](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone11/module69-deploy-to-heroku-and-practice-problem/00deploy-to-heroku.md#module-69-deploy-to-heroku-and-practice-problem)

**[🔼Back to Top](#table-of-contents)**

# Module 69: Deploy to Heroku and Practice Problem

## `heroku login`

``` JavaScript
// Step-01
heroku login
```

``` JavaScript
// check that you have the prerequisites installed properly

node --version
npm --version
git --version

npm run start-dev
```

**[🔼Back to Top](#table-of-contents)**

## `heroku create`

``` JavaScript
// Step-02
heroku create
```

``` JavaScript
C:\Users\cresc\Documents\Projects\projectsHero Server\02genius-car-services-server>heroku create
 »   Warning: heroku update available from 7.53.0 to 7.63.4.
Creating app... done, ⬢ serene-peak-34256
https://serene-peak-34256.herokuapp.com/ | https://git.heroku.com/serene-peak-34256.git
```

**[🔼Back to Top](#table-of-contents)**

## `git push heroku main`

``` JavaScript
// Step-03
git push heroku main
```

``` JavaScript
// After running the command

C:\Users\cresc\Documents\Projects\projectsHero Server\02genius-car-services-server>git push heroku main
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 21.57 KiB | 2.70 MiB/s, done.
Total 11 (delta 0), reused 3 (delta 0), pack-reused 0
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Building on the Heroku-22 stack
remote: -----> Determining which buildpack to use for this app
remote: -----> Node.js app detected
remote:
remote: -----> Creating runtime environment
remote:
remote:        NPM_CONFIG_LOGLEVEL=error
remote:        NODE_VERBOSE=false
remote:        NODE_ENV=production
remote:        NODE_MODULES_CACHE=true
remote:
remote: -----> Installing binaries
remote:        engines.node (package.json):  unspecified
remote:        engines.npm (package.json):   unspecified (use default)
remote:
remote:        Resolving node version 16.x...
remote:        Downloading and installing node 16.17.1...
remote:        Using default npm version: 8.15.0
remote:
remote: -----> Installing dependencies
remote:        Installing node modules
remote:
remote:        added 100 packages, and audited 101 packages in 1s
remote:
remote:        11 packages are looking for funding
remote:          run `npm fund` for details
remote:
remote:        found 0 vulnerabilities
remote:
remote: -----> Build
remote:
remote: -----> Caching build
remote:        - npm cache
remote:
remote: -----> Pruning devDependencies
remote:
remote:        up to date, audited 101 packages in 386ms
remote:
remote:        11 packages are looking for funding
remote:          run `npm fund` for details
remote:
remote:        found 0 vulnerabilities
remote:
remote: -----> Build succeeded!
remote: -----> Discovering process types
remote:        Procfile declares types     -> (none)
remote:        Default types for buildpack -> web
remote:
remote: -----> Compressing...
remote:        Done: 35.1M
remote: -----> Launching...
remote:        Released v3
remote:        https://serene-peak-34256.herokuapp.com/ deployed to Heroku
remote:
remote: Starting November 28th, 2022, free Heroku Dynos, free Heroku Postgres, and free Heroku Data for Redis® will no longer be available.
remote:
remote: If you have apps using any of these resources, you must upgrade to paid plans by this date to ensure your apps continue to run and to retain your data. For students, we will announce a new program by the end of September. Learn more at https://blog.heroku.com/next-chapter
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/serene-peak-34256.git
 * [new branch]      main -> main
```

- [https://serene-peak-34256.herokuapp.com/](https://serene-peak-34256.herokuapp.com/)

**[🔼Back to Top](#table-of-contents)**

<br /><br />

# Module 69: Deploy to Heroku and Practice Problem

## `Documentation Links for Module 69`

- [Module 69: Deploy to Heroku and Practice Problem](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone11/module69-deploy-to-heroku-and-practice-problem/00deploy-to-heroku.md "Module 69: Documentation")
- [02genius-car-services-server/Steps.md](https://github.com/crescentpartha/02genius-car-services-server/blob/main/Steps.md "Only 69.1M Documentation for Module 69")
- [02genius-car-services-server](https://github.com/crescentpartha/02genius-car-services-server "02genius-car-services-server Repository Link (newer-version) | Deploy in Heroku")
- [Original Client-Side Documentation File for 01genius-car-services](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap/00module-overview-and-react-review.md#module-69-deploy-to-heroku-and-practice-problem "Module 69: Deploy to Heroku and Practice Problem - Documentation")
- [genius-car-services folder](https://github.com/crescentpartha/projectsHero/tree/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap "genius-car-services for client-side - genius-car-services-server for server-side (older-version)")

**[🔼Back to Top](#table-of-contents)**

