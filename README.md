# ARM-LAB3
my-lab

az deployment group validate \
  --resource-group asiwaju-cloud-lab \
  --template-file template.json \
  --parameters @parameters.json

  az deployment group show \
  --resource-group asiwaju-cloud-lab \
  --name template.json

  az vm list-ip-addresses \
  --resource-group asiwaju-cloud-lab \
  --name <VM_NAME> \
  -o table
