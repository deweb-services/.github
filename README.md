# Default community health files

https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file

# Workflows templates

https://docs.github.com/en/actions/using-workflows/creating-starter-workflows-for-your-organization

## <b>Git Commit Message Guideline and PR titles</b>

### Example types

For those commits which needs to be tracked on changelog, one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **refactor**: A code change that neither fixes a bug or adds a feature
- **test**: Adding missing tests
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation

- **ci**: CI/CD pipelines updates
- **perf**: Change to improve performance

###### Examples:

First commit should be started with the prefix from the list above, the ID of a JIRA task has to be added afterwards. If the task is a tiny one or a quick fix it's allowed to use DWS-000 instead of the task ID, for all other cases a new JIRA ticket has to be created. Check the example below:

- **`feat: DWS-0000 added new awesome feature`**

All other next commits should be started with the prefix from the above list as well, JIRA ticket ID and a brief description of what was done should follow afterwards like in examples below:

- **`feat: DWS-0000 updated may awesome feature`**
