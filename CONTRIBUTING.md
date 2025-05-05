# 기여 가이드

Discord Webhook Logger에 기여해주셔서 감사합니다! 이 문서는 프로젝트에 기여하는 방법을 설명합니다.

## 기여 방법

1. **버그 리포트**
   - GitHub Issues에서 버그를 보고해주세요
   - 버그 재현 방법을 자세히 설명해주세요
   - 예상되는 동작과 실제 동작의 차이를 명시해주세요

2. **기능 요청**
   - 새로운 기능을 제안할 때는 GitHub Issues를 사용해주세요
   - 기능의 목적과 사용 사례를 설명해주세요
   - 가능하다면 구현 방법에 대한 아이디어를 제시해주세요

3. **코드 기여**
   - Fork 후 Pull Request를 보내주세요
   - 코드 스타일 가이드를 준수해주세요
   - 테스트 코드를 포함해주세요

## 개발 환경 설정

1. 저장소를 클론합니다:
   ```bash
   git clone https://github.com/your-username/discord-webhook-logger.git
   cd discord-webhook-logger
   ```

2. 가상환경을 생성하고 활성화합니다:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   # 또는
   .\venv\Scripts\activate  # Windows
   ```

3. 의존성을 설치합니다:
   ```bash
   pip install -r requirements.txt
   ```

## 코드 스타일

- PEP 8 스타일 가이드를 준수합니다
- 타입 힌트를 사용합니다
- 문서화된 함수와 클래스를 작성합니다
- 테스트 코드를 작성합니다

## 테스트

- pytest를 사용하여 테스트를 실행합니다:
  ```bash
  pytest
  ```

## Pull Request 프로세스

1. Fork 저장소에서 새로운 브랜치를 생성합니다
2. 변경사항을 커밋합니다
3. 테스트를 실행하고 모든 테스트가 통과하는지 확인합니다
4. Pull Request를 생성합니다
5. 리뷰를 기다립니다

## 행동 강령

- 모든 기여자는 프로젝트의 행동 강령을 준수해야 합니다
- 건설적인 피드백을 제공합니다
- 다른 기여자를 존중합니다

## 라이센스

기여하신 모든 코드는 MIT 라이센스 하에 배포됩니다. 