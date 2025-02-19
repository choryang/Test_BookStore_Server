# 실행하기 (https://nodejs.org/ko/download/ 참고)

```
   # nvm 다운로드 및 설치:
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

   # Node.js 다운로드 및 설치:
   nvm install 22

   # Node.js 버전 확인:
   node -v # "v22.14.0"가 출력되어야 합니다.
   nvm current # "v22.14.0"가 출력되어야 합니다.

   #npm 버전 확인:
   npm -v # 10.9.2가 출력되어야 합니다.

   git clone https://github.com/choryang/Test_BookStore_Server.git
   cd ./Test_BookStore_Server
   npm install
   node server.js
```
# 기술 스택
Node.js express PostgreSQL Sequelize
