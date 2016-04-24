# ubuntu-python
Python(Django)の開発環境を構築します。

## 必要

* Mac 10.11.4
* Vagrant 1.8.1
* VirtualBox 5.0.14
* Ansible 2.0.1.0

## 開発環境

* Ubuntu 15.10
* Python 3.5.1
* Mysql 5.6.30
* Django 1.9.4

## 実行

* Host(Mac)

      $ git clone git@github.com:ksk-saka/ubuntu-python.git
      $ cd ubuntu-python
      $ vagrant up
      $ vagrant ssh

* Client(Ubuntu)

      $ cd mysite
      $ python3 manage.py runserver 0.0.0.0:8000

## 確認

    http://192.168.33.12:8000/
    -> Django Welcome!