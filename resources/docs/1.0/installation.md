# Installation

Eventmie can be installed via composer. Easy... 🍻

---

> {info.fa-youtube} Here's a complete video tutorial guide for getting started quickly **[Eventmie Academy](https://classiebit.com/academy/eventmie/getting-started)** ✌️

---

- [Prerequisites](#Prerequisites)
- [Install](#Install)
- [Configurations](#Configurations)


<a name="Prerequisites"></a>
## Prerequisites

* Laravel version 5.5 / 5.6 / 5.7 / 5.8
* Make sure to install Eventmie package on a **Fresh** or **Existing** Laravel application. 
* We also assume that you've setup the database.


<a name="Install"></a>
## Install

1. If installing Eventmie on an existing Laravel application and you already have Auth system then **skip this step**

    if installing Eventmie on **Fresh Laravel application** then run 

    ```php
    php artisan make:auth

    php artisan migrate
    ```

2. Install Eventmie via Composer

    ```php
    composer require classiebit/eventmie
    ```

3. Run Eventmie install command

    ```php
    php artisan eventmie:install
    ```


<a name="Configurations"></a>
## Configurations

After installation, you'll see the Eventmie config `config/eventmie` file. You can make the following changes-

<br>

1. Route config - whether to run Eventmie as a base site e.g `example.com` or on a specific url e.g `example.com/myevents`

    ```php
    'route' => [
        'prefix'            => null, // for front-end
        'admin_prefix'      => 'admin', // for admin panel
    ],
    ```



2. RTL Languages - Eventmie detects RTL language from this list and changes site direction accordingly. You can add any other RTL language to the list.

    ```php
    'rtl_langs'        => [
        'ar', // arabic
        'fa', // persian
        'he', // hebrew
        'ms', // malay
        'ur', // urdu
        'ml' // malayalam
    ],
    ```