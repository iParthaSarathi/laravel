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





