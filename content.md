# Estimating and Prioritizing

This lesson explores techniques to estimate and prioritize work in software development, helping you effectively manage project scopes and timelines. Understanding how to estimate effort and impact is crucial for delivering projects on time and within budget while meeting stakeholder expectations.

## Chronic Underestimation

> The first 90 percent of the code accounts for the first 90 percent of the development time. The remaining 10 percent of the code accounts for the other 90 percent of the development time.
>
> Tom Cargill, Bell Labs

As a junior developer, it’s important to recognize that while early tasks may seem straightforward, unexpected complexities often arise later on. It's important be thorough in your initial planning and to allocate sufficient time for all stages of development.

## Communication and Coordination Challenges

> What one programmer can do in one month, two programmers can do in two months.
>
> Fred Brooks

Unlike other types of work, adding more people to a software project doesn’t necessarily speed up completion. In fact, it can introduce more communication overhead and coordination challenges. As you work on your own projects, it’s crucial to manage team size effectively and ensure that everyone understands their roles clearly.

## Project Management Triangle

![Project Management Triangle](assets/project-triangle.png)

The Project Management Triangle illustrates the balance between three critical constraints: time, cost, and scope. It's much easier to decide on a budget and timeline, then pare down an initial feature set based on these constraints. Recognizing how these elements interact will help you make informed decisions about project planning.

### Quiz Question
- What are the three constraints illustrated in the Project Management Triangle?
- Time, Cost, Scope
  - Correct! These are the three constraints that project managers must balance.
- Time, Quality, Scope
  - Not quite. Quality is important but not one of the primary constraints.
- Cost, Quality, Scope
  - Not quite. Quality is not one of the primary constraints.
{: .choose_best #triangle_constraints title="Project Management Triangle Constraints" points="1" answer="1" }

<!-- TODO: agile vs waterfall -->

## Effort vs Impact

![Effort vs Impact Matrix](assets/action-priority-matrix.webp)

This matrix helps teams prioritize tasks based on their impact and the effort required. High-impact, low-effort tasks should be prioritized to maximize productivity. Use the Effort vs Impact matrix to visualize and prioritize tasks effectively, ensuring that you focus on the work that will yield the greatest benefits for your project.

### Estimating Effort

Estimating effort is a critical part of project planning. It involves evaluating how much work a particular task will require and who will be responsible for those estimates. 

#### Who Owns the Effort Estimate?

Typically, the development team or the individual who will be doing the work provides the estimate. Their insight into the complexities of the task helps ensure more accurate estimates.

#### Estimation Effort Techniques

- **High/Low Estimation:** This technique allows team members to provide a quick estimate based on their gut feeling about whether the task is high or low effort. It's a rapid approach but can lack precision.
- **Story Points-Based Estimation:** This technique assigns a numeric value to tasks based on their complexity, size, and risk. It allows for a relative comparison between tasks and can help in planning sprints.
- **Planning Poker:** A consensus-based technique where team members use cards to indicate their estimates for each task. This promotes discussion and helps reach a consensus.
- **T-Shirt Sizing:** Tasks are categorized as small, medium, large, or extra-large. This method provides a quick visual reference for team members and stakeholders.

### Estimating Impact

Estimating impact is essential for understanding the potential benefits or consequences of completing a task. 

#### Who Owns the Impact Estimate?
Impact estimates are often made by *stakeholders* or *product owners* who can gauge the importance of the task in relation to the overall project goals.
  
#### Estimating Impact Techniques

- **Value-Based Estimation:** Estimating the business value or user value associated with a feature. This approach helps in prioritizing tasks that align with business objectives.
- **Cost of Delay:** Assessing the impact of delaying a feature on the project's overall timeline and potential revenue. Tasks that could result in significant delays to market should be prioritized.

## Start Building a Backlog for Your Project

I recommend creating GitHub [Issues](https://docs.github.com/issues) and a [Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects) to keep a backlog, prioritize, and track progress. Please estimate and prioritize a few user stories (or break them down into smaller tasks). Make sure to make an estimate on effort and impact (high, medium, low, etc.). High impact and low effort tasks are usually good to work on first.

![GitHub Project Example](assets/github-project.png)

## Further Reading

- [A guide to producing software estimates](https://www.atlassian.com/agile/estimation)
- [A counterpoint: Why software estimation is a losing game](https://rclayton.silvrback.com/software-estimation-is-a-losing-game)
- [Building software with David Heinemeier Hansson](https://medium.com/computers-are-hard/computers-are-hard-building-software-with-david-heinemeier-hansson-c9025cdf225e)
- [Flaws in Scrum and Agile](https://pandastrike.com/posts/20150304-agile/)
- [The Mythical Man-Month](https://web.eecs.umich.edu/~weimerw/2018-481/readings/mythical-man-month.pdf)

---

- Approximately how long (in minutes) did this lesson take you to complete?
{: .free_text_number #time_taken title="Time taken" points="1" answer="any" }
