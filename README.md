# Arq_Seguridad_Cloud
## Arquitectura propuesta 
<img width="1026" height="1021" alt="image" src="https://github.com/user-attachments/assets/a07ffd3d-273c-4773-b819-7a814eaefcb4" />
## Organizacion Proyecto
```text
/data-plaftform tf
|
|-- /environments
| |-- /dev
| | |-- main.tf
| | |-- terraform.tfvars
| |  -- backend.tfvars
| |-- /prd
| | |-- main.tf
| | |-- terraform.tfvars
| |  -- backend.tfvars
|
-- /modules
    |-- /vpc
    |-- /alb
    |-- /ecs_service
    |-- /rds
    |-- /elasticache
    |-- /WAF
    |-- /Route53
```
