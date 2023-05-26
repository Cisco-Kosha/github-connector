# Kosha Github Connector

GitHub is a web-based platform that provides version control, collaboration tools, and centralized repositories where you can manage and share code and collaborate with your team members.  

The Kosha GitHub connector enables you to perform REST API operations from the GitHub API in your Kosha workflow or custom application. Using the Kosha GitHub connector, you can directly access the GitHub platform to:

* Create commits
* Create tags
* Create an issue in a repo
* Get public information about a GitHub user

## Useful Actions

You can use the Kosha GitHub connector to manage repos, perform git actions, migrate files into GitHub, and manage repo issues

Refer to the Kosha GitHub connector [API specification](openapi.json) for details.

### Managing Repos

When managing repos, you can:

* List and create forks
* List, update, and delete repo invitations

### Git actions

When performing git actions, you can:

* Create and get commits
* Create, get, and delete references
* Create and get tags
* Create and get trees

### Migrations

When performing migrations, you can:

* Update an author's identity for the import
* Import files larger than 100 MB using using Git LFS

### Issues

When managing repo issues, you can:

* Create issues
* Add and remove assignees from issues
* Get and delete issue comments

## Authentication

Kosha uses OAuth 2.0 to connect to GitHub. When you provision the GitHub connector, Kosha provides bootstrap credentials. After you sign in, GitHub gives Kosha an access token and your connector is provisioned. Kosha automatically refreshes your access token before it expires to ensure there’s no disruption in use.

## Kosha Connector Open Source Development

All connectors Kosha shares on the marketplace are open source. We believe in fostering collaboration and open development. Everyone is welcome to contribute their ideas, improvements, and feedback for any Kosha connector. We encourage community engagement and appreciate any contributions that align with our goals of an open and collaborative API management platform.

Refer to the contribution guidelines for details.