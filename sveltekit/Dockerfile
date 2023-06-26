FROM	ubuntu:latest
RUN		apt-get update && apt-get install -y git curl wget
# https://github.com/nodesource/distributions 설명글 참고해서 nodejs 설치하기. 아래는 18 버전
RUN		curl -fsSL https://deb.nodesource.com/setup_18.x | bash - && apt-get install -y nodejs
CMD		sleep infinity

# npm create svelte@latest my-app
# cd my-app
# npm install
# npm run dev