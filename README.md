## 1. 노인 교통사고 데이터

### 데이터 링크

[**https://github.com/lookbackjh/Tobigs_18th_Conference_DA/tree/main/DA/junho/노인사고데이터**](https://github.com/lookbackjh/Tobigs_18th_Conference_DA/tree/main/DA/junho/%EB%85%B8%EC%9D%B8%EC%82%AC%EA%B3%A0%EB%8D%B0%EC%9D%B4%ED%84%B0)

Column구성

'year', 'sidocode', 'guguncode', 'spot_nm', 'occrrnc_cnt',
'sido_sgg_nm', 'caslt_cnt', 'dth_dnv_cnt', 'se_dnv_cnt', 'sl_dnv_cnt',
'wnd_dnv_cnt', 'lo_crd', 'la_crd'

**year**: 연도

**sidocode**: 11(서울 )

**spot_nm** : 지점명

**guguncode**: 구

**spot_nm**: 지점명(상세주소), e.g 서울특별시 강남구 논현동(청하빌딩 부근)

**occrrnc_cnt**: 교통사고 발생건수

**sido_sgg_nm**: 시도군구명(spotnm이라 겹처서 굳이?)

**caslt_cnt**: 사상자수

**dth_dnv_cnt**: 사망자수

**se_dnv_cnt**: 중상자수

**sl_dnv_cnt**: 경상자수

**wnd_dnv_cnt**: 부상신고자

**lo_crd**: 위도

**la_crd**: 경도

### **간단한 사용법→ https://github.com/lookbackjh/Tobigs_18th_Conference_DA/blob/main/DA/junho/example.ipynb**

위 링크 확인

### 만약 일별데이터가 필요하다 싶으면..

이걸 사용해도 괜찮지 않을까… 

https://www.data.go.kr/data/15094143/fileData.do?recommendDataYn=Y

## 2.  서울시 생활이동 데이터

### 데이터

https://github.com/lookbackjh/Tobigs_18th_Conference_DA/tree/main/DA/junho/서울이동데이터_지역별

위링크 들어가면 확인 할 수 있고, 지역별로 나누어두었습니다.

### 데이터 간단한 설명

그 시간대에 그 지역에 생활 인구가 얼마나 많이 몰려있는지 를 측정한 데이터입니다

활용예시: https://github.com/lookbackjh/Tobigs_18th_Conference_DA/blob/main/DA/junho/example.ipynb