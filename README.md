# kt_05_18
KT AIVLE SCHOOL 3기 AI개발자 트랙

팀원: 이현지(팀장, 데이터 분석, AI개발), 김예찬(BE, DB), 김철우(BE, DB), 박미나(UI/UX, 데이터 분석, AI개발), 오재욱(FE, 데이터 분석), 이충영(FE, BE, DB), 최정윤(FE, UI/UX)

주제: ChatGPT를 활용한 리더 GROW 코칭 실습 서비스

🛠기술스택🛠
<div>
 <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/>
 <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=Vue.js&logoColor=white"/>
 <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=Django&logoColor=white"/>
 <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"/>
 <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
</div>

[선정배경] 

 기업 내 리더들에 대한 코칭 교육은 소규모 그룹훈련으로 진행되기 때문에 높은 비용이 발생하고 전문코치들을 활용한 그룹훈련 방식이기 때문에 훈련 기간이 길게 소요된다. 또한 빈번한 리더들에 대한 집합 교육은 조직운영의 효율성을 저하시킨다. 

 리더들의 자발적 코칭 역량 향상에 대한 니즈가 점진적으로 강화되었지만 코칭 역량의 숙련을 위한 코칭 대상을 확보하기가 쉽지 않은 상황이다. 

 이러한 팀원과의 코칭 전에 코치는 스스로 예상되는 주제에 대한 사전 코칭 훈련의 필요성을 느끼게 되었다. 

 

[기대효과] 

 AI를 이용한 가상의 코칭 대상과의 대화 시뮬레이션, 일명 롤플레잉을 통해 코치가 어떤 질문을 했을 때 어떤 답변을 받을 수 있을지를 예상해보며 실제 코칭에서 더 좋은 결과를 이끌어 낼 수 있다.   

 

 또한, 롤플레잉을 통해 여러 변수적인 상황에 대응할 수 있는 훈련을 진행하고 이후 실제 코칭을 진행할 시 유연한 질문으로 수월하게 이끌어 나가며 코칭 능력 향상에 긍정적인 영향을 미칠 것이다. 

 

 추후 해당 서비스를 직무별 역량에 맞추어 영업, 면접, 고객관리 등 여러 상황 및 직무를 위한 훈련 서비스로 확장시킬 수 있다. 

[서비스 주요 기능] 

• 홈 화면 / 서비스 소개 

• 회원가입 / 로그인 

• GROW 코칭대화 모델로 가상대상과의 대화 Role-Playing 

프롬프트 기반 gpt 세팅 

페르소나 설정: 성별, 연령, 직급, 직군 등 선택 가능 

목소리 고르기 : 대화하는 가상 상대(페르소나)의 목소리 선택 가능 

대화 주제 지정 

코칭대화 표본질문 가이드 (팝업창) 

GROW 코칭대화 모델 질문 순서로 샘플 질문 출력 

                    - GROW 각 단계의 표본 질문 리스트화 

                    - 단계별 질문 개수 지정하여 요구 가능 

                    - 질문의 유형(전문가적, 부드러운 등) 지정 가능 

신뢰도 : 롤플레잉을 할 때 맨 처음 기본적인 신뢰도 점수를 제공한 후, 사용자가 대화를 통해 신뢰도 점수가 변화함. 대화가 끝난 후 신뢰도 결과를 bar 형태로 제공함. 이때 다른 사용자의 평균값과 함께 제공함. 이를 랭킹으로 하여 다른 사용자와 비교 가능.  

Web상에서 입력받은 음성 정보를 텍스트로 변환 

대화 시뮬레이션 진행 

질문에서 벗어난 답변을 받을 시 클릭버튼을 통해 정해진 질문 템플릿에서 올바른 질문을 추천받음 

질문도 음성, 답변도 음성으로 가능하게 하여 답변 음성의 목소리를 선택할 수 있게 함.  

• Role-Playing 진행 후 결과 확인 

4개의 평가 요소 (긍/부정성, 질문의 명확도, 대화상대의 대한 이해도, 분위기)에 대한 마름모형 결과 그래프 제공 

신뢰도 결과: 신뢰도 결과를 bar 형태로 제공함. 이때 다른 사용자의 평균값과 함께 제공함. 이를 랭킹으로 하여 다른 사용자와 비교 가능. 

평가 결과에 대한 코멘트 제공 

• 마이페이지 

개인 정보 수정 

시뮬레이터 내역 리스트화 하여 다시보기 (대화내용, 페르소나 등 저장) 

대화 내역 다운로드 

리더십 자기진단 서비스 

포인트 제도 : 대화를 시도하거나, 다른 사람들의 대화에 피드백을 제공했을 시 포인트가 쌓이게 함. 이 포인트를 환전할 수 있게 하여 사내 카페, 구내식당 등에서 사용할 수 있도록 함.   

• 관리자 페이지 

회원관리 : DataBase 관리(분석, 개인정보, 대화내역) 

• 유저 피드백 페이지 

유저들에게 피드백을 요청할 대화내역을 선택해 익명으로 피드백을 요청. 

피드백에는 대화 평가 설문과 개선점 입력이 가능하고 피드백은 요청한 주체가 마이페이지를 통해 확인할 수 있도록 한다. 

피드백 설문을 많이 실시한 유저들에 대해서 포인트를 지급해 피드백 문화가 형성 되도록 유도 

 

[AI 주요 기능] 

•  음성인식 및 텍스트변환 (Speech-To-Text & Text-To-Speech) 

Clova API 또는 Google API를 활용한 STT/TTS 기능 구현 

(STT) 사용자 음성데이터를 텍스트로 변환해 GPT에게 전달,  
채팅 내용으로 표시 

(TTS) GPT의 응답 내용 또는 사용자 채팅 내용을 음성으로 변환 

•  음성인식 후 감정 분류 

목소리의 톤을 구분하여 질문자의 분위기 파악 

•  chatGPT API 활용 및 학습 

•  질문에서 벗어난 답변 분류 및 질문 추천 

•  질문 분석에 따른 결과 추출 

각 질문 마다 피드백이 필요한 부분을 추출하여 개선 방안 등 코칭 

•  가상 상대의 목소리 선택  

 

[주요 기술 스택] 

•  Data & AI 

Python  

Speech API 

Chat GPT api 

Deep Learning (Transformer Model) 

Tacotron2(seq2seq) 

•  Front – End 

Vue.js 

•  Back – End 

Django 

mySQL 


[서비스 FLOW]

![image](https://github.com/AIVLE-School-Third-Big-Project/kt_05_18/assets/116613061/c991c694-a250-4200-8d24-2338b64a46bb)

[관리자 FLOW]

![image](https://github.com/AIVLE-School-Third-Big-Project/kt_05_18/assets/116613061/09c0de51-639c-45c9-b87c-c5e5e6e815c1)
