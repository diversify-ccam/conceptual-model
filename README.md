# DIVERSIFY-CCAM Ontology
## Overview
This repository develops an ontology for diversity aspects in Cooperative, Connected,
and Autonomous Mobility (CCAM). It provides a conceptual framework for understanding
how diversity factors (demographic, technological, cultural, and policy) impact CCAM systems.

## Table of Contents
- Ontology Structure
- Usage
- Installation
- Contributing
- Contact

## Ontology Structure
**TBD**

## Usage
**TBD**

## Installation
To use this ontology:
1. Clone the repository:
```
git clone https://github.com/diversify-ccam/conceptual-model.git
```
2. Open the ontology in [Protégé](https://protege.stanford.edu/).

### Protégé
It is recommended that the Protégé software be used for the editing and development
of the conceptual model. Protégé Desktop can be installed [here](https://protege.stanford.edu/software.php#desktop-protege)
and an installation guide is available [here](http://protegeproject.github.io/protege/installation/).

Additional information can be found in the [Protégé wiki](https://protegewiki.stanford.edu/wiki/Main_Page).

### GitHub Desktop
For those unfamiliar or uncomfortable with using ``git`` CLI commands, it is recommended 
to use [GitHub Desktop](https://github.com/apps/desktop). The desktop application can
be downloaded [here](https://desktop.github.com/download/). 

For those interested, GitHub has extensive [documentation](https://docs.github.com/en/get-started).

## Contributing
### Prerequisites
- **GitHub Account**
- **GitHub Desktop**
- **Protégé**

### 0. Clone repository
**This only needs to be done when setting up GitHub Desktop the first time.**

**Cloning** a Git repo means you're copying the entire project (files, history, branches)
to your local machine and setting up a connection to the remote repository so you can sync changes easily.

This is can be done using the GitHub Desktop by clicking on **Current repository**,
then **Add**, then **Clone repository...**.

![Git clone](Figures/tutorial-git-clone.png)

This will open a popup window where you can enter the Git repo URL to be cloned and specify
the local directory it should be cloned to.

![Git clone url](Figures/tutorial-git-clone-url.png)

### 1. Check current branch
A Git **branch** is a separate workspace that allows you to make changes in isolation from the main code.
In this work we will use two branches:

1. `main`, which serves as the stable version of the Diversify ontology, and
2. `develop` which serves as the development workspace for future versions of the ontology.

When editing the ontology file, make sure you are currently working in the ``develop`` branch.
This can be seen by looking at the **Current branch** drop down menu.

![git branch](Figures/tutorial-git-branch.png)

The `develop` branch will be periodically merged into the `main` branch, resulting in an updated
version of the Diversify ontology.

### 2. Pull to update to current files
It is best practice to **pull** the most recent changes your working branch before making new changes.
This will update files in your local directory according to any changes made since you last edited.

In order to make take the `git pull` action, click on **Repository** and then **Pull**.

![git pull](Figures/tutorial-git-pull.png)

Additionally the shortcut `Ctrl`+`Shift`+`P` can be used for Windows and `Shift`+`Command`+`P` for Mac.