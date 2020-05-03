# datetimeserver_demo_cicd_kubernetes

This is a sample project for demo purposes.     

1. Start minikube: minukube start --driver=virtualbox
1. Show info with kubectl: kubectl get nodes, kubectl get pods (nothing)
<!-- 1. Show minikube vm in virtualbox    -->
1. Start Jenkins: in our case: java -jar jenkins.war
1. Start ngrok: First install ngrok and authenticate yourself following the instructions on ngrok website. Then run: ./ngrok http 8080
1. Create credentials for Github and Dockerhub.
<!-- 1. show the Jenkinsfile and the instructions to set up the Jenkins
1. Show 2 different docker file: one for build/test and the other for deploy
1. Show ansible playbook, deployment, service.
-->
1. change the version in the java file: SampleDemoMain.java. and push to github.
1. Execute: minikube service node-service-example. this will open your default browser and show you the website on the running k8s node.
1. Show info with kubectl: kubectl get nodes, kubectl get pods (2 pods)
1. Show Dockerhub
1. Change the version again. Push to github.
1. <!-- show auto refresh--> Refresh the page continously and note zero down time deployment, Show info with kubectl: kubectl get nodes, kubectl get pods (2 pods). <!-- split screen with watch: browser + terminal with: kubectl get nodes --watch -->
1. Show Dockerhub









---------------------------
