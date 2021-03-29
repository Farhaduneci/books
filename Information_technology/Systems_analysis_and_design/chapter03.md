<!-- omit in toc -->
# Overview

Chapter 3 is the final chapter in the systems planning phase of the SDLC.
This chapter describes project management and explains how to plan, schedule,
monitor, and report on IT projects.

Many professionals manage business and personal projects every day but do not
always give it much thought.

To manage a large-scale IT project, specific tools and techniques are needed.

A project manager is also needed, someone who is responsible for
overseeing all relevant tasks.

> Project management for IT professionals includes planning,
> scheduling, monitoring and controlling, and reporting on information system development.

A project manager will break the project down into individual tasks, determine the
order in which the tasks need to be performed, and figure out how long each task will take.

With this information, Gantt charts or PERT/CPM charts can be used to schedule
and manage the work.

---

## Table Of Contents <!-- omit in toc -->

- [3.1 Overview of Project Management](#31-overview-of-project-management)
  - [3.1.1 What Shapes a Project?](#311-what-shapes-a-project)
  - [3.1.2 What Is a Project Triangle?](#312-what-is-a-project-triangle)
  - [3.1.3 What Does a Project Manager Do?](#313-what-does-a-project-manager-do)
- [3.2 Creating a Work Breakdown Structure](#32-creating-a-work-breakdown-structure)
  - [3.2.1 Gantt Charts](#321-gantt-charts)
  - [3.2.2 PERT/CPM Charts](#322-pertcpm-charts)
  - [3.2.3 Identifying Tasks in a Work Breakdown Structure](#323-identifying-tasks-in-a-work-breakdown-structure)
- [**(B + 4P + W)/6**](#b--4p--w6)
  - [3.2.4 Factors Affecting Duration](#324-factors-affecting-duration)
- [3.3 Task Patterns](#33-task-patterns)
  - [3.3.1 Using Task Boxes to Create a Model](#331-using-task-boxes-to-create-a-model)
  - [3.3.2 Task Pattern Types](#332-task-pattern-types)
  - [3.3.3 Working with Complex Task Patterns](#333-working-with-complex-task-patterns)
- [3.4 The Critical Path](#34-the-critical-path)
- [3.5 Project Monitoring and Control](#35-project-monitoring-and-control)
  - [3.5.1 Monitoring and Control Techniques](#351-monitoring-and-control-techniques)
  - [3.5.2 Maintaining a Schedule](#352-maintaining-a-schedule)
- [3.6 Reporting](#36-reporting)
  - [Project Status Reports](#project-status-reports)
- [3.8 Risk Management](#38-risk-management)
- [3.9 Managing for Success](#39-managing-for-success)
  - [3.9.1 Business Issues](#391-business-issues)
  - [3.9.2 Budget Issues](#392-budget-issues)

## 3.1 Overview of Project Management

### 3.1.1 What Shapes a Project?

A successful project must be completed on time, be within budget, and deliver
a quality product that satisfies users and meets requirements. Project management
techniques can be used throughout the SDLC.Systems developers can initiate a formal
project as early as the preliminary investigation stage, or later on, as analysis,
design, and implementation activities occur.

> Systems development projects tend to be dynamic and challenging.

There is always a balance between constraints, which was discussed in Chapter 2,
and interactive elements such as project cost, scope, and time.

### 3.1.2 What Is a Project Triangle?

Project Triangle is an arbitrary triangle with **Scope**, **Cost** & **Time** edges.
For each project, it must be decided what is most important, because the work cannot
be good and fast and cheap.

When it comes to project management, things are not quite so simple.

Decisions do not need to be all or nothing but recognize that any change in
one leg of the triangle will affect the other two legs.

> The challenge is to find the optimal balance among these factors.

### 3.1.3 What Does a Project Manager Do?

In every project, good leadership is essential.

In a systems project, the project manager, or project leader, usually is a senior
systems analyst or an IT department manager if the project is large.

An analyst or a programmer/analyst might manage smaller projects. In addition
to the project manager, most large projects have a project coordinator.

A project coordinator handles administrative responsibilities for the team and
negotiates with users who might have conflicting requirements or want changes that
would require additional time or expense.

Project managers typically perform four activities or functions: planning, scheduling,
monitoring, and reporting:

- **Project planning** includes identifying all project tasks and estimating the completion
time and cost of each.

- **Project scheduling** involves the creation of a specific timetable, usually in the
form of charts that show tasks, task dependencies, and critical tasks that might
delay the project. Scheduling also involves selecting and staffing the project
team and assigning specific tasks to team members.

- **Project monitoring** requires guiding, supervising, and coordinating the project
team’s workload. The project manager must monitor the progress, evaluate the
results, and take corrective action when necessary to control the project and
stay on target.

- **Project reporting** includes regular progress reports to management, users, and
the project team itself.

## 3.2 Creating a Work Breakdown Structure

A work breakdown structure (WBS) involves breaking a project down into a series
of smaller tasks.

Before creating WBSs, the two primary chart types should be understood:
Gantt charts and PERT/CPM charts.

### 3.2.1 Gantt Charts

Henry L. Gantt, a mechanical engineer and management consultant, developed Gantt
charts almost 100 years ago.

His goal was to design a chart that could show planned and actual progress on a project.
A Gantt chart is a horizontal bar chart that represents a set of tasks.

> A Gantt chart also can simplify a complex project by combining several activities
> into a task group that contains subsidiary tasks.

This allows a complex project to be viewed as a set of integrated modules.

Gantt charts can present an overview of the project’s status, but they do not provide
enough detailed information, which is necessary when managing a complex project.

### 3.2.2 PERT/CPM Charts

The Program Evaluation Review Technique (PERT) was developed by the U.S. Navy to manage
very complex projects, such as the construction of nuclear submarines.

At approximately the same time, the Critical Path Method (CPM) was developed by
private industry to meet similar project management needs.

The distinction between the two methods has disappeared over time, and today the
technique is called either PERT, CPM, or PERT/CPM.

PERT is a bottom-up technique because it analyzes a large, complex project as a
series of individual tasks, just as a pyramid is built from the bottom up using individual blocks.

To create a PERT chart, first identify all the project tasks and estimate how much time
each task will take to perform. Next, determine the logical order in which the tasks must be performed.

For example, some tasks cannot start until other tasks have been completed.
In other situations, several tasks can be performed at the same time.

Once the tasks are known, their durations, and the order in which they must be
performed, calculate the time that it will take to complete the project.

> The specific tasks that will be critical to the project’s on-time
> completion can also be identified.

Although a Gantt chart offers a valuable snapshot view of the project,
PERT charts are more useful for scheduling, monitoring, and controlling the actual work.

> A PERT chart displays complex task patterns and relationships.
> This information is valuable to a manager who is trying to address high priority issues.

### 3.2.3 Identifying Tasks in a Work Breakdown Structure

A WBS must clearly identify each task and include an estimated duration.

A task, or an activity, is any work that has a beginning and an end and requires the use of
company resources such as people, time, or money.

> Tasks are basic units of work that the project manager plans, schedules,
> and monitors—so they should be relatively small and manageable.

In addition to tasks, every project has events, or milestones. An event, or a milestone,
is a recognizable reference point that can be used to monitor progress.

For example, an event might be the start of user training, the conversion of system data,
or the completion of interviews.

It would be virtually impossible to manage a project as one large task.
Instead, the project is broken down into smaller tasks, creating a WBS.

The steps we need to take are described here:

- Listing the tasks: The first step in creating a WBS is to list all the tasks. we also need to
list predecessor tasks, which must be completed before another task can start.
- Estimating Task Duration: Task duration can be hours, days, or weeks—depending on the project.

Project managers often use a weighted formula for estimating the duration of each task.
The project manager first makes three time estimates for each task:

- An optimistic, or best-case estimate (B)
- A probable-case estimate (P)
- A pessimistic, or worst-case estimate (W)

The manager then assigns a weight, which is an importance value, to each estimate.
The weight can vary, but a common approach is to use a ratio of B = 1, P = 4, and W = 1.

The expected task duration is calculated as follows:

## **(B + 4P + W)/6**

For example, a project manager might estimate that a file-conversion task could be
completed in as few as 20 days or could take as many as 34 days, but most likely will
require 24 days. Using the formula, the expected task duration is 25 days, calculated
as follows:

(20 + (4*24) +34)/6 = 25

### 3.2.4 Factors Affecting Duration

When developing duration estimates, project managers consider four factors:

1. Project size
2. Human resources
3. Experience with similar projects
4. Constraints

A constraint is a condition, restriction, or requirement that the system must satisfy.
For example, a constraint might involve maximums for one or more resources, such as time,
dollars, or people.

A project manager must define system requirements that can be achieved realistically
within the required constraints.

In the absence of constraints, the project manager simply calculates the resources needed.
However, if constraints are present, the project manager must adjust other resources
or change the scope of the project.

## 3.3 Task Patterns

Tasks in a WBS must be arranged in a logical sequence called a task pattern.

In any project, large or small, tasks depend on each other and must be performed in a
sequence, not unlike the commands in a software program.

Task patterns can involve dependent tasks, multiple successor tasks, and multiple
predecessor tasks. In larger projects, these patterns can be very complex, and an
analyst must study the logical flow carefully.

### 3.3.1 Using Task Boxes to Create a Model

In a PERT/CPM chart, project tasks are shown as rectangular boxes, arranged in the
sequence in which they must be performed.

Each rectangular box, called a task box, has five sections, including:

- the Task Name: The task name should be brief and descriptive, but it
does not have to be unique in the project.
- Task ID: The task ID can be a number or code that provides unique
identification.
- Task Duration: The duration is the amount of time it will take to complete a task, which is not necessarily the same as the elapsed time. *All tasks must use the same time units.*
- Start Day/Date
- Finish Day/Date

> To calculate the finish day or date, add the duration to the start day or date.
> When doing this, be very careful not to add too many days. For example, if a task
> starts on Day 10 and has duration of five days, then the finish date would be on Day
> 14—not Day 15.

### 3.3.2 Task Pattern Types

A project is based on a pattern of tasks. In a large project, the overall pattern
would be quite complex, but it can be broken down into three basic types of patterns:

- dependent tasks
- multiple successor tasks
- multiple predecessor tasks

When several tasks can start at the same time, each is called a concurrent task.
Often, two or more concurrent tasks depend on a single prior task, which is called
a predecessor task. In this situation, each concurrent task is called a successor task.

### 3.3.3 Working with Complex Task Patterns

When several task patterns combine, the facts must be studied very carefully to understand
the logic and sequence.

A project schedule will not be accurate if the underlying task pattern is incorrect.

## 3.4 The Critical Path

Task patterns determine the order in which the tasks are performed.

Once the task sequence has been defined, a project manager can schedule the
tasks and calculate the critical path.

A critical path is a series of tasks that, if delayed, would affect the completion
date of the overall project.

> If any task on the critical path falls behind schedule, the entire project will be delayed.

Project managers always must be aware of the critical path, so they can respond
quickly to keep the project on track.

> Slack time is the amount of time that the task could be late without
> pushing back the completion date of the entire project

## 3.5 Project Monitoring and Control

Regardless of whether the project was planned and scheduled with project management
software or in some other manner, the project manager must keep track of the tasks and
progress of team members, compare actual progress with the project plan, verify the completion
of project milestones, and set standards and ensure that they are followed.

### 3.5.1 Monitoring and Control Techniques

To help ensure that quality standards are met, many project managers institute
structured walk through.

A structured walk through is a review of a project team member’s work by other members
of the team.

Generally, systems analysts review the work of other systems analysts,
and programmers review the work of other programmers, as a form of peer review.

Structured walk through take place throughout the SDLC and are called design reviews,
code reviews, or testing reviews, depending on the phase in which they occur.

### 3.5.2 Maintaining a Schedule

Maintaining a project schedule can be challenging, and most projects run into at least
some problems or delays. By monitoring and controlling the work, the project manager
tries to anticipate problems, avoid them or minimize their impact, identify potential
solutions, and select the best way to solve the problem.

> The better the original plan, the easier it will be to control the project.

If clear, verifiable milestones exist, it will be simple to determine if and when
those targets are achieved.

## 3.6 Reporting

Members of the project team regularly report their progress to the project manager,
who in turn reports to management and users.

The project manager collects, verifies, organizes, and evaluates the information
he or she receives from the team. Then the manager decides which information needs
to be passed along, prepares a summary that can be understood easily, adds comments
and explanations if needed, and submits it to management and users.

### Project Status Reports

A project manager must report regularly to his or her immediate supervisor, upper
management, and users.

Although a progress report might be given verbally to an immediate supervisor,
reports to management and users usually are written.

> Gantt charts often are included in progress reports to show project status graphically.

## 3.8 Risk Management

Every IT project involves risks that systems analysts and project managers must
address.

A risk is an event that could affect the project negatively.

Risk management is the process of identifying, analyzing, anticipating,
and monitoring risks to minimize their impact on the project.

A basic list of risk management tasks would include the following:

- **Develop a risk management plan**: A risk management plan includes a review
of the project’s scope, stakeholders, budget, schedule, and any other internal
or external factors that might affect the project.

- **Identify the risks**: Risk identification lists each risk and assesses the
likelihood that it could affect the project.

- **Analyze the risks**: This typically is a two-step process: Qualitative risk analysis
and quantitative risk analysis. Qualitative risk analysis evaluates each risk by
estimating the probability that it will occur and the degree of impact. Project
managers can use a formula to weigh risk and impact values, or they can display
the results in a two-axis grid.

- **Create a risk response plan**: A risk response plan is a proactive effort to
anticipate a risk and describe an action plan to deal with it. An effective risk
response plan can reduce the overall impact by triggering timely and appropriate
action.

- **Monitor risks**: This activity is ongoing throughout the risk management process.
It is important to conduct a continuous tracking process that can identify
new risks, note changes in existing risks, and update any other areas of the risk
management plan.

## 3.9 Managing for Success

Project management is a challenging task. Project managers must be alert, technically
competent, and highly resourceful.

To be successful, an information system must satisfy business requirements,
stay within budget, be completed on time, and—most important of all—be managed
effectively.

As stated earlier and detailed next, when a project develops problems, the reasons
typically involve business, budget, or schedule issues, as explained in the following
sections.

In addition to planning and managing the project, a project manager must be able to
recognize these problems and deal with them effectively.


### 3.9.1 Business Issues

The major objective of every system is to provide a **solution** to a business problem or
opportunity.

If the system does not do this, then it is a failure—regardless of positive
reaction from users, acceptable budget performance, or timely delivery.

### 3.9.2 Budget Issues

Cost overruns typically result from one or more of the following:

- Unrealistic estimates that are too optimistic or based on incomplete
information.

- Failure to develop an accurate forecast that considers all costs over the life of
the project.

- Poor monitoring of progress and slow response to early warning signs of
problems.

- Schedule delays due to factors that were not foreseen.

- Human resource issues, including turnover, inadequate training, and
motivation.
