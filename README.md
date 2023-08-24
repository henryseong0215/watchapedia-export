# Watchapedia export
- 요즘 왓챠 기사가 많이 나와서 데이터 백업하려고 예전 [익무글](https://extmovie.com/movietalk/37623288)을 찾아봤는데 막혀버렸네요.
- 그래서 직접 만들었습니다. 저와 같은 분들이 많으실 것 같아서 관련 방법 공유합니다.

### 백업 방법
1. 크롬에서 왓챠피디아 웹사이트에 로그인합니다. https://pedia.watcha.com
    <img width="650" src="https://raw.githubusercontent.com/henryseong0215/watchapedia-export/main/img/export_001.png">
2. 왓챠피디아 주소 창에 javascript:를 입력하고(:콜론 까지 입력)
    <img width="650" src="https://raw.githubusercontent.com/henryseong0215/watchapedia-export/main/img/export_002.png">
3. [watchapedia_export.js](https://github.com/henryseong0215/watchapedia-export/blob/main/watchapedia_export.js) 링크 클릭 후 스크립트를 복사하고 javascript: 바로 뒤에 붙여넣기 한 뒤에 엔터 키를 입력해주세요.
    <img width="650" src="https://raw.githubusercontent.com/henryseong0215/watchapedia-export/main/img/export_003.png">
    <img width="650" src="https://raw.githubusercontent.com/henryseong0215/watchapedia-export/main/img/export_004.png">
4. 잠시만 기다리면 내 기록이 파일로 다운로드됩니다. 

### 참고사항
- 왓챠피디아 계정이 '비공개' 또는 '친구 공개'인 경우 '전체 공개'로 변경해야만 모든 데이터를 다운로드 받을 수 있습니다.
- 본 날짜(WatchedAt)는 왓챠피디아에 코멘트를 작성한 경우에만 기록됩니다.

### Demo 영상
https://www.loom.com/share/dc1babd208ae4aa89d7b95a5b1c78f24
