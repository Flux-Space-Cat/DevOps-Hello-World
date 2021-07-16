# Technical Exercise for DevOps - Hello World Project

## The exercise

This is a DevOps exercise aimed at taking a basic HTML application and building an Nginx Dockerfile to contain it. 
You will then create a BitBucket Pipeline yaml file to build your image. 
Finally, you must create Kubernetes manifest file(s) to release your container to a Kubernetes instance.

You will need a BitBucket or GitHub account to push your code to.

## The application

The application resides in the `app` folder. It is a single page, basic HTML file.

## The task?

Fork the repository. You must then:

1. Create a new Dockerfile that extends the base Nginx Dockerfile and import the application files
2. Create Kubernetes manifest files that define a Service and Deployment to release your container to a Kubernetes cluster.

You should push your changes to the forked repository. The repository should be public.

## Bonus Points

If you have time, extend your assignment with the following.

1. Comment your Dockerfile, explaining the steps it's taking. 
2. Update your Dockerfile to copy the application files to `/app` instead. Include a customised Nginx configuration file that expects the application files there.  
3. Update your Kubernetes manifest files to include an Ingress resource definition.
4. Provide the `docker` commands to build and run your container locally on port 3000.
5. If you're using BitBucket, create a BitBucket Pipeline yaml file that defines a simple pipeline to build your image on every commit to the `master` branch

## Useful links

- https://hub.docker.com/_/nginx
- https://support.atlassian.com/bitbucket-cloud/docs/configure-bitbucket-pipelinesyml/
- https://kubernetes.io/docs/concepts/cluster-administration/manage-deployment/

## Further help and assistance or Questions?

Good luck, and if you've any questions, please contact Max or Jay via hr@capital-iom.com for assistance.