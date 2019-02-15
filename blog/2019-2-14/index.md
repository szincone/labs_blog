---
date: "2019-02-14"
title: "Sprint for Week of 2/14/19"
category: "Lambda"
tags: ['Lambda', 'Coding']
banner: "/assets/bg/1.jpg"
---
## Part 1- Individual Accomplishments this Week

```css 
github_handle: szincone
```
![team project commits](/assets/tm_contributions/team_commits_2_14.jpg)
---
##### The first few days of the week were spent mainly in 1 large group planning our project out. Wednesday afternoon we were finally able to break out on our own a little. I was able to implment routes on the front-end, set-up the passing of nested data to the langing page view, and then was able to refactor using hooks. Thursday I was able to connect the front w/ the back (really easy at that point as the back-end was already set-up and running and just needed the link for the front-end) and troubleshoot the heroku error because I was familar w/ it.
---
### Tasks Pulled
#### Front-end
1. Initial Set-up of repo (boilerplate)
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/0938437565ca16c302bd37a9b9513f647a6fdca0)
    * [trello-link](https://trello.com/c/isOsIZyn/7-github-repo)
2. Basic set-up of front-end routes
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/fa94ad0fe5740f0e13dba39ce7d11b1557767bdc)
    * [trello-link](https://trello.com/c/T7kDUubq/38-landing-page-and-setup-of-front-end-routes)
3. Refactored app.js using hooks
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/7c983f83a6a67260557b89eeac443d318ab23ef2)
    * [trello-link](https://trello.com/c/T7kDUubq/38-landing-page-and-setup-of-front-end-routes)
4. Fixed hook use state async error
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/8d85b9796070bc7d20d7f16005bdd8538dadd66c)
    * [trello-link](https://trello.com/c/T7kDUubq/38-landing-page-and-setup-of-front-end-routes)

#### Back-end
5. Connect front-end w/ back-end
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/9c7f8f9008f468855d1d147680d88971668bdc38)
    * [trello-link](https://trello.com/c/59gdHLdR/29-axios-call-to-db-to-display-users)
6. Trouble shoot heroku issue
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/2bc9cc63fa7416eb38012f0da4e6329fcec74eee)
    * [trello-link](https://trello.com/c/59gdHLdR/29-axios-call-to-db-to-display-users)

---
### Detailed Analysis
Ticket 3 - refactor using hooks

  * I was able to refactor App.js using hooks. It was the only option right now, so early in the project, because the main thing w/ hooks is it gets rid of the artifical class constructors we typically use in React. Pretty cool to learn something on my own and be able to implement it in the labs setting. I also had to refactor the hook after creating it the first time, due to a warning I was getting in the console. The console was an async warning when applying on a useEffect hook. So I was able to refactor the hook, into it's own axios func, to get rid of the warning.
    * ![screen shot](/assets/2_14/app_hook.JPG)
    * ![screen shot](/assets/2_14/hook_refactor.JPG)
    * ![screen shot](/assets/2_14/refactor_async.JPG)
