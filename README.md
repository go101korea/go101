
<b>[Go 101](https://go101.org)</b>은 Go 프로그래밍 서적 시리즈입니다.
지금까지 공개된 책들은 아래와 같습니다:

* [Go (Fundamentals) 101](https://go101.org/article/101.html): Go 구문/의미(맞춤 제네릭 관련 제외) 및 모든 종류의 런타임 관련 항목에 중점을 둡니다.
* [Go Generics 101](https://go101.org/generics/101.html): Go 제네릭에 대해 자세히 다룹니다.
* [Go Optimizations 101](https://go101.org/optimizations/101.html): 코드 성능 최적화 트릭, 팁 및 제안을 제공합니다.
* [Go Details & Tips 101](https://go101.org/details-and-tips/101.html): 다수의 깊이 있는 정보와 Go 프로그래밍에 대한 팁들을 제공합니다.

이 책들은 초보자 혹은 숙련된 Go 언어를 사용하는 개발자들이 Go에 대한 깊고 철처한 이해를
얻기 위한 도움이 되는 것을 목표로 합니다.

공식 트위터 계정인 [@go100and1](https://twitter.com/go100and1)을 팔로우하시고
[Go 101 슬랙](https://go-101.slack.com)에 참여하시면 Go 101 서적의 최신 소식들을
좀 더 빠르게 만나볼 수 있습니다!

### 설치, 업데이트, 로컬에서 읽기

Go 1.16 버전 이상을 사용 중이라면 이 저장소를 로컬에 복제할 필요는 없습니다:

```shell
### 설치 혹은 업데이트

$ go install go101.org/go101@latest

### 읽기 (GOBIN path, defaulted as GOPATH/bin, should be set in PATH)

$ go101
Server started:
   http://localhost:55555 (non-cached version)
   http://127.0.0.1:55555 (cached version)
```

Go 1.15 이하 버전을 사용 중이라면 약간의 수정이 필요합니다 (기여를 하려고 하는 등의 경우):

```shell
### 설치

$ git clone https://github.com/go101/go101.git

### 업데이트: `README.md` 파일이 있는 Go 101 프로젝트의 기본 디렉터리로 이동한 후에 실행하세요.

$ git pull

### 읽기: 업데이트와 마찬가지로 Go 101 프로젝트의 기본 디렉터리로 이동한 후에 실행하세요.

$ go run .
Server started:
   http://localhost:55555 (non-cached version)
   http://127.0.0.1:55555 (cached version)
```

시작 페이지가 웹 브라우저에서 자동으로 열립니다.
열리지 않으면 웹 브라우저를 통해 http://localhost:55555 로 접근해보세요.

옵션:
```
-port=1234
-theme=light # or dark (default is auto)
```

일부 HTML 파일은 해당 마크다운 파일에서 생성됩니다.
마크다운 파일이 수정되었다면 `go run . -gen`을 실행해서 해당 HTML 파일을 동기화할 수 있습니다.

### 기여하기

다음과 같은 Go 101의 개선은 언제든지 환영합니다:
* 오타, 문법 오류, 단어 부정확성, 설명 결함, 코드 버그 및 끊어진 링크와 같은 모든 종류의 실수에 대한 수정 사항 제출
* Go와 관련된 재미있는 콘텐츠 제출

기여자들은 [이곳](https://go101.org/article/acknowledgements.html)에서 확인할 수 있습니다.

번역 작업도 환영합니다. 아래와 같은 진행 중인 번역 프로젝트들이 있습니다:

* [中文版](https://github.com/golang101/golang101)
* [한국어](https://github.com/go101korea/go101)

### 라이선스

자세한 내용은 [LICENSE](LICENSE) 파일을 확인해주세요.
