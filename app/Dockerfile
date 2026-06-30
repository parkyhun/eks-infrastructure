# Python 3.11 기반 이미지
FROM python:3.11-slim

# 작업 디렉토리 설정
WORKDIR /app

# 파일 복사
COPY main.py .
COPY requirements.txt .

# 라이브러리 설치
RUN pip install -r requirements.txt

# 앱 실행
CMD ["python", "main.py"]

