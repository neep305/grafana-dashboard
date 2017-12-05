# grafana-dashboard

### docker 설치
- 설치파일 경로 <br>
https://download.docker.com/win/stable/DockerToolbox.exe

- 설치 Guide <br>
http://pseg.or.kr/pseg/infoinstall/6076

- oracle 연결 <br>
https://github.com/bdrouvot/oracledb-telegraf

- 참고자료<br>
http://blog.naver.com/alice_k106/220360418725

#### 도커 실행 (윈도우 기준)
- 이미지 조회    
``` bash
$ docker search ubuntu
```

- 파일 복사하기
1. 호스트에서 컨테이너로 파일 전송하는 방법
```
$ docker cp /path/foo.txt mycontainer:/path/foo.txt
```
2. 컨테이너에서 호스트로 파일 전송하는 방법 
```
$ docker cp mycontainer:/path/foo.txt /path/foo.txt
```

### influxdb 설치
https://portal.influxdata.com/downloads#influxdb
``` bash
$ wget https://dl.influxdata.com/influxdb/releases/influxdb_1.4.2_amd64.deb
$ sudo dpkg -i influxdb_1.4.2_amd64.deb
```
