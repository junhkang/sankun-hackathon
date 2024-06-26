### 해커톤 과제 설명:
#### 배경:

웹상에서 긴 URL은 공유와 관리에 불편함을 줄 뿐만 아니라, 암호화가 되었더라도 사용자 정보 노출의 위험을 가지고 있습니다. "산업의 역군"은 사용자 경험 향상 및 보안 강화를 목표로, 웹 서비스 내에서 간편하게 사용할 수 있는 "URL 축소" 기능을 도입하려고 합니다. 이 도구는 긴 URL을 짧고 관리하기 쉬운 형태로 변환하여, 사용자가 웹 주소를 쉽게 공유하고 관리할 수 있게 해줍니다. 이번 해커톤에서는 간단하면서도 효율적인 URL 축소기 함수를 개발하여, 사용자가 더 나은 웹 경험을 할 수 있도록 지원하는 것을 목표로 합니다.

#### 목표:

사용자가 입력한 긴 URL을 짧게 축소하여 반환하는 함수를 개발합니다. 이 함수는 기존의 긴 URL을 인자로 받으며 축소된 URL을 리턴합니다. 리턴된 짧은 URL을 통해 사용자는 원본 URL의 자원에 안전하게 접근할 수 있어야 하며, 원본 URL의 무결성이 유지되어야 합니다. 구현 자체는 간단할 수 있지만, 기존의 알려진 방식들 대비 효율적이고 창의적인 알고리즘을 포함한 기능을 개발하는 것이 목표입니다.

#### 기간:

- 2024/03/28 ~ 2024/04/05

#### 기본 요구 사항:

- **함수명:** `shortenURL`
- **입력 파라미터:**
    - `longUrl` (string): 사용자가 축소하고자 하는 긴 URL.
- **출력:** `shortUrl` (string): 축소된 형태의 URL.

#### 기술 요구 사항:

- 긴 URL을 입력 받아 내부 로직을 통해 짧은 URL을 생성.
- 생성된 짧은 URL은 원본 긴 URL접근이 가능해야 함.
- `<hash function>` 또는 기타 방법을 사용하여 고유한 짧은 URL 생성.

#### 과제 예시:

- **입력된 긴 URL:** "https://www.sankun.com/pages/very-long-url-parameter?with-longer-query-parameter"
- **출력된 짧은 URL:** "https://short.url/abcd123"