# Example how to use Express and TypeORM with TypeScript



## 有關如何把此範例跑起來，可參考此教學。
主要包括mysql安裝和設定db的前置作業，和包括curl測試API的測試
- [mysql + typeorm 初探 - Ben Hu - Medium](https://medium.com/@hupinwei/mysql-typeorm-%E5%88%9D%E6%8E%A2-ff98dc999437)

## 下面是官網教學，照這個步驟走就可以跑起來

1. clone repository
2. run `npm i`
3. edit `ormconfig.json` and change your database configuration (you can also change a database type, but don't forget to install specific database drivers)
4. run `npm start`
5. open `http://localhost:3000/posts` and you'll empty array
6. use curl, postman or other tools to send http requests to test your typeorm-based API

## How to use CLI?

1. install `typeorm` globally: `npm i -g typeorm`
2. run `typeorm -h` to show list of available commands