export SUBSCRIPTION_ID=$(az account show --query id -o tsv)
terraform plan -var="subscription_id=$SUBSCRIPTION_ID"

------------------
1. rg
2. vnet
3. subnet
4. public_ip
5. network_interface
6. sec_gr
7. security_group_association
8. linux_vm