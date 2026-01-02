# kubernetes-mission

- 0001 : 환경 설정 완료
- 0002 : `kubectl` 명령어 사용
- 0003 : `kubectl pod`
- 0004 : `kubectl` - `yaml` 파일 구성
- 0005 : `Multi Container Pod` - `Sidecar`, `Ambassador`, `Adapter`
- 0006 : `Deployment` & `ReplicaSet`
- 0007 : `Scaling` (Horizontal or Vertical) 
- 0008 : `Rolling Update` - `rollout` 명령어
- 0009 : `ClusterIP Service` - 고정된 접점 제공, 로드 밸런싱, 서비스 디스커버리
- 0010 : `NodePort Service` - 외부 접근 허용(30000 - 32767), ClusterIP 기능 포함
- 0011 : `LoadBalancer Service` - 외부 로드밸런서 프로비저닝, 전용 공인 IP 주소 할당, 표준 포트 사용 가
- 0012 : `ConfigMap` - 설정과 코드 분리, 환경별 설정, 중앙 관리
- 0013 : `Secret` - 민감 정보(ex. 비밀번호, API 키), Base64 인코딩 (암호화 X)
- 0014 : 'PersistentVolume(PV) & PersistentVolumeClaim(PVC)'
  - `PV` : 클러스터 레벨의 스토리지 리소스, **관리자**가 미리 프로비저닝, 실제 스토리지 추상화
  - `PVC` : Pod가 PV를 요청, **개발자**가 필요한 용량 및 접근 모드 명시
  - 실제 클라우드 환경에서는 PV를 미리 만들지 않고, PVC를 만들면 자동으로 PV가 생성되는 `동적 프로비저닝`을 주로 사용합니다.
