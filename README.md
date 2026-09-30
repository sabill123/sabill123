# 한재석 Jaeseok Han

Forward Deployed Engineer @ Letsur (AX팀)

현업의 반복 업무에서 풀 문제를 고르고, 도구로 만들어 붙이고, 사용 지표로 키웁니다.
좋은 모델보다 매일 쓰이는 도구가 성과를 만든다고 생각합니다.

## 경력

| 기간 | 소속 | 역할 |
| --- | --- | --- |
| 2026.01 ~ 현재 | Letsur AX팀 | Forward Deployed Engineer. 고객사 상주 AI·데이터 시스템 구축·운영 |
| 2025.01 ~ 2025.12 | Letsur 영업팀 | AI Consultant·PM. AI 과제 제안, 3일 PoC로 수주 |

- 고객 문의를 3일 안에 PoC로 만들어 보여주는 방식으로 10곳 이상의 고객사 과제를 진행했습니다.
- 사내 공통 도구 4종(데이터 분석 엔진, 이미지·영상 생성 허브, SNS 데이터 수집기, 통합 청구서 생성기)을 운영합니다.

### 대표 사례 (고객사명 비공개)

**K-뷰티 수출무역사 업무 시스템**
요구정의서대로 만들었지만 쓰이지 않던 시스템을 6개월 상주하며 다시 정의했습니다.
스프레드시트 38개를 하나의 DB로 옮기고, 해외 발주 메일의 첨부 파일을 LLM이 읽어 자동 등록하게 했습니다(등록 품목 재현율 96.3%).
1명이 1건에 5일 걸리던 업무를 1명이 10건 동시에 1시간 안에 처리하게 됐고, 3개 부서 약 45명이 쓰는 도구가 됐습니다.

**음악 숏폼 자동 제작 플랫폼 가사 싱크**
결함이 있는 줄만 골라 음성 강제 정렬로 다시 맞추고, 기준을 통과하지 못하면 기존 값을 유지했습니다.
공식 가사 48,775줄 중 시각이 배치된 줄의 비율이 80.8%에서 97.0%로 올랐고, 사람이 고친 소스 9건은 바뀌지 않았습니다.

## 개인 프로젝트

| 프로젝트 | 내용 | 스택 |
| --- | --- | --- |
| [Lilac](https://github.com/sabill123/Lilac) | 한국의 J-POP 팬과 일본의 K-POP 팬을 위한 공연·티켓·앨범·소식 허브. 예매처·판매처·뉴스 원문을 실시간 수집하고 바뀐 것만 SSE로 알림 | TypeScript, Node.js, Vite |
| [ANNA](https://github.com/sabill123/ai-researcher) | Researcher·Engineer·Judge 3개 에이전트가 논문 탐색, 코드 수정, 결과 분석을 반복하는 자율 ML 실험 시스템. 위험한 실험은 승인 게이트를 거침 | Python, Claude Code CLI |
| [Debut](https://github.com/sabill123/debut) | 유닛 이름과 콘셉트를 넣으면 멀티에이전트가 멤버 기획부터 비주얼, MV 시나리오, BGM, 32초 MV 티저까지 제작 | Next.js, FastAPI, Gemini, Veo |
| [Make Shorts](https://github.com/sabill123/shorts-generator) | 키워드 하나로 시나리오, 이미지, 나레이션, 자막을 거쳐 MP4 숏폼을 생성. 긴 영상 하이라이트 추출과 타임라인 편집기 포함 | React, FastAPI, Remotion |
| [Deplight](https://github.com/Softbank-mango/deplight-platform) | SoftBank Hackathon 2025 2위 팀 프로젝트. GitHub Actions와 Terraform으로 AWS ECS 블루/그린 배포, AI 분석기가 PR에 배포 설정을 제안 | Python, Terraform, AWS |
| [NPU 스마트 보안 솔루션](https://github.com/sabill123/Smart_Security_Solution-) | Furiosa NPU에서 실시간 얼굴 탐지·비식별화, 특정 인물은 제외 | Python, YOLOv5, SAM |

## 수상·자격

- AI반도체 기술인재 선발대회 최우수상(정보통신산업진흥원장상), 244팀 중 2위, 2024.12
- SoftBank Hackathon 2025, 2nd Place, 2025.11
- 달서 전국대학생 AI활용 아이디어 콘테스트 입상, 2025.08
- Palantir Foundry Foundations, 2025.08

## 학력

- 숭실대학교 수학과, 연계전공 인공지능반도체 (2027.02 졸업예정)
- SKT FLY AI Challenger 5기 (2024.06 ~ 2024.08)

## 주로 쓰는 것

Python, TypeScript, FastAPI, React, Next.js, PostgreSQL(Supabase), OpenAI·Claude·Gemini API, Claude Code, Codex
