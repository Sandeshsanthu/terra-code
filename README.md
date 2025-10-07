# terra-code

git filter-branch -f --index-filter 'git rm --cached -r --ignore-unmatch .terraform/'

terraform plan -var-file="vars/east-us-2.tfvars"


terraform apply -var-file="vars/east-us-2.tfvars"
