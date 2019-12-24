# graphQL_noSQL
安裝 MongoDB

# 前置作業

    $ npm install apollo-server-express
==> + apollo-server-express@2.9.7

    $ npm install graphql-playground-middleware-express
==> + graphql-playground-middleware-express@1.7.12

# Alternatives

* Postgres

* SQL Server

* Firebase

* MySQL

* Redis

* Elastics

# MongoDB in local, 安裝套件

CLI 

    $npm install mongodb
==> + mongodb@3.3.3

CLI

    $brew services list
    $brew services start
    
==> Searching for similarly named formulae...
These similarly named formulae were found:
mongo-c-driver                           mongo-orchestration
mongo-cxx-driver                         mongoose

# add context to config Apollo Server in index.js, 組態設定

//index.js

normal url 環境變數

    DB_HOST = mongodb://localhost:27017/<db-name>
    
url using mLab 環境變數

    DB_HOST = mongodb://<usranme>:<password>@5555.mlab.com:5555/<db-name>
    
# code to create MongoClient

https://github.com/poupougo/graphQL_noSQL/blob/master/index.js


    
    
    
