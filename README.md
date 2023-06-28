# map-project
## 카카오맵 API 기반 위치 정보 받아오기

index.html - 현재위치가져오기
search.html - 현재위치(x), api 검색결과 제공

test.html - index + 다른 장소 객체 생성
             -> 생성한 객체의 위도, 경도 및 현재 위치 거리
             -> 생성한 객체 지도상 마커 표시 
             
test2-search.html - test + 검색 기능

tset3-markerPoint - test2 + 마커에  name 표시 




## 네이버맵 API 기반 위치 정보 받아오기

네이버로 진행 ! (카카오맵 API 사용 X )

주요 페이지
naver/main-page.html



## ADMIN 

주소 -> 위도,경도로 변환


주요 페이지
admin/admin-page.html


※ admin-page.html 에서 주소 검색시, 올바른 지번주소 또는 도로주소를 사용하여야 한다.

(ex) 서울특별시 성동구 성수동2가 아차산로 92 에스타워 
-> 존재하는 주소이긴 하지만, 더 명확한 주소로 검색하여야 찾을 수 있음 

수정 >>  지번 주소: 서울특별시 성동구 성수동2가 314-5 S TOWER
        도로명: 서울특별시 성동구 아차산로 92 S TOWER

        둘 중 하나로 사용하여야 위도,경도 변환 가능 !!
