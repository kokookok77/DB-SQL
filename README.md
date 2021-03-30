# DB-SQL

## SQL 활용 및 DB 공부 정리

### 1. 주차
#### HIVE 와 Impala
      HIVE
      - Map/Reduce를 기반으로 한다. 무겁고, High Latency
      - Fault Tolerant 하다. (즉, 작업 중 일부 worker node에 문제가 생겨도 정확한 결과를 보장할 수 있다.)
      - 대용량 테이블 간의 조인 연산이 효율적
      - Data Engineers
      
      Impala
      - Massively Parallel Processing (MPP) 기반으로 RAM을 많이 차지한다.
      - Low Latency("빠르다!"), 즉각적으로 쿼리를 실행하여 결과를 보고 싶을때 유용
      - Data Analyst / Data Scienctist
      - parquet 파일 포맷을 지원

      reference : https://www.youtube.com/watch?v=vmiWOlcnFW8

