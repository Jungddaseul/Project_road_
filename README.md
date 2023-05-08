# Project_road_

### 📌 주    제 : 도로 균열 자동감지 시스템
#### 📆 기    간 : 2022.08.08.~2023.08.26.
### 개발목표
- 도로에 발생한 균열을 자동으로 감지하여 관리 주체와 연계하여 조속한 조치를 취할 수 있는 시스템 구축
### 담당역할
- 도로 이미지 전처리 및 웹 페이지 구현
### 개발 내용
- labelIMG tool을 이용하여 이미지 바운딩 박스처리
- YOLOv5를 활용하여 객체 분류 이미지 학습 모델링
- HTML, CSS를 활용한 웹 페이지 구현
- Tkinter모듈을 이용하여 실시간 도로 크랙 검출 화면 개발

### 📌 빅데이터분석정의서
#### 1. 데이터 준비
 1-1)데이터 정의 : 도로균열 이미지(크랙, 포트홀)
 1-2) 데이터 획득 방법
- Espírito Santo, Rio Grande do Sul 및 연방 지구의 고속도로(브라질) 약 4,000장 이미지
  https://biankatpas.github.io/Cracks-and-Potholes-in-Road-Images-Dataset/
- AI-hub-(도로장애물/표면 인지 영상(수도권 외) 약 10,000장 이미지
  https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&
  aihubDataSe=realm&dataSetSn=178
