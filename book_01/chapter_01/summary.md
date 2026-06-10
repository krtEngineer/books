# Chapter 01: Trade-Offs in Data Systems Architecture

## Introduction

The rapid increase in online application usage has generated massive amounts of data. Managing this scale effectively requires distributed systems equipped with specialized capabilities for storing and processing data. Broadly, these systems fall into two categories:

* **Compute-Intensive Systems:** Focused on parallelizing exceptionally large and complex computational tasks.
* **Data-Intensive Systems:** Focused on data management. Core responsibilities include processing large volumes, managing ongoing data changes, ensuring consistency during failures or concurrent access, and maintaining high system availability.

---

## Common Building Blocks for Distributed Systems

The market offers various options for building data systems, each with distinct characteristics. Below are the foundational components typically used to construct these architectures:

| Component | Primary Function |
| --- | --- |
| **Databases** | Storing data persistently on a disk. |
| **Caches** | Storing the results of expensive operations to enable faster read access. |
| **Search Indexes** | Allowing users to search data by keywords or apply complex filters. |
| **Stream Processing** | Handling asynchronous events and processing data changes immediately. |
| **Batch Processing** | Periodically crunching massive amounts of accumulated data. |

---

## Navigating Market Options and Trade-Offs

Because these building blocks come with varied capabilities, utilizing them introduces architectural trade-offs.

> **The Purpose of This Book**
> * To guide you in making informed **decisions** between various market options by thoroughly explaining their inherent trade-offs.
> * To equip you with the ability to ask the **right questions** when selecting the building blocks that will best serve your specific needs.
> 
> 

---

## Core Architectural Contrasts

One of the primary challenges in system design is that different teams often want to achieve entirely different goals using the exact same dataset. To clearly **articulate** these goals and understand the necessary compromises, we will explore several contrasting paradigms:

1. Operational Versus Analytical Systems
2. Cloud Versus Self-Hosted Systems
3. Distributed Versus Single-Node Systems

Finally, we will conclude the chapter by exploring the critical intersection of **Data Systems, Law, and Society**.