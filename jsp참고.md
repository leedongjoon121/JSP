# JSP 개발 참고

### 현재 경로 찾기
```swift

 표현식
 ${pageContext.request.contextPath}
 
 jsp스크립트
 <%=request.getContextPath()  %>

 예시
 $('#fn').attr('action','${pageContext.request.contextPath}/ad/menu/indexMenu.do').submit();

```

## Jquery

### .prop()
.prop()는 지정한 선택자를 가진 첫번째 요소의 속성값을 가져오거나 속성값을 추가한다. 주의할 점은 HTML 입장에서의 속성(attribute)이 아닌 JavaScript 입장에서의 속성(property)

```swift
.prop( propertyName )
속성값을 가져옴

.prop( propertyName, value )
속성값을 추가
```
