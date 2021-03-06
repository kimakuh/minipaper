##CSS의 기초 - 상하정렬(vertical-align)

텍스트의 상하정렬을 정의합니다. 중요한것은 텍스트들 끼리의 정렬을 지정하며,
블럭 안의 상하정렬을 이야기 하는것은 아닙니다.  

단, table-cell(td)일 경우에는 전체적인 상하를 이야기 합니다.

### vertical-align
- 기본값 : "baseline"
- 자식상속 : 안됨
- 작성방법 : `vertical-align: baseline|length|sub|super|top|text-top|middle|bottom|text-bottom;`

#### 주로 쓰이는 값 
값 | 설명
---| ----
top | 모든 inline or inline-block 요소를 자평을 기준하여 상단 정렬합니다.
middle | 모든 inline or inline-block 요소를 자평을 기준하여 중단 정렬합니다.
bottom | 모든 inline or inline-block 요소를 자평을 기준하여 하단 정렬합니다.

#### 거의 안쓰이는 값
값 | 설명
---| ----
baseline | 영문의 하단꼬리 부분을 뺀 라인(이것이 베이스라인)을 기준합니다.
length | 부모요소의 베이스라인의 위치에서 양수라면 위로, 음수라면 아래로 베이스라인을 적용합니다.
sub | 부모요소의 영문 아랫첨자 라인에 자신의 베이스라인을 맞춥니다.
super | 부모요소의 영문 윗첨자 라인에 자신의 베이스라인을 맞춥니다.
text-top | 부모요소의 맨윗라인에 자신의 글자 상단 라인을 맞춥니다.
text-bottom | 부모요소의 맨 하단라인에 자신의 글자 하단 라인을 맞춥니다.


#### 실무 포인트
- 자평을 기준해서 적용되는것이 수훨하기 떄문에, top , middle , bottom 이 주로 쓰입니다.

