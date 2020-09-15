# ~tutorial vote app ~part2

## python 가상환경 설정
python3 -m venv env-name

## 가상환경 실행
### windows
env-name\Scripts\activate.bat
### mac or linux
source env-name\bin\cativate

## 프로젝트 생성
django-admin startproject site-name

## 웹 개발 서버 실행 (실재 배포는 웹 서버로 바꿔서 올려야 함!!)
python manage.py runserver

## 프로젝트 내 앱 생성!
python manage.py startapp app-name

## migration 관련 명령 (app-name/models.py 및 site-name/settings.py 수정 후)
### migration 생성
python manage.py makemigrations app-name
### migration 실행
python manage.py migrate

## 쉘 실행
python manage.py shell

## 관리자 실행
python manage.py createsuperuser
>> id, email, password 설정



