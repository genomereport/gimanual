### GRUploader 사용자 매뉴얼

#### 선행작업
  - 회원가입
     - 사이트 주소는 [https://omics.genome-report.com/member](https://omics.genome-report.com/member)
  - GRUploader 다운로드
     - 다운로드 경로는 [http://www.genome-report.com/download](http://www.genome-report.com/download)
     - 자신의 OS 버전에 맞게 다운로드한다. 왼쪽 DOWNLOAD 버튼은 윈동우용, 오른쪽 DOWNLOAD 버튼은 OS X 용입니다.
  - JDK7.0+  설치
     - 미설치시 설치하라는 알람창이 열립니다.
     
#### 화면 설명 
 - 왼쪽 상단 : PC의 폴더 정보입니다.
 - 왼쪽 하단 : 선택한 디렉토리의 하위 폴더및 파일 목록 입니다.
   - Icon : 폴더 여부입니다.
   - File : 파일명입니다.
   - Path_name : 파일의 전체 경로입니다
   -  Size : 디렉토리 또는 파일의 크기입니다.
   -  Last Modified : 폴더 또는 파일의 마지막 수정 일자입니다.
 - 오른쪽   :  업로드한 파일의 정보와 상태 입니다.
  - Filename : 업로드한 파일명입니다.
  - Filesize : 업로드한 파일의 크기입니다.
  - Upload Folder : 업로드한 파일의 저장 위치 입니다. 형식은 yyyy/MM/dd-당일로그인횟수 입니다.
  - Status : 업로드 파일의 상태입니다., 별첨 1) 참조
  - command : 업로드가 완료되기 전에 취소할 수 있는 버튼입니다.  
  ![화면](http://www.genome-report.com/assets/images/manual/screen_1.jpg)
   
#### File Upload  방법 
- GRUploader를 실행합니다.
- 로그인 을 합니다.
   - 로그인 창이 보이지 않으면  상단 메뉴바의 GRUploader > Login  메뉴를 선택합니다.
- [단계 1]왼쪽 상단 판넬에서 업로드할 파일이 있는 폴더를 선택합니다.
- [단계 2]왼쪽 하단 판넬에서 업로드할 파일을 선택한다. 여러개의 파일을 선택할 수 있습니다.
- [단계 3]선택한 파일들을 오른쪽 판넬로 드래그앤드랍을 합니다.
![화면](http://www.genome-report.com/assets/images/manual/screen_2.jpg)

#### GRUploader 업그레이드 방법 
- 로그인시 업그레이드가 있는 경우  업그레이드 안내 팝업창이 나타납니다.
-  Help > Download page 메뉴를 통해서 최신 버전으로 업그레이드 할 수 있습니다.
- 업그레이드는 프로그램 성능향상을 위해 수시로 진행됩니다.
- 왼쪽 DOWNLOAD 버튼은 윈동우용, 오른쪽 DOWNLOAD 버튼은 OS X 용입니다.
![화면](http://www.genome-report.com/assets/images/manual/screen_3.jpg)
 
#### GRUploader 버전 확인
- Help > About 메뉴에 현재 버전이 있습니다.
![화면](http://www.genome-report.com/assets/images/manual/screen_4.jpg)


#### GRUploader 주요 기능
 - Drag&Drop으로 파일 업로드
 - 업로드 작업 취소
   - 파일 업로드 도중에 취소를 할 수 있습니다.
   - 취소 하고 싶은 파일 있는 행에서 Cancel버튼을 클릭합니다.
 - 업그레이드 알람
  - 로그인시 새로운 버전이 있는 경우 팝업창이  나타납니다.
 - GRUploader 다운로드 페이지 제공
 - 자동 재 업로드 기능
   - 업로드가 실패한 경우에 다시 로그인을 하는 경우 자동으로 업로드 작업이 진행됩니다.
   - 사용자가 취소한 작업은 자동으로 다시 업로드 되지 않습니다. 
 - 진행 상태바
   - 업로드 파일의 진행 상황을 알 수 있는 상태바 입니다.

#### 별첨1) 파일 업로드 상태
 - Init : 파일 업로드를 요청한 상태입니다.
 - Completed : 파일 업로드가 정상적으로 완료 된 상태입니다.
 - Canceled : 파일 업로드를 사용자가 취소한 상태입니다.
 - File upload fail : 알 수 없는 이유로 파일 업로드를 실패한 상태입니다., 해당 파일을 다시 업로드 할 수 있습니다.
 - File duplication error : 같은 upload folder에 같은 파일이 업로드 된 상태입니다. 
