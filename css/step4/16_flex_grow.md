##CSS의 기초 - 플랙스아이템 가로비율(flex-grow)

플랙스 아이템의 디렉션 방향의 사이즈 비율을 지정합니다. 본 속성을 지정하면,
디렉션에 해당하는 사이즈속성(width | height)가 무시될수 있습니다.

### flex-grow
- 기본값 : 0
- 상속성 : 없음
- 작성방법 : `flex-grow: number|initial|inherit;`

#### 주로쓰이는 값
값 | 설명
---| ----
number | 적용될 비율을 적용합니다.

#### 사이즈조정 알고리즘
- 디렉션에 따른 아이템의 사이즈을 선반영하여, 줄바꿈을 발생시킨다.
- 줄바꿈이 되어 발생한 가상의 컨테이너안에서 각 아이템들의 사이즈를 계산하여 유후공간을 계산한다.
- 유후공간을 지정된 비율대로 나누어 적용한다.