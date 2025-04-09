
<h1 align="center"> Deep Learning Efficient Inference</h1>

<div align="center">
<a href="https://pseudo-lab.com"><img src="https://img.shields.io/badge/PseudoLab-S10-3776AB" alt="PseudoLab"/></a>
<a href="https://discord.gg/EPurkHVtp2"><img src="https://img.shields.io/badge/Discord-BF40BF" alt="Discord Community"/></a>
<a href="https://github.com/Pseudo-Lab/EfficientML/stargazers"><img src="https://img.shields.io/github/stars/Pseudo-Lab/EfficientML" alt="Stars Badge"/></a>
<a href="https://github.com/Pseudo-Lab/EfficientML/network/members"><img src="https://img.shields.io/github/forks/Pseudo-Lab/EfficientML" alt="Forks Badge"/></a>
<a href="https://github.com/Pseudo-Lab/EfficientML/pulls"><img src="https://img.shields.io/github/issues-pr/Pseudo-Lab/EfficientML" alt="Pull Requests Badge"/></a>
<a href="https://github.com/Pseudo-Lab/EfficientML/issues"><img src="https://img.shields.io/github/issues/Pseudo-Lab/EfficientML" alt="Issues Badge"/></a>
<a href="https://github.com/Pseudo-Lab/EfficientML/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Pseudo-Lab/EfficientML?color=2b9348"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fpseudo-lab%2FEfficientML&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
</div>
<br>

<!-- sheilds: https://shields.io/ -->
<!-- hits badge: https://hits.seeyoufarm.com/ -->


최근 AI 기술이 빠르게 발전하며 딥러닝 모델의 규모와 성능이 폭발적으로 증가하고 있습니다. 그러나 모델이 커질수록 **메모리 사용량**, **추론 시간**, **에너지 소모**가 급격히 증가하기 때문에, 효율적인 **경량화 기법**과 **추론 최적화**에 대한 수요도 높아지고 있습니다.  
가지치기(Pruning), 양자화(Quantization), 지식 증류(Knowledge Distillation), 네트워크 구조 검색(NAS) 등을 통해 모델을 가볍게 만들고, 하드웨어 제약이 있는 환경에서도 충분한 성능을 낼 수 있게 하는 기술은 앞으로 더욱 중요해질 것입니다.


## 이번 시즌에 배울 지식 Introduction
- **Pruning**: 모델 파라미터를 부분적으로 제거해 모델 크기를 줄이면서 성능은 최대한 유지하는 기법  
- **Quantization**: 파라미터를 낮은 정밀도로 표현해 계산량과 메모리 사용량을 절감하는 기법  
- **Knowledge Distillation**: 큰 모델의 지식을 작은 모델에 전이하여 경량화하면서도 높은 성능을 유지하는 기법  
- **Neural Architecture Search**: 다양한 아키텍처를 자동으로 탐색해 최적의 모델 구조를 찾는 기법

본 스터디에서는 이론적 지식뿐만 아니라, **실제 모델을 경량화하고 추론 효율을 개선**하는 일련의 실습 프로젝트를 통해 실전 감각을 키우려고 합니다.


## 왜 이걸 배워야 하는가?
- 기업들의 효율적인 모델 서빙을 통해 클라우드 비용 절감과 엣지 디바이스 적용 필요성 증가
- 대용량 데이터를 다루는 스타트업부터 대기업까지, AI 응용 분야 전반에서 모델 최적화 역량 요구 증가
- LLM(대형 언어 모델), 컴퓨터 비전, 음성 인식 등 적용 범위가 넓고 활용 가치가 높음


## 배우면 어떤 이득이 있는가?
- **AI 연구원**, **ML 엔지니어**, **Mobile/Edge device Developer**, **MLOps** 등 다양한 직무에 적용할 수 있는 스킬셋을 갖출 수 있습니다.  
- **인프라 비용** 최적화, on-device AI, IoT 솔루션 개발 등과 연계되어 국내외 주요 기업에 진출 가능성을 높일 수 있습니다.  
- 직접 경량화 프로젝트를 수행하면서, 현업에 필요한 실무 역량을 쌓을 수 있습니다.


