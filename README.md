# 2023년 데이콘 NH 투자증권 경진대회 <br> 재무제표 분석을 통한 투자 성향 맞춤형 글로벌 투자 가이드

<div align="center">

![image](https://github.com/jayjinnie/Customized-Investment-Guideline/assets/65335952/3cb9d5ac-6e67-45cb-9d8f-ea7af06db209)
</div>

## 공모전 개요
* **공모 주제:** 데이터 속에 숨어있는 해외주식 투자기회 찾기
* **세부 주제:** 해외 주식 데이터를 이용한 국내/해외 종목 관계 분

<br>

## 프로젝트 개요
* **작업 기간**<br>
  2023.09.12 ~ 2023.11.24
* **참여 인원** <br>
  3명 (데이터 수집 및 DDPG 강화학습 모델 개발, 시계열 클러스터링 및 발표자료 제작, Streamlit 웹 페이지 개발 )
* **분석 데이터** <br>
  * 국내외 종목 26개 재무제표(QuantiWise)
  * 블룸버그 공급망(보안 문제로 비공개)
  * NH 종목별 개인 투자자 구성 보유 종목(보안 문제로 비공개)
* **분석 목적** <br>
  * 해외 주식 투자에 막막함을 느끼는 개인 투자자를 위해 투자자의 투자 성향에 알맞는 종목을 추천하는 가이드를 제시한다.
* **주요 업무 및 상세 역할** <br>
  과거 10년 간 국내외 주식 종목의 재무제표 트렌드를 기반으로 시계열 클러스터링을 수행하여 유사한 종목을 묶는다. 이를 NH 투자증권 고객에게 적용해 적절한 투자 가이드를 제공한다. 
* **분석 환경** <br>
  Python, Streamlit

<br>

## 프로젝트 내용
* **예선**<br>
  지난 10년 간의 26개 재무제표 변동사항을 기반으로 주식 종목에 대한 시계열 클러스터링을 수행한다. <br>
  유사한 특성을 통해 묶인 종목 군집을 해석하여 국내외 종목 간의 관계를 도출한다. <br>
  군집별 종목의 특성을 고려하여 적절한 투자자 성향을 매칭하고, <br>
  DDPG 강화학습 모델을 기반으로 최적의 수익률을 확보할 수 있는 투자 포트폴리오를 제시한다.<br>
  <a href="https://dacon.io/competitions/official/236145/codeshare/9005?page=1&dtype=random">DACON 예선 제출물</a>
* **본선**<br>
  예선 데이터에 더해 블룸버그 공급망 데이터와 NH 개인 투자자 구성 보유 종목 데이터를 추가로 활용하였다. <br>
  블룸버그 공급망 데이터를 활용해 공급망 네트워크에서 각 종목의 중심성을 계산하고, <br>
  이를 시계열 클러스터링 시 각 종목에 부여하는 가중치로서 사용한다. <br>
  이후 클러스터링 결과를 NH 투자증권 고객 데이터에 적용하여 NH 고객들의 투자 성향 유형을 분석한다. <br>
  고객의 투자 성향 유형별로 투자 포트폴리오를 도출하고, 강화학습 모델을 학습시켜 예상 수익률을 도출한다.<br>
  <a href="https://drive.google.com/file/d/1PgsIEMTzLm3sZWR7qfyuQvCOdDog7301/view?usp=sharing"> 본선 코드 녹화본(보안 문제로 파일 비공개)</a>

<div align="center">

![데이콘](https://github.com/jayjinnie/Customized-Investment-Guideline/assets/65335952/27b0d831-a7bd-4f8c-b5af-b6ba9c776812)
</div>

<br>

## 프로젝트 성과
**NH 투자 증권 및 데이콘 주관상 , 입선상 수상🎉**
![입선상스캔본](https://github.com/jayjinnie/Customized-Investment-Guideline/assets/65335952/3542386b-f96f-440a-9e18-3d9f8039ed4e)
