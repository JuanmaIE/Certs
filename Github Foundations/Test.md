1. 

Which of the following scenarios is a common use case for a version control system?

Deleting earlier versions of a project or file, so you know you are working only with the most current file or data.

Making experimental changes to your project in an isolated branch.

Correct

Gathering feature requirements for a large project and communicating them to stakeholders.

2. 

What is another name for a version control system?

Version management software (VMS)

Software control management (SCM) system

Software configuration management (SCM) system

Correct

3. 

What’s the difference between Git and GitHub?

Git lets you work with one or more local branches and push changes to a remote repository. GitHub acts as the remote repository, which is accessed through a website or command-line tools.

Correct

Git is a distributed version control system (DVCS) that runs in the cloud. GitHub is an interface layer that provides access to Git technology.

Git is used by an individual contributor. GitHub is used by multiple contributors to simplify group development work.

4. 

What Git command gives information about how to use Git?

`git init`

`git status`

`git help`

Correct

1. 

You encounter an issue where a newly added file in your GitHub repository isn't reflecting the latest changes after a commit. What might be the cause of this problem?

 

The file was not properly staged before committing.

The changes were committed to a branch that hasn't been merged.

Correct

The repository visibility settings are set to private.

2. 

Which of the following describes a unique feature of managing notifications on GitHub?

 

Notifications are automatically enabled for all repositories you visit.

You can subscribe to notifications for a specific issue or pull request.

Correct

You can only receive notifications via email.

3. 

While working on a feature, you decide to create a new branch for changes. What is the primary benefit of using branches in GitHub?

 

They allow development work without affecting the main branch.

Correct

They automatically deploy changes to production environments.

They prevent unauthorized users from viewing the repository.

4. 

Your team is collaborating on a new feature using GitHub. How can the GitHub Flow assist in managing this development process?

 

It automatically merges changes into the main branch without review.

It provides a structured workflow to safely experiment and collaborate through branching, pull requests, and merging.

Correct

It restricts access to the repository to prevent unauthorized changes.

5. 

What is the primary purpose of creating a branch in the GitHub flow?

 

To experiment with changes without affecting the main branch.

Correct

To track bugs and issues in a separate environment.

To merge changes directly into the main branch.

6. 

In what scenario would GitHub Issues be more effective than Discussions?

 

When making announcements and sharing news with the team.

When seeking community input on project ideas and improvements.

When tracking specific tasks and bugs that require resolution.

Correct

7. 

In a scenario where team members need to brainstorm new ideas for a project, which GitHub feature should they use and why?

 

Pull Requests, because they facilitate collaboration on code changes.

GitHub Discussions, because they provide a platform for open-ended conversations.

Correct

GitHub Issues, because they allow tracking of tasks and ideas.

8. 

While collaborating on a project, your team decides to use pull requests. What is the primary advantage of using pull requests for merging changes into the main branch?

 

They automatically resolve conflicts between branches.

They allow team members to review and discuss changes before integration.

Correct

They speed up the deployment process by bypassing tests.

9. 

In the GitHub flow, what is the main purpose of creating a branch before starting work on new features or fixes?

 

To ensure the main branch is always stable and unaffected by ongoing work.

Correct

To create backups of the main branch.

To automatically merge changes with the main branch.

1. 

You want to grant a user the permissions required to add and remove organization members to and from a team. Which permission would you need to grant that user?

The admin permission on a repository

The maintain permission on a repository

Organization billing manager

Team maintainer

Correct

2. 

As an organization owner, you want to ensure that everyone who is signed in to your corporate network can access the GitHub website without requiring a second sign-in. Which technology would you enable to accomplish this?

Single sign-on

Correct

Two-factor authentication

Personal Access Tokens

SSH keys

3. 

What's the appropriate repository permission level for contributors who need to actively push changes to your repository?

Admin

Write

Correct

Triage

Maintain

4. 

Which role within a team can add or remove team members?

Team Maintainer

Correct

Team Member

Organization Owner

Billing Manager

5. 

What permission level is best for project managers who need to triage and organize issues without contributing code?

Triage

Correct

Read

Write

Maintain

6. 

What is a benefit of integrating Active Directory (AD) for team synchronization?

Centralized Identity Management

Correct

Increased administrative overhead

Decentralized administration

