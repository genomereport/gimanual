### Genome report Tutorial

1. 회원가입
2. GRUploader 다운로드
3. 해독 파일 다운로드
4. 해독 파일 업로드
5. Sample 생성
6. Sample Feature 등록
7. 프로젝트(분석) 요청
8. 프로젝트 보고서 열람


### 1. 회원가입
1. Genome report  <a href="https://omics.genome-report.com/member" target="_blank"> 회원 가입</a> 사이트를 방문합니다.
1. 아래 항목을 입력하고 회원 가입 버튼을 클릭합니다.
    - 로그인아이디 : 이메일 입니다.
    - 이름  : 고객의 이름 (예: 길동)
    - 성   : 고객의 성 (예: 홍)
    - 생년월 : 년월(YYYY-MM)만 입력합니다.
    - 패스워드 : 영문자, 숫자, 특수문자중 두개 이상의 조합으로 8~20자리입니다.
    - 패스워드 확인 :
1. 회원가입 확인페이지의 안내문을 읽고 승인 버튼을 클릭합니다. 이때 회원 가입 승인 메일이 발송됩니다.
1. 회원 가입 승인 절차
    1. 등록된 메일 계정에 로그인해서 메일을 확인합니다.
    2. 본문에 있는 승인 URL을 클릭합니다.
    3. 회원 가입 승인 페이지가 보여집니다.


### 2. 해독 파일 다운로드

실습을 위해서 Genome report가 제공하는 예제 데이터를 받아야 합니다. 예제 데이터는 2개 샘플 4개 파일로 구성되어 있으며, 다음 과정을 통해서 파일을 받으실 수 있습니다.

1.  <a href="https://omics.genome-report.com/member" target="_blank">Genome report</a> 사이트 로그인 후, <a href="https://omics.genome-report.com/down_file/sample" target="_blank">SAMPLE FILE DOWNLOAD </a> 페이지를 방문합니다.
1. 아래 4개의 해독 파일을 다운로드 합니다.
    - Ctrl01_1.fq.gz
    - Ctrl01_2.fq.gz
    - Exp01_1.fq.gz
    - Exp01_2.fq.gz

 ````
 [TIP] 4개 파일 모두를 다운로드 하면 분석에 필요한 포인트를 자동으로 지급합니다. 포인트는 단 한번만 지급됩니다.
 ````
 ````
 [TIP] 다운로드 파일들은 SAMPLE 생성시 사용됩니다. 다운로드 폴더를 기억하십시요.
 ````

![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/tutorial_file_download.jpg)


### 3. 해독 파일 업로드 

Genome report를 이용한 NGS데이터 분석을 위해서 해야할 첫 번째 작업은 파일 업로드 입니다. Genome report는 파일 업로드를 위해서
**GRUploader를 이용한 파일 업로드**와 **웹을 이용한 파일 업로드**를 지원하고 있으며, 500M 이상의 대용량 파일은 GRUploader를 이용하셔야만
업로드 하실 수 있습니다. 이 예제에서는 GR Uploader를 이용해서 파일 업로드하는 것을 실습하겠습니다.

#### 3-1. GRUploader 다운로드

1. <a href="http://www.genome-report.com/down_file" target="_blank"> GRUploader 다운로드</a> 페이지로 방문합니다.
2. 각 운영체제에 해당하는 실행파일을 다운로드 받습니다. (윈도우는 왼쪽, OSX와 리눅스는 오른쪽을 선택하시면 됩니다.)
![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/screen_3.jpg)


#### 3-2. 해독 파일 업로드

1. 다운로드 받은 GRUploader를 실행합니다. 
2. 로그인 창이 나타나면, Genome report 가입 ID와 암호를 입력하고 로그인 합니다.
3. 해독 파일을 업로드합니다.
    1. 왼쪽상단에서 다운로드 받은 폴더로 이동합니다.
    2. 왼쪽하단에서 아래 4개의 파일을 선택하고 오른쪽으로 드래그앤드랍 합니다.
        - Ctrl01_1.fq.gz
        - Ctrl01_2.fq.gz
        - Exp01_1.fq.gz
        - Exp01_2.fq.gz
