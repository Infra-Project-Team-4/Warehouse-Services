# Python 3.12 기반 이미지
FROM python:3.12-slim

# 작업 디렉터리
WORKDIR /app

# requirements 복사
COPY requirements.txt .

# 라이브러리 설치
RUN pip install --no-cache-dir -r requirements.txt

# 프로젝트 전체 복사
COPY . .

# Flask 포트
EXPOSE 5000

# Flask 실행
CMD ["python", "app.py"]
