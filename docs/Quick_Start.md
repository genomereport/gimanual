### GenomeReport Tutorial

1. 회원가입
2. GRuploader 다운로드
3. sample file 다운로드
3. Sample 등록
4. Sampel 생성
5. 프로젝트(분석) 요청
6. 프로젝트 보고서 열람


### 회원가입
1.  Gerome Report 회원 가입[https://omics.genome-report.com/member](https://omics.genome-report.com/member) 사이트를 방문합니다.
1. 아래 항목을 입력하고 회원 가입 버튼을 클릭합니다.
    - 로그인아이디 : 이메일 입니다.
    - 이름  : 고객의 이름 (예: 길동)
    - 성   : 고객의 성 (예: 홍)
    - 생년월 : 년월(YYYY-MM)만 입력합니다.
    - 패스워드 : 영문자, 숫자, 특수문자중 두개 이상의 조합으로 8~20자리입니다.
    - 패스워드 확인 :
1. 회원가입 확인페이지의 안내문을 읽고 승인 버튼을 클릭합니다. 이때 회원 가입 승인 메일이 발송됩니다.
1. 회원 가입 승인
   1. 메일을 열니다.
   2. 메일 본문에서 승인 URL을 클릭합니다.
   3. 회원 가입 승인 페이지가 보여집니다.

### GRUploader 다운로드
1. 다운로드 [http://www.genome-report.com/down_file](http://www.genome-report.com/down_file) 사이트를 방문합니다.
2. 윈도우는 왼쪽 버튼을 클릭합니다. OSX와 리눅스 사용자는 오른쪽 버튼을 클릭합니다.
![화면](http://www.genome-report.com/assets/images/manual/screen_3.jpg)


### 해독 파일 다운로드

1. SAMPLE FILE DOWNLOAD[https://omics.genome-report.com/down_file/sample](https://omics.genome-report.com/down_file/sample) 페이지를 방문합니다.

    ````
    [Tip] 로그인이 되어 있지 않으면 로그인 페이지로 이동합니다.
    ````

3. 아래 4개의 해독 파일을 다운로드 합니다.
   1. Ctrl01_1.fq.gz
   2. Ctrl01_2.fq.gz
   3. Exp01_1.fq.gz
   4. Exp01_2.fq.gz

  ````
 [TIP]4개 파일 모두를 다운로드 하면 분석에 필요한 포인트를 자동으로 지급합니다. 포인트는 단 한번만 지급됩니다.
 [TIP] 다운로드 파일들은 SAMPLE 생성시 사용됩니다. 다운로드 폴더를 기억하십시요.
 ````

![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/tutorial_file_download.jpg)

### 해독 파일 업로드
1. 다운로드 받은 GRUploader를 실행합니다. 로그인 창이 나타납니다.
2. 로그인을 합니다.
3. 해독 파일을 업로드
   1. 왼쪽상단에서 다운로드 받은 폴더로 이동합니다.
   1. 왼쪽하단에서 아래 4개의 파일을 선택하고 오른쪽으로 드래그앤드랍 합니다.
      * Ctrl01_1.fq.gz
      * Ctrl01_2.fq.gz
      * Exp01_1.fq.gz
      * Exp01_2.fq.gz


   ````
     [TIP]"로그인 창"을 닫은 경우, GRUploader >> 로그인 메뉴를 클릭합니다.
     [TIP]업로드한 파일의 상태값이 'File Upload Fail'인 경우 해당 파일을 업로드 작업을 다시 하면 됩니다.
     [TIP]여러개의 파일을 한번에 선택해서 드래그앤 드랍도 가능합니다.
   ````

1. 오른쪽 테이블에서 업로드한 파일들의 "status"가 모두 'Compleated'가 되면 업로드가 완료입니다.
![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/gruploader_screen_1.jpg)



###  SAMPLE 생성
1. 먼저 Gerome Report[https://omics.genome-report.com/member](https://omics.genome-report.com/member) 페이지에서 로그인을 합니다.
1. 로그인후, 왼쪽 매뉴에서 ["RESOURCE" 메뉴](https://omics.genome-report.com/resource)를 클릭합니다.
2. Resource 페이지에서 "Sample" 메뉴를 클릭합니다.

     ````
     [TIP]GRUploader 프로그램에서 등록한 해독 파일은  YYYY>> MM>>dd-로그인차수 (예:2016>>08>>24-01)에 있습니다.
     ````
4. 수작업으로 sample 생성
   1. 2016>>08>>24-01 폴더에서 Ctrl01_1.fq.gz 파일을 선택(check) 합니다.
   2. 트리위의 버튼 중에서 포워드 버튼을 클릭합니다.
   3. 2016>>08>>24-01 폴더에서 Ctrl01_2.fq.gz 파일을 선택(check) 합니다.
   4. 트리위의 버튼 중에서 백워드 버튼를 클릭합니다.
   5. SAMPLE 명을  "Ctrl01"로 입력합니다.
   5. "샘플 목록 추가" 버튼을 클릭합니다.
   6. 샘플 목록 맨 아래에 있는 승인 버튼을 클릭합니다.

        ````
           [TIP]샘플명은 파일명을 이용하여 프로그램에서 부여합니다. 예)Ctrl01로 합니다.
        ````

   ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_screen_1.jpg)

5. 마법사를 통한 sample 생성
   3. 2016>>08>>24-01 폴더에서 Exp01_1.fq.gz, Exp01_2.fq.gz 파일을 체크합니다.
   4. 트리위의 버튼 중에서 마법사 버튼를 클릭합니다.
   5. 샘플 목록 맨 아래에 있는 승인 버튼을 클릭합니다
   ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_wizard.jpg)

      ````
     [TIP]Explorer 페이지에서 트리를 조회하면  user>>uncategorized>>년(YYYY)>>월(MM)>>일(DD)에 생성한 샘플을 확인할 수 있습니다. 년월일은 SAMPLE 생성일입니다.
     [TIP]마법사 이용시 "샘플명은 필수 입력입니다" 라는 메세지가 나오면 사용자가 직접 "샘플명"을 입력하면 됩니다.
      ````


### 프로젝트(분석) 요청
 2. 왼쪽 매뉴에서 ANALYSIS [https://omics.genome-report.com/analysis](https://omics.genome-report.com/analysis)를 선택합니다. 사용 가능한 파이프라인 목록이 보여집니다.

 3. "유전자 발현량 및 발현량 차이 분석 (Tuxedo Protocol)" 파이프라인을 클릭합니다.
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/analysis_pipeline.jpg)
 4. 분석 요청서 작성
    1. 분석정보의 제목과 설명을 입력합니다.
      ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/pipeline_title.jpg)
    2. 샘플 항목에서 샘플 버튼을 클릭합니다. 팝업창에서  "Ctrl01, Exp01" 샘플을 선택합니다.
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

### 프로젝트 보고서 열람
1. 로그인 상태가 아니면 로그인을 합니다.
2. PRJECT [https://omics.genome-report.com/project](https://omics.genome-report.com/project)페이지로 이동합니다.
3. "유전자 발현량 및 발현량 차이 분석" 제목의  프로젝트를 클릭합니다. 프로젝트 보고서 페이지로 이동합니다.
