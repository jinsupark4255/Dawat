![dawat_logo](https://github.com/jinsupark4255/Dawat/assets/116702892/d4536fcb-a697-450f-86c0-2db299221679) 
# DAWAT
해당 프로젝트는 이미지를 input으로 받아와서 자동으로 segment를 진행하고 결과 마스크를 원본 이미지에 오버레이하는 웹사이트 입니다.<br/> 
사용자는 annotation 툴을 사용해 마스크 데이터를 추가, 수정, 삭제할 수 있습니다.

# 실행방법
- SAM 모델을 돌리려면 백엔드 서버를 열어둬야 하므로 프로젝트 확인을 원하시면 jin04007@naver.com으로 연락 부탁드립니다.

  ## 설치방법
    1. 깃의 main 브랜치에서 pull을 받는다.
    2. vscode의 터미널을 연다.
    3. 'cd segment-any-document' 입력 -> 'cd frontend' 입력 -> 'npm install' 입력 -> 'npm start' 실행.
    4. 온보딩 페이지가 확인된다면 성공적으로 실행 완료.
       
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/fe244eb0-50ef-4fea-9309-1dc45fff4900)

## 사이트 설명

### 온보딩 페이지 (HOME)
  - 온보딩 페이지에서는 Dawat 웹사이트의 전반적인 설명을 동영상 형식으로 보여주고 있습니다.
  - Dawat 웹사이트에 사용된 모델인 META의 SAM(Segment-Anything-Model)의 작동 방식을 확인하실 수 있습니다.

![image](https://github.com/jinsupark4255/Dawat/assets/116702892/292e1d3e-39ed-48dd-8538-1d1268a6abbf)
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/be29d332-5f01-474d-87a8-9feea7473110)

### Tool 페이지 (Thumbnails)
  - Tool 페이지의 Thumbnails는 사용자가 업로드 한 이미지를 확인할 수 있는 페이지 입니다.
  - 한 장 이상의 이미지 파일 (PDF)도 Input 하실 수 있습니다.
    
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/3dcf68c6-abcd-4da0-b973-721c589a4c22)

### Tool 페이지 (Annotation)
  - Tool 페이지의 Annotation은 업로드 한 이미지를 본격적으로 SAM 모델을 통해 분할을 진행하실 수 있는 페이지입니다.
  - Annotation Tool 설명
    1. 첫번째 Tool은 Drag & Drop 커서 입니다. 사용자는 해당 커서를 이용하여 캔버스 내 이미지의 위치를 변경할 수 있습니다.
    2. 두번째 Tool은 기본 커서 입니다. 사용자는 해당 커서를 이용하여 마스크 데이터를 클릭할 수 있습니다.
    3. 세번째 Tool은 Annotation 버튼입니다. 사용자는 해당 버튼을 클릭하여 SAM 모델을 돌릴 수 있습니다.
    4. 네번째 Tool은 bbox 버튼입니다. 사용자는 해당 버튼을 클릭하여 마스크 데이터를 CRUD  수 있습니다.


* 처음 이미지를 import 했을 때 화면
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/47ba204e-f3ce-4b1f-a536-6585f9198ae9)

* 세번째 Tool인 Annotation 버튼을 클릭했을 때 화면
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/dab133a0-43ca-464a-8770-5f3e87beba79)

* Annotation 정보를 클릭했을 떄 화면
![image](https://github.com/jinsupark4255/Dawat/assets/116702892/3a7d8024-3e09-47e7-b41e-2b68f4036a04)


### How to Use 페이지
- 해당 페이지는 사용자의 UI/UX 경험을 최대화시키고자 추가한 페이지 입니다.
- 사용자는 DAWAT 웹사이트를 사용하는 방법을 동영상을 통해 쉽고 빠르게 학습할 수 있습니다.
- 동영상은 Tool 페이지와 동일하게 설계된 UI의 각 버튼에 마우스를 올려놓으 자동으로 재생됩니다.


![image](https://github.com/jinsupark4255/Dawat/assets/116702892/fc7611e1-8286-4f83-b866-3992297c97e4)
