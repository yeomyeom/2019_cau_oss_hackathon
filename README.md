## 2019_cau_oss_hackathon

### 프로젝트 진행 전 준비

* 본 GitHub repository를 개인 GitHub 계정으로 fork
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/fork_window.png" width="80%"><br>
    - 위 사진 같이 우측 상단에 있는 fork 버튼 클릭 후 개인 계정 선택<br>
    (2인 1팀인 경우, 두 사람 다 fork한 후, 프로젝트 후 제출 할 repo를 하나 선택해주세요)<br>
    fork로 생성된 Git repo는 추후 전체 팀 파일 관리, 수상자 코드 공개 등에 사용 될 예정입니다.
    
* Fork한 repository의 노트를 colab로 열기<br>
    https://colab.research.google.com/github/{%username}/2019_cau_oss_hackathon/blob/master/hackathon_template.ipynb <br>
    위 url에서 {%username}을 본인 계정 이름으로 변경 후 접속<br>
    ex) 
    https://colab.research.google.com/github/weenybeenymini/2019_cau_oss_hackathon/blob/master/hackathon_template.ipynb 

* 구글 드라이브에 노트 저장하고 조교와 공유 **(중요)** <br>
    - 파일 - 드라이브에 사본 저장 클릭<br>
        (사본을 저장해야 편집하고 공유가 가능합니다. 생성한 사본에서 작업해주세요.)
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/copy_save.png"><br>
    <br>
    
    - 열린 사본 노트 이름을 더블클릭하고 **hackathon_teamXX** 형식으로 이름 변경<br>
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/rename.png"><br>
    <br>
    
    - 우측 상단에 있는 공유 버튼 클릭 -> 조교 메일 주소 : cau.oss.hackathon.ta@gmail.com 입력하고 완료<br>
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/share.png">
    <br>
     
**위의 일련의 과정들을 모든 팀이 진행하여야 해커톤 개발을 시작합니다** <br>
**(2인 1팀인 경우, 각각 컴퓨터로 작업을 하기 위해 두 사람 모두 위의 과정을 진행해주셔야 합니다)**

<img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/history.png" width="80%">
부정행위를 방지하기 위해 조교가 모든 팀의 colab 노트에 접근, 히스토리를 확인 가능한 상태로서, 부정행위 적발시 해당 팀은 수상자 제외 및 실격 처리

---

### 프로젝트 진행 후 (결과물 제출, 프로젝트 진행 도중에도 가능)

* 소스코드 (.ipynb) 제출<br>
    "파일 -> GitHub에 사본 저장"을 클릭하면 아래와 같은 창을 확인할 수 있으며, 원하는 커밋 메세지 입력 후 확인
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/push_git.png" width="80%">
    
* 소스코드 외 모델 구조, weight, 컴파일된 모델 파일 (.json, .h5) 제출<br>
    - 주어진 템플릿으로 올바르게 실행을 하면<br>
    모델 구조(model_structure_teamXX.json)<br>
    가중치(model_weight_teamXX.h5)<br>
    컴파일된 모델(model_entire_teamXX.h5) 파일이 /content에 생성됩니다.<br>
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/file.png">  <br>
    이 세 파일을 더블클릭 또는 우클릭 - 다운로드 방법으로 다운로드<br>
    (사진엔 파일이 두 개지만 총 3개의 파일을 올리셔야 하고, 사진과 파일 이름이 다를 수 있음)<br>
    (템플릿에도 설명이 되어있지만 **..._teamXX...** 형식으로 변경하는 것을 잊지마세요.)
    
    - 그 후 fork한 repository에서 우측 Upload files를 클릭 후 다운 받은 파일들을 드래그해 GitHub에 commit<br>
    <img src="https://raw.githubusercontent.com/cauosshackathonta/2019_cau_oss_hackathon/master/image/upload.png"> <br>
        
---
        
**최종 제출물 : 소스코드 (hackathon_teamXX.ipynb), 모델 구조 (model_structure_teamXX.json), 모델 weight(model_weight_teamXX.h5), 컴파일된 모델 (model_entire_teamXX.h5)**

**(중요) 최종 제출물이 가장 최신 버전인지, GitHub에 잘 올라가졌는지 다시 한번 확인 부탁드립니다.**
