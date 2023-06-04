목표: 화성땅 구매자의 정보의 추가와 전체 구매자의 주문건수 자동로딩
환경: Flask, mongoDB
구현계획:
이름, 주소, 평수를 선택 후 [주문하기] 버튼으로 POST 했을 때 하단에 주문목록이 모두 나오도록 GET 진행하기.



* 구조 생성

1. 폴더생성 후 app.py만들고 가상환경(venv) 을 잡는다. (이름 변경 가능)
$ python -m venv venv

2. 새폴더 -> templates 만든 후 index.htm 생성하기 (templates 스펠링오타 주의하기)
3. app.py에서 flask 라이브러리를 담기
$ pip install flask
4. 데이터베이스(mongoDB) 도구 설치
$ pip install pymongo 
$ pip install dnspython

