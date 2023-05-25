# DockerImages

클러스터 맥에서 활용할 수 있는 도커 이미지   

1. 원하는 DockerImages의 하위 디렉터리로 이동한다.   

2. 도커 이미지를 빌드한다.

	```bash
	docker build .
	```

3. 도커 이미지 ID를 확인해 백그라운드에서 실행한다.

	```bash
	docker run -d <이미지 ID>
	```

4. 백그라운드에서 실행 중인 도커 컨테이너 ID를 확인한다.
	```bash
	docker ps
	```

5. 해당 컨테이너 내부에 접근한 후 원하는 작업을 수행한다.

	```bash
	docker exec -it <컨테이너 ID> bash
	```

터미널 환경에서 활용할 수도 있지만, vscode 환경에서 컨테이너를 다루고 싶다면 vscode extension인 docker dev를 설치하고 Remote Explorer에서 Containers를 선택한 후 실행중인 컨테이너를 선택하면 vscode에서 다룰 수 있다.