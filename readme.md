Steps to run the helm chart -
1. Clone the Git repo https://github.com/ce-waiops-helm-chart/waiops-event-manager
2. Go to root directory (waiops-event-manager)
3. Connect to OpenShift Cluster
4. Run below command <br />
    a. helm install <appname> ./install-emgr <br />
    b. If 030-global-image-pull-secret.yaml doesn't work, then please create "ibm-entitlement-key" secret for docker registry. <br />
5. Entire process might take a while to execute all the dependencies and change the status as OK or READY inside "evtmanager" instance of "IBM Cloud Pak for Watson AIOps Event Manager" operator.
