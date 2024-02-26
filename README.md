# django-tutorial
Repository For the django-tutorial

## 개발 환경
- macOS
- python3.7
- venv
- django

## 실행 방법
1. 프로젝트를 클론받는다.
2. 클론받은 프로젝트 안에서 venv 가상환경을 만든다.
```bash
python3 -m venv venv 
```
3. 가상환경을 실행한다
```bash
source ./venv/bin/activate
```
4. 가상환경에 저장된 패키지 목록 requirements.txt 를 설치한다.
```bash
python -m pip install -r requirements.txt
```
5. django-site 디렉토리로 들어가서 django project 를 시작한다.
```bash
cd django-site
python manage.py runserver
```

## 진행 세부 내용
- [블로그](https://jimin52.hashnode.dev/django) 에서 진행 세부 내용을 확인할 수 있다.
