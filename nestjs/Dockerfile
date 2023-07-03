FROM	node:18-alpine
# WORKDIR를 지정하면 npm ERR! Tracker "idealtree" already exists 에러가 발생하지 않는 이유 알아보기
WORKDIR	/application
RUN		npm install -g @nestjs/cli
RUN		npm install @nestjs/typeorm typeorm reflect-metadata pg
CMD		sleep infinity
