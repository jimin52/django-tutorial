# django-tutorial
Repository For the django-tutorial

## 개발 환경
- macOS
- venv
- django
- vscode / vim

## 실행 방법
1. 프로젝트를 클론받는다.
2. 클론받은 폴더 이름은 django-tutorial 일 것일테니 같은 이름으로 venv 를 실행한다.
```bash
python3 -m venv django-tutorial
```
3. 가상환경을 실행한다
```bash
source ./bin/activate
```
4. 저장된 패키지 목록 requirements.txt 를 설치한다.
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