4. 오른쪽 테이블에서 업로드한 파일들의 "status"가 모두 'Completed'가 되면 업로드가 완료입니다.

   ````
   [TIP]"로그인 창"을 닫은 경우, GRUploader >> 로그인 메뉴를 클릭합니다.
   [TIP]업로드한 파일의 상태값이 'File Upload Fail'인 경우 해당 파일을 업로드 작업을 다시 하면 됩니다.
   [TIP]여러개의 파일을 한번에 선택해서 드래그앤 드랍도 가능합니다.
   ````

![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/gruploader_screen_1.jpg)


### 4. 샘플 생성

샘플 생성은 업로드한 파일을 이용하여 분석의 단위가 되는 샘플을 등록하는 과정입니다. 샘플 등록은 **파일을 직접 지정하는 방법**과 **마법사를 통한 파일 등록 방법**이 있습니다.
2개의 샘플을 각 각의 방법으로 등록해보겠습니다.


1. <a href="https://omics.genome-report.com/member" target="_blank">Genome report</a> 사이트 로그인 후, 왼쪽 매뉴에서 <a href="https://omics.genome-report.com/resource" target="_blank">RESOURCE</a>를 클릭합니다.
2. Resource 페이지에서 "Sample" 메뉴를 클릭합니다.
     ````
     [TIP]GRUploader 프로그램에서 등록한 해독 파일은  YYYY>> MM>>dd-로그인차수 (예:2016>>08>>24-01)에 있습니다.
     ````
3. 파일 지정 방법을 통한 Ctrl01 샘플 등록
    1. 2016>>09>>01-01 폴더에서 Ctrl01_1.fq.gz 파일을 선택(check) 합니다.
    1. 선택창 위쪽에 있는 **포워드 버튼**을 클릭합니다.
    1. 2016>>09>>01-01 폴더에서 Ctrl01_2.fq.gz 파일을 선택(check) 합니다.
    1. 선택 창 위쪽에 있는 **백워드 버튼**를 클릭합니다.
    1. SAMPLE 명을  "Ctrl01"로 입력합니다.
    1. "샘플 목록 추가" 버튼을 클릭합니다.
    1. 샘플 목록 맨 아래에 있는 승인 버튼을 클릭합니다.

    ````
     [TIP]샘플명은 파일명을 이용하여 프로그램에서 부여합니다. 예)Ctrl01로 합니다.
    ````
   ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_screen_1.jpg)


4. 마법사를 통한 Exp01 샘플 등록
     1. 2016>>09>>01-01 폴더에서 Exp01_1.fq.gz, Exp01_2.fq.gz 파일을 동시에 체크합니다.
     1. 선택창 위쪽에 있는 **마법사 버튼**를 클릭합니다..
     1. 샘플 목록에 새로운 샘플이 등록된 것을 확인한 후 샘플 목록 맨 아래에 있는 승인 버튼을 클릭합니다.

      ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_wizard.jpg)

      ````
     [TIP]Explorer 페이지에서 트리를 조회하면  user>>uncategorized>>년(YYYY)>>월(MM)>>일(DD)에 생성한 샘플을 확인할 수 있습니다. 년월일은 SAMPLE 생성일입니다.
     [TIP]마법사 이용시 "샘플명은 필수 입력입니다" 라는 메세지가 나오면 사용자가 직접 "샘플명"을 입력하면 됩니다.
      ````
5. 샘플 등록 확인
    1. 화면 왼쪽의 Resource 메뉴를 선택해서 탐색기(Explorer)화면으로 들어갑니다.
    1. 왼쪽 상자 안에서 **user>>uncategorized>>2016>>09>>01**  선택합니다. 
    1. 등록된 2개의 샘플이 나타나는 것을 확인합니다.


