# grafana-dashboard

### docker 설치
- 설치파일 경로 (필수) <br>
https://download.docker.com/win/stable/DockerToolbox.exe

### influxdb 설치 (https://swalloow.github.io/influx-grafana1)
- 도커에 Download & install
> docker powershell 실행하기
```
docker pull tutum/influxdb
```

- Installing latest version 
> 최신 버전은 GUI 버전을 사용할 수 없음
> official download url --> https://portal.influxdata.com/downloads#influxdb
``` bash
$ wget https://dl.influxdata.com/influxdb/releases/influxdb_1.4.2_amd64.deb
$ sudo dpkg -i influxdb_1.4.2_amd64.deb
```

### Install Grafana on a docker container
- Pull Docker Image
```bash
$ docker pull grafana/grafana
```

### 참고 자료
- 설치 Guide <br>
http://pseg.or.kr/pseg/infoinstall/6076

- oracle 연결 <br>
https://github.com/bdrouvot/oracledb-telegraf

- 기타<br>
자주 쓰는 도커 명령어 (http://blog.naver.com/alice_k106/220360418725) <br>
Getting Started (InfluxDB - Grafana - Docker) (https://coderwall.com/p/fg18jq/getting-started-influxdb-grafana-docker)

### How to use docker command (윈도우 기준)
- 이미지 조회    
``` bash
$ docker search ubuntu
```

- 파일 복사하기
> 호스트에서 컨테이너로 파일 전송하는 방법
```
$ docker cp /path/foo.txt mycontainer:/path/foo.txt
```
> 컨테이너에서 호스트로 파일 전송하는 방법 
```
$ docker cp mycontainer:/path/foo.txt /path/foo.txt
```

### Excuting influx
```
$ influx
```
