# 파일 업로드

Genome report를 이용한 NGS데이터 분석을 위해서 해야할 첫 번째 작업은 파일 업로드 입니다. 

Genome report는 파일 업로드를 위해서
**GRUploader를 이용한 파일 업로드**와 **웹을 이용한 파일 업로드**를 지원하고 있으며, 500M 이상의 대용량 파일은 GRUploader를 이용하셔야만
업로드 하실 수 있습니다. 이 예제에서는 GR Uploader를 이용해서 파일 업로드하는 것을 실습하겠습니다.


## Step 1. GRUploader 받기

GRUploader는 Genome report 에서 사용하는 전용 파일 업로드 프로그램 입니다. 로그인 후  **SUPPORT -> Download** 메뉴를 선택하거나 다음 주소를 이용하여 바로 접근할 수 있습니다.

* <a href="http://www.genome-report.com/down_file" target="_blank">http://www.genome-report.com/down_file</a>

다운로드 페이지에는 각 운영체제에 해당하는 다운로드 프로그램을 받을 수 있는 링크가 준비되어 있습니다.
각 운영체제에 해당하는 실행파일을 다운로드 받습니다. (윈도우는 왼쪽, OSX와 리눅스는 오른쪽을 선택하시면 됩니다.)

![화면](https://github.com/genomereport/gimanual/raw/master/docs/images/screen_3.jpg)



## Step 2. 실행 및 로그인

다운로드 받은 GRUploader를 실행합니다. 만약 윈도우에서 다운로드 받은 파일 실행 시에 "Windows의 PC보호"화면이 나올 경우 화면안의 **"추가 정보"**를 선택하시면, 설치를 계속 진행하실 수 있습니다.

로그인 창이 나타나면, Genome report 가입 ID와 암호를 입력하고 로그인 합니다.

!!!tip "Tip"
    "로그인 창"을 닫은 경우, GRUploader >> 로그인 메뉴를 클릭합니다.

## Step 3. 파일을 업로드

다운 받은 파일을 업로드 할 차례입니다. GRUploader는 3개의 화면으로 구성되어 있습니다. 왼쪽 상단의 디렉토리 선택 창, 왼쪽 하단의 파일 창, 오른쪽 파일 업로드 창입니다.
다음 순서를 따라서 파일을 업로드 합니다.

1. 왼쪽상단에서 다운로드 받은 폴더로 이동합니다.
1. 왼쪽하단에서 아래 4개의 파일을 선택하고 오른쪽으로 드래그앤드랍 합니다.
    - Ctrl01_1.fq.gz
    - Ctrl01_2.fq.gz
    - Exp01_1.fq.gz
    - Exp01_2.fq.gz

!!!tip "Tip"
    여러개의 파일을 한번에 선택해서 드래그앤 드랍도 가능합니다.

오른쪽 창에서 업로드한 파일들의 "Status"가 모두 'Completed'가 되면 업로드가 될때까지 기다립니다.

!!!note "Note"
    업로드한 파일의 상태값이 'File Upload Fail'인 경우 해당 파일을 업로드 작업을 다시 하면 됩니다.



![업로드가 완료된 후 표시](https://github.com/genomereport/gimanual/raw/master/docs/images/gruploader_screen_1.jpg)


