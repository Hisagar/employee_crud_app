
## Following are steps to setup this project on local.
### Prerequisite :
1. Install Symfony.
2. Install Composer.
3. Install php, mysql & apache web server on your local machine.

### Steps:    
1. Update Mysql Database URL [here](https://github.com/Hisagar/employee_crud_app/blob/master/.env#L27)
2. Create Database as per entity ```php bin/console doctrine:database:create ```
3. Create migration using following commands.
   
   ``` php bin/console make:migration```
   
   ```php bin/console doctrine:migrations:migrate ```
   
5. Run ```composer update``` & ```composer install```
6. Start the Symfony development server : ```symfony server:start```
7. Validate api documentation @ ```http://localhost:8000/api```




## Create
![image](https://github.com/Hisagar/employee_crud_app/assets/32439113/c45fadc4-9ae7-4512-a6e9-893879f5ff03)

## Read 
![image](https://github.com/Hisagar/employee_crud_app/assets/32439113/9877fac3-cc59-4b31-a597-2eafb20d5eaf)

## Update 
![image](https://github.com/Hisagar/employee_crud_app/assets/32439113/8ae24550-7a96-4c90-b413-905d3b1b4831)


## Delete 
![image](https://github.com/Hisagar/employee_crud_app/assets/32439113/4dbdff36-840f-4bd5-9d48-50cbbb5e4380)



