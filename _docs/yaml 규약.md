YAML은 "YAML Ain’t Markup Language"의 약자로, **사람이 읽기 쉬운 데이터 직렬화 포맷**입니다. 주로 설정 파일(`.yml` 또는 `.yaml`)에서 사용되며, JSON보다 간결하고 들여쓰기를 통해 계층 구조를 표현합니다.

---

## ✅ YAML 기본 형식과 작성 규칙

### 1. **기본 문법**

```yaml
key: value
```

* `key`는 문자열이고 `value`는 문자열, 숫자, 불리언, 리스트, 맵 등 다양하게 올 수 있음
* 콜론(`:`) 뒤에 **공백**이 반드시 있어야 함 (`key:value` ❌)

---

### 2. **들여쓰기**

* **스페이스(Space)** 2칸 또는 4칸을 사용 (Tab은 금지 ❌)
* 들여쓰기는 **계층 구조**를 의미함

```yaml
person:
  name: Alice
  age: 30
```

---

### 3. **리스트**

```yaml
fruits:
  - apple
  - banana
  - cherry
```

---

### 4. **중첩된 딕셔너리**

```yaml
database:
  host: localhost
  port: 3306
  credentials:
    username: root
    password: secret
```

---

### 5. **주석**

* `#` 기호로 주석 작성

```yaml
# 이것은 주석입니다
name: Bob  # 이름 필드
```

---

### 6. **문자열 처리**

```yaml
plain: hello         # 일반 문자열
quote_single: 'hi'   # 작은따옴표 사용
quote_double: "hi!"  # 큰따옴표 사용
multiline: |
  여러 줄
  텍스트입니다.
folded: >
  줄바꿈은 공백으로
  바뀝니다.
```

---

### 7. **불리언, 숫자, null**

```yaml
is_active: true
score: 95.7
nothing: null  # 또는 ~
```

---

## ⛔ 자주 발생하는 오류

| 유형       | 예시                 | 설명                            |
| -------- | ------------------ | ----------------------------- |
| 잘못된 들여쓰기 | `key:\n value`     | key와 value 간 띄어쓰기 없거나 들여쓰기 오류 |
| 탭 사용     | `\tkey: value`     | 스페이스 대신 Tab 사용 ❌              |
| 중복 키     | `name: A\nname: B` | 같은 레벨에서 동일 키가 2개 이상 ❌         |

---

필요하면 실제 Jekyll이나 GitHub Actions 같은 YAML 예제도 보여드릴 수 있어요.
