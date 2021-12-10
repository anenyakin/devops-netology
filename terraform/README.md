# исключить все файлы внутри скрытой папки .terraform не зависимо от поддиректорий
**/.terraform/*
#исключить файлы с расширением .tfstate и .tfstate.* во всех директориях
*.tfstate
*.tfstate.*
#Исключить файл crash.log во всех директориях
crash.log
#исключить файлы с расширением .tfvars во всех директориях
*.tfvars
#исключить файлы override.tf, override.tf.json и содержащие *_override.tf, *_override.tf.jso во всех директориях
override.tf
override.tf.json
*_override.tf
*_override.tf.jso
#Исключить файл terraform.rc и .terraformrc  во всех директориях
.terraformrc
terraform.rc