[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://main--abderrahmaneamerrhiportfoliov2.netlify.app/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abderrahmane-amerrhi-807b40201/)

# The car rental application

The car rental application enables you to rent cars and display cars through the main factory company

Discover [Vedio](https://abderrahmaneamerrhi.com/assets/carrentalprojectved-36a6384e.mp4).

## Information

I built the app using laravel and vuejs, made a simple backend and also used api, created apis using laravel and used them in vuejs components

### Technologies used in Backend

| Technology |        Description        | Version |
| :--------- | :-----------------------: | :-----: |
| Php        |       PHP language        | ^8.0.2  |
| Laravel    | Laravel backend framework |  ^9.11  |

### Technologies used in FrontEnd

| Technology             |                                                                           Description                                                                           | Version  |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------: |
| vuejs                  |                                                                        Vuejs3 Framework                                                                         | ^3.2.36  |
| vue-good-table         |                                                                     vuejs table componenet                                                                      | ^2.21.11 |
| laravel-vue-pagination |                                                            vuejs with laravel pagination componenet                                                             |  ^2.3.1  |
| vuex                   |                                                                     Vuejs state management                                                                      |  ^3.6.5  |
| vue-router             | vuejs router Vue Router is the official router for Vue.js. It deeply integrates with Vue.js core to make building Single Page Applications with Vue.js a breeze |  ^3.5.4  |
| vue-chartjs            |                                                                    vuejs charts componenets                                                                     |  ^4.1.1  |
| moment                 |                                                                            moment js                                                                            | ^2.29.3  |
| scrollreveal           |                                                                     scrollreveal Animation                                                                      |  ^4.0.9  |

⚡️ And other tools used: Visit file package.json

## Cloning and use

```bash or terminal
  # Cloning app
  git clone  https://github.com/AbderrahmaneAmerhhi/car_rental_app

  # install composer
   composer install
   php artisan config:clear
   php artisan config:cache
  # copy .env.example => rename it to .env

  # generate App key
   php artisan key:generate

  # install node_modules
   npm install

```

## Configuration

```env
# in .env file config database

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=yourdatabse_name
DB_USERNAME=root
DB_PASSWORD=databasepassword

# config Mail add your mail configuration

MAIL_MAILER=smtp
MAIL_HOST=mailhog
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"


```

## Migrate database and run app

```bash or terminal
  ########### open app in terminal or cmd or bash ... ###############
  # Migrate data base run in terminal
   php artisan migrate

  # seed database
   php artisan db:seed

  # run app
  php artisan serve
   ## in other terminal
    npm run dev

  # open app in
  http://127.0.0.1:8000

  # login to admin dashboard
   Url : http://127.0.0.1:8000/admin
   Email :   admin@gmail.com
   Password : admin


```

## Features

-   Dynamic backend with laravel Backend framework
-   Responsive front-end with dark mode and other widgets built using vue.js framework

#### Dashboard Features

-   Administrators can manage factory companies for every car, add new companies data, update a companies, delete a companies or archive it. Export company or multiple companies data.
-   Administrators can manage the vehicle, add new vehicle data, update delete or archive a vehicle data. Export vehicle or multiple vehicle data.
-   Track companies cars orders data statistics in charts and cards .
-   Manage show orders
-   change admin profile data

#### User side

-   Visitors can view cars and can send you email Create a new account Log in...
-   To order new car the user must be connected to their own account
-   The user can change their profile data

## Some dashboard images

#### Admin Login

![Admin Login image](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/auth/loginadmin.png)

#### Manage factory companies

![manage cats image](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/catdashboardimage.png)

#### Manage vehicles

![manage products image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/manageproducts.png)
![manage products image2](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/manageproducts2.png)

#### manage admin profile

![manage admins image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/manageadminandadminprofile.png)

#### Manage Orders

![manage Orders image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/manageorders.png)

## Some user side images

#### User Login Register

![User Login image](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/auth/loginuser.png)
![User Register image](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/auth/registerdarkmode.png)

#### Home

![ home image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/home1.png)
![ home image2](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/home2.png)

#### Contact Us

![ Contact image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/contactus.png)

#### Show Porduct

![ Porduct image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/showproduct.png)

#### Cart

![ Cart image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/cart.png)

#### Open Ticktes

![ Open Ticktes image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/openTicket.png)

#### Ticktes

![  Ticktes image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/tickets.png)

#### Invoices

![  invoices image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/invoices.png)

#### User Profile

![  User Profile image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/userprofile.png)

## Some DarkMode images

![  User DarkMode image1](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/frontend/Darkmodefront.png)
![  User DarkMode image2](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/backend/darkmode.png)
![  User DarkMode image3](https://github.com/AbderrahmaneAmerhhi/Digital-store/blob/main/public/Githubfiles/auth/registerdarkmode.png)
