##CSS의 기초 - 포지션(position)

요소의 절대적 또는 상대적 위치를 지정하여 배치합니다. 절대적이면 공중에 붕뜨게 되고, 상대적이면 공중에 뜨진 않지만, 배치가 가능해집니다.
포지션은 자신의 부모중, position값이 "static" 가 아닌 요소를 기준하여 배치가 적용됩니다.

### position
- 기본값 : static
- 상속성 : 없음
- 작성방법 : `position: static|absolute|fixed|relative|initial|inherit;`

#### 주로쓰이는 값 
값 | 설명
---| ----
absolute | 절대적 위치로 요소를 배치합니다. 주변 요소에 영향을 주지 않습니다.
relative | 상대적 위치로 요소를 배치합니다. 주변 요소에 영향을 줍니다.
fixed | 절대적이면서 윈도우창을 기준하여 배치됩니다. 주변요소에 영향을 주지 않습니다.

#### 거의 안쓰이는 값
값 | 설명
---| ----
static | 문서의 흐름대로 배치됩니다.
 
 
#### 꼭 기억하세요.
- absolute 와 fixed의 차이는 자신의 상위요소의 영향을 받는가 안받는가 입니다.
- 부모요소의 overflow 속성에 따라서 보이고 안보이고가 적용됩니다.