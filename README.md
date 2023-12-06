# 프로젝트 소개
yolo를 활용한 맹견, 입마개 detection을 통해 개 물림 사고 예방을 위한 맹견 입마개 탐지 사회 서비스를 데이터청년캠퍼스에서 프로젝트 진행 

# 프로젝트 목적
개물림 사고의 증가와 단속의 어려움을 AI 기술을 통해 해결하는 방법론을 제시하고, 이 인공지능 모델을 실제 영상 데이터를 기반으로 구현하였다. 맹견과 입마개 이미지 학습을 통해 입마개 미착용 맹견을 사전에 탐지하고 안내해줄 수 있는 모델을 개발해 현재의 법안과 제도 하에서 개물림 사고를 효과적으로 예방할 수 있는 방법을 제시

# 상세 내용 
1. 영상기반으로 반려견을 탐지하며, 반려견이 맹견에 속하는지 아닌지를 판별한다. 맹견에 속한다면, 최종적으로 입마개의 착용여부를 판별하여 입마개를 착용하지 않았을 시 다양한 조치를 취한다.
2. 기존 도시에 설치된 CCTV를 활용할 수 있으며, 반려견의 이동이 많은 특수한 지역(산책로, 공원 입구 등)에는 입구에 직접 CCTV를 설치하여 실시간 관제가 이루어지게 한다. 
3. 위치기반시스템을 활용해 인근 지역 시민들에게 입마개 미착용 맹견이 있음을 스마트폰이나 안내방송을 통해 정보를 제공하여 사전 행동을 취할 수 있도록 한다.

# 활용 방법
1. 각자 저장소를 복제
```
$ git clone https://github.com/jang-jaehyuk/yoloproject.git
```
2. 각자의 환경에서 작업
3. 작업물 push

push를 진행하기 전에 다른 팀원이 변경해놓은 내용이 있을 수 있으므로
```
$ git pull
```
을 사용하여 최종상태로 업데이트 한 후에 나의 변경 내용을 push하여 충돌을 방지하는 것에 주의

아래사진에는 fetch후 merge형식으로 나와있지만 branch개념을 이해한 후에 천천히 시도하는 것이 좋을듯하다.
### 사진으로 된 예시
<img src="https://github.com/jang-jaehyuk/yoloproject/blob/6ac4d9f672ad5ee5df2a4b751bf8a030ff13d4d1/git.PNG" width="800" height="500"/>
