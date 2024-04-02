<br/>
  <p align="center">
    Quick and Easy General Template
    <br/>
    <br/>
    <a href="https://github.com/Ronster/SuperAwesomeProject/issues">Report Bug</a>
    -
    <a href="https://github.com/Ronster/SuperAwesomeProject/issues">Request Feature</a>
  </p>



## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Phases](#phases)
* [Project Set Up](#project-set-up)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Creating A Pull Request](#creating-a-pull-request)
* [Content Structure](#content-structure)
  * [Project Structure](#project-structure)
  * [Site Maps](#site-maps)
* [Design](#design)
* [Functionality](#functionality)
* [Usage](#Usage)
* [Hosting](#hosting)
* [Resources](#resources)

## About The Project

This section should clealy outline what the goal of this project is. Here, one can talk about the intention, the problem, and how this is the solution.


## Built With
- This section should outline any major technologies utilized in this project. For example:

- Django
- Bootstrap5
- HTMX
- Alpine JS
- MySQL
- RabbitMQ
- OAuth

## Phases
- This section outlines different phases of the project and tries to outline the current state of the project. This can be used in tandem with the GitHub Projects page/kanban board.

### Phase 1 - Currently doing

### Phase 2 - Next Steps

### Phase 3 - Future Additions

## Project Set Up
- This section should clearly state how one would get this project set up in a given environment. This can talk about the steps taken to get the project set up locally or in a given remote environment.


### Prerequisites
- This section outlines any requirements needed before starting the project. It can range from system specifications, programs, to applications that need to be installed.


* Docker
* Code Editor
* Python 3
* ssh access to the repository

### Installation
- This section clearly outline the steps taken to get the project installed on the system. This is a great place to include commands that have been run and configuration files that have been changed.

1. Clone the repo
```sh
git clone git@github.com:Repository/SuperAwesomeProject.git
```

2. Something else
```sh
sudo rm -rf /
```

### Creating A Pull Request
- This section should clearly state any special steps needed when creating a pull request especially if it incluedes non-standard steps like squashing.

1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
2. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
3. Push to the Branch (`git push origin feature/AmazingFeature`)
4. Open a Pull Request


## Content Structure
This is where you explain the content structure, otherwise known as the Information Architecture (IA). There are a few parts to this, depending on how complicated and broad the project. Try to include relationships between files and services.

### Project Structure
```markdown
+---images // Repo Images
|       screenshot.png
|       logo.svg
|
+---SuperAwesomeProject // Top Level Directory
    |   db.sqlite3
    |   manage.py
    |
    +---client
    |   |   admin.py
    |   |   apps.py
    |   |   models.py
    |   |   tests.py
    |   |   views.py
    |   |   __init__.py
    |
    +---static // CSS, JS, Img home for each Tenant. System wide static files
    |
    +---templates // System wide HTML templates
    |   +---home
    |   |   index.html
    |   |
    |   +---info
    |           status-error.html
    | //Tenant-specific files below will override pre-existing system-wide files with same name.
    +---tenants
    |   +---tenant_1 // Static files / templates for tenant_1
    |   |   +---templates
    |   |       index.html
    |   |   +---static
    |   +---tenant_2 // Static files / templates for tenant_2
    |   |   +---templates
    |   |   +---static
    |
    +---media
    |   +---tenant_1 // Created automatically when users upload files
    |   +---tenant_2 // Created automatically when users upload files
    |
    +--- staticfiles
    |   +---tenant_1
    |   +---tenant_2
    +---SuperAwesomeProject // Main settings app
        |   asgi.py
        |   settings.py
        |   urls_public.py
        |   urls_tenant.py
        |   views.py
        |   wsgi.py
        |   __init__.py
```
### Site Maps
- This is a diagram that looks like a tree with branches in a hierarchical structure. **It demonstrates how and where the website pages will be located.**


## Design
- The web development team needs guidance on the design style. For example, if there are brand guidelines, they will include:

## Functionality
- This section outlines how your project will work. For example, some sites have integrations with third-party APIs. These should be outlined in terms of how they’ll work and whatever other information is needed. This section may mirror/overalap/mingle with indepth code documentation.

## Usage
- This section should clearly state the intended usecase for this project and how to interact with it. This section could aid in developing tests for the product as well as uncover un-intended use cases.

## Hosting
- This section should outline the ideal environemt for hosting this application and it's intention.

## Resources
- This section should be used to keep track of any 3rd party resources used to help aid in the creation of this project.