---
id: doc6
title: WEB 사용자 매뉴얼(시민)
sidebar_label: WEB 사용자 매뉴얼(시민)
---

서울기록원의 WEB Application의 사용자 매뉴얼입니다.
[마크다운사용법 확인하기](https://docusaurus.io/docs/en/doc-markdown)

## 1.[기록]검색

기록검색은 푸터,GNB 메뉴에서 접근가능하며, 웹 검색과 구분된다.
별도 접근 페이지에서 접근가능하며 검색페이지에서는 전체 기록을 확인할 수 있다. https://archives.seoul.go.kr/search
* [2018년 12월 13일 기준] : 108039 건
* 집합체 
* 아이템
* 내부파일


### 1.1. [기록]키워드 검색 결과

* 예제 키워드를 “뉴타운"이라고 잡고 검색했을 때
* 표제 “뉴타운"
* 생산자 “뉴타운"
* 설명 “뉴타운"
* 소장처 “뉴타운"
* 파일명 “뉴타운"
* 파일 내부 검색 “뉴타운"


### 1.2. 키워드 검색 결과 - 패싯 세부 검색

* [선택값]기록군/컬렉션, 시리즈, 기록철, 기록건
* [선택값] 키워드를 포함한 생산자 패싯
* [선택값] 키워드를 포함한 기록 년도
* [선택값] 키워드를 포함한 파일 포맷
	* 웹 아카이브
	* 소셜미디어 아카이브
* [선택값] 키워드를 포함한 기록 소장처 (내부 / 외부)


### 1.3. 키워드 검색 결과 - 상세 검색

* [선택값]기록군/컬렉션, 시리즈, 기록철, 기록건
* [입력값] 표제 “뉴타운"
* [입력값] 생산자 “뉴타운"
* [선택값] 키워드를 포함한 기록 년도 설정
* [선택값] 키워드를 포함한 기록 소장처 (내부 / 외부)


### 1.4. 부분검색

* 시리즈 세부에서 https://archives.seoul.go.kr/browse-class/CS-011-000738
* [시리즈]뉴타운사업 관련 기록 #1, 2005 ~ 2009 내에 포함된 파일, 아이템에 대한 키워드 및 년도를 입력시 결과값 노출
	* "하위자료 검색"의 키워드 영역에 키워드를 입력하면 해당 시리즈 내에 포함된 파일, 아이템 내의 좁혀진 검색 결과를 보여줌. 
	* "하위자료 검색"의 년도 영역에 키워드를 입력하면 해당 시리즈 내에 포함된 파일, 아이템의 생산년도를 검색해 좁혀진 결과를 보여줌. 

* 특정 ID 값을 가진 분류(군)에서 하위자료 검색
	* 예) 문화체육(분류) -  https://archives.seoul.go.kr/class/CS-010-000724
		* 하위검색 키워드 “올림픽"
		```https://archives.seoul.go.kr/search?query=올림픽&lowrank_year=&lowuid=74F1046B-A108-475A-B183-DB6BD58B84B5```
		* 하위검색 키워드 “서울"
		```https://archives.seoul.go.kr/search?query=서울&lowrank_year=&lowuid=74F1046B-A108-475A-B183-DB6BD58B84B5```

* 특정 ID 값을 가진 시리즈(계열)에서 하위자료 검색
	* 예) 혁신파크 도면(시리즈) - https://archives.seoul.go.kr/aggregation/0000000000004468
		* 하위검색 키워드 “5동" ```https://archives.seoul.go.kr/search?query=5동&lowrank_year=&lowuid=222B5847-7F3D-484E-B1C8-B0C309480B33```
		* 하위검색 키워드 “7동" ```https://archives.seoul.go.kr/search?query=7동&lowrank_year=&lowuid=222B5847-7F3D-484E-B1C8-B0C309480B33```

* 특정ID 값을 가진 파일(철)에서 하위자료 검색
	* 예) 촉진계획결정(파일) - https://archives.seoul.go.kr/aggregation/5563
		* 하위검색 키워드 “행정" ```https://archives.seoul.go.kr/search?query=행정&lowrank_year=&lowuid=3bd4a382-fd11-4b19-b447-4e73dab8a47d```


### 1.5. 키워드 중심 검색의 어려움

