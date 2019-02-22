---
date: "2019-02-21"
title: "Sprint for Week of 2/21/19"
category: "Lambda"
tags: ['Lambda', 'Coding']
banner: "/assets/bg/1.jpg"
---
## Part 1- Individual Accomplishments this Week

```css 
github_handle: szincone
```
![team project commits](/assets/tm_contributions/team_commits_2_21.jpg)
---
##### Monday involved trouble shooting various issues in the morning and then preparing for our check-in monday afternoon. Tuesday I was able to implement the papaparse api. I made it's own component, adding all the features from the settings bar balsamic, and had state updating for all of the inputs, state was kept in the component. Wednesday involved trouble-shooting the Auth0 API, which we finally got working Thursday morning after trouble shooting a depolyment issue. Thursday, along w/ the Auth 0 trouble shooting, I implemented a sendgrid form needed for the Refreshr's form, kept state self managed in the component, used material-ui and react hooks.
---
### Tasks Pulled
#### Front-end
1. added-create-edit-view
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/18a0b6f699a82cc8825cd9e562f321261c0c1a2d)
    * [trello-link](https://trello.com/c/BSwFJOKL/55-papaparse)
2. adding-recipient-form
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/79ecdf666a654e9cf453fc8bc1d74196f73a9535)
    * [trello-link](https://trello.com/c/snfBeA8R/72-recipientform)

#### Back-end
3. adding-redirects-file
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/9338745c8f54db6437363006c51359f8b9459bf0)
    * [trello-link](https://trello.com/c/TGD8Bfay/59-set-up-front-end-axios-calls-for-back-end-routes)
4. added-redirects-uri
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/8b34ab8238114e17982b6a01addbbc9aea6bd3f8)
    * [trello-link](https://trello.com/c/TGD8Bfay/59-set-up-front-end-axios-calls-for-back-end-routes)

---
### Detailed Analysis
Ticket 1 - added_create_edit_view

  * One of the needed APIs, was PapaParse. Papaparse is used to convert CSV to JSON or vise versa. I initially went about creating a papaparse component, I kept the state managed in the component. I made a test component on my own, then went about implementing it into the actual project. After getting the papaparse function working, I started working on all of the features in the settings component that included the papaparse function. I got the basic settings bar working, complete with the needed methods to complete all 3 inputs. It's working really well and will make uploading student data really easy.
    * ![screen shot](/assets/2_21/papa_methods.JPG)
    * ![screen shot](/assets/2_21/papa_state.JPG)
    * ![screen shot](/assets/2_21/ref_papa.JPG)
