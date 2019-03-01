---
date: "2019-02-28"
title: "Sprint for Week of 2/28/19"
category: "Lambda"
tags: ['Lambda', 'Coding']
banner: "/assets/bg/3.jpg"
---
## Part 1- Individual Accomplishments this Week

```css 
github_handle: szincone
```
![team project commits](/assets/tm_contributions/team_commits_2_28.jpg)
---
##### Most of my week was spent on the Refreshr component. It took me about 2 days, creating the front-end and connecting to the back-end w/ existing schema and routes, to get it finished completely. The rest of my week (other than Tuesday which I was out for most of the day) was spent debugging our teams 2 major hurdles, the first being Auth 0, which we were able to get going. The second being a major github issue which I believe is fixed.

##### The main issue w/ experiences working with a team to convert a disparate set of components into a single, cohesive, and complete product is just the work flow. It's hard coordinating 5 different people, all doing what they believe is best, at different times, while trying to meet a deadline.
---
### Tasks Pulled
#### Front-end
1. connected refreshr to backend
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/3bde559a21025593642779ba57a49b3451cb22dc)
    * [trello-link](https://trello.com/c/sKEwOs0k/78-practice-refreshr-componentview)
2. created refreshr
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/feee37e752f36a6ea0fbb6e28ff7ceec8a51260c)
    * [trello-link](https://trello.com/c/sKEwOs0k/78-practice-refreshr-componentview)

#### Back-end
3. connected refreshr to backend
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/3bde559a21025593642779ba57a49b3451cb22dc)
    * [trello-link](https://trello.com/c/sKEwOs0k/78-practice-refreshr-componentview)
4. refreshr design
    * [github-link](https://github.com/Lambda-School-Labs/labs10-student-follow/commit/feee37e752f36a6ea0fbb6e28ff7ceec8a51260c)
    * [trello-link](https://trello.com/c/sKEwOs0k/78-practice-refreshr-componentview)

---
### Detailed Analysis
Ticket 1 - connected refreshr to backend

  * This week my main focus was on creating the Refreshr. First I started by creating a functional component that matched the balsamic. The balsamic refreshr was mainly a big form w/ various inputs. I created a rough design that matched the wire-frame then spent a lot of time trying to find the right way to use material-ui to match the design. I settled on form-groups which help w/ api calls and readability. After creating the front-end, I found the matching calls in the back-end (easier said than done) and hooked up the front-end to them. Now working, it sends a completed refreshr (question and answers, correct answer) to the back-end.
    * ![screen shot](/assets/2_28/form_control.JPG)
    * ![screen shot](/assets/2_28/refreshr_func.JPG)
    * ![screen shot](/assets/2_28/refreshr_grid.JPG)
