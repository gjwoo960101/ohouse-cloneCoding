# ohouse-cloneCoding
오늘의집 클론코딩


## css 정리
- flex
flex는 3개의 개별속성을 가진다.
flex-grow, flex-shrink, flex-basis

### flex-grow
- 기본값 0
- 남은 공간이 있을때 얼마나 늘어날지

### flex-shrink
- 기본값 1
- 공간이 부족할때 얼마나 줄어들지

### flex-basis
- 기본값 auto
- 사용한 요소의 기본크기
```
    0,0,(전체크기에서 5vw를 뺀 크기를 6으로 나눳을때 크기를 적용)
    flex: 0 0 calc((100% - 5vw) / 6);
```