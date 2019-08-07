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

### JSTL

#### 

```swift

fn:contains(string, sbustring)
=> string이 substring을 포함하면 return true 반환


fn:containsIgnoreCase(string, sbustring)
=> 대소문자 관계없이 string이 substring을 포함하면 return true 반환

 

fn:startsWith(string, prefix)
=> string이 prefix로 시작하면 return True


fn:endsWith(string, suffix)
=> string이 suffix로 끝나면 return True


fn:escapeXml(string)
=> string에 XML과 HTML에서 < >& ' " 문자들이 있으면, XML엔티티 코드로 바꿔준뒤 문자열 반환


fn:indexOf(string, sbustring)
=> string에서 substring이 처음으로 나타나는 인덱스 반환

fn:split(string, separator)
=> string내의 문자열 separetor에 따라 나누어서 배열로 구성해서 반환

fn:join(array, separator)
=> array요소들을 separator를 구분자로 하여 연결해서 반환

fn:length(item)
=> item이 배열이나 컬렉션이면 요소의 개수를 문자열이면 문자의 개수를 반환


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