* [시리즈]뉴타운사업 관련 기록 #1, 2005 ~ 2009에 포함되어 있는 다양한 키워드를 알고 있더라도 [시리즈]뉴타운사업 관련 기록 #2, 2009 ~ 2012 같은 다른 시리즈에 도달할 가능성이 있음. 두 시리즈가 어떻게 다른지에 대한 설명은 없음. 
	* 상위 분류 및 하위 분류에 지속적으로 시리즈, 파일이 추가되어 특수한 URL 및 등록번호를 알고있지 않으면 대화 및 논의 과정에서 혼선이 생길 수 있음.
	* 이관된 기록이 많아질 수록 기록의 복잡도는 계속 높아지고, 중복되는 키워드는 많아져서 구체적인 생산자, 생산부서등의 혼선이 올 수 있다. 
* 보안책(운영) -> 웹검색에 걸리는 기록 접근 도구 제공
	* 웹검색
	* 조사/연구 가이드
	* 기록 공지 및 안내
	* 도움말
* 보안책(사용자 제공 서비스)
	* 즐겨찾기
	* 다운로드
	* 사용자 태그



### 1.6. 사용자 태그 검색

* 현재 태그는 별도 목록에서 제공 (기록으로부터 나오는 메타 정보가 아니기 때문에 사용자가 작성한 태그가 정확한 태그인지 확인하는 과정이 필요하다.)
* 내가 기록을 보면서 적어놓은 태그는 바로 활성화 되기 때문에, 공개된 태그를 중심으로 기록을 엮어 놓을 수 있다. 
* 특정사용자의 - 뉴타운(태그)
	* [시리즈] 뉴타운사업 관련 기록 #1, 2005 ~ 2009
	* [파일]*****
	* [파일]*****
	* [파일]*****
	* [파일]*****
	* [파일]*****
	* [아이템]******
	* [아이템]******
	* [아이템]******
	* [아이템]******


### 1.7. 웹아카이브, 소셜미디어 아카이브

* “뉴타운"이라는 키워드를 포함한 웹아카이브, 소셜미디어 아카이브 검색결과 값
	* 시리즈 기술의 카탈로그 정보로 검색
* 시리즈 기술 하위에 관련된 웹 아카이브 링크를 통해 세부 제공 함. 


## 2. [접근도구]웹사이트 검색

* 메인에 웹사이트 검색 제공
* 복잡한 카탈로그와 검색정보는 사용자에게 어려운 허들이다. 관련해서 도움말 및 기록이 어떻게 서비스 되고 있는지에 대한 제반 정보들을 웹사이트 검색을 통해 우회적으로 제공하려는 용도가 크다. 
* 웹사이트 관련 메뉴들을 작성할 시에는 반드시 해당 기록의 명칭과 링크를 남겨서 카탈로그로 접근할 수 있도록 도와야한다. 
* 같은 구조로 서울시 홈페이지로 전달하는 DB는 기록 DB를 전달하기 보다, 연계정보를 전달할 수 있는 웹사이트 검색의 결과 및 색인 조회하는 구조와 동일하게 전달하는 것이 좋다. 


### 2.1. [접근도구]웹사이트 검색 - 도움말

* https://archives.seoul.go.kr/user-guide/1
* 모든 사용자는 디지털아카이브에 대한 간단한 사용 안내 내용을 확인할 수 있다.
	* 기록 조사/연구자를 위한 도움말
	* 기록물을 기증한 민간 단체, 개인을 위한 도움말
	* 서울의 공공기록물에 관심있는 모든 사람을 위한 도움말



### 2.2. [접근도구]웹사이트 검색 - 공지, 칼럼, 연구보고서

* https://archives.seoul.go.kr/newsList
* 공지, 칼럼, 연구보고서  보기


### 2.3. [접근도구]웹사이트 검색 - 조사/연구 가이드

* https://archives.seoul.go.kr/research-guides
* 조사/연구 가이드 보기


### 2.4. [접근도구]웹사이트 검색 - 입수기록 공지(최근 입수된 기록)

* 공지사항 중 (최근 입수된 기록 설명) 보기

### 2.5. [접근도구]사용자 커뮤니티 - 공개된 질의 응답 

* 로그인 사용자들이 직접 공개적으로 질문을 함
* 공개된 질문에  응답할 수 있음
* 질문 발행시 - 요청과 동일하게 이슈 티켓이 발생


### 2.6. 일반문의

* 비로그인/.로그인 사용자가 상시적으로 문의가능
* 이름, 이메일, 전화번호를 적고 개인정보제공동의 후 서울기록원과 관련된 기본적인 문의 가능
* 관련된 문의신청을 관리자가 확인하고 회신함


### 2.7. 오류신고

