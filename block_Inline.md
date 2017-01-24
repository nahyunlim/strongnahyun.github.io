# Block , Inline, Inline-Block 이란?


css에서 요소의 종류를 선택하는  display속성으로 원래 inline인 요소
(ex. `<span>`,`<a>`)를 block요소처럼 보이게 하거나 원래 block인 요소
(ex. `<div>`,`<p>`)를 inline요소처럼 보이게 할 수 있음

## block , inline, inline-block 의 차이 비교

| 속성                   | 설명                                 | 줄 바꿈                                  | 너비(width),높이(height) 지정 | margin 여백 지정           |
| -------------------- | ---------------------------------- | ------------------------------------- | ----------------------- | ---------------------- |
| display:inline       | 요소를 inline요소처럼 표시                  | X , 일렬로 배치                            | 불가능                     | 좌우 여백만 적용(상하여백 적용되지않음) |
| display:block        | 요소를 block요소처럼 표시                   | O, 자동 줄 바꿈(앞뒤로 줄 바꿈)                  | 가능, defult : width100%  | 가능                     |
| display:inline-block | 요소는 inline 속성으로, 내부는 block 속성으로 표시 | X, 일렬로 배치(즉, block이 inline처럼 옆으로 늘어섬) | 가능                      | 가능                     |




#div와 span 비교#

| div        | span                    |
| ---------- | ----------------------- |
| block속성    | inline속성                |
| 가로폭을 전부 차지 | 태그 안의 내용 만큼만 너비, 높이를 차지 |


















