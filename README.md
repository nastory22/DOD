<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=b41dbf&height=180&text=D오디&animation=fadeIn&fontColor=ffffff&fontSize=70" />
    </div>

    

---------------------------------------

## 자율주행을 통한 실시간 포트홀 신고 서비스

---------------------------------------

# 프로젝트 계획서

## 1. 프로젝트 개요
- **프로젝트명**: 자율주행을통한 포트홀 신고 서비스
- **목표**:
- 1.자율주행 차량을 위한 실시간 객체 탐지, 포트홀 감지 및 자동 신고 서비스 구축
- 2.YOLOv11을 통해 높은 탐지 정확도와 빠른 응답 속도 구현
- 3.ESP32-CAM을 통해 실시간 포트홀사진을 수집하고 AWS클라우드에 자동화 처리
- **기간**: 2024년 6월 - 2025년 1월
---------------------------------------
## 2. 프로젝트 일정
- **1차 프로젝트** (기획): 2024년 8월 19일 - 8월 21일
- **2차 프로젝트** (프로토타입): 2024년 10월 22일 - 10월 28일
- **3차 프로젝트** (최종): 2024년 11월 07일 - 1월 04일
---------------------------------------
## 3. 팀 구성
<table style="width:100%; text-align:center; table-layout:fixed;">
  <colgroup>
    <!-- 전체 6열이므로 20%씩 -->
    <col style="width:20%;">
    <col style="width:20%;">
    <col style="width:20%;">
    <col style="width:20%;">
    <col style="width:20%;">
    <col style="width:20%;">
  </colgroup>
  <thead>
    <tr>
      <th>김승엽</th>
      <th>한은선</th>
      <th>김동혁</th>
      <th>김준희</th>
      <th>박장원</th>
      <th>김나현</th>
    </tr>
  </thead>
  <tbody>
<!--     <tr>
      <td>img</td>
      <td>img</td>
      <td>img</td>
      <td>img</td>
      <td>img</td>
      <td>img</td>
    </tr> -->
    <tr>
      <td>PM, 데이터분석가, AI엔지니어</td>
      <td>데이터분석가, 클라우드인프라, 클라우드엔지니어</td>
      <td>데이터분석가, 모델엔지니어링, 시스템인프라</td>
      <td>클라우드인프라, 클라우드엔지니어, 풀스택</td>
      <td>클라우드인프라, 클라우드엔지니어, 로봇엔지니어</td>
      <td>클라우드인프라, 클라우드엔지니어, 로봇엔지니어</td>      
    </tr>
    <tr>
      <td><a href="https://github.com/yeop6033" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a>
</td>
      <td><a href="https://github.com/Hansilverline" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a></td>
      <td><a href="https://github.com/dohy-98" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a></td>
      <td><a href="https://github.com/MINLUV" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a></td>
      <td><a href="https://github.com/jang7987" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a></td>
       <td><a href="https://github.com/nastory22" target="_blank">
          <img src="https://img.shields.io/badge/GitHub-Link-black?style=flat&logo=github&logoColor=white" />
        </a></td>
    </tr>
  </tbody>
</table>
<br>
----------------------------------------
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">  </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;">  </div> 
    </div>
    <div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2> <br> 
    <div style="margin: ; text-align: left;" "text-align: left;"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=plastic&logo=Amazon S3&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=plastic&logo=Git&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=plastic&logo=Github&logoColor=white">
          <img src="https://img.shields.io/badge/C-A8B9CC?style=plastic&logo=C&logoColor=white">
          <img src="https://img.shields.io/badge/C++-00599C?style=plastic&logo=C%2B%2B&logoColor=white">
          <br/><img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=plastic&logo=Amazon AWS&logoColor=white">
          <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white">
          <img src="https://img.shields.io/badge/Notion-000000?style=plastic&logo=Notion&logoColor=white">
        <img src="https://img.shields.io/badge/AduinoIDE-61DAFB?style=flat&logo=React&logoColor=white">
       <img src="https://img.shields.io/badge/YOLO-A8B9CC?style=plastic&logo=YOLO&logoColor=white">
        

        
        
        
----------------------------------------
# 요구사항 정의서

## 1. 기능적 요구사항
**객체 탐지[YOLO]**: 
  - 도로 노선 탐지: 차량이 주행 가능한 경로를 인식
  - 객체 탐지 (좌/우회전, 정지): 표지판 정보를 기반으로 차량 제어
  - 포트홀 탐지: 포트홀 위치를 감지하고 차량 속도 조절 및 클라우드 데이터베이스에 업로드
  - 이미지 데이터 생성: 객체 인식 시 train 이미지데이터를 생성

**제어 [아두이노]**:
  - 좌회전, 우회전, 정지, 감속 및 직선 주행 제어
  - 도로 구간 식별 및 포트홀 좌표 데이터 업데이트

**신고 서비스[클라우드]**:
 - 수집된 데이터의 실시간 전송 및 클라우드 데이터베이스(dynamo) 저장
  - 웹 서버로의 데이터 전송 및 웹페이지 게시


## 2. 비기능적 요구사항
- **응답 시간**: 
  - 시스템은 2초 이내에 요청에 응답해야 한다.
