# Implement the CI/CD pipeline for deploying application on GKE

1. create two simple Flast app (app1 and app2)
2. setup a github repository and push the app code
3. create two GKE cluster: dev-cluster and prod-cluster, using GKE
4. create kubernetes manifest files in the kubernetes folder to deploy the app and expose it as a service
5. create skaffold.yaml file 
6. now create cloudbuild.yaml file to build and push docker image to artifact registry for both app and configure the cloud build trigger to initiate the pipeline upon code push event in thr GitHub
7. implement the necessary code to define the cloud deploy pipeline and target for both dev and prod cluster
8. push the updated code to the github repo, trigger the cloud build and deploy process