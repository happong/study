# 배운 개념 정리 (레벨별)

## Lv.1 print()
- `print()`로 문자열/숫자 출력
- 여러 줄 `print()`는 위에서부터 순차 실행됨 (자동으로 합쳐지지 않음)

## Lv.2 변수
- 변수 선언과 할당 (`x = 값`)

## Lv.3 자료형
- 문자열(str), 정수(int), 실수(float), 불리언(bool)

## Lv.4 input()
- `input()`으로 사용자 입력 받기 (기본적으로 문자열로 반환됨)

## Lv.5 if
- `if` / `elif` / `else`, 조건문 끝에는 콜론(`:`) 필수

## Lv.6 for
- `for` 반복문, `range()` 사용
- `print()`는 기본적으로 각 호출마다 자동 줄바꿈됨

## Lv.7 while
- `while` 반복문, 경계값 처리 (`<` vs `<=`)

## Lv.8 함수
- `def`로 함수 정의, 매개변수/인자
- `return`(값을 함수 밖으로 반환) vs `print()`(화면에 출력만 함) 구분

## Lv.9 리스트
- 인덱스로 요소 접근 (`list[i]`)
- `append()`로 요소 추가
- `len()`으로 길이 구하기
- `range(len(list))` 패턴으로 인덱스 순회
- 최댓값/최솟값 찾을 때 시작값 설정 주의

## Lv.10 딕셔너리 (도입: 2026-08-10, 진급 보류 중)
- 기본 키 접근: `dict[key]`
- 키 추가/수정: `dict[key] = value`
- `.items()`로 키-값 쌍 순회: `for key, value in dict.items():`
- `"key" in dict`로 키 존재 여부 확인
- `[]`(딕셔너리/리스트 접근) vs `()`(함수 호출) 구분
- `return True/False`(불리언) vs `return "True"/"False"`(문자열) 구분

→ 아직 100% 정답 세트를 받지 못해 Lv.11(튜플)로 진급하지 않음. 자주 틀리는 패턴은 `mistakes/wrong-patterns.md` 참고.
