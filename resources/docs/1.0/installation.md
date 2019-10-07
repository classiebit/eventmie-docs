# Installation

Eventmie can be installed via composer. Easy... 🍻

---

> {info.fa-youtube} Here's a complete video tutorial guide for getting started quickly **[Eventmie Academy](https://classiebit.com/academy/eventmie/getting-started)** ✌️

---

- [Prerequisites](#Prerequisites)
- [Install](#Install)


<a name="Prerequisites"></a>
## Prerequisites

* Laravel version 5.5 / 5.6 / 5.7 / 5.8
* Make sure to install Eventmie package on a **Fresh** or **Existing** Laravel application. 
* We also assume that you've setup the database.


<a name="Install"></a>
## Install

1. Install via Composer

    ```php
    composer require classiebit/eventmie
    ```

2. Install Eventmie without dummy data simply run

    ```php
    php artisan eventmie:install
    ```

    or with dummy data

    ```php
    php artisan eventmie:install --with-dummy
    ```