* 비로그인/.로그인 사용자가 상시적으로 문의가능
* 푸터 위에 있는 정보로 오류신고 입력창으로 입력 가능


## 3. [탐색]카탈로그와 기록탐색

기록 '탐색'은 검색어를 직접 입력해 기록을 찾는 '검색'과 달리, 분류체계를 기준으로 지정된 기록 묶음 단위(시리즈, 파일)에서 출발해 기록물의 생산 맥락에 따라 기록을 찾아가는 과정이다. 
탐색을 통해 존재 여부를 알 수 없었던 기록을 발견할 수도 있고, 기록의 생산 맥락을 확인하며 찾아낸 기록물의 내용을 정확하게 이해할 수 있다.
현재는 2018년 시범적으로 진행된 카탈로그 모형과 카탈로깅 내용을 기반으로 분야별(Records by Subject), 기관유형별 (Records by Organization), 행정, 수집기록의 컬렉션(Records by Collection)별 탐색과정을 제공하고 있습니다. 진행중인 카달로깅 정보가 포함되어 있으며, 추후 카탈로그 서비스로 귀속될 수 있다. 기술계층(시리즈, 파일, 아이템)에 한하여 서비스를 제공하며, 아이템 세부 페이지에서 원문파일을 조회할 수 있다.

사용자간 기록과 관련된 커뮤니케이션을 위해서는 아래와 같은 방법으로 할 수 있다.
* 기술계층과 표제 
* 일련번호
* 서비스되고 있는 링크 그 자체 전달


### 3.1. 분야(Subject)별 기록보기

* https://archives.seoul.go.kr/class/CS-010-000730
* 현재는 2018년 시범적으로 진행된 카탈로그 모형과 카탈로깅 내용을 기반으로 분야별(Records by Subject) 탐색과정을 제공한다.

### 3.2. 기관(Organization)별 기록보기

* https://archives.seoul.go.kr/class/CS-011-000738
* 현재는 2018년 시범적으로 진행된 카탈로그 모형과 카탈로깅 내용을 기반으로 기관유형별 (Records by Organization) 탐색과정을 제공한다.

### 3.3. 컬렉션(Collection)별 기록보기

* https://archives.seoul.go.kr/class/CS-009-000806
* 현재는 2018년 시범적으로 진행된 카탈로그 모형과 카탈로깅 내용을 기반으로 행정, 수집기록의 컬렉션(Records by Collection)별 탐색과정을 제공한다.

### 3.4. 카탈로그 내의 컬렉션 vs. 푸터 메뉴의 컬렉션 차이점

서울기록원에서는 행정, 수집기록의 컬렉션(Records by Collection)과 디지털 전시 혹은 임시 모음의 명칭 또한 컬렉션을 사용하기로 결정한다. 다수의 기록을 관리하는 지방영구기록관리기관에서 목록중심의 서비스를 하는 카탈로그내의 수집기록, 디지털 전시, 임시 모음 모두를 컬렉션으로 지칭하고 서비스하기로 결정했기 때문이다. 

## 4. [조회] 기록조회

### 4.1. 군, 시리즈, 파일 목록 조회

* 탐색과정에서는 여러 목록을 가진 기록군/컬렉션, 시리즈, 기록철 목록을 제공
* 클릭시 세부 기록기술이 보여지는 페이지로 이동


### 4.2. 군, 시리즈, 파일, 아이템 기록기술 조회

* 각 타입은 개별 기록 정보가 보여지는 세부 페이지가 존재
* 기록군/컬렉션
	* 기록군 : https://archives.seoul.go.kr/browse-class/CS-010-000730
	* 컬렉션 : https://archives.seoul.go.kr/browse-class/CS-009-000775
* 시리즈 : https://archives.seoul.go.kr/aggregation/4407
* 기록철 : https://archives.seoul.go.kr/aggregation/5563
* 기록건 : https://archives.seoul.go.kr/item/1835777


### 4.3. 군, 시리즈, 파일, 아이템 기록기술상 전거(Athority) 조회

* 현재는 2018년 시범적으로 진행된 카탈로그 모형과 카탈로깅 내용을 기반으로 기록기술상 전거(Athority)를 제공하고 있습니다. 관련된 제공방식은 카탈로그 서비스 방식에 따라 변경될 수 있다. 

### 4.4. 아이템 컴포넌트 조회(아이템 화면)

* 기록건(PDF) : https://archives.seoul.go.kr/item/1835777
* 기록건(JPG,PNG) : https://archives.seoul.go.kr/item/1840441
* 기록건(영상) : https://archives.seoul.go.kr/item/1840446
* 기록건(hwp) : 노출 안 함.
* 컴포넌트 자세히 보기
	* 전체화면
	* 일반화면
	* 확대
	* 축소
	* 초기화


