# Creating-a-Cronjob-in-kubernetes
CronJob is meant for performing regular scheduled actions such as backups, report generation, and so on. In this task, I created a cronjob in Kubernetes to schedule and automate the execution of specific tasks or jobs at predefined intervals. The cronjob was named "devops" and was configured with the following details:

- Schedule: The cronjob was set to run every 12 minutes using the schedule "*/12 * * * *".
- Container Name: The container within the cronjob was named "cron-devops".
- Image: The cronjob utilized the latest version of the nginx image, specified as "nginx:latest".
- Command: A dummy command, "echo Welcome to xfusioncorp!", was executed within the container.
- Restart Policy: The restart policy was set to "OnFailure", ensuring that the cronjob would be restarted if it failed.
# Firstly create a yaml file and upon instruction given to you create your cronjob in the kubernetes cluster. 
<img width="1423" alt="Screenshot 2023-08-31 at 08 30 14" src="https://github.com/boltpius/Creating-a-Cronjob-in-kubernetes/assets/127052041/fa94692b-ced9-4e42-9567-a3bceacd2d63">
<img width="1423" alt="Screenshot 2023-08-31 at 08 31 24" src="https://github.com/boltpius/Creating-a-Cronjob-in-kubernetes/assets/127052041/6b86fd62-4720-4d4d-8773-845706a36126">
<img width="1423" alt="Screenshot 2023-08-31 at 08 32 20" src="https://github.com/boltpius/Creating-a-Cronjob-in-kubernetes/assets/127052041/b94e539f-6f3d-433c-97d0-cee36eb8fb38">
