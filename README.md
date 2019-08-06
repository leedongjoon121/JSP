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


