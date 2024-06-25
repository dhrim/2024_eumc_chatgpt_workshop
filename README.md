# 2024 이대의대 ChatGPT 워크샾

## 주제
ChatGPT를 사용한 의학 자료의 QnA 엔진 구현(Implementing Questiong and Answering Engine using ChatGPT)

<br>

## 내용
ChatGPT 소개와, 동작 원리, 제한점 등에 대하여 설명하고, ChatGPT를 사용하여 2가지 작업을 진행합니다. <br>
<br>
- 작업1. 네이버지식인의 건강 QnA의 자료를 크롤링하여 이를 ChatGPT로 학습시키고, 건강 질문에 대하여 medical speciality를 예측하도록 합니다.  <br>
- 작업2. ChatGPT를 가지고 논문과 같은 의학문서에 기반한 QnA엔진을 구축합니다.  <br>
<br>
ChatGPT에 대한 소개와 이를 프로그래밍 언어로 호출하기 위한 OpenAI API를 소개합니다. 더불어 ChatGPT의 한계와 의학적 사용에서의 제약등 기반적인 것도 설명 드립니다. 프로그래밍 코드로 실제 동작하는 시스템을 구축합니다.

<br>

# 프로그램

- 09:00 - 09:50 : ChatGPT 소개, OpenAI API 소개 [from_DNN_to_GPT.pptx](from_DNN_to_GPT.pptx)
- 10:00 - 10:50
    - 실습을 위한 환경 준비 [실습위한_환경_준비.pdf](실습위한_환경_준비.pdf)
    - API 단순 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)    
- 11:00 – 11:50 : OpenAI API 실습 #1
    - API 역활 설정과 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)
        - https://platform.openai.com/examples
    - 챗봇 : [practice/tiny_chatbot.ipynb](practice/tiny_chatbot.ipynb)
- 13:00 – 14:50 : 작업1. 지식인 의학 QnA의 전공과 예측
    - ChatGPT 추가 학습 방법 소개 : [practice/how_to_fine_tuning.ipynb](practice/how_to_fine_tuning.ipynb)
    - 지식인 데이터 크로울링 : [practice/task1_medical_speciality.ipynb](practice/task1_medical_speciality.ipynb)
    - 수집된 데이터로 ChatGPT 추가 학습과 Qna 실행 : [practice/task1_medical_speciality.ipynb](practice/task1_medical_speciality.ipynb)
- 15:00 – 16:50 : 작업2. 의학 논문에 기반한 QnA 엔진 #1
    - ChatGPT 임베딩 방법 소개 : [practice/how_to_embedding.ipynb](practice/how_to_embedding.ipynb)
        - 임베딩을 사용한 분류 [practice/classification_using_embedding.ipynb](practice/classification_using_embedding.ipynb)
        - 임베딩을 사용한 추천 [practice/recommendation_using_embedding.ipynb](practice/recommendation_using_embedding.ipynb)
    - 논문 임베딩과 QnA 구현 : [practice/task2_customer_qna_engine.ipynb](practice/task2_customer_qna_engine.ipynb)

<br>

# 워크샾 자료

- [ChatGPT_소개.pdf](ChatGPT_소개.pdf)
- GPT 구조 : [from_DNN_to_GPT.pptx](from_DNN_to_GPT.pptx)
- 실습 준비 : [실습위한_환경_준비.pdf](실습위한_환경_준비.pdf)
- [OpenAI_API_사용_기초.pdf](OpenAI_API_사용_기초.pdf)


<br>

# 참고 자료

- OpenAI 홈 : https://openai.com/
- ChatGpt 홈 : https://chat.openai.com/
- OpenAI Platform 홈 : https://platform.openai.com/
    - API 레퍼런스 : https://platform.openai.com/docs/api-reference
    - 웹에서 설명한 사용 예제 : https://platform.openai.com/examples
- OpenAI API CookBook : https://github.com/openai/openai-cookbook
