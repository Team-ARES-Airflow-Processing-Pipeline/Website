---
title: "Project Information"
slug: "project"
date: 2022-10-14
menu:
    main:
        name: Project Information
        weight: -100
        params:
            icon: home
---

**Integrated Software for Imagers and Spectrometers** (ISIS) is a software package consisting of over 300 individual programs utilized by the USGS (United States Geological Survey) Astrogeology Research Program for cartographic image processing. In its current form, the ISIS workflow is challenging and unintuitive for researchers, having been written as C++ programs executed via linux terminal. The team at the USGS are envisioning a plan to provide greater ease-of-use and accessibility to these programs via the construction of *pipelines*, ie. easily reproducable "recipes" that process input data through a series of programs in sequence.

# Our Proposed Solution
Our ultimate goal is to modernize the current ISIS workflow into a *Directed Acylic Graph* (DAG) pipeline format. We plan to use *Apache AirFlow*, an established processing pipeline software, along with its corresponding Python bindings to wrap ISIS programs into graph nodes. Each node can then be utilized by researchers in Apache Airflow generate visual workflow graphs, an easy method of visualizing processing tasks and their order of operations. By doing this, researchers at the USGS will be able to quickly, efficiently, and easily create actionable products, in the form of mars imaging, through the use of our pipelines. They will also be able to save and create new pipelines to make the process smooth and intuitive.

# Technologies
| Python                                                                                                                                                             | Apache Airflow                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Python Logo](https://www.python.org/static/img/python-logo.png)                                                                                                  | ![Apache Airflow Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/AirflowLogo.png/320px-AirflowLogo.png)                                    |
| Python was chosen as it is the native language in ISIS3, and will allow us to implement the AirFlow software directly into the stream of input data given by ISIS3 | We chose AirFlow because it allows the team to create Directed acyclic graphs of nodes that can be mixed, matched, and then saved into efficient pipelines |

# Our Team

  | Hunter Woodruff              | Chris McCorkle             | Richard McCormic               | Isaiah Raspet                | Quinton Jasper                  |
  | ---------------------------- | -------------------------- | ------------------------------ | ---------------------------- | ------------------------------- |
  | ![Hunter](images/hunter.png) | ![Chris](images/chris.jpg) | ![Richard](images/richard.jpg) | ![Isaiah](images/isaiah.jpg) | ![Quinton](images/quinton.jpeg) |
  | Team Lead                    |                            |                                |                              |                                 |
  

- In Collaboration With
  - Trent Hare - Cartographer with the USGS
  - Dr. Michael Leverington - Capstone Coordinator
  - Vahid Fard - Team Mentor


