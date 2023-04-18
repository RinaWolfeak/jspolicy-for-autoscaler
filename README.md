# *jspolicy-for-autoscaler*
Before you start create __API-key__ and default type __Secret__ "env-for-jspolicy" in kube-system namespace with key-value:<br>
- key "values.yaml",  in value: 

```
env:
  RANCHER_AUTH: "your API-key"    
  RANCHER_URL: "rancher url without https://"
```

After that your can add this repo to your GitOps in Rancher