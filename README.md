개인적으로 사용하는 의사코드 스타일.

```
if /condition/ do
	...
elif /condition/ do
	...
else do
	...
end

switch /flag/ do
	case /case/ do
		...
	end
	/default case code/
end

loop do
	...
end

while /code/ do
	...
	break
	continue
end

for /variable/ in /iteratable/ do
	/code/
end

try do
	...
catch /exception/ do
	...
finally
	...
end

function /function name/ (/var name/: /var type/, ...) -> /return type/ do
	...

	defer do
		...
	end

	return /return value/
end

class /class name/ extends /superclass/ do
	var /var name/ : /var type/ = /initial value/
	const /const name/ : /const type/ = /initial value/

	method /method name/ (...) -> ... do
		this./member name/ = ...
		...
	end
end
```

1. 기본 자료형과 클래스를 포함하여 모든 타입 이름은 PascalCase
1. 함수나 변수 이름은 snake_case
1. 상수 이름은 CONSTANT_CASE
1. <제네릭>
1. '문자'
1. "문자열"
1. $"{포매팅 문자열}"