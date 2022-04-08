## 프로젝트 생성

---

```bash
django-admin startproject [site-name]
```

## 개발 서버 실행

---

- 운영사이트 배포는 웹서버에 바꿔서 올려야한다.

```bash
python manage.py runserver
```

## 앱 생성 (in 프로젝트)

---

```bash
python manage.py startapp [app-name]
```

## Migration

---

```bash
# migration 생성
python manage.py makemigrations [app-name]
# migration 실행
python manage.py migrate
```

## Django Shell 실행

---

```bash
python manage.py shell
```

## 어드민 페이지 실행

---

```bash
python manage.py createsuperuser
```
