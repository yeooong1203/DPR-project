# 데이터패턴인식 텀프로젝트 [2024 DPR Proj]
## 프로젝트 주제
유튜브 악성 댓글 탐지 프로그램 - 자연어 처리 딥러닝 모델

## 🔎 프로젝트 개요
인터넷의 '익명성'이 악의적으로 활용되어 타인을 비난하거나 비방하는 '악성 댓글(악플)'은 오랜 기간 사회적 문제로 지적되어 왔습니다.
최근 SNS와 유튜브와 같은 플랫폼이 주요 소통 창구로 자리 잡으면서, 이러한 악성 댓글의 확산은 더욱 심각한 사회적 이슈로 대두되고 있습니다. 

이 프로젝트는 Google의 YouTube Data API를 활용해 직접 수집한 댓글 데이터를 기반으로, 한국어 악성 댓글을 탐지하는 자연어 처리 모델을 구현한 것입니다. 
유튜브는 특정 연령층이나 성별에 치우치지 않고 전 세계적으로 사용되는 대표적 플랫폼으로, 악성 댓글 탐지 시스템의 적용 가치가 높다고 판단했습니다. 

현재는 한국어 댓글을 대상으로 모델을 학습하고 평가하였으며, 향후 다국어 확장을 통해 글로벌 수준에서 건전한 온라인 소통 문화 조성에 기여할 수 있는 시스템으로 발전시키는 것을 목표로 합니다. 

## 🧠 사용 기술
- 언어: Python
- 데이터 수집: YouTube Data API (댓글 및 작성자 정보 크롤링)
- 데이터 처리 및 시각화: numpy, pandas, matplotlib, scikit-learn
- 자연어 처리(NLP): KoNLPy (Okt), nlpaug (WordNet 기반 데이터 증강)
- 모델링 및 학습: tensorflow, keras
- 하이퍼파라미터 튜닝: Optuna
- 개발 환경: Google Colab

## 📎 Colab 원본   
colab 노트북: https://colab.research.google.com/drive/1KqjJbqxW5dLULYOZWLcs1dxQBMk52ALv?usp=sharing


## 🙋‍♂️ 기여자
- 김나영 (nayoung.kim.it@gmail.com / yeooong1203)

