# DRF_Projcet
<br>


## DRF(Django Rest Framework)?
- Django 내에서 REST API 서버를 쉽게 구축할 수 있도록 돕는 오픈소스 라이브러리
- 범용성이 넓고 개발을 쉽게 만들어줌
- Serializer 기능을 제공(DB data -> JSON)
   - Serializer : 복잡한 데이터를 파이썬 데이터 타입에 맞춰 변환 및 렌더링을 쉽게 해줌
    
### REST API
- 어떤 자원에 대해 CRUD 연산을 수행하기 위해 URL로 요청
- GET(Read), POST(Create), PUT(Update), DELETE(Delete) Method를 사용하여 요청
<br>

## DRF 초기 설정

### Library install
- `settings.py` 에서 `INSTALLED_APPS`에 `rest_framework`추가
```
pip install djangorestframework markdown django-filter
```  

### Django Startapp 
- `settings.py` 에서 `INSTALLED_APPS`에 `employee`추가
```
python manage.py startapp employee
```

#### 그 외 설치된 package는 requirements.txt 확인

