# Kubernetes-task4
Task 4

A) Create a deployment:
	* Name: nginx-app
	* Using container: nginx:1.14.0
	* The deployment should contain 5 replicas
   Next, update the app 1.15.1, by performing a rolling update, and record that update.
   Finally, rollback that update to the previous version.
   Records rollout commands into rollout-steps.txt file

B) Launch 3 replicas of the nginx image with the label:app_runtime_stage=staging
   Deployment name: nginx-deploy

C) Scale the deployment nginx-deploy to 6

D) Create group of apps which serve WorpPress:
   - Deployment:
	* Name: wordpress-deployment
	* 3 replicas
	* Use wordpress image
   - MySQL ReplicaSet:
	* Name: mysql-rs
	* 1 replica
	* Use mysql image
	* Use PersistentVolume
   - Expose Wordpress using LoadBalancer service
