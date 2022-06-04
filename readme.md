# Download the plugins
terraform init

# Provision the NGINX server container
terraform apply

# Verify NGINX instance
docker ps

# Destroy the resource
terraform destroy