## 🌟 프로젝트 개요
1. **이론 학습**: Pruning, Quantization, Knowledge Distillation, Network Architecture Search 등의 핵심 개념과 기법 학습  
- [MIT 6.5940 TinyML and Efficient Deep Learning Computing](https://hanlab.mit.edu/courses/2024-fall-65940) 강의를 기반으로 함
2. **실전 프로젝트 수행**: 실제 모델을 경량화하고 추론 최적화를 적용화해 경량화 전후 성능을 비교하는 프로젝트 수행 예정  
- 개인 또는 팀 단위로 프로젝트 제안 및 진행


## 🧑 팀 소개

| 역할          | 이름 | LinkedIn |
|---------------|------|-----------------------------------------------------------------------|
| **Project Manager** | 박성수 | [Link](https://www.linkedin.com/in/seongsu-park/)           |
| **Member** | 김슬 | |
| **Member** | 박동찬 | |
| **Member** | 오새빛나 |  |
| **Member** | 윤남규 | |
| **Member** | 이정수 | |




## 💻 주차별 계획

| 날짜 | 내용 | Link | 
| -------- | -------- | ---- |
| 2025/3/4 | OT       |      |
| 2025/3/11 |  Basics of Deep Learning <br> Transformers | [[Part 1]](https://github.com/Pseudo-Lab/EfficientML/discussions/3) <br> [[Part 2]](https://github.com/Pseudo-Lab/EfficientML/discussions/5) | 
| 2025/3/18 |  Pruning and Sparsity (Part I) <br> Transformer Design Variants | [[Part 1]](https://github.com/Pseudo-Lab/EfficientML/discussions/6) <br> [[Part 2]](https://github.com/Pseudo-Lab/EfficientML/discussions/7) | 
| 2025/3/25 |  ⭐ Magical Week 휴일 ⭐ | | 
| 2025/4/1 |  Pruning and Sparsity (Part II) <br> Large language models <br> LLM Fine-Tuning | [[Part 1]](https://github.com/Pseudo-Lab/EfficientML/discussions/8)  <br> [[Part 2]](https://github.com/Pseudo-Lab/EfficientML/discussions/9)| 
| 2025/4/8 |  Quantization (Part I) | [[Link]](https://github.com/Pseudo-Lab/EfficientML/discussions/12) | 
| 2025/4/15 |  Quantization (Part II) | [[Link]](https://github.com/Pseudo-Lab/EfficientML/discussions/13) | 
| 2025/4/22 |  Neural Architecture Search (Part I) | 미정 | 
| 2025/4/29 |  ⭐ Magical Week 휴일 ⭐ | 미정 | 
| 2025/5/6 |  Neural Architecture Search (Part II) | 미정 | 
| 2025/5/13 |  Knowledge Distillation | 미정 | 
| 2025/5/20 |  MCUNet: TinyML on Microcontrollers | 미정 | 
| 2025/5/27 |  TinyEngine and Parallel Processing | 미정 | 

> **매주 일정**:  
> - 스터디 전, 할당된 강의를 사전에 학습 (영어 자막 강의 + PPT 등)  
> - 스터디 시간에 강의 내용 토의 및 질의응답  
> - 개인 혹은 팀별 프로젝트 진행 상황 공유 및 피드백


## 💡 프로젝트
| 제목 | 담당자 | Link |
|---|---|---|
| Face-based age classification | 박성수 | [[Link]](https://github.com/Pseudo-Lab/EfficientML/discussions/11) |
|  | 김슬 |  |
|  | 박동찬 | |
| LLM Minimalism | 오새빛나 | [[Link]](https://github.com/Pseudo-Lab/EfficientML/discussions/16) |
|  | 윤남규 | |
|  | 이정수 | [[Link]](https://github.com/Pseudo-Lab/EfficientML/discussions/17)|

<!-- ## 💡 학습 자원 (Learning Resources)
**우리가 만든 지식 허브**  
- [AI Playbook](https://github.com/your-org/ai-playbook): 150+ 페이지의 실전 가이드
- [MLOps Pipeline Template](https://github.com/your-org/mlops-template): 재사용 가능한 인프라 코드
- [Failure Journal](https://your-org.github.io/failure-journal): 50+개의 실패 사례 분석 [31][34] -->


## 🌱 참여 안내

<!-- ### 지원 시 유의사항
- **3/2에 러너 발표 예정이므로, 해당 날짜에 이메일(스팸 게시판 포함)과 Discord를 꼭 확인해 카톡방에 입장해, 3/4의 첫 모임에 지장이 가지 않도록 해야 함** -->

- 매주 화요일 오후 9시, 가짜연구소 Discord Room-IS 채널
- 자유롭게 청강 가능합니다.
<!-- - 일부 주간은 오프라인(강남) 모임 예정, 화요일 저녁
- 첫 모임(3/4)은 오프라인 진행, 오후 7시 예정

 ### ✔️ 참여 조건
- **3개월** 동안 꾸준히 참여할 수 있는 **의지**  
- **주 4시간** 정도의 학습 및 실습 시간 확보해야 함
- 딥러닝 기본 이론 지식 (CNN, Transformer 등) 보유, **PyTorch 기초 사용** 가능  
- 영어 자막 강의를 수강하고, 영어 PPT를 이해할 수 있어야 함  

### 지원서 작성 시 추가로 작성하면 좋을 것
- 이번에 다룰 4개의 경량화 기술 중 가장 관심있는 기술

<!-- **누구나 청강을 통해 모임을 참여하실 수 있습니다.**  
1. 특별한 신청 없이 정기 모임 시간에 맞추어 디스코드 #Room-?? 채널로 입장
2. Magical Week 중 행사에 참가
3. Pseudo Lab 행사에서 만나기 -->

<!-- ## Acknowledgement 🙏

OOO is developed as part of Pseudo-Lab's Open Research Initiative. Special thanks to our contributors and the open source community for their valuable insights and contributions. -->

## About Pseudo Lab 👋🏼</h2>

[Pseudo-Lab](https://pseudo-lab.com/) is a non-profit organization focused on advancing machine learning and AI technologies. Our core values of Sharing, Motivation, and Collaborative Joy drive us to create impactful open-source projects. With over 5k+ researchers, we are committed to advancing machine learning and AI technologies.

<h2>Contributors 😃</h2>
<a href="https://github.com/Pseudo-Lab/EfficientML/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Pseudo-Lab/EfficientML" />
</a>
<br><br>

<!-- <h2>License 🗞</h2>

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). -->
