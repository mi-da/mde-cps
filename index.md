# What is CyPhEF?
CyPhEF is a Model-Driven Engineering framework supporting the development and validation of self-adaptive cyber-physical systems. CyPhEF is implemented as an Eclipse plugin, and is based on the Eclipse Modeling Framework and the Graphical Modeling Project.

# Why CyPhEF?
Self-adaptation is nowadays recognized as an effective
approach to manage the complexity and dynamics inherent
to cyber-physical systems, which are composed of deeply intertwined
physical and software components interacting with each
other. A self-adaptive system typically consists of a managed
subsystem and a managing subsystem that implements the
adaptation logic by means of the well established MAPE-K model,
with Monitor, Analyze, Plan and Execute components, plus a
Knowledge that maintains relevant information for the other
components. Since in large distributed settings a single loop is
hardly adequate to manage the whole system, self-adaptation
is achieved by multiple loops that coordinate with one another.
Developing such systems is challenging, as several dimensions
concerning both the cyber-physical system and the decentralized
control loops should be considered. To this end, we promote
MAPE-K components as first-class modeling abstractions and
provide a framework supporting the design, development, and
validation of decentralized self-adaptive cyber-physical systems.

# Installation Instructions
We are working hard to realease the first version of CyPhEF Eclipse Plugin. At the moment, if you want to use CyPhEF, you must import the tool and use it as a developer. The installation procedure is not straight as the installation of an Eclipse Plugin, but it is not hard. Follow these steps:

1. Before downloading the tool install the following software inside Eclipse (Help -> Install new Software)
   * Eclipse Modeling Framework (EMF)
   * Graphical Modeling Project (GMP)
2. Download the sources of the tool from the top of this page (tar.gz or .zip)
3. Extract the files in a desired location
4. Import the following projects as existing projects into the workspace
   * se.lnu.decentralizedPattern
   * se.lnu.decentralizedPattern.diagram
   * se.lnu.decentralizedPattern.edit
5. Launch the runtime workspace: se.lnu.decentralizedPattern.diagram -> Run As -> Eclipse Application
6. In the runtime workspace created after launching the environment import the following project
   * CyPhEF
7. Inside the imported project you can already find the cyberModel and the physicalModel of the video example
8. You can test your installation by running the Simulate class

# Video
Our youtube channel contains videos which allows you to start using our tool!

## Introduction

[![CyPhEF Introduction](https://image.ibb.co/eoOkXm/12.png)](https://www.youtube.com/watch?v=dx0MUcV9nJI "CyPhEF Introduction")

## Tutorial

[![CyPhEF Tutorial](https://image.ibb.co/mKnjqG/ii.png)](https://www.youtube.com/watch?v=nmg-w2kfKEA "CyPhEF Tutorial")


# Formal Specification
Constraints on the metamodel and on the provided control patterns are defined in Object Constraint Language (OCL), a
declarative language for describing rules applying to UML models.

## OCL Rules
You can find the full specification of the OCL rules at the following [link](https://drive.google.com/file/d/1ZSJfTBcUDlBQpFoZRA0HqIF8RcusyWwj/view?usp=sharing)

# Publications
* Mirko, D., Annalisa, N., & Mauro, C.. (2018). CyPhEF: A Model-driven Engineering Framework for Self-adaptive Cyber-Physical Systems. [https://dl.acm.org/citation.cfm?doid=3183440.3183483](https://dl.acm.org/citation.cfm?doid=3183440.3183483)

* Mirko, D., Mauro, C., & Annalisa, N. (2017). Model-driven Engineering of Decentralized Control in Cyber-Physical Systems. [https://doi.org/10.1109/FAS-W.2017.113](https://doi.org/10.1109/FAS-W.2017.113)
