## 1주차 TASK

### 기본 셋팅
- [x] svg 파일 다운
- [x] 색상 코드 설정
- [x] 폰트 css 파일

### 헤더 영역

가계부의 모든 화면에 나타나야 함

- [x]  로고
- [ ]  로고 누르면 메인으로 이동
- [x]  현재 연월 표시(좌우 이동 가능)
- [x]  탭
- [ ]  탭 누르면 화면 변환

### 새로운 내역 입력(메인)

수입 지출 내역 입력

- [ ]  날짜 인풋 박스
- [ ]  마이너스/플러스 버튼
- [ ]  금액 인풋 박스
- [ ]  내용 입력 칸
- [ ]  결제수단 입력 셀렉트 박스
    - [ ] 결제 수단 삭제 기능
    - [ ] 결제 수단 추가 하기 기능
- [ ]  분류 셀렉트 박스
- [ ]  확인 버튼
    - [ ] 유효성 검증하는 부분 (기획 `필요`)

### 수입 지출 내역 목록(메인)

상단

- [ ]  전체 내역 건수
- [ ]  해당 월의 총 수입액, 지출액
- [ ]  수입 내역, 지출 내역 필터링 기능

내용

- [ ]  수입지출 리스트 정렬(최신순)
- [ ]  일별 리스트 컴포넌트 (일자, 요일, 수입액, 지출액)
- [ ]  수입지출 각 내역 컴포넌트
    - [ ] 마우스 올리면 삭제 버튼
    - [ ] 삭제 알럿창
    - [ ] 마우스 올린 후 삭제 버튼이 아닌 곳 클릭하면 해당 내용이 내역 입력 부분으로 이동 → 수정 가능하도록
        - [ ] 선택되었던 수입지출 내역은 내역 입력바가 아닌 다른 영역을 클릭하거나 완료 버튼을 눌렀을 때 hover/selected 상태에서 해제되도록 함

## 2주차 TASK

### 달력 화면

일별 내역 통계를 캘린더로 확인할 수 있음

- [ ]  오늘 날짜 배경색 다르게
- [ ]  수입, 지출 일별 합계 표시(색깔 다르게)
- [ ]  해당 월의 총 수입, 총 지출, 총합 표시(하단)

### 통계 화면

카테고리별 지출 내용을 확인할 수 있는 페이지

- [ ]  해당 월의 총 지출금액 표시
- [ ]  카테고리 지출 컴포넌트
    - 클릭 시 월별 소비 추이 그래프 및 상세 내역 펼쳐짐
- [ ]  가장 비율이 큰 카테고리순 정렬
- [ ]  `필수 조건 아님` 차트 애니메이션
- [ ]  월별 소비 추이 그래프 (최근 6개월 지출 내역)
- [ ]  월별 소비 상세 내역 (메인과 동일)
