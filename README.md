# jspolicy-for-autoscaler
Before you start create API-key and default type Secret "env-for-jspolicy" in kube-system namespace with key-value:
key "RANCHER_AUTH", in value your API-key 
key "RANCHER_URL", in value rancher url without "https://"
key "values.yaml",  in value "env:
                                RANCHER_AUTH: "your API-key"    
                                RANCHER_URL: "rancher url without https://""

After that your can add this repo to your GitOps in Rancher