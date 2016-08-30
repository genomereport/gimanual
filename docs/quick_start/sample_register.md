# 샘플 등록 및 특성 부여

샘플을 등록하고 정확한 분석을 위한 특성을 부여하는 과정입니다.


## 샘플 등록

샘플 등록은 **파일을 직접 지정하는 방법**과 **마법사를 통한 파일 등록 방법**이 있습니다. 2개의 샘플을 각 각의 방법으로 등록해보겠습니다.


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
      ````
      ````
     [TIP]마법사 이용시 "샘플명은 필수 입력입니다" 라는 메세지가 나오면 사용자가 직접 "샘플명"을 입력하면 됩니다.
      ````

5. 샘플 등록 확인
    1. 화면 왼쪽의 Resource 메뉴를 선택해서 탐색기(Explorer)화면으로 들어갑니다.
    1. 왼쪽 상자 안에서 **user>>uncategorized>>2016>>09>>01**  선택합니다. 
    1. 등록된 2개의 샘플이 나타나는 것을 확인합니다.


## 샘플 특성 부여

Genome report를 이용한 자료 분석 전 샘플의 특성을 설정하는 단계입니다. 앞서 생성된 샘플을 이용하여
샘플의 특성을 설정해보겠습니다.


1. 화면 왼쪽 상자에서  **user>>uncategorized>>YYYY>>MM>>dd(예:2016>>08>>24)**를 선택합니다.
![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen1.jpg)
2. 오른쪽 테이블에서 "Ctrl01" 이 표시된 첫번째 행의 마지막 칸에서 "수정"버튼을 클릭합니다.
3. 아래 화면의 팝업과 같이 설정하고 **승인**을 눌러 저장합니다.
    1. 카테고리 : NGS Sequencing Data
    1. 플랫폼 : Illumina
    1. 샘플 종류 : RNA
    1. 라이브러리 유형 : mRNA-seq
    1. 라이브러리 : TruSeq RNA Library Prep Kit
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen2.jpg)
4. "Exp01"도 윗 작업을 반복합니다.
5. "Ctrl01"과 "Exp01"에 sample Feature등록 완료 화면입니다.
   1. 테이블의  "샘플기능" 컬럼에 데이타가 있습니다.
 ![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/sample_feature_screen3.jpg)



