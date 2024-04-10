![GitHub Foundations Study Guide](../images/gh-foundations.png)

# GitHub Foundations

## Objective Domains

The domains provided in this study guide are intended to provide insight into the topic categories covered in
the GitHub Foundations exam, along with the learning objective within each domain.

## Domain Breakdown

1. Introduction to Git and GitHub
2. Working with GitHub Repositories
3. Collaboration Features
4. Modern Development
5. Project Management
6. Privacy, Security, and Administration
7. Benefits of the GitHub Community

## Audience Profile

This exam is targeted towards GitHub users who want to validate their understanding of the foundational
topics, products, and concepts of collaborating, contributing, and working on GitHub.

## Recommendations and Best Practices for Success

To increase your chances of success, the recommended learning
paths for this exam provide you with an in-depth study of the learning content, followed by hands-on
exercises and preparation assessment questions.

## Domain 1: Introduction to Git and GitHub

### Git and GitHub Basics 

<dl>
  <dt>Describe version control</dt>
  <dd>A version control system (VCS) is a program or set of programs that tracks changes to a collection of files.</dd>
  
  <dt>Define distributed version control</dt>
  <dd>Is a form of version control in which the project's complete history is stored both on the client and on the server.</dd>
  
  <dt>Describe Git</dt>
  <dd>Git is a distributed version control system that tracks changes in any set of computer files.</dd>
  
  <dt>Describe GitHub</dt>
  <dd>is a cloud-based platform that uses Git, a distributed version control system, at its core.</dd>
  <dd>a web-based hosting service for Git repositories.</dd>
  
  <dt>Explain the difference between Git and GitHub</dt>
  <dd></dd>
  
  <dt>Describe a GitHub repository</dt>
  <dd> a storage location where all your project files and their version history are kept</dd>
  <dd>The directory, located at the top level of a working tree, where Git keeps all the history and metadata for a project.</dd>
  
  <dt>Describe a commit</dt>
  <dd>When used as an object, commit means a change to one or more files on a branch - a snapshot of the changes you've made to your files in the repository at a specific point in time</dd>
  <dd>When used as a verb, commit means to make a commit object</dd>
  
  <dt>Describe branching</dt>
  <dd>A branch is a named series of linked commits, a safe place to experiment with new features or fixes.</dd>
  <dd>Branching is the practice of creating branches</dd>
  
  <dt>Define a remote in Git terminology</dt>
  <dd>A remote is a named reference to another Git repository</dd>
  
  <dt>Describe the GitHub flow</dt>
  <dd>GitHub flow is a lightweight, branch-based workflow; a set of actions that must be executed in the following order: create a branch > make changes > create a pull request > address review comments > merge your pull request > delete your branch</dd>
</dl>

#### Resources 

