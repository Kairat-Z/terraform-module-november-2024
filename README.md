# terraform-module-november-2024

```hcl
module "november-2024" {
  source  = "Kairat-Z/november-2024/module"
  version = "3.0.0"
  region = "us-east-1"   # Replace with your valies
  vpc_cidr = "10.0.0.0/16"   # Replace with your valies
  subnet_cidr = "10.0.1.0/24"   # Replace with your valies
  igw_name = "Kaizen"   # Replace with your valies
}
```