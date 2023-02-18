# The Three Musketeers: Kubernetes, ConfigMap & HTML Come Together To View A Webpage

   ![1_eCnrmhea0lnhWtDUnxjJdg Medium](https://user-images.githubusercontent.com/105087652/219882992-bed6c99c-aa01-4a8f-82df-bf6a1683d221.jpeg)

   - [Medium Article](https://aws.plainenglish.io/the-three-musketeers-kubernetes-configmap-html-come-together-to-view-a-webpage-29f6cbae927f)

## Objectives:

### - Spin up two deployments. One deployment contains 2 pods running the Nginx image.
### - Include a ConfigMap that points to a custom index.html page that contains the line “This is Deployment One”.
### - The other deployment contains 2 pods running the Nginx image.
### - Include a ConfigMap that points to a custom index.html page that contains the line “This is Deployment Two”.
### - Create a service that points to both deployments, You should be able to access both deployments using the same IP address and port number.
### - Use the curl command (curl service-IP-address:service-port) to validate that you eventually see the index.html pages from both Deployment 1 and Deployment 2.

## Commands

### - Check nodes running on system
`kubectl get nodes
