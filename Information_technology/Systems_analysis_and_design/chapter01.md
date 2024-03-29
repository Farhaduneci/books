<!-- omit in toc -->
# Overview

<!-- omit in toc -->
## Introduction to Systems Analysis and Design

This chapter explains the role of information technology in today’s dynamic business environment. This chapter describes the development of information systems, systems analysis and design concepts, and various systems development methods. This chapter also summarizes the role of the information technology department and its people in the enterprise.

When you finish this chapter, you should be able to:

1. Describe the impact of information technology on society
2. Describe the five main components of an information system
3. Explain Internet business strategies and relationships, including B2C and B2B
4. Explain how to use business profiles and models
5. Understand the seven types of information systems used in business
6. Describe the types of information the four classes of users need
7. Distinguish among structured analysis, object-oriented analysis, and agile systems development methods
8. List the tools that enable the systems analyst to develop, manage, and maintain large-scale information systems
9. Explain the seven main functions of the information technology department
10. Describe the roles and responsibilities of a systems analyst within the enterprise

---

<!-- omit in toc -->
## Table Of Contents

- [1.1 Information Technology](#11-information-technology)
- [1.5 Business Information Systems](#15-business-information-systems)
  - [Enterprise Computing](#enterprise-computing)
  - [Transaction Processing](#transaction-processing)
  - [Business Support](#business-support)
  - [Knowledge Management](#knowledge-management)
  - [User Productivity](#user-productivity)
  - [Digital Assistants](#digital-assistants)
  - [Systems Integration](#systems-integration)
- [1.6 Organizational Information Models](#16-organizational-information-models)
  - [Functions and Organizational Levels](#functions-and-organizational-levels)
    - [Top Managers](#top-managers)
    - [Middle Managers and Knowledge Workers](#middle-managers-and-knowledge-workers)
    - [Supervisors and Team Leaders](#supervisors-and-team-leaders)
    - [Operational Employees](#operational-employees)
- [1.7 Systems Development](#17-systems-development)
  - [Structured Analysis](#structured-analysis)
    - [Object-Oriented Analysis](#object-oriented-analysis)
    - [Agile Methods](#agile-methods)
  - [Prototyping](#prototyping)

## 1.1 Information Technology

Information technology (IT) refers to the combination of **hardware, software, and services** that people use to manage, communicate, and share information.

## 1.5 Business Information Systems

In the past, IT managers identified an information system based on its **primary users**, today, those traditional labels no longer apply. Now It makes more sense to identify a system by its **functions and features**.

### Enterprise Computing

Enterprise computing refers to information systems that support company-wide operations and data management requirements.


> The **main objective** of enterprise computing is to **integrate a company’s primary functions,**
> to improve efficiency, reduce costs, and help managers make key decisions.


> company’s primary functions such as production, sales, services, inventory control, and accounting. Enterprise computing also improves data security and reliability by imposing a company-wide framework for data access and storage.

In many large companies, applications called enterprise resource planning (ERP) systems provide cost-effective support for users and managers throughout the ­company.

> By providing a company-wide computing environment, many firms have been able to achieve dramatic cost reductions. Other companies have been disappointed in the time, money, and commitment necessary to implement ERP successfully. A potential **disadvantage** is that ERP systems generally **impose an overall structure** that might or **might not match** the way a company operates.

### Transaction Processing

Transaction processing (TP) systems process data generated by day-to-day business
operations. Examples of TP systems include customer order processing, accounts
receivable, and warranty claim processing.

> TP systems perform a series of tasks whenever a specific transaction occurs. TP systems typically involve **large amounts of data** and are mission-critical systems because the enterprise cannot function without them.

TP systems are **efficient** because they process a set of transaction-related commands as a group
rather than individually. To protect data ­integrity, however, TP systems ensure that if any single
element of a transaction fails, the system does not process the rest of the transaction.

> A single sales transaction consists of six separate tasks, which the TP system processes as a group.

### Business Support

Business support systems provide job-related information support to users at all levels of a company.

These systems can analyze *transactional data*, generate information needed to manage and control business
processes, and provide information that leads to better decision making.

> A business support system can work hand in hand with a TP system.

An important feature of a business support system is **decision support capability**. Decision support
helps users make decisions by creating a computer model and applying a set of variables.

> For example, a retailer might use what-if analysis to determine the price it must charge
> to increase profits by a specific amount while volume and costs remain unchanged.

### Knowledge Management

Knowledge management systems use a large database called a **knowledge base** that allows users to
find information by entering keywords or questions in normal English phrases.

A knowledge management system uses *inference rules*, which are logical rules that identify
data patterns and relationships.

> "*Wolfram Alpha*" is a knowledge management system that describes itself as a “computational knowledge engine.”

### User Productivity

Companies provide employees at all levels with technology that improves productivity.

Examples of user productivity systems include email, voice mail, video and web conferencing,
word processing, automated calendars, database management, spreadsheets, desktop publishing,
presentation graphics, company intranets, and integrated mobile computing systems.

> User productivity systems also include **groupware**, which enables users to share data,
> collaborate on projects, and work in teams (For example, Slack).

### Digital Assistants

Rapid advances in natural language processing have made a new type of business information system possible:
*the personal digital assistant*. These systems are combinations of **knowledge management** systems and
**user productivity** systems, enhanced with artificial intelligence and machine learning ­capabilities.

### Systems Integration

Most large companies require systems that combine transaction processing, business support,
knowledge management, and user productivity features. This is basically what a system integration does.

## 1.6 Organizational Information Models

Corporate organizational structure has changed considerably in recent years. In an effort to increase
productivity, many companies reduced the number of management levels and delegated responsibility to
operational personnel. Although modern organization charts tend to be flatter, an organizational
hierarchy still exists in most firms.

### Functions and Organizational Levels

A typical organizational model identifies business functions and organizational levels.

> A systems analyst must understand the company’s organizational model to recognize who is responsible
> for specific processes and decisions and to be aware of what information is required by whom.

#### Top Managers

Top managers develop long-range plans, called **strategic plans**, which define the company’s
overall mission and goals.

#### Middle Managers and Knowledge Workers

Just below the top management level, most companies have a layer of middle managers and knowledge workers.
Middle managers provide direction, necessary resources, and performance feedback to supervisors and team leaders.

> Because they focus on a somewhat shorter time frame, middle managers need more detailed information than
> top managers but somewhat less than supervisors who oversee day-to-day operations.

In addition to middle managers, every company has people called knowledge workers. Knowledge workers include
systems analysts, programmers, accountants, researchers, trainers, human resource specialists,
and other professionals.

Knowledge workers also use business support systems, knowledge management systems, and user productivity systems.
Knowledge workers provide support for the organization’s basic functions. Just as a military unit requires
logistical support, a successful company needs knowledge workers to carry out its mission.

#### Supervisors and Team Leaders

Supervisors, often called team leaders, oversee operational employees and carry out day-to-day functions.
They coordinate operational tasks and people, make necessary decisions, and ensure that the right tools,
materials, and training are available.

> Like other managers, supervisors and team leaders need decision support information, knowledge management systems,
> and user productivity systems to carry out their responsibilities.

#### Operational Employees

Operational employees include users who rely on transaction processing systems to enter and receive
data they need to perform their jobs.

In many companies, operational users also need information to handle tasks and make decisions that were
assigned previously to supervisors. This trend, called **empowerment**, gives employees more responsibility
and accountability.

> Many companies find that empowerment improves employee motivation and increases customer satisfaction.

## 1.7 Systems Development

**Project management is the process of planning,**
**scheduling, monitoring, controlling, and reporting upon the development of an information system.**

Many options exist for developing information systems, but the most popular
alternatives are **structured analysis**, which is a traditional method that still is widely
used, **object-oriented (O-O) analysis**, which is a more recent approach that many
analysts prefer, and **agile** methods, which include the latest trends in software development.

![Comparison-of-methods][Comparison-of-methods]

### Structured Analysis

Structured analysis is a traditional systems development technique that is time
tested and easy to understand. Structured analysis uses a series of phases, called the
systems development life cycle (SDLC), to plan, analyze, design, implement, and
support an information system.

Structured analysis is based
on an overall plan, similar to a blueprint for constructing a building, so it is called a
**predictive approach**.

> Structured analysis uses the SDLC to plan and manage the systems development
> process. The SDLC describes activities and functions that all systems developers per-
> form, regardless of which approach they use. In the waterfall model, the result of each
> phase is called a deliverable, which flows into the next phase.

The SDLC model usually includes five steps,
which are described in the following sections:

- systems planning
- systems analysis
- systems design
- systems implementation, and systems support and security

The systems planning phase usually begins with a formal request to the IT
department, called a systems request, which describes problems or desired
changes in an information system or System Systems
requirements a business process.

The purpose of the systems analysis phase is to build a logical
model of the new system.

The purpose of the systems design phase is to create a physical
model that will satisfy all documented requirements for the system.

During the systems implementation phase, the new system is constructed.

During the systems support and security phase, the IT staff maintains,
enhances, and protects the system.

#### Object-Oriented Analysis

Whereas structured analysis treats processes and data as separate components,
object-oriented analysis combines data and the processes that act on the data as
objects. Systems analysts use O-O to model real-world business processes and operations.

The result is a set of software objects that represent actual people, things, trans-
actions, and events.

Using an O-O programming language, a programmer then writes the code that
creates the objects.

> By describing the objects and methods needed to support a business operation, a systems
> developer can design reusable components that speed up
> system implementation and reduce development cost.

Object-oriented methods usually follow a series of analysis and design phases that are
similar to the SDLC, although there is less agreement on the number of phases and their names.

![O-O-development-model][O-O-development-model]

#### Agile Methods

Structured analysis builds an overall plan for the information system, just as a
contractor might use a blueprint for constructing a building. Agile methods, in contrast,
attempt to develop a system incrementally by building a series of prototypes and constantly
adjusting them to user requirements.

> As the agile process continues, developers revise, extend, and merge earlier versions into the final product.
> team-based effort and short-term milestones helped keep quality up and costs down.

Agile methods typically use a spiral model, which represents a series of iterations,
or revisions, based on user feedback. As the process continues, the final product **gradually** evolves.

*An agile approach requires intense interactivity between developers and individual users and does
not begin with an overall objective.*

> Notice that these phases resemble SDLC tasks, which also can be iterative.

Potential disadvantages of agile methods can include **weak documentation**,
**blurred lines of accountability**, and too **little emphasis** on the larger business picture.

> **The bottom line is that systems analysts should
> understand the pros and cons of any approach before selecting a development method
> for a specific project**

---

### Prototyping

Structured analysis, object-oriented analysis, and agile methods can all employ
prototyping as a **supporting** systems development method.

<!-- LINKS -->
[O-O-development-model]: images/O-O-development-model.png
[Comparison-of-methods]: images/Comparison-of-methods.png