- **성능**:
  - YOLO 모델의 객체 탐지 정확도를 90% 이상 유지
- **확장성**:
  - 데이터 증가에 따른 클라우드 확장성
  - 다양한 도로 상황과 추가 객체 탐지에 대한 모델 업데이트 기능.
- **보안**:
  - 클라우드 데이터는 IAM역할 관리로 인증된 사용자만 접근 가능.
- **가용성**
  - 시스템 가용성 99.9%이상 유지
  - 장애 발생 시 5분 이내 복구 가능
- **유지보수**:
  - 코드 모듈화 및 주석 처리로 유지보수 대비
  - 클라우드 및 모델 업데이트
----------------------------------------

# WBS

## 1. 프로젝트 분석
- 요구사항 수집 및 분석
- 아키텍처 설계

## 2. 시스템 개발
- 백엔드 및 프론트엔드 개발
- 데이터베이스 설계 및 구축
- YOLO모델 통합 및 최적화
- ESPCAM,ESP,LOCAL 파이프라인 구축

## 3. 테스트 및 배포
- 단위 테스트 및 통합 테스트
- 성능 테스트

-----------------------------------------

# 모델 정의서

[모델 정의서 보기](./[모델 정의서 .pdf](https://github.com/user-attachments/files/18484383/default.pdf))


![YOLOv11](https://img.shields.io/badge/YOLOv11-0.99%20mAP-blue)
![Python](https://img.shields.io/badge/Python-3.9-blue)


- **선택 모델**: YOLOv11
- **선정 이유**:
  - 높은 정확도(mAP 39.5)와 빠른 응답 시간(56.1ms)
  - 최신 기술 반영으로 효율성과 성능 개선

- **데이터셋 구성**:
  - 학습 대상: 포트홀, 표지판(좌/우회전, 정지), 차선
  - 데이터 출처: GitHub, AIHub, Kaggle
  - 초기 데이터: 학습 160장, 검증 20장, 테스트 20장
- **데이터 전처리**:
  - 크기 조정: 640x640 픽셀
  - 바운딩 박스 최소 크기: 10x10 픽셀
- **데이터 라벨링**:
  - 라벨링 비율: 학습 80%, 검증 10%, 테스트 10%
  - mAP 70% 미만 시 데이터 증강 적용
 
4. 모델 구조 및 기술 사양

- **선택 모델**: YOLOv11
- **선정 이유**:
  - 높은 정확도(mAP 39.5)와 빠른 응답 시간(56.1ms)
  - 최신 기술 반영으로 효율성과 성능 개선

5. 모델 학습 및 검증

- **학습 과정**:
  - Epoch 수: 100
  - 프레임워크: PyTorch, Tensorboard 사용
- **평가 지표**:
  - mAP: 0.99
  - Precision, Recall

6. 사용 기술 및 라이브러리

- **기술**: YOLOv11, PyTorch, CUDA
- **라이브러리**: NumPy, OpenCV, Tensorboard

7. 향후 계획 및 개선안

- 추가 데이터 확보 및 학습 강화
- 모델 경량화
- 배포 및 통합 테스트 진행


----------------------------------------

# 성능 평가 결과서

## 1. 테스트 환경
- **서버**: AWS EC2 c5.large 인스턴스
- **DB**: MySQL 8.0
- **네트워크**: 1Gbps

## 2. 테스트 결과
- **응답 시간**: 1초 이내
- **동시 사용자 처리**: 5,000명
- **CPU 사용률**: 70%
- **메모리 사용률**: 60%

## 3. 성능 개선 필요 사항
- 데이터 처리 성능 향상을 위한 캐시 적용
- 서버 성능 개선을 위한 리소스 스케일링 필요

-----------------------------------------

# 최종 보고서

## 1. 프로젝트 개요
- **목표**: 클라우드 기반 빅데이터 분석 시스템 구축
- **기간**: 2025년 1월 - 2025년 12월

## 2. 주요 성과
- 시스템 구축 완료 및 안정적인 운영
- 10,000명 이상의 사용자가 동시 접속 가능한 클라우드 서비스 제공

## 3. 향후 개선 사항
- 사용자 인터페이스 개선
- 성능 최적화 및 리소스 효율성 향상

-----------------------------------------

# 회고

## 1. 잘된 점
- **협업**: 팀원 간의 협업이 원활하게 이루어졌으며, 주기적인 피드백 세션이 유효했다.
- **일정 관리**: 프로젝트 일정에 맞춰 개발이 진행되었고, 큰 지연 없이 배포를 완료했다.

## 2. 개선할 점
- **초기 요구사항 정의 부족**: 초기 요구사항이 부족하여 개발 도중 변경 사항이 많았다.
- **테스트 시간 부족**: 프로젝트 후반부에 테스트 시간이 부족했으며, 더 많은 시간을 할애해야 했다.

## 3. 교훈
- **명확한 요구사항 정의**: 초기 단계에서 요구사항을 명확히 정리하는 것이 중요하다.
- **적절한 테스트 계획 수립**: 충분한 테스트와 성능 점검을 통해 출시 전에 문제를 해결할 수 있어야 한다.
