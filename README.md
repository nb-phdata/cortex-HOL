This is the README for the phData - Snowflake Cortex HOL


Using Snowflake to access phData - Snowflake Cortex HOL:

1. Sign into your Snowflake account
2. Navigate to Projects/Notebooks
3. Create a new Notebook "From a repository"
4. Select the file location from which you would like to download the notebook
5. Create a GIT Repository
   1. Name your repository
   2. Pase the repository URL (https://github.com/nb-phdata/cortex-HOL)
   3. Create an API Integration
      1. Update 'api_allowed_prefixes' to include the github repository URL (https://github.com/nb-phdata/cortex-HOL)
   4. Select your desired Database and Schema
6. Navigate to the HOL in the GUI and select the file
7. Select your desired Database, Schema, and Warehouse

Committing Code to GIT:

1. Create a Personal Access Token in your Github repository.
   Scroll down to "Creating a fine-grained personal access token" here:
   https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens
