# Streamlit Example - 데이터 시각화 웹 애플리케이션

## 프로젝트 개요
이 프로젝트는 **Streamlit을 활용한 대화형 데이터 시각화 예제 애플리케이션**입니다.
사용자는 슬라이더를 조정하여 나선형(spiral) 패턴을 생성하고, 이를 시각적으로 확인할 수 있습니다.

## 주요 기능
- **Streamlit UI 제공** (사용자 입력 가능)
- **나선형 데이터 패턴 생성** (`math` 모듈 활용)
- **Altair를 이용한 데이터 시각화**

## 프로젝트 구조
```
streamlit-example/
│── streamlit_app.py  # Streamlit 웹 애플리케이션 실행 파일
│── requirements.txt  # 필요 라이브러리 목록
│── .devcontainer/
│   ├── devcontainer.json  # VS Code 개발 환경 설정
│── README.md  # 프로젝트 설명 파일
```

## 설치 및 실행 방법
### 1. 필수 라이브러리 설치
```bash
pip install -r requirements.txt
```

### 2. Streamlit 애플리케이션 실행
```bash
streamlit run streamlit_app.py
```

### 3. 웹 UI 접속
```
http://localhost:8501/
```

## 필요 라이브러리
- `streamlit`
- `pandas`
- `altair`
- `math`

## 기여 방법
1. 본 레포지토리를 포크합니다.
2. 새로운 브랜치를 생성합니다.
3. 변경 사항을 커밋하고 푸시합니다.
4. Pull Request를 생성하여 기여합니다.

## 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.

