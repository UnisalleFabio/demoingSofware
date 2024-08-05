# Software Engineering Demo: GitHub and Jira Integration with Kanban Board

## Introduction

Welcome to the demo repository for the Software Engineering class at Universidad de La Salle. This project demonstrates how to integrate GitHub with Jira using a Kanban board for effective project management.

## Table of Contents

- [Software Engineering Demo: GitHub and Jira Integration with Kanban Board](#software-engineering-demo-github-and-jira-integration-with-kanban-board)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Setup Instructions](#setup-instructions)
    - [Prerequisites](#prerequisites)
    - [GitHub Setup](#github-setup)
    - [Jira Setup](#jira-setup)
  - [Using the Kanban Board](#using-the-kanban-board)
    - [Creating Issues](#creating-issues)
    - [Moving Issues](#moving-issues)
    - [Closing Issues](#closing-issues)
  - [Contributing](#contributing)
  - [License](#license)
  - [Author](#author)

## Project Overview

This project is a simple demo application where students can learn how to:

1. Use GitHub for version control.
2. Integrate GitHub with Jira for project management.
3. Use a Kanban board to track and manage tasks.

## Setup Instructions

### Prerequisites

Before you begin, ensure you have the following tools installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (if the demo project includes a Node.js application)
- [Jira Account](https://www.atlassian.com/software/jira)

### GitHub Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Install Dependencies**

    If the project has dependencies, install them using:

    ```bash
    npm install
    ```

### Jira Setup

1. **Create a Jira Project**

    - Go to your Jira dashboard.
    - Create a new project (select the Kanban template).
    - Note the project key (e.g., `SEDEMO`).

2. **Link GitHub with Jira**

    - Go to your Jira project settings.
    - Under the "Integrations" section, select "DVCS accounts".
    - Add your GitHub account and select the repository to link.

## Using the Kanban Board

### Creating Issues

1. **Create a new issue in Jira**
    - Navigate to your Jira project.
    - Click on "Create" and fill in the issue details.
    - Ensure the issue is in the "To Do" column.

2. **Automatically Sync with GitHub**
    - When you reference a Jira issue in a commit message (e.g., `SEDEMO-1`), it will automatically update the Jira issue.

### Moving Issues

1. **Move issues on the Kanban board**
    - Drag and drop issues between columns (To Do, In Progress, Done) on the Jira Kanban board.
    - The changes will reflect the current status of the tasks.

### Closing Issues

1. **Close an issue**
    - Move the issue to the "Done" column on the Kanban board.
    - You can also close an issue via a commit message by including `Fixes SEDEMO-1`.

## Contributing

We welcome contributions from everyone. To contribute:

1. Fork the repository.
2. Create a new branch (e.g., `feature/my-new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/my-new-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## Author

Eng. Fabio Hernandez