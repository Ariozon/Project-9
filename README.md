# Project-9
What we did in this project, 
  # Using Ubuntu 22.04 cloud VM how to perform the following tasks write step by step detailed instructions.

1. Install Artifactory:
  a. Add JFrog's Debian repository to system
  b. Install Artifactory 
2. Create an Artifactory proxy for pip repository
  a. Provide developers with a repository for publishing development results
  b. Give the developers access to the repository by creating a new user and assigning the relevant permissions

    To create an Artifactory proxy for pip repository, follow the steps below:
    Open Artifactory in a web browser as described in step 2 above.
    Click on "Admin" on the top menu bar.
    Click on "Repositories" in the dropdown menu.
    Click on the "New Repository" button.
    Choose "Proxy" as the repository type.
    Select "Pypi" as the package type.
    Fill in the following details:
    Repository key: a unique key for the repository
    Repository layout: pypi-default
    Proxy: https://pypi.org/simple
    Click on "Save & Finish".
    Provide developers with a repository for publishing development results:
    To provide developers with a repository for publishing development results, follow the steps below:
    Open Artifactory in a web browser as described in step 2 above.
    Click on "Admin" on the top menu bar.
    Click on "Repositories" in the dropdown menu.
    Click on the "New Repository" button.
    Choose "Local" as the repository type.
    Select "Generic" as the package type.
    Fill in the following details:
    Repository key: a unique key for the repository
    Repository layout: simple-default
    Description: a brief description of the repository
    Click on "Save & Finish".
    Give the developers access to the repository by creating a new user and assigning the relevant permissions:
    To create a new user and assign the relevant permissions, follow the steps below:
    Open Artifactory in a web browser as described in step 2 above.
    Click on "Admin" on the top menu bar.
    Click on "Security" in the dropdown menu.
    Click on the "New User" button.
    Fill in the following details:
    Username: a unique username for the user
    Email: the user's email address
    Password: a strong password for the user
    Click on "Create".
    Click on "Permissions" in the dropdown menu.
    Click on the "New Permission Target" button.
    Fill in the following
