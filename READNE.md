# DATABASE DOCKER

이 문서는 PostgreSQL과 Redis를 Docker 컨테이너로 실행하는 방법과 설정에 대해 설명합니다.

> ❗ `Docker` 및 `Docker Compose`가 설치되어 있어야 합니다.

## PostgreSQL

PostgreSQL 데이터베이스를 Docker로 설정하고 실행하기 위한 가이드를 제공합니다.

## Redis
Redis는 고속 키-값 데이터베이스로 캐싱 및 세션 관리를 위해 자주 사용됩니다. 이 섹션에서는 Redis를 Docker로 실행하고 구성하는 방법을 설명합니다.

### Redis 실행

Redis를 Docker 컨테이너에서 실행합니다. 데이터 지속성을 위해 **AOF(Append-Only File)** 모드를 활성화합니다.

