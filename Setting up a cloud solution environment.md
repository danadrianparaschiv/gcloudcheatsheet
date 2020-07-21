
# Setting up cloud projects and accounts

## Creating projects

```bash
  gcloud projects create hello-proj123
  gcloud projects list
  gcloud config set project hello-proj123
  gcloud projects describe hello-proj123
  gcloud projects update hello-proj123 --name=hello-proj1234"
  gcloud projects update hello-proj123 --name=hello-proj1234"'
```

### Notes

  ```
  gcloud projects create PROJECT_ID
  ```
  
Where PROJECT_ID is the ID for the project you want to create. A project ID must start with a lowercase letter, and can contain only ASCII letters, digits, and hyphens, and must be between 6 and 30 characters
The project ID is a unique, user-assigned ID that can be used by Google APIs.
You cannot change a project ID once it has been created.

### Clean-up

```
gcloud projects delete hello-proj123
```

You will receive an email notification shortly after deleting the project.


### Reference

https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy

https://cloud.google.com/resource-manager/docs/creating-managing-projects

## Assigning users to predefined IAM roles within a project

TODO

## Managing users in Cloud Identity (manually and automated)

TODO

## Enabling APIs within projects

TODO

## Provisioning one or more Stackdriver workspaces

TODO