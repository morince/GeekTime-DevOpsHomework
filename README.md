```
# 先删除 k3s state
terraform state rm 'module.k3s'
terraform destroy -auto-approve
```