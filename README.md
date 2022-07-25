# node.js_postgresql_jwt
node.js demo for jwt authentication with postgresql 

ref. https://www.bezkoder.com/node-js-jwt-authentication-postgresql/

node.js
postgresql
jwt
sequelize
express

## Study
1. postgre 실행 오류 발생
```ConnectionError [SequelizeConnectionError]: database "testdb" does not exist```
testdb가 존재함에도 불구하고 오류 발생 -> 다른 db로 변경하여 사용
testdb 권한이 없는 문제라고 판단

2. 파일 올린 후 gitignore 적용 방법
```
git rm -r --cached [취소하고자 하는 파일 또는 폴더]
```
후 다시 올리기

3. sequelize **belongstomany**