### Date
7th Nov 2021
### Location of deployed application

- App - https://thinkfic-app.devopsonline.co.in/

Username - bikram
Password - xtMDG7jUze

- Monitoring Matrics - https://thinkfic-app.devopsonline.co.in/metrics

- ElasticSearch UI - http://34.125.150.162:9200/_cat/indices?v

- Kibana dashboard - http://34.125.150.162:5601/

- Kibana logs - http://34.125.150.162:5601/app/discover#/?_g=(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:now-15m,to:now))&_a=(columns:!(),filters:!(),index:'7c87b1d0-3f1a-11ec-bded-fb6e57d7217c',interval:auto,query:(language:kuery,query:''),sort:!(!('@timestamp',desc)))

- Setup documents - https://docs.google.com/document/d/1Z9_EHD8VtutKU8ed6JnpQKgZ2AgLW0s4rWySARE4th8/edit?usp=sharing

### Time spent
8 hours 
### Assumptions made
- To enable HTTPS for the application, I have used let's encrypt SSL certificate with Nginx.
- Also used my personal domain for making HTTPS
- To display the application logs I have used the EFK solution.
- Drawn an architecture diagram assuming ruby on rails as backend and frontend application with autoscaling.
- I have also drawn another architecture diagram considering angular as frontend, laravel as backend with ECS Fargate service with autoscaling. 

### Shortcuts/Compromises made
Yes, Instead of ec2 deployment, we can use ecs fargate deployment. I have also mentioned ECS fargate architecture.
### Stretch goals attempted

### Instructions to run assignments locally
If We want to run the same setup, we can just follow the setup document attached in the mail.
### What did you not include in your solution that you want us to know about?
- I have included the EKF solution that was not mentioned in this task.
- I have also provided one more architecture diagram that is not part of the task.

### Other information about your submission that you feel it's important that we know if applicable.
### Your feedback on this technical challenge

I have created a very simple document for those who want to do the setup from the scratch with all steps.
Personally, I like all tasks
