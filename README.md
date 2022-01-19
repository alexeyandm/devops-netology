First line in file README

# Local .terraform directories
<**/.terraform/*> - игнорироваать все вложенное в папку ".terraform" (где бы эта папка не находилась, не выше Terraform по иерархии) 

# .tfstate files
<*.tfstate> - игнорироваать все файлы, оканчивающиеся на ".tfstate" (во всех папках, не выше Terraform)
(*.tfstate.*) - игнориировать все файлы, оканчивающиеся на ".tfstate.*" (во всех папках, не выше Terraform), где "*" - любой 0 или более символ

# Crash log files
(crash.log) - игнорировать этот файл (во всех папках, не выше Terraform)
(crash.*.log) - игнорироваать файлы с данной маской (во всех папках, не выше Terraform), где "*" - любой 0 или более символ

# Exclude all .tfvars files
(*.tfvars) - игнорировать файлы, оканчивающиеся на ".tfvars" (во всех папках, не выше Terraform)

# are not checked in
(override.tf) - игнорировать этот файл (во всех папках, не выше Terraform)
(override.tf.json) - игнорировать этот файл (во всех папках, не выше Terraform)
(*_override.tf) - игнорировать файлы, оканчивающиеся на "_override.tf" (во всех папках, не выше Terraform)
(*_override.tf.json) - игнорировать файлы, оканчивающиеся на "_override.tf.json" (во всех папках, не выше Terraform)

# Ignore CLI configuration files
(.terraformrc) - игнорировать эту папку/файл (во всех папках, не выше Terraform ) 
(terraform.rc) - игнорировать этот файл (во всех папках, не выше Terraform)
