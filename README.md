# datadog-test

# step1 Create a kubernetes cluster with ingress on

# step2 Create d deployment and expose to public
 * referring https://kubernetes.io/ja/docs/tutorials/stateless-application/expose-external-ip-address/　　<br>
 $ kubectl create -f test-deployment.yaml　　<br>
 $ kubectl expose deployment hello-world --type=LoadBalancer --name=my-service　　<br>
 
# step3 Access svc via internet on External-IP:Port
 
# step4 Setup single locust
  $　source .env/bin/activate <user virtual env>  
  * refeering https://docs.locust.io/en/stable/running-in-docker.html <br>
  > docker-compose.yml <br>
  > locustfile.py <br>
 
