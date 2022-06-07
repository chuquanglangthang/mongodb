**_Basic commands_**
```
mongosh // mở thông tin phiên bản sử dụng
cls // clear screen
```
/* hệ thống mặc định trỏ đến test database */
test> // db mặc định ban đầu, không tồn tại, mục đích là để nhắc mình tạo db

/* tại test> */
show dbs // hiện các db và file hiện có
use <name-db-you-want-to-use> // create a new database or use an existed database
e.g: use demo // create a new db named 'demo'

/* write commands in demo */ demo>
show collections // collections = tables inside of database
db.dropDatabase() // delete db
 