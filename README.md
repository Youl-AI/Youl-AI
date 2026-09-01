## 김하율 · Hayoul Kim

게임 시스템을 규칙과 수치로 옮기고, 그 결과를 측정으로 확인합니다.
AI 서비스는 기획부터 배포까지 혼자 만듭니다.

### 게임 기획 · 개발

- **[Ephemeris](https://github.com/Youl-AI/Ephemeris)** — 상용 엔진 없이 Vulkan 인프라부터 직접 올린 C++17 실시간 렌더링 엔진. 텍스처를 용도별 포맷으로 압축해 VRAM을 1/4로 줄였습니다.
- **[Surfancer](https://github.com/Youl-AI/Surfancer)** — 오염도 전이 시스템 기반 생존 디펜스 게임. 연세대학교 × KRAFTON 사회적 게임 기획·제작 공모전 **대상**. 기획서 원본과 발표 자료를 `docs/`에 공개했습니다.

### AI · AX 엔지니어링

- **[cited](https://github.com/Youl-AI/cited)** — 여러 LLM 답변에서 브랜드 언급률을 재는 측정 파이프라인. 답이 매번 달라지는 대상이라 점추정 대신 신뢰구간으로 보고하고, 판정기 자체를 수작업 골드셋 248건으로 검증했습니다(recall 99.1% · precision 100%). [cited.co.kr](https://cited.co.kr) 운영 중.
- **[claude-pet](https://github.com/Youl-AI/claude-pet)** — Claude Code 세션 상태에 반응하는 Windows 데스크톱 펫. C# · WPF로 스프라이트 렌더 루프와 상태 머신을 직접 짰습니다. "작업을 1%도 방해하지 않는다"를 설계 제약으로 두고 유휴 CPU 0.0% · 메모리 61~66MB까지 줄였고(측정 전 84~110MB), 코어 로직은 단위 테스트 190개가 붙잡고 있습니다.
- **[byeolsaem](https://github.com/Youl-AI/byeolsaem)** — 태어난 순간의 행성 배치를 브라우저에서 직접 계산하는 천궁도 서비스. 구 버전이 서버 왕복에 쓰던 14.7초가 통째로 사라졌고, 해석은 LLM 없이 조립해 같은 입력이면 언제 다시 열어도 같은 글이 나옵니다. [byeolsaem.com](https://byeolsaem.com)
- **[Nexus](https://github.com/Youl-AI/Nexus)** — 게임 패치 노트를 근거로 답하는 RAG 어시스턴트. LangChain · FAISS
- **[Nuggy](https://github.com/Youl-AI/Nuggy)** — 미세 구조를 보존하는 배경 제거 서비스

### 연구

한국정보과학회 KCC 2021 논문 2편 — 제1저자 1편, 공동저자 1편

- **[Class-Balanced-FewShot-Fault-Diagnosis](https://github.com/Youl-AI/Class-Balanced-FewShot-Fault-Diagnosis)** — 분포의 중심에 가까운 대표 표본부터 뽑는 규칙으로 분류 정확도 5~17% 향상 (제1저자)
- **[Triplet-Graph-Transformer-Malware](https://github.com/Youl-AI/Triplet-Graph-Transformer-Malware)** — 제어 흐름 그래프 임베딩으로 백도어 탐지 재현율 37.5%p 향상 (공동저자)
- **[Few-Shot-Color-Constancy](https://github.com/Youl-AI/Few-Shot-Color-Constancy)** — 카메라 센서 간 색 복원. 오차율 15% 감소, 졸업 프로젝트 최우수상

---

기획서와 코드를 함께 공개합니다.

📫 hayoul1999@gmail.com
