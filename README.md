# devops-netology
first redaction
# В файле .gitignore в папке terraform будут игнорироваться:
 - все файлы в каталоге .terraform/
 - Файлы с расширением .tfstate и .tfstate.
 - файл crash.log и любые файлы конструкции crash.*.log (например crash.123.log)
 - файлы c расширением .tfvars и .tfvars.json
 - файлы override.tf, override.tf.json и любые файлы заканчивающиеся на _override.tf и _override.tf.json
 - файл .terraform.tfstate.lock.info
 - файлы .terraformrc и terraform.rc