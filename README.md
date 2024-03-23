# SamsungZNSOptimzing
graduation paper work

한국컴퓨터종합학술대회 (KCC 2023 – Korea Computer Congress) 학부생 부문 발표

### Samsung ZNS SSD 상에서 RocksDB 최적화
김세란(성균관대), 이보현(성균관대), 박종혁(한국외대), 임수준(삼성전자), 이상원 (성균관대)

삼성의 ZNS SSD는 타사 제품에 비해 작은 존의 크기를 가진 것이 특징이며, 이에 따라 삼성은 작은
존의 병렬성을 극대화 하도록 하는 에코시스템을 개발하였다.[1] 그러나 같은 에코시스템 상에서도 함께 사용할 수 있는DBMS인 RocksDB의 파라미터 값에 따라서도 성능이 향상될 수 있다. 본 논문은 존의 크 기가 작은 삼성의 ZNS SSD와 이에 최적화된 에코시스템 상에서 ZNS SSD의 병렬성과 관련된 RocksDB 파라미터인 컴팩션 잡의 파티션 개수, 백그라운드 쓰레드 개수, L0계층에서의 파일 개수 3가지 파라미터 값에 대하여 각각 RocksDB 성능에 어떠한 영향을 미치는 지 알아본다. 실험 결과 백그라운드 쓰레드 개 수가 삼성 ZNS 상에서 RocksDB 성능을 가장 크게 개선하며, 백그라운드 개수의 증가 역시 성능 향상에 도움이 되지만, 컴팩션 잡의 파티션 개수는 성능 향상에 큰 관련이 없음을 확인하였다.

https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11488479


working at
VLDB@SKKU




