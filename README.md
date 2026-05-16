
# LikeLion Dongguk Univ 14th - FE Week7 Form Tag Session

멋쟁이사자처럼 동국대학교 14기 FE 7주차 **Form 태그 세션 실습 자료**입니다.

## 실습 내용

- Django MTV 구조 이해
- Form 태그 기본 사용법
- 회원가입 / 로그인 Form 구현
- 상품 후기 작성 Form 구현
- 이미지 업로드
- DB 저장 및 화면 출력

## 실행 방법

```bash
git clone https://github.com/LikeLion-at-DGU/14th-fe-form-tag-practice.git
cd 14th-fe-form-tag-practice

python -m venv venv
source venv/Scripts/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py seed_demo
python manage.py runserver
````

## 접속 주소

* Main: `http://127.0.0.1:8000/`
* Auth: `http://127.0.0.1:8000/auth/`
* Review: `http://127.0.0.1:8000/review/`
* Admin: `http://127.0.0.1:8000/admin/`

## Admin 계정

```text
ID: admin
PW: admin
```
