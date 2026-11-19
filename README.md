# Ansible Infrastructure Automation Labs

멀티 OS(Rocky Linux, Ubuntu) 환경에서의 서버 및 데이터베이스 자동화 실습 저장소입니다.

## 디렉터리 구성
- **test03_playbook**: Ansible 기본 설정(`ansible.cfg`) 및 인벤토리 구성
- **test06_nginx / test06_nginx2**: OS별 변수 분리(`vars/`) 및 조건문(`when`)을 활용한 Nginx 설치·삭제
- **test07_postgre**: Rocky Linux 환경 PostgreSQL 설치, 외부 접속(`pg_hba.conf`) 및 DB/계정 자동 구축
- **test08_role**: Nginx 및 PostgreSQL 배포/삭제 플레이북의 Ansible Role 모듈화 (`site.yml`, `teardown.yml`)
