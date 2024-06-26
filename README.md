# MyMedicine

## 프로젝트 개요
MyMedicine은 사용자의 의약품 처방 정보를 관리하고 복약 지도를 제공하는 애플리케이션입니다. AI 기술을 활용하여 사용자 경험을 최적화하고, 모바일 앱을 통해 언제 어디서나 편리하게 약 정보를 관리할 수 있습니다.

## 주요 기능
- **회원가입 및 로그인**: 사용자는 앱을 통해 계정을 생성하고 로그인할 수 있습니다.
- **처방 정보 관리**: 사용자는 자신의 의약품 정보를 입력하고 기간별로 관리할 수 있습니다.
- **복약 주의사항 생성**: OpenAI API를 사용하여 자동으로 복약 주의사항을 생성합니다.
- **이미지 처리**: OpenCV를 활용하여 처방전 이미지를 처리하고, 의약품 정보를 추출합니다.

## 사용자 인터페이스
- 로그인 화면
- 회원가입 화면
- 홈 화면(처방 건 목록 및 업로드 버튼 포함)
- 처방 건 상세 정보 화면
- 이미지 업로드 화면
- 사용자 정보 및 수정 화면
- 복약 주의사항 화면

## 개발 환경
- **클라이언트**: Android OS 4.4 이상, Flutter Framework 사용
- **서버**: Ubuntu, AWS EC2 인스턴스, Spring Boot(Tomcat) 사용
- **데이터베이스**: MySQL
