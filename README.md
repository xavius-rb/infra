# infra
IaC with Terraform

## Usage
```
cd aws_ecs/
docker run -it -v $(PWD):/base_dir --workdir=/base_dir hashicorp/terraform:latest init
docker run -it -v $(PWD):/base_dir --workdir=/base_dir hashicorp/terraform:latest validate
docker run -it -v $(PWD):/base_dir --workdir=/base_dir hashicorp/terraform:latest plan
docker run -it -v $(PWD):/base_dir --workdir=/base_dir hashicorp/terraform:latest apply
```
