🚀 Ansible Landing Page Deployment

This Ansible playbook automates the deployment of a simple landing page website. It installs and configures all necessary services such as Apache, MariaDB, PHP, and Git, and sets up the backend database and firewall rules.

This playbook is part of a hands-on Ansible course, designed to demonstrate how automation can streamline the setup of a basic web application.


📦 Features

Installs required packages: Git, Apache (httpd), PHP, MariaDB, Python dependencies

Starts and enables services: firewalld, httpd, and mariadb

Configures firewall rules for HTTP and MySQL ports

Creates a MySQL database ecomdb and a user ecomuser

Loads sample product data into the database

Clones a PHP-based e-commerce landing page from GitHub

Replaces hardcoded DB IP in the app with localhost
