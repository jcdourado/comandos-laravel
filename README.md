#Comandos Laravel

##Servindo a aplicação
* Para servir a aplicação (estará disponível no localhost:4000)
```bash
php artisan serve
```
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
* Para dar rollback
```bash
php artisan migrate:rollback 
```
##Model
* Para criar o Model
```bash
php artisan make:model Nome
```
##Controller
* Para criar o Controller
```bash
php artisan make:controller Nome
```
##Request
* Para criar um Request (para validações de formulários)
```bash
php artisan make:request Nome
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
