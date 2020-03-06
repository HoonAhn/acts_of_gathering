# ActsOfGathering

## Installation Guide

해당 웹 애플리케이션은 동일한 개발 및 테스트의 편의성을 위해서 도커 컨테이너로 구현되었습니다.

그렇기 때문에 도커(Docker)가 설치되어있다는 가정하에 커맨드들이 안내되어 있고,

도커가 설치되지 않은 상태라면 [다음 링크](https://docs.docker.com/install/)를 통해 테스트하는 Host OS에 맞게 도커를 설치해주시기 바랍니다.

도커 설치 이후에는 프로젝트를 내려받습니다.

```
git clone https://github.com/HoonAhn/ActsOfGathering.git
```

이후 프로젝트 디렉토리에서 다음 커맨드를 실행합니다.

```
docker-compose up
```

도커 컨테이너가 안정적으로 실행된 이후에, 다음 주소로 웹페이지에 접근가능합니다.

http://localhost:3000