### 5. Sample Feature 등록

Genome report를 이용한 자료 분석전 정확한 분석을 위해서 샘플의 특성을 설정하는 단계입니다. 앞서 생성된 샘플을 이용하여
샘플의 특성을 설정해보겠습니다.


1.  왼쪽 트리에서  user>>uncategorized>>YYYY>> MM>>dd(예:2016>>08>>24)를 선택합니다.
![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen1.jpg)
2. 테이블에서 "Ctrl01" 첫번째 행의 작업 셀에서 "수정"버튼을 클릭합니다.
    1. 아래 화면의 팝업과 같이 설정하고 저장을 합니다.
    2. "Exp01"도 윗 작업을 반복합니다.
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen2.jpg)
3. "Ctrl01"과 "Exp01"에 sample Feature등록 완료 화면입니다.
   1. 테이블의  "샘플기능" 컬럼에 데이타가 있습니다.
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen3.jpg)



### 7. 프로젝트(분석) 요청
 1. 왼쪽 매뉴에서 <a href="https://omics.genome-report.com/analysis" target="_blank"> ANALYSIS</a>를 선택합니다. 사용 가능한 파이프라인 목록이 보여집니다.

 2. "유전자 발현량 및 발현량 차이 분석 (Tuxedo Protocol)" 파이프라인을 클릭합니다.
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/analysis_pipeline.jpg)
 3. 분석 요청서 작성
    1. 분석정보의 제목과 설명을 입력합니다.
      ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/pipeline_title.jpg)
    2. 샘플 항목에서 샘플 선택 버튼을 클릭합니다. 팝업창에서  "Ctrl01, Exp01" 샘플을 선택합니다.
    ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/pipeline_sample_choose.jpg)
    3. 선택된 샘플이 테이블 형식으로 보여집니다.
      ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/analysis_sample.jpg)
    4. 참조유전체는 "Horse(EquCab2/Ensembl 84)"를 선택합니다.
     ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/pipeline_reference.jpg)
    5. 기본선택사항과 고급선택사항은 수정을 하지 않습니다.
    6. 실험 디자인에서 Control 셀렉트 박스에서 "Ctrl01" SAMPLE을 선택합니다.
    7. 실험 디자인에서 Experimental 셀렉트 박스에서 "Exp01" SAMPLE을 하나 선택합니다.
    ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/pipeline_design.jpg)
    5. 승인 버튼을 클릭합니다.

    ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/analysis_full_screen.png)

 ````
 [TIP]분석 요청이 정상적으로 처리되면 프로젝트 페이지로 자동이동 합니다.
 [TIP]프로젝트가 완료되면 회원 가입시 등록된 메일주소로 프로젝트 진행 상황이 메일이 발송됩니다.
 ````

### 8. 프로젝트 보고서 열람
 1. 로그인 상태가 아니면 로그인을 합니다.
 2. <a href="https://omics.genome-report.com/project" target="_blank"> PROJECT </a>페이지로 이동합니다.
![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/project_screen.jpg)

 ````
   [TIP]프로젝트의 상태가 "오류"이면  Q&A에 문의를 해주세요.
   [TIP]문의시 ID와 제목을 꼭 기재해 주세요.
   [TIP]프로젝트 진행 상황 수신 메일에서도  오류 프로젝트가 있으면 Q&A에 문의를 해주세요.
 ````

 3. 테이블에서 "유전자 발현량 및 발현량 차이 분석" 제목의 프로젝트를 클릭합니다. 프로젝트 보고서 페이지로 이동합니다.
  ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/project_report_screen_1.jpg)
 4. 진행상황에서  "Report"버튼을 클릭하면  보고서가 pdf 형식으로 열립니다.
  ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/project_report_screen_3.jpg)
 5. 진행상황에서 "상세보기"버튼을 클릭하면 상세보기 페이지로 이동합니다.
  ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/project_report_screen_2.png)

