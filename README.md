#Comandos Laravel

##Namespace
* Para mudar o nome do namespace
```bash
php artisan app:name nome_namespace
```
##Migrate
* Comando para adicionar as migration no banco
```bash
php artisan migrate
```
* Comando para criar as migrate
* Obs: Criar sempre o nome da migrate no plural igual no exemplo (nomes)
```bash
php artisan make:migration create_nomes_table --create=nomes
```
##Model
* Para criar o Model
```bash
php artisan make:model Nome
```
##Seeders
* Para criar clase de seeders
```bash
php artisan make:seed Nome
```
* Para criar seeders e adicionar no banco
```bash
php artisan db:seed
```
* Para dar um refresh no banco e criar as seeders novamente 
```bash
php artisan migrate:refresh --seed
```
##Tinker
* Para iniciar o tinker
```bash
php artisan tinker
```
###Exemplo do uso de tinker
* Retorna todos os dados do banco da tabela Nomes
```bash
 App\Models\Nome::all();
```
