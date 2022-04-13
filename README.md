# login
- 최종 구현 화면

![image](https://user-images.githubusercontent.com/100753588/163206253-0527d4ab-caa0-4a90-bd20-f4efe66079a0.png)

## 부분별 상세
### 1. wrapper 부분
1) 새로 배운 부분 : 모든 요소에 margin을 주지 않고 큰 박스 안에 padding을 주는 방식으로 보다 쫀득하고 간편하게 만들 수 있다.

### 2. 로그인 부분

![image](https://user-images.githubusercontent.com/100753588/163206565-fdbcee9b-2350-45e7-84ba-dcb477af8b17.png)
1) 어려웠던 부분
  - 역시나 중앙정렬 ^^ 가로 중앙정렬은 이미지, 텍스트 이기 때문에 text-align: center로 쉽게 해결되었으나 세로 줄맞춤은 로고 이미지에 vertical-align: bottom 혹은 픽셀 값을 주어 해결했다.
2) 놓친 부분 : a 태그는 inline이기 때문에 width 값 주려면 display: block 혹은 inline-block 속성 주어야 한다.
3) 새로 배운 부분 : height 값을 주지 않고 width, padding 값만 주어 추후 수정에 쫀득하게 대응한다.


### 3. 가상 클래스 이미지 삽입

![image](https://user-images.githubusercontent.com/100753588/163209260-0ef59799-0f83-40eb-a805-f06d00af06b9.png)
1) 어려웠던 부분 : float
  - float를 사용하면 부모-자식, 형제 관계에서 서로를 인식하지 못하기 때문에 전체 wrapper에 가상클래스를 주어 형제들끼리 서로를 알아볼 수 있게 하였다.
  - 역시나 이미지와 텍스트 세로 중앙정렬 ^^ 세로 정렬하기 위해 vertical-align: bottom 혹은 픽셀 값을 주어 해결했다.
2) 새로 배운 부분
- width, height 값을 모두 줘야 한다... width만 줘도 되는줄 ^^
- ｜ 요 바를 텍스트 타이핑 하지 않고 넣는 법을 배웠다.