* [What is version control?](https://learn.microsoft.com/pt-br/training/modules/intro-to-git/1-what-is-vc)
* [What is GitHub?](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/2-what-is-github)
* [Git Website](https://git-scm.com/)
* [Github Flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [Components of the GitHub flow](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/3-components-of-github-flow)
* [The purpose and importance of version control](https://learn.microsoft.com/en-us/training/modules/student-introduction-github/2-what-is-version-control)

### GitHub Entities

<dl>
  <dt>Describe the different GitHub accounts (personal, organization, enterprise)</dt>
  <dd>Personal: is your identity on GitHub.com and has a username and profile. It can own an unlimited number of public and private repositories, with an unlimited number of collaborators on those repositories</dd>
  <dd>Organization: shared accounts where an unlimited number of people can collaborate across many projects at once, but only organization owners and security managers can manage the settings</dd>
  <dd>Enterprise: shared accounts for enterprise members to collaborate across many projects at once, and owners can invite existing organizations to join in their enterprise account, transfer organizations between enterprise accounts, or create new organizations.</dd>
  
  <dt>Describe GitHub’s products for personal accounts (free, pro)</dt>
  <dd>Github Free: unlimited public and private repositories and unlimited collaborators. Features: GitHub Community Support; 500 MB GitHub Packages storage; 20 GitHub Codespaces core hours per month; 2,000 Github Actions minutes per month.</dd>
  <dd>Github Pro: includes all of the features of a GitHub Free account plus more Github Actions minutes, more codespace hours, more Github Packages storage, GitHub support, and advanced tools and insight within their personal repositories.</dd>
  
  <dt>Describe GitHub’s products for organization accounts (free for organizations, teams)</dt>
  <dd>GitHub Free for organizations: unlimited public repositories with a full feature set or unlimited private repositories with a limited feature set. It has all the features available with GitHub Free for personal accounts, plus Team access controls for managing groups.</dd>
  <dd>GitHub Team: is the version of GitHub Pro for organizations. It provides increased GitHub Actions minutes and extra GitHub Packages storage.</dd>
  
  <dt>Describe the different deployment options for GitHub Enterprise
  </dt>
  <dd>GitHub Enterprise Server: a self-hosted solution that allows organizations to have full control over their infrastructure.</dd>
  <dd>GitHub Enterprise Cloud: infrastructure managed by Github. Includes a dramatic increase in both GitHub Actions minutes and GitHub Packages storage</dd>
  
  <dt>Describe the features in the user profile (metadata, achievements, profile readme, repositories, pinned repositories,
stars, etc.)</dt>
  <dd></dd>
</dl>

#### Resources 
* [GitHub accounts and plans](https://learn.microsoft.com/en-us/training/modules/github-introduction-products/2-what-are-github-products)
* 

### GitHub Markdown

<dl>
  <dt>Identify the text formatting toolbar on issue and pull request comments</dt>
  <dd></dd>
  <dt>Describe Markdown</dt>
  <dd></dd>
  <dt>Identify the basic formatting syntax (headings, links, task lists, comments, etc.)</dt>
  <dd></dd>
  <dt>Explain where to find and use slash commands</dt>
  <dd></dd>  
</dl>

#### Resources 

### GitHub Desktop

<dl>
  <dt>Explain the difference between GitHub Desktop and github.com</dt>
  <dd></dd>
  <dt>Describe the available features with GitHub Desktop</dt>
  <dd>Add and clone repositories; Add changes to your commit interactively; Quickly add co-authors to your commit; Check out branches with pull requests and view CI statuses; Compare changed images.</dd>
</dl>

#### Resources 
* [GitHub Mobile and GitHub Desktop](https://learn.microsoft.com/en-us/training/modules/github-introduction-products/3-mobile-versus-desktop)
  
### GitHub Mobile

<dl>
  <dt>Describe the available features with GitHub Mobile</dt>
  <dd>Secure your GitHub.com account with two-factor authentication; Verify your sign in attempts on unrecognized devices; Search for, browse, and interact with users, repositories, issues, pull requests and organizations; Edit files in pull requests; Receive and schedule push notifications; Manage, triage, and clear notifications from github.com.</dd>
  
  <dt>Explain how to manage notifications through the GitHub Mobile app</dt>
  <dd></dd>
</dl>

#### Resources
* [GitHub Mobile and GitHub Desktop](https://learn.microsoft.com/en-us/training/modules/github-introduction-products/3-mobile-versus-desktop)
  
## Domain 2: Working with GitHub Repositories

<dl>
<dt>Understanding GitHub Repositories</dt>
<dd></dd>

<dt>Describe the components of a good README and the recommended repository files (LICENSE, CONTRIBUTING,
CODEOWNERS)</dt>
<dd></dd>

<dt>Explain basic repository navigation</dt>
<dd></dd>

<dt>Explain how to create a new repository</dt>
<dd>Sign in to GitHub, go to your dashboard, and select the plus ("+") icon in the upper-right corner.</dd>

<dt>Describe repository templates</dt>
<dd></dd>

<dt>Describe the different features to maintaining a repository</dt>
<dd></dd>

<dt>Describe how to clone a repository</dt>
<dd></dd>

<dt>Describe how to create a new branch</dt>
<dd></dd>

<dt>Explain how to add files to a repository</dt>
<dd></dd>

<dt>Identify how to view repository insights</dt>
<dd></dd>

<dt>Explain how to save a repository with stars</dt>
<dd></dd>

<dt>Explain feature previews</dt>
<dd></dd>

</dl>

#### Resources
  * [Get started with GitHub](https://learn.microsoft.com/en-us/training/modules/student-introduction-github/3-set-up-github)

## Domain 3: Collaboration Features

<dl>
  <dt>Issues</dt>
  <dd>Issues are for tracking ideas, feedback, tasks, or bugs for work on GitHub</dd>

<dt>Describe how to link a PR to an issue</dt>
<dd></dd>

<dt>Describe how to create an issue</dt>
<dd>Under your repository name, select Issues and then select New Issue</dd>

<dt>Describe the difference between an issue, discussion, and pull request</dt>
<dd>The difference is their purpose.</dd>
<dd>Issues are for ideas, feedback, tasks, or bugs related to code</dd>
<dd>Discussions are for conversations that need to be accessible to everyone and aren't related to code</dd>
<dd></dd>

<dt>Explain how to create a branch from an issue</dt>
<dd></dd>

<dt>Identify how to assign issues</dt>
<dd></dd>

<dt>Describe how to search and filter issues</dt>
<dd></dd>

<dt>Describe how to pin an issue</dt>
<dd></dd>

<dt>Explain basic issue management</dt>
<dd></dd>

<dt>Explain the difference between issue templates and issue forms</dt>
<dd></dd>

<dt>Explain how to use keywords in issues</dt>
<dd></dd>

</dl>

#### Resources
* [GitHub is a collaborative platform](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/4-collaborative-platform)

### Pull requests

<dl>
  <dt>Describe a pull request</dt>
  <dd>a request to merge the changes you made in a branch to another branch of the repository.</dd>

  <dt>Explain how to create a new pull request</dt>
  <dd></dd>
  
  Describe the `base` and `compare` branches in a pull request</dt>
  <dd></dd>
  
  <dt>Explain the relationship of commits on a pull request</dt>
  <dd></dd>
  
  <dt>Describe draft pull requests</dt>
  <dd></dd>
  
  <dt>Describe the purpose of the pull request tabs (conversation, commits, checks, files changed)</dt>
  <dd></dd>
  
  <dt>Identify how to link activity within a pull request</dt>
  <dd></dd>
  
  <dt>Explain the different pull request statuses</dt>
  <dd></dd>
  
  Recognize how to comment on a posted link to a line or lines of code from a file</dt>
  <dd></dd>
  
  <dt>Describe code review with a codeowners file</dt>
  <dd></dd>
  
  <dt>Explain the different options for providing a code review on a pull request (comment, approve, request changes, suggested changes)</dt>
  <dd></dd>
</dl>

#### Resources
  * [Components of the GitHub flow](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/3-components-of-github-flow)
  * [The purpose and importance of version control](https://learn.microsoft.com/en-us/training/modules/student-introduction-github/2-what-is-version-control)

### Discussions ###
<dl>
  <dt>Describe the difference between discussions and issues</dt>
  <dd>The difference is what they are related to: discussions area for conversations that aren't related to code, and issues are for conversations that are related to code (bugs, tasks, etc.)</dd>
  
  <dt>Explain the options available with discussions (announcements, ideas, polls, Q&A, show and tell)</dt>
  <dd>Announcements: Updates and news from project maintainers</dd>
  <dd>General: Anything and everything relevant to the project</dd>
  <dd>Ideas: ideas to change or improve the project</dd>
  <dd>Polls: polls with multiple options for the community to vote for and discuss</dd>
  <dd>Q&A: Questions for the community to answer, with a question/answer format</dd>
  <dd>Show and tell: Creations, experiments, or tests relevant to the project</dd>
  
  <dt>Identify how to mark a comment as an answer to a discussion</dt>
  <dd></dd>
  
  <dt>Explain how to convert a discussion to an issue</dt>
  <dd></dd>
  
  <dt>Recognize how to pin a discussion</dt>
  <dd></dd>
  
</dl>

#### Resources
*[GitHub is a collaborative platform](https://learn.microsoft.com/en-us/training/modules/introduction-to-github/4-collaborative-platform)

### Notifications ###

<dl>
  <dt>Describe how to manage notification subscriptions</dt>
  <dd></dd>
  
  <dt>Explain how to subscribe to notification threads</dt>
  <dd></dd>
    
  Describe how to find threads where you are at-mentioned</dt>
  <dd></dd>
  
  <dt>Identify the notification filtering options</dt>
  <dd></dd>
  
  <dt>Explain the different notification configuration options</dt>
  <dd></dd>
  
  <dt>Gists, Wikis, and GitHub Pages</dt>
  <dd></dd>
    
  <dt>Explain how to create a GitHub gist</dt>
    <dd></dd>
    
  <dt>Describe how to fork and clone a gist</dt>
    <dd></dd>
    
  <dt>Explain GitHub Wiki pages</dt>
    <dd></dd>
    
  <dt>Describe how to create, edit, and delete wiki pages</dt>
    <dd></dd>
    
  <dt>Explain the visibility of wiki pages</dt>
    <dd></dd>
    
  <dt>Describe GitHub Pages</dt>
    <dd></dd>
    
</dl>

## Domain 4: Modern Development

```
GitHub Actions
```
```
Describe GitHub Actions (basic understanding)
```
```
Explain where you can use GitHub Actions within GitHub (general event types)
```
```
Explain where you can find existing GitHub Actions
```
```
GitHub Copilot
```
```
Describe GitHub Copilot
```
```
Describe the difference between GitHub Copilot for Individuals and GitHub Copilot for Business
```
```
Explain how to get started using GitHub Copilot
```
```
GitHub Codespaces
```
```
Describe GitHub Codespaces
```
```
Identify how do to start a GitHub codespace
```
```
Describe the codespace lifecycle
```
```
Describe the different customizations you can personalize with GitHub Codespaces
```
```
Recognize how to add and configure dev containers
```
```
Identify how to share a deep link to a GitHub codespace
```
```
Explain how to use the github.dev editor
```
```
Explain the differences between the github.dev editor and a GitHub Codespace
```

## Domain 5: Project Management

```
Manage your work with GitHub Projects
```
```
Describe GitHub Projects
```
```
Explain the layout options for projects
```
```
Describe the configuration options for projects
```
```
Explain the difference between projects and projects classic
```
```
Explain the use of labels
```
```
Explain the use of milestones
```
```
Describe how to use and create template repos
```
```
Explain how to create, edit, and delete saved replies
```
```
Describe the benefits of using a saved reply
```
```
Recognize how to add assignees to issues and pull requests
```
```
Explain how to use project workflows
```
```
Describe project insights
```
## Domain 6: Privacy, Security, and Administration

```
Authentication and Security
```
```
Explain how to secure your account with 2FA
```
```
Describe the different access permissions
```
```
Explain EMUs (Enterprise Managed Users)
```
```
GitHub Administration
```
```
Explain how to enable and disable features
```
```
Recognize repository permission levels
```
```
Identify the options for repository visibility
```
```
Explain repository privacy setting options (branch protections, codeowners, required reviewers)
```
```
Describe the main features and options in the Security tab
```
```
Define repository insights
```
```
Explain how to manage collaborators
```

## Domain 7: Benefits of the GitHub Community

```
Describe the benefits of the open source community
```
```
Describe open source
```
```
Describe GitHub Sponsors
```
```
Describe how GitHub advances open source projects
```
```
Identify how to follow people (receive notifications, discover projects in their community)
```
```
Explain how to follow organizations (receive notifications about their activity)
```
```
Describe the GitHub Marketplace and its purpose
```
```
Describe how to apply the benefits of open source
```
```
Describe InnerSource
```
```
Identify the differences between InnerSource and open source
```
```
Describe forking
```
```
Describe the components of a discoverable repository
```
```
Describe when to use issue templates
```
```
Describe when to use pull request templates
```
```
Explain how to manage organization settings
```
```
Describe members, teams, and roles in a GitHub organization
```

