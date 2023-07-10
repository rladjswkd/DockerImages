FROM	node:18-alpine
# WORKDIR를 지정하면 npm ERR! Tracker "idealtree" already exists 에러가 발생하지 않는 이유 알아보기
RUN		npm install -g @nestjs/cli
# npm package manager로 application 프로젝트를 생성
RUN		nest new application -p npm
WORKDIR	/application
RUN		npm install --save class-validator class-transformer @nestjs/typeorm typeorm reflect-metadata pg
CMD		sleep infinity
