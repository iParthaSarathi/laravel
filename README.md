# laravel
practice  
# php modules for linux  
sudo apt install openssl php-common php-curl php-json php-mbstring php-mysql php-xml php-zip    
sudo apt install php-mbstring php-xml php-bcmath  

venom@ps:~$ sudo apt-get install composer  
composer global require laravel/installer <= if error delete all file in home >> .config >> composer then try to install from composer  
composer create-project --prefer-dist laravel/laravel travel_list  << to create new project  
nano .env  << to edit .env file 

+===============================================================================================  
APP_NAME=TravelList  
APP_ENV=development  
APP_KEY=APPLICATION_UNIQUE_KEY_DONT_COPY  
APP_DEBUG=true  
APP_URL=http://domain_or_IP  
  
LOG_CHANNEL=stack  
  
DB_CONNECTION=mysql  
DB_HOST=127.0.0.1  
DB_PORT=3306  
DB_DATABASE=travel_list  
DB_USERNAME=travel_user  
DB_PASSWORD=password  
  
+==================================================================================================
go to project folder and run  

$ php artisan serve  
Starting Laravel development server: http://127.0.0.1:8000  
[Sun Dec  6 19:48:44 2020] PHP 7.4.13 Development Server (http://127.0.0.1:8000) started  
# create new controller  
php artisan make:controller PageController  <location << app << http << controllers  


# data flow 
controller return view template to router  

# layout  

If you want to install bootstrap 4 in your laravel 8 project then install following laravel ui composer package to get command:  

composer require laravel/ui  
After successfully install above package then we are ready to install bootstrap 4 with our application.  

we can install two way, one is a simple bootstrap 4 setup install and another is install bootstrap 4 with auth. So let's see both way.  

Install Bootstrap 4  

php artisan ui bootstrap   
Install Bootstrap 4 with auth  
  
php artisan ui bootstrap --auth  
Now we installed bootstrap, you can see your resource directory js folder.  
  
You also need to install npm and run it. so let's run both command:  
  
Install NPM  
  
npm install  
Run NPM  
  
npm run dev  
Now you can work with your bootstrap 4 app.  

  






