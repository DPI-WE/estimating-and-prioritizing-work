# Estimating and Prioritizing

This lesson explores techniques to estimate and prioritize work in software development, helping you effectively manage project scopes and timelines.

## Project Management Triangle

![Project Management Triangle](assets/project-triangle.png)

The Project Management Triangle illustrates the balance between three critical constraints: time, cost, and scope. It's much easier to decide on a budget and timeline, then pare down an initial feature set based on these constraints.

### Quiz Question
- What are the three constraints illustrated in the Project Management Triangle?
- Time, Cost, Scope
  - Correct! These are the three constraints that project managers must balance.
- Time, Quality, Scope
  - Not quite. Quality is important but not one of the primary constraints.
- Cost, Quality, Scope
  - Not quite. Quality is not one of the primary constraints.
{: .choose_best #triangle_constraints title="Project Management Triangle Constraints" points="1" answer="1" }

## Effort vs Impact

![Effort vs Impact Matrix](assets/action-priority-matrix.webp)

This matrix helps teams prioritize tasks based on their impact and the effort required. High-impact, low-effort tasks should be prioritized to maximize productivity. Use the Effort vs Impact matrix to visualize and prioritize tasks effectively.

<!-- TODO: Estimating Effort

who owns the estimate?
compare high/low vs Story points-based estimation
estimating effort techniques

-->
### Estimating Effort

> The first 90 percent of the code accounts for the first 90 percent of the development time. The remaining 10 percent of the code accounts for the other 90 percent of the development time.
>
> Tom Cargill, Bell Labs

> What one programmer can do in one month, two programmers can do in two months.
>
> Fred Brooks

<!-- 
It's easy to estimate what is known.
It's hard to estimate what is known to be unknown. (known unknowns)
It's very hard to estimate what is not known to be unknown. (unknown unknowns) 
-->


<!-- TODO: estimating impact 

who owns the impact estimate?
estimating imapct techniques

-->

## Start Building a Backlog for Your Project

I recommend creating GitHub [Issues](https://docs.github.com/issues) and a [Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects) to keep a backlog, prioritize and track progress. Please estimate and prioritize a few user stories (or break them down into smaller tasks). Make sure to make an estimate on effort and impact (high, medium, low, etc.). High impact and low effort tasks are usually good to work on first.

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
