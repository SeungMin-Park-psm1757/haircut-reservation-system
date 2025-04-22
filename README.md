# 이발 예약 시스템

학교 교직원을 위한 이발 예약 시스템입니다.

## 주요 기능

- 30분 단위로 예약 가능
- 시간당 최대 2명까지 예약 가능
- 공휴일 자동 감지 (양력, 음력)
- 모바일 친화적인 UI
- 관리자 설정 (운영 시간, 휴일 관리, 예약 관리)

## 설치 방법

1. 저장소 클론
```bash
git clone https://github.com/SeungMin-Park-psm1757/haircut-reservation-system.git
cd haircut-reservation-system
```

2. 가상환경 생성 및 활성화
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

3. 패키지 설치
```bash
pip install -r requirements.txt
```

4. 환경변수 설정
```bash
# .env 파일 생성
SECRET_KEY=your-secret-key
ADMIN_PASSWORD=your-admin-password
```

5. 서버 실행
```bash
python app.py
```

## 사용 방법

1. 웹 브라우저에서 `http://localhost:5000` 접속
2. 원하는 날짜와 시간 선택
3. 예약자 정보 입력
4. 예약 완료

## 관리자 기능

1. `/admin` 페이지에서 관리자 로그인
2. 운영 시간 설정
3. 휴일 관리
4. 예약 관리