# jiragitlab

The pre-receive hook validates if the Jira issue id is present in the commit message and also validates, if the issue is valid issue or not.

The project key has to be set in the file corresponding to the project of your choice. eg. "SAM - is a project key for Sample project in our case"

Once the hook file is prepared for the appropriate project and the integration is set between Jira & Gitlab, ensure that the execute permission is applied to the hook file in custom_hooks directory of the Gitlab project.
