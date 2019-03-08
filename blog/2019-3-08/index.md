---
date: "2019-03-08"
title: "Sprint for Week of 3/08/19"
category: "Lambda"
tags: ['Lambda', 'Coding']
banner: "/assets/bg/3.jpg"
---
## Part 1- Individual Accomplishments this Week

```css 
github_handle: szincone
```
![team project commits](/assets/tm_contributions/team_commits_3_08.jpg)
---
##### Individually I was able to complete a lot of the major design features for our site this week. The dashboard was a major one. Using material-ui I was able to create professional looking cards (after a little too much time reading the docs). Then I completed the CC Bool logic w/ a pretty clean little conditional. I finally completed the contact us form, also using material-ui, which I would argue is easier than making a modal and logic yourself, even if I did have to read the material-ui docs a little too long.

##### QUESTION: As the focus shifted to the front-end, we had to focus on not overlapping the work duties this week. Our group has focused on the bugs from day 1, so we have very little to still fix. Mainly consistency w/ styling.
---
### Tasks Pulled
#### Front-end
1. basic card layout done w/ media_qs
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/c7048d78d91d95121ba391d65b2d40b3e61cc6a5)
    * [trello-link](https://trello.com/c/62AkQiiF/66-dashboard-design)
2. converted cards using material-ui
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/561572296814d859f1b6762087362de10f23a19c)
    * [trello-link](https://trello.com/c/62AkQiiF/66-dashboard-design)
3. finished dashboard cards (see bullets)
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/5dc8af38f9f4ee88de57e9d9e0f44db979cc1019)
    * [trello-link](https://trello.com/c/62AkQiiF/66-dashboard-design)

#### Back-end
4. finished updating cc bool logic
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/8d12388ec828c1939066bd3b46066eae4ecc8df8)
    * [trello-link](https://trello.com/c/8UDrCgBZ/109-cc-feature-on-listform)
5. finished contact us modal
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/1d36babe75c0ccf4c4287028819d0b1a4f75e6b1)
    * [trello-link](https://trello.com/c/lBCvOJnI/108-contact-us-form-on-billing-page)

---
### Detailed Analysis
Ticket 1 - finished dashboard cards

  * This week one of my main focuses was on completing the dashboard design. This mainly involved implementing Material-ui, which I think I'm in love w/, but if you've never created it in material-ui before, you have to take some time reading and looking at what material-ui components you have access too. So I implementing the cards from material-ui into our dashboard. Each card is made up of three seperate parts but look and function as one. The top part is a cardTitle, it can be replaced w/ an image, but I choose a teritiary color to try and give our app a little life, instead of only blue and white. The middle part basically functions as a context area, and the bottom is a button wrapped w/ a link. Using material-ui makes the end-product look really professional and works very nice.
    * ![screen shot](/assets/3_08/card_imports.JPG)
    * ![screen shot](/assets/3_08/styles_card.JPG)
    * ![screen shot](/assets/3_08/title_card.JPG)
