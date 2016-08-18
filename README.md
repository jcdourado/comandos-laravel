#Comandos Laravel

##Namespace
* Para mudar o nome do namespace
```bash
php artisan app:name nome_namespace
```
##Migrate
* Comando para criar adicionar as migration no banco
```bash
php artisan migrate
```
* Comando para criar as migrate
* Obs: Criar sempre o nome da migrate no plural igual no exemplo (nomes)
```bash
php artisan make:migration create_nomes_table --create=nomes
```
#Model
* Para criar o Model
```bash
php artisan make:model Nome
```
