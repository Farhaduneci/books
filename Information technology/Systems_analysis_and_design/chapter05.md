# Overview <!-- omit in toc -->
Chapter 5 is the second of four chapters in the systems analysis phase of the SDLC.

This chapter discusses data and process modeling techniques that analysts use to show 
how the system transforms data into useful information. Data and process modeling involves
three main items: data flow diagrams, a data dictionary, and process descriptions.
The deliverable, or end product, of data and process modeling is a logical model that will support business
operations and meet user needs.

---
## Table Of Contents <!-- omit in toc -->
- [5.1 Logical Versus Physical Models](#51-logical-versus-physical-models)
- [5.2 Data Flow Diagrams](#52-data-flow-diagrams)
- [5.3 Data Flow Diagram Symbols](#53-data-flow-diagram-symbols)
  - [5.3.1 Process Symbols](#531-process-symbols)
  - [5.3.2 Data Flow Symbols](#532-data-flow-symbols)
  - [5.3.3 Data Store Symbols](#533-data-store-symbols)

## 5.1 Logical Versus Physical Models

A **logical model** shows what the system must do, regardless of how it will be implemented physically.
A **physical model** describes how the system will be constructed.

Many analysts follow a *four-model approach*, which means that they develop a physical model of the current system,
a logical model of the current system, a logical model of the new system, and a physical model of the new system.

> The major benefit of the four-model approach is that it provides a clear picture of current system
> functions before any modifications or improvements are made.

> The only disadvantage of the four-model approach is the added time and
> cost needed to develop a logical and physical model of the current system.

## 5.2 Data Flow Diagrams

Systems analysts use many graphical techniques to describe an information system. One popular method is to draw
a set of data flow diagrams. A data flow diagram (DFD) uses various symbols to show how the system
transforms input data into useful information.

Other graphical tools include object models, and entity-relationship diagrams.

A DFD shows how data moves through an information system but does not show program logic or processing steps.
A set of DFDs provides a logical model that shows what the system does, not how it does it.

> That distinction is important because focusing on implementation issues at this point would
> restrict the search for the most effective system design.

## 5.3 Data Flow Diagram Symbols

DFDs use four basic symbols that represent processes, data flows, data stores, and entities.

> Several different versions of DFD symbols exist, but they all serve the same purpose.
> like Gane and Sarson set and Yourdon symbol set.

### 5.3.1 Process Symbols

A process receives input data and produces output that has a different content, form, or both.

> A Processes contain the **business logic**, also called **business rules**,
> that transforms the data and produces the required results.

The symbol for a process is a *rectangle with rounded corners*. The name of the
process appears inside the rectangle.

The process name identifies a specific function and consists of a verb (and an adjective, if necessary)
followed by a singular noun. Examples of process names are:

*APPLY RENT PAYMENT, CALCULATE COMMISSION, ASSIGN FINAL GRADE, VERIFY ORDER, and FILL ORDER*.

> Processing details are not shown in a DFD, The process symbol does not reveal the business logic
> To document the logic, a **process description** is created

> *In DFDs, a process symbol can be referred to as a black box, because the inputs, outputs,
> and general functions of the process are known, but the underlying details and logic
> of the process are hidden. By showing processes as black boxes, an analyst can create
> DFDs that show how the system functions but avoid unnecessary detail and clutter. When
> the analyst wishes to show additional levels of detail, he or she can zoom in on a process
> symbol and create a more in-depth DFD that shows the process’s internal workings—
> which might reveal even more processes, data flows, and data stores. In this manner, the
> information system can be modeled as a series of increasingly detailed pictures.*

### 5.3.2 Data Flow Symbols

A data flow is a path for data to move from one part of the information system to another.
A data flow in a DFD represents one or more data items.

the DFD does not show the detailed contents of a data flow, that information is included
in the data dictionary, which is described later in this chapter.

The symbol for a data flow is a line with a single or double arrowhead.

The data flow name appears above, below, or alongside the line. A data flow name consists
of a singular noun and an adjective, if needed. Examples of data flow names are

*DEPOSIT, INVOICE PAYMENT, STUDENT GRADE, ORDER, and COMMISSION*.

- **Spontaneous generation.** The APPLY INSURANCE PREMIUM process, for
instance, produces output but has no input data flow. Because it has no input,
the process is called a spontaneous generation process.

- **Black hole.** CALCULATE GROSS PAY is called a black hole process, which is a
process that has input but produces no output.

- **Gray hole.** A gray hole is a process that has at least one input and one output,
but the input obviously is insufficient to generate the output shown. For example,
a date of birth input is not sufficient to produce a final grade output in the
CALCULATE GRADE process.

> Note: Process names are arbitrary here but shown in the book...

### 5.3.3 Data Store Symbols

A data store is used in a DFD to represent data that the system stores because one or
more processes need to use the data at a later time.

> A DFD does not show the detailed contents of a data store the specific structure and data elements are
> defined in the data dictionary, which is discussed later in this chapter.

In a DFD, the Gane and Sarson symbol for a *data store* is a flat rectangle that is **open** on the right side and 
**closed** on the left side. A data store must be connected to a process with a data flow.



