##CSS의 기초 - 인라인 박스모델(inline Box Model)

HTML 엘리먼트는 block , inline-block , inline , none 이라는 4가지의 외형구조를 가지고 있습니다.
이 4가지의 외형구조는 CSS의 display의 기본값으로 적용되지만, CSS을 통해서 엘리먼트의 외형구조를 바꿀수도 있습니다.

그 중, inline 요소에 해당하는 부분에 대하여 설명합니다.

![박스모델](http://www.cssterm.com/uploads/images/box_model.gif)
(출처 - www.cssterm.com)

- Content : 내부의 내용을 말합니다. 텍스트 요소만 올수 있습니다.
- Padding : 컨덴츠와 보더사이의 간격입니다. 배경의 영향을 받습니다.
- border : 컨덴츠와 패딩을 포함한 영역의 내곽선입니다. 가로값의 영향을 받습니다.
- Margin : 보더와 외부 엘리먼트의 간격입니다. 배경의 영향을 받지않습니다.
- outline : 컨덴츠와 패딩 및 보더를 포함한 포함한 외곽선입니다. 가로값의 영향을 받지 않습니다.


Inline Box Model

anonymous Box Model(가상의 박스모델)




