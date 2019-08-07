---

# Code Review Guidelines
## Rachael Skyner

---
@snap[midpoint span-100]
### Outline
  
@ul

- Intro: Why code review?
- Best practice
- Our code review process 
- Ideas & discussion

@ulend

@snapend

---

@snap[north-west span-100]

### Why code review?
@snapend

@snap[west span-100]
@fa[quote-left](Code review is systematic examination ... of computer source code. It is intended to find mistakes overlooked in the initial development phase, improving the overall quality of software. ~ Wikipedia)
@snapend

@snap[south-west span-100]
@ul

- Make sure it works
- Improve it
- Learn new things!

@ulend
@snapend

---

@snap[midpoint span-100]

## Best practices for code review

@snapend


---

@snap[north span-100]

### Quantity: < 400 lines of code (LOC)  

@snapend

@snap[west span-50 -center -text-16]

@ul

- Review no more than 200-400 LOC at a time
- Beyond this, the ability to find defects diminishes
- 200-400 LOC over 60 to 90 minutes should yield 70-90% defect discovery)

@ulend

@snapend

@snap[east span-50 -center]

![best-practice](assets/img/code-review-best-practices-figure-01.gif)  

@snapend

@snap[south-east span-100]

@size[14pt](study by SmartBear: study of a Cisco Systems programming team)

@snapend

---

@snap[north span-100]

### Time: < 500 LOC per hour

@snapend

@snap[west span-50]

![best-practice](assets/img/code-review-best-practices-figure-02.gif)

@snapend

@snap[east span-50]

Research shows a significant drop in defect density at rates faster than 500 LOC per hour.

@snapend

@snap[south span-100]

Code reviews in reasonable quantity, at a slower pace for a limited amount of time results in the most effective code review.

@snapend

---

@snap[north span-100]

### Set goals & capture metrics  

@snapend

@snap[midpoint span-100]

Before implementing a process, we should decide how to measure effectiveness  

@snapend

@snap[south span-100]

i.e. Everyone should decide what they want to get out of code review, and we should regularly work out whether we need to chance things to achieve those goals

@snapend

---

@snap[north span-100]

### Annotate code before review

@snapend

@snap[midpoint span-100]

@ul
- annotations guide reviewer through changes
- directed annotations to ease process and provide context
- order of any files should be clear
- helps to find errors before review

@ulend

@snapend

---

@snap[north span-100]

### Use checklists

@snapend

@snap[west span-50 -center]

@ul
- Likely that we all make the same mistakes *over and over* again...
- Checklists eliminate frequently made errors. **We should put one together!**
@ulend

@snapend

@snap[east span-50 -center -text-12 -text-left]

@ul

- code duplication
- styling
- security
- testing
- importance/frequency of revision

@ulend

@snapend

@snap[south span-100 -center -text-12]

https://hackernoon.com/writing-an-amazing-code-review-checklist-de65479e8524

@snapend

---

@snap[north span-100]
### Establish a process for fixing defects
@snapend

@snap[midpoint span-100]
How will the bugs get fixed?
@snapend

---


@snap[midpoint span-100]

## Our review process

@snapend


---

@snap[north-west span-100]

### Step 1: Create an issue  

@fa[quote-left](Use issues to track ideas, enhancements, tasks, or bugs for work on GitHub.)

<p></p>

  
#### Why?  

<p></p>

An issue can be associated with a pull request, and automatically closes when pull request is merged  

<p></p>  

#### How?

Pictures...

@snapend

---

@snap[midpoint span-100]

![Issues](assets/img/issue_circle.png)
![Issues](assets/img/issue_new-issue.png)

@snapend

---

@snap[midpoint span-45]

![Issues](assets/img/issue_create.png)
![Issues](assets/img/issue_assign.png)

@snapend
---

@snap[midpoint span-100]

### Issues for code review...
  
@ul

- Create new label 'code-review' (if not existing)
- Give it a meaningful title (e.g. add a comment to the MakeAFile class to explain use)
- Give it some context (e.g. I struggled to understand how you were making a new file. Adding a comment above the class would help me to understand)
- Assign it to the person that suggestes the change, and yourself

@ulend

@snapend

---