### 4.5. 아이템 컴포넌트 조회(전체화면 보기)

* 기록건(PDF) : https://archives.seoul.go.kr/item/1835777
* 기록건(JPG,PNG) : https://archives.seoul.go.kr/item/1840441
* 기록건(영상) : https://archives.seoul.go.kr/item/1840446
* 기록건(hwp) : 노출 안 함.
* 컴포넌트 자세히 보기
	* 전체화면
	* 일반화면
	* 확대
	* 축소
	* 초기화

### 4.6. 군, 시리즈, 파일, 아이템 기록기술 정보 공유, 출력

* 해당 세부보기 내용을 다운로드 할 수 있다. 
* 해당 세부보기 내용을 인쇄할 수 있다. 인쇄버전에서는 별도의 CSS를 제공해서 프린트로 보기 좋은 화면을 제공한다. 
* CCL 라이센스 적용에 따른 저작권 정책 내용을 확인할 수 있다. 
* 서울기록원의 링크를 전달하면 해당 기록의 메타 정보가 노출된다.

### 4.7. 아이템 컴포넌트 다운로드

* 해당 아이템의 컴포넌트를 다운로드

### 4.8. 군, 시리즈, 파일, 아이템 즐겨찾기

* 내 계정에 즐겨찾기 추가 가능

### 4.9. 로그인 사용자의 공개된 태그 작성

* 로그인 사용자만 태그 작성 가능
* 욕설, 문제가 있는 태그 신고 가능
* 자신이 작성하거나 다른 사용자가 작성한 이후 태그 공개 정책에 따라서 차단될 수 있음


### 4.10. 허용된 기록에 사용자 참여 전사(트랜스크립션)

* 관리자가 기록을 찾아서 트랜스크립션 공개 설정
* 기존화면과 다르게 트랜스크립션 가능한 상태로 변경
* 트랜스크립트 가능한 기록
	* 전사전 기록상태
	* 전사 진행중 기록상태
* 견학 및 다양한 이벤트에 함께 사용할 수 있음
* 공개된 트랜스크립션을 보는 것은 가능
* 로그인 사용자만 공개된 트랜스크립션에 참여 가능

### 4.11. 기록내용에 대한 확인 및 문의

* 기록(아이템) /  기록(파일)  / 기록(시리즈) / 기록(그룹) 세부화면에서 정보오류신고 문의하기
* 문의 내용을 내 계정 페이지에서 확인

## 5. [내 계정]보관함

* 기록(아이템) /  기록(파일) 세부의 보관함 추가 버튼 클릭
* 기본 보관함에 추가
* 닫거나 타 영역을 누르면 화면 전환


### 5.1. 보관함(임시 저장 목록)

* 기록(아이템) /  기록(파일) 세부의 보관함 추가 버튼 클릭
* 기본 보관함에 추가
* 닫거나 타 영역을 누르면 화면 전환


### 5.2. 방문열람신청
(2019년 열람실 준비 후 서비스 시작)
* 기록(아이템) /  기록(파일) 기본 보관함에서 보관함 추가 버튼 클릭
* 추가된 항목을 방문열람 탭으로 이동
* 열람자 정보 신청 하고 등록
* 방문열람 신청한 내용을 내 계정 페이지에서 확인
* 관리자 승인시 사용자는 안내 메일을 수신


### 5.3. 보존여부확인

* 추가된 항목을 보존여부확인 탭으로 이동하거나 / 항목이 없어도 신청 가능
* 신청자 개인 정보 입력하고 등록
* 보존여부확인을 신청한 내용을 내 계정 페이지에서 확인
* 관리자 승인시 사용자는 안내 메일을 수신


### 5.4. 반출
(2019년 열람실 준비 후 서비스 시작/4월 목동 컬렉션)
* 기록(아이템) /  기록(파일) 기본 보관함에서 보관함 추가 버튼 클릭
* 추가된 항목을 반출 탭으로 이동
* 반출 정보 신청 하고 등록
* 반출신청한 내용을 내 계정 페이지에서 확인
* 관리자 승인시 사용자는 안내 메일을 수신


### 5.5. 출력

* 기록군/컬렉션, 시리즈, 기록철, 기록건 세부 페이지에서 웹 기본 출력
* 이용자가 스스로 전자/전자화 기록을 출력


