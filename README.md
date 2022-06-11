# datadog-test

# step1 Create a kubernetes cluster with ingress on

# step2 Create d deployment and expose to public
 * referring https://kubernetes.io/ja/docs/tutorials/stateless-application/expose-external-ip-address/
 $ kubectl create -f test-deployment.yaml
 $ kubectl expose deployment hello-world --type=LoadBalancer --name=my-service
 
# step3 Access svc via internet on External-IP:Port
 
# step4 Setup single locust
 
