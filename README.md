# java-calculator-precourse

## 기능 요구 사항
### 입력한 문자열에서 숫자를 추출하여 더하는 계산기를 구현한다.
- 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.
- 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다. 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

## 기능 목록

### 계산기 객체
- [X] 계산기는 숫자들을 가진다.
- [X] 숫자는 양수로 이루어져 있다.
- [X] 숫자의 합을 반환한다.
- [ ] 숫자가 정수로만 이루어져 있으면 정수값을 반환한다.

### 사용자 입력 파싱 객체
- [ ] 객체는 사용자의 입력을 구분자와 숫자 부분으로 나눈다.
- [ ] 커스텀 구분자가 입력 되었을 때 커스텀 구분자는 1자리 문자다.
- [ ] 숫자 문자열은 기본 구분자와 커스텀 구분자로 파싱이 가능하다.
- [ ] 파싱된 문자는 숫자여야 한다.