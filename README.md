# 🥋 BJJ 개인 맞춤 훈련 시스템

Brazilian Jiu-Jitsu 수련생을 위한 AI 기반 개인 맞춤 훈련 프로그램 생성 시스템

## 🌐 온라인 체험
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://parkhookjung-debug.streamlit.app)

## 🥋 주요 기능

### 🎯 맞춤형 훈련 프로그램
- 띠별(화이트~블랙) 난이도 자동 조절
- 자연어 입력으로 개인 목표 분석
- 워밍업-메인-쿨다운 완전한 프로그램 구성

### 📹 실시간 영상 추천
- YouTube에서 관련 기술 영상 자동 검색
- 수준별 맞춤 강사 추천
- 기술별 상세 분석 영상 제공

### 📊 개인 발전 추적
- 훈련 세션별 완주율 및 만족도 기록
- 기술별 숙련도 마스터리 시스템
- 띠별 진행상황 및 승급 가이드

### 🏆 기술 데이터베이스
- 31가지 핵심 BJJ 기술 수록
- 가드, 패스, 서브미션, 스윕 등 전 영역 커버
- 하프가드 특화 기술 시스템 포함

## 🚀 빠른 시작

### 온라인 버전 (추천)
1. 위의 Streamlit App 배지 클릭
2. 데모 계정으로 즉시 체험:
   - 사용자명: `demo`
   - 비밀번호: `demo123`

### 로컬 설치
```bash
# 저장소 복제
git clone https://github.com/parkhookjung-debug/bjj-training-system.git

# 디렉토리 이동
cd bjj-training-system

# 패키지 설치
pip install -r requirements.txt

# 앱 실행
streamlit run bjj_training_improved.py
```

## 📱 사용 방법

### 1. 회원가입 및 로그인
- 현재 BJJ 벨트 레벨 선택
- 개인 프로필 설정

### 2. 훈련 프로그램 생성
```
예시 입력:
"블루벨트입니다. 하프가드 기술 위주로 1시간 집중 훈련하고 싶어요"
```

### 3. AI 맞춤 프로그램 받기
- 자동 생성된 워밍업-메인-쿨다운 프로그램
- 개인 수준에 맞는 기술 난이도 조절
- 예상 소요 시간 및 상세 설명

### 4. 관련 영상 학습
- 생성된 기술별 YouTube 영상 추천
- 수준별 강사 및 튜토리얼 자동 검색

### 5. 훈련 완료 후 기록
- 완주율, 체감 난이도, 만족도 입력
- 기술별 성공/실패 체크
- 개인 메모 및 피드백 저장

## 🎯 지원 벨트 시스템

| 벨트 | 경험 기간 | 최대 난이도 | 특징 |
|------|-----------|-------------|------|
| 🤍 화이트 | 0-12개월 | 2/5 | 기본기 위주, 안전한 훈련 |
| 🔵 블루 | 12-36개월 | 3/5 | 기초 기술 숙련, 연결 기술 학습 |
| 🟣 퍼플 | 36-60개월 | 4/5 | 중급 기술, 개인 스타일 개발 |
| 🟤 브라운 | 60-84개월 | 5/5 | 고급 기술, 교육 역할 |
| ⚫ 블랙 | 84개월+ | 5/5 | 마스터 레벨, 창의적 응용 |

## 🔧 기술 스택

- **Frontend**: Streamlit
- **Backend**: Python 3.8+
- **Database**: SQLite3
- **AI/NLP**: 자연어 처리 알고리즘
- **Data Analysis**: Pandas, NumPy
- **Deployment**: Streamlit Community Cloud

## 📊 시스템 아키텍처

```
사용자 입력 (자연어)
    ↓
NLP 분석 (목표, 레벨, 시간 추출)
    ↓
기술 데이터베이스 쿼리
    ↓
AI 프로그램 생성기
    ↓
개인 맞춤 훈련 프로그램
    ↓
YouTube 추천 시스템
    ↓
훈련 실행 및 피드백 수집
    ↓
개인 통계 업데이트
```

## 🌟 특별 기능

### 하프가드 전문 시스템
- 하프가드, 딥하프가드, Z가드 구분
- 전용 스윕 및 서브미션 기술
- 상대방 관점의 패스 기술 포함

### 실시간 YouTube 통합
- 기술별 최적화된 검색 쿼리 생성
- 수준별 강사 자동 매칭
- 품질 지표 및 추천 이유 제공

### 진보된 통계 시스템
- 기술별 마스터리 레벨 추적
- 띠별 진행상황 시각화
- 개인 발전 패턴 분석

## 🤝 기여하기

이 프로젝트에 기여하고 싶으시다면:

1. 저장소를 Fork
2. 새 기능 브랜치 생성 (`git checkout -b feature/amazing-feature`)
3. 변경사항 커밋 (`git commit -m 'Add amazing feature'`)
4. 브랜치에 Push (`git push origin feature/amazing-feature`)
5. Pull Request 생성

## 🥋 주짓수 수련생을 위한 AI 맞춤 훈련 시스템을 만들었습니다!

✨ 주요 기능:
- 띠별 맞춤 프로그램 자동 생성
- YouTube 영상 실시간 추천  
- 개인 발전 통계 추적

🌐 바로 체험: https://bjj-training8137.streamlit.app/
📱 데모계정: demo / demo123

## 📝 라이센스

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 🙏 감사의 말

- BJJ 커뮤니티의 모든 수련생들
- 오픈소스 기술 영상을 제공하는 강사님들
- Streamlit 팀의 훌륭한 플랫폼

## 📞 연락처

- 프로젝트 링크: [https://github.com/parkhookjung-debug/bjj-training-system.git](https://github.com/parkhookjung-debug/bjj-training-system.git)
- 이슈 리포트: [Issues](https://github.com/parkhookjung-debug/bjj-training-system.git)

---

**"기술보다 중요한 것은 꾸준한 연습이다"** - BJJ 명언

Made with ❤️ for the BJJ community