### 5.6. 복사
(2019년 열람실 준비 후 서비스 시작/4월 목동 컬렉션)
* 기록(아이템) /  기록(파일) 기본 보관함에서 보관함 추가 버튼 클릭
* 추가된 항목을 복사 탭으로 이동
* 복사요청자 정보 신청 하고 등록
* 복사 요청한 내용을 내 계정 페이지에서 확인
* 관리자 승인시 사용자는 안내 메일을 수신

## 6. [내 계정]사용자

* 사용자 정보는 이메일이 기본
* 페이스북을 통해 로그인한 사용자만을 대상으로 프로필 이미지를 수집 
* 비밀번호를 재설정하는 페이지에 접근가능

### 6.1. 사용자 정보

* 사용자 정보는 이메일이 기본
* 비밀번호를 재설정하는 페이지에 접근가능

### 6.2. 즐겨찾기

* 사용자는 기록에 대해 즐겨찾기 가능
* 즐겨찾기 기록시에 분류와 이름을 지정

### 6.3. 다운로드 목록

* 사용자는 기록에 대해 다운로드한 목록 확인가능
* 다운로드 목록을 다시 다운로드 할 수 있음

### 6.4. 태그 목록

* 본인이 작성한 태그 목록을 확인
* 태그를 클릭하면 해당 기록물로 이동

### 6.5. 내가 요청한 목록

* 보관함으로 이동버튼
* 방문열람신청, 보존여부확인, 반출, 출력, 복사 요청한 이력 목록 클릭시 세부로 이동



## 7.[확장] 디지털, 공간 및 현장, 외부


### 7.1. 온라인 컬렉션(전시)

* 샘플 컬렉션 및 전시
	* 서울사진아카이브
	* 용산공원 특별전시
	* 일본군 위안부 기록
* 컬렉션 메인
	* 프리셋 - 블로그형
	* 프리셋 - 갤러리 세로형
	* 프리셋 - 갤러리 가로형
	* 프리셋 - 사진 목록형

### 7.2. 디지털접점 - 모바일 접근 및 활용에 대한 안내

* 반응형 웹 디자인(전체)
* 모바일 디자인 대응(전체)

### 7.3. VR - 청도문서고

* 청도문서고는 각종 재난이나 자연재해에 대비, 중요 기록물의 안전한 분산 보존을 위해 서울특별시가 경상북도 청도군에 운영하는 전용 서고입니다. 기록과 기물의 이전을 준비중에 있으며 청도문서고 공간을 기억하기 위해 내.외부를 촬영한 VR 영상을 보실 수 있습니다.

### 7.4.공간접점 - 서울기록원 안내, 조직 안내

* 서울기록원 안내
* 조직도
* 개발자를 위한 안내

### 7.5.공간접점 - 견학 안내 및 신청

* 비로그인/.로그인 사용자가 상시적으로 문의가능
* 견학문의는 단체에 소속된 개인이 단체명의로 신청시 진행가능 - 단체명, 인솔자 이름, 방문일 및 시간, 방문자수, 연락처, 목적 및 기타문의, 개인정보제공동의
* 관련된 문의신청을 관리자가 확인하고 회신함

### 7.6.외부접점(연계기관) - 검색 API 제공

* 검색 API 설명 및 문서
* 개발자를 위한 안내
* API 설명 문서관리 :  https://github.com/sda17dev/sda-dev-docs
* API 설명(자세히) : https://sda17dev.github.io/sda-dev-docs/docs/doc8.html

### 7.7.외부접점(연계기관) - Restful API / 타 조직을 위한 Wrapper

* 설명 문서관리 :  https://github.com/sda17dev/sda-dev-docs
* Restful API 설명(자세히) : https://sda17dev.github.io/sda-dev-docs/docs/doc9.html
* Wrapper 설명(자세히) : https://sda17dev.github.io/sda-dev-docs/docs/doc8.html
* PHP Wrapper : github(진행 전)
* JAVA Wrapper : github(진행 전)

### 7.8.외부접점(연계기관) - 개발자를 위한 안내, Github 및 Document 제공

* 개발자를 위한 안내 :  https://archives.seoul.go.kr/helps-for-developer
* 설명 문서관리 :  https://github.com/sda17dev/sda-dev-docs

## 8.[기타]웹 서비스 전반

### 8.1. 이용약관

https://archives.seoul.go.kr/agreement

### 8.2. 개인정보보호방침
https://archives.seoul.go.kr/privacy

### 8.3. 저작권정책
https://www.seoul.go.kr/helper/copyright.do

