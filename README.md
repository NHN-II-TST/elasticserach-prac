# ElasticSearch for TST
ElasticSearch를 로컬에서 테스트하기 위한 docker compose 파일입니다.  
로컬에서 Docker Engine이 실행 중이어야 합니다.

- Docker Compose
- ElasticSearch 8.4.2
- Kibana 8.4.2

```bash
# 실행
docker-compose up d

# 종료
docker-compose down
```

실행 시 다음과 같은 응답이 나타난다면 ElasticSearch가 정상적으로 실행 중입니다.

```bash
curl -XGET http://localhost:9200
```

![image](https://github.com/NHN-II-TST/elasticserach-prac/assets/60968342/a6d4e974-888b-4771-befd-38e56bb8b0f3)
