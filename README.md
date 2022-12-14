# 尾牙抽獎程式

## Folder Description

- mainWeb.py : 後端程式

  - Python 語法搭配Flask框架
  - Pandas 處理數據

<br>

- templates: html 存放區, Flask 採用Jinja 語法讀取網頁

  - base.html: 網頁主框架
  - mainPage.html: 網頁內容

<br>

- static: 前端程式存放區, Flask 採用Jinja 語法讀取網頁

- unitTest: 測試隨機抽樣功能

- test.xlsx: 測試用檔案

<br>

## Block diagram

<img src='01.png'>

<br>

## How to build

- install Python & packeges

  - Python >= 3.9.13

  - Pandas >= 1.4.4
    
    ```python
    import pandas as pd
    print(pd.__version__) #1.4.4
    ```

  - Flask >= 1.1.2

    ```python
    import flask
    print(flask.__version__) #1.1.2
    ```

  - json >= 2.0.9

    ```python
    import json
    print(json.__version__) #2.0.9
    ```

  - scikit-learn >= 1.0.2

    ```python
    import sklearn
    print(sklearn.__version__) #1.0.2
    ```

- Run mainWeb.py in terminal

  ```
  python mainWeb.py
  ```

<img src='03.png'>

## Angular & ASP.NET

### How to build

- Nuget install the followings in VS2019:

  - Dapper 2.0.123

  - Oracle.ManagedDataAccess 21.8.0

- VS code

  ```
  cd 尾牙抽獎專案/ASP_Test/EndYear/EndYear/angular
  rm -rf node_modules
  rm -rf dist
  npm install
  npm run build
  ```

### Run project

- Open EndYear.sln by VS2019

- Run/build the project 

- Key in: http://localhost:60623/angular/dist/content on browser

<img src='02.png'>