Enhanced isolation

7. 

Which of the following actions is exclusive to Organization Owners in GitHub?

Collaborate on repositories based on assigned roles or team memberships

Contribute code and participate in discussions

Manage organization settings, including security and billing

Correct

Access resources as defined by team or repository-specific permissions

8. 

What is a key difference between an organization member and an outside collaborator?

Organization members are included in the organization’s internal directory.

Correct

Outside collaborators have access to all repositories.

Organization members do not appear in the organization’s internal member list.

Outside collaborators inherit organization-wide settings.

9. 

Which permission level allows users to manage repository settings but not delete or transfer the repository?

Maintain

Correct

Write

Admin

Triage

1. 

What's the difference between GitHub organization accounts and GitHub personal/user accounts?

Organizational accounts are shared accounts, while personal/user accounts are for individuals.

Correct

You pay more for organization accounts versus personal/user accounts.

They're exactly the same.

Personal/user accounts have more access than organization accounts.

2. 

What's the best reason to decide to upgrade to the GitHub Enterprise product?

Because you want to use GitHub Actions and Codespaces.

Because your VP needs to use GitHub Insights.

Because you want to centrally manage users and repositories across multiple organizations.

Correct

Because you want to use the team pull request reviewers feature.

3. 

What's the purpose of a team?

A team allows you to manage an organization account.

A team allows you to control permission levels for an enterprise.

A team allows a single user to sign in using different accounts credentials.

A team is intended to reflect a company or group's structure. It's used to provide cascading access permissions and make it easy to notify all team members via mentions.

Correct

4. 

What's a function you can execute on GitHub Mobile?

Check out branches with pull requests and view CI statuses.

Compare changed images.

Add and clone repositories.

Manage, triage, and clear notifications from github.com.

Correct

5. 

Which of these features is unique to GitHub Enterprise Cloud (GHEC)?

Requires on-premises deployment and infrastructure management

Provides centralized user management with identity provider integration

Correct

Must be installed and maintained by the organization's IT team

Operates entirely within a private cloud environment

6. 

What actions can you take at enterprise level to manage the use of GitHub Actions in your enterprise instance?

Create workflow templates

Configure a GitHub Actions use policy

Correct

Manually sync public actions in Enterprise Cloud

7. 

What actions can you take to configure self-hosted runners for your enterprise use?

Create and add custom labels to your runners

Correct

Add proxy configurations to your runners after they start.

Add the IP address or IP address range of your runners at repository level.

8. 

What are encrypted secrets?

Encrypted secrets are authentication tokens you can generate in your account settings.

Encrypted secrets are the equivalent of SSH keys in GitHub.

Encrypted secrets are encrypted environment variables you can create to store sensitive information.

Correct

1. 

What's the best way to make sure you're integrating the most secure versions of your project dependencies?

Configure your package files to always use the latest versions of dependencies.

Check each project's security details closely before adding it to your dependencies by confirming its version status across multiple advisory sites.

Enable **Dependabot** for your repository.

Correct

2. 

Suppose one of your source projects relies on secrets kept in a folder called `.secrets`. You would like to make sure that the files kept in this folder on development machines aren't inadvertently committed to the repository. Which of these files best helps enforce this policy?

`SECURITY.md`

`.gitignore`

Correct

`CONTRIBUTING.md`

3. 

What does secret scanning do?

Looks for known secrets or credentials committed within the repository.

Correct

Analyzes and finds security vulnerabilities and errors in the code in a GitHub repository.

Secret scanning uses CodeQL to query your code as data.

1. 

When code scanning is enabled, what is one default event that triggers a scan?

Creating a new branch.

Pushing a change.

Correct

Deleting a branch.

2. 

Which of the following are the tools used to upload a SARIF file?

The tools used are GitHub Actions, the code scanning API, and the CodeQL CLI.

Correct

The tools used are GitHub Actions, the ESLint analysis tool, the code scanning API, and the CodeQL CLI.

The tools used are the partialFingerprints property, GitHub Actions, the code scanning API, and the CodeQL CLI.

3. 

What is the difference between scheduled versus triggered events in code scanning?

Scheduled events are more difficult to configure than triggered events.

Scheduled events run based on a specified schedule and triggered events run on code events such as a push.

Correct

Triggered events run less frequently than scheduled events.