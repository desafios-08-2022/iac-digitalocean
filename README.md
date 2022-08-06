# iac-digitalocean

crie e populo o arquivo rterraform.tfvars conforme exemplo
o Token da DO é na console no menu API

terraform plan -out plan1
terraform apply plan1
kubectl apply -f kube-news/k8s/deployment.yaml

espere gerar o IP e acesse a aplicação e faça seus testes

terraform destroy