# 원티드 프리온보딩 8차 과제 1

[![React Version](https://img.shields.io/badge/React-version-blue.svg)](https://ko.reactjs.org/)
[![Package Manager Version](https://img.shields.io/badge/npm-version-yellow)](https://www.npmjs.com/)

### 💡 과제 설명

팀 단위로 다시 한번 원티드 프리온보딩 선발과제를 진행 해보면서 동료학습을 경험하고 이를 바탕으로 Best Practice 를 도출해내는 과제를 수행했습니다

<br/>

### 📅 수행 기간

> 2022.12.20 - 2022.12.23

<br/>

## 목차

- [팀 정보](#팀정보)
- [요구 사항](#요구-사항)
- [Best Practice](#Best-Practice)
- [로컬 서버 구동 방법](#로컬-서버-구동-방법)
- [배포](#배포)
- [디렉토리 구조](#폴더-구조)

<br />

## 👨‍👨‍👧‍👧 팀정보

<table>
    <tr>
        <td align="center">
            <a href="https://github.com/hyejj19">
                <img src="https://avatars.githubusercontent.com/u/89173923?v=4" width="100px;" alt="박혜정"/>
                <br />
                <sub>
                    <b>박혜정</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/minsang98">
                <img src="https://avatars.githubusercontent.com/u/64800318?v=4" width="100px;" alt="김민상"/>
                <br />
                <sub>
                    <b>김민상</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/kwakhyun">
                <img src="https://avatars.githubusercontent.com/u/73919235?v=4" width="100px;" alt="곽현"/>
                <br />
                <sub>
                    <b>곽현</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/badmaniacs">
                <img src="https://avatars.githubusercontent.com/u/96967183?v=4" width="100px;" alt="박경태"/>
                <br />
                <sub>
                    <b>박경태</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/zkzk8953">
                <img src="https://avatars.githubusercontent.com/u/78520794?s=400&u=355629856caf2969fe39e5cc7f4a07f800e90f5d&v=4" width="100px;" alt="seoungheon lee"/>
                <br />
                <sub>
                    <b>이성헌</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/rewrite0w0">
                <img src="https://avatars.githubusercontent.com/u/55968557?v=4" width="100px;" alt="오태준"/>
                <br />
                <sub>
                    <b>오태준</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/bigwave-cho">
                <img src="https://avatars.githubusercontent.com/u/105909665?v=4" width="100px;" alt="조재현"/>
                <br />
                <sub>
                    <b>조재현</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td> 
        <td align="center">
            <a href="https://github.com/JeongTaekCho">
                <img src="https://avatars.githubusercontent.com/u/92679073?v=4" width="100px;" alt="조정택"/>
                <br />
                <sub>
                    <b>조정택</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td> 
        <td align="center">
            <a href="https://github.com/aydenote">
                <img src="https://avatars.githubusercontent.com/u/77476077?v=4" width="100px;" alt="최승수"/>
                <br />
                <sub>
                    <b>최승수</b>
                </sub>
            </a>
            <br />
            <a href="https://github.com/codesandbox/codesandbox-client/commits?author=bengummer" title="Code">💻</a>
        </td>                 
    </tr>
</table>
<br>

<br/>

## 🎈 요구 사항

### 1. 로그인 / 회원가입

- `/` 경로에 로그인 / 회원가입 기능을 개발해주세요

  - 페이지 안에 이메일 입력창, 비밀번호 입력창, 제출 버튼이 포함된 형태로 구성해주세요
  - 로그인, 회원가입을 별도의 경로로 분리해도 무방합니다.

#### Assignment1

- 이메일과 비밀번호의 유효성 검사기능을 구현해주세요
  - 이메일 조건: `@` 포함
  - 비밀번호 조건: 8자 이상
  - 입력된 이메일과 비밀번호가 위 조건을 만족할 때만 버튼이 활성화 되도록 해주세요
  - 보안 상 실제 사용하고 계신 이메일과 패스워드말고 테스트용 이메일, 패스워드 사용을 권장드립니다.

#### Assignment2

- 로그인 API를 호출하고, 올바른 응답을 받았을 때 `/todo` 경로로 이동해주세요
  - 로그인 API는 로그인이 성공했을 시 Response Body에 JWT를 포함해서 응답합니다.
  - 응답받은 JWT는 로컬 스토리지에 저장해주세요

#### Assignment3

- 로그인 여부에 따른 리다이렉트 처리를 구현해주세요
  - 로컬 스토리지에 토큰이 있는 상태로 `/` 페이지에 접속한다면 `/todo` 경로로 리다이렉트 시켜주세요
  - 로컬 스토리지에 토큰이 없는 상태로 `/todo`페이지에 접속한다면 `/` 경로로 리다이렉트 시켜주세요

---

### 2. 투두 리스트

#### Assignment4

- `/todo`경로에 접속하면 투두 리스트의 목록을 볼 수 있도록 해주세요
- 리스트 페이지에는 투두 리스트의 내용과 완료 여부가 표시되어야 합니다.
- 리스트 페이지에는 입력창과 추가 버튼이 있고, 추가 버튼을 누르면 입력창의 내용이 새로운 투두 리스트로 추가되도록 해주세요

#### Assignment5

- 투두 리스트의 수정, 삭제 기능을 구현해주세요
  - 투두 리스트의 개별 아이템 우측에 수정버튼이 존재하고 해당 버튼을 누르면 수정모드가 활성화되고 투두 리스트의 내용을 수정할 수 있도록 해주세요
  - 수정모드에서는 개별 아이템의 우측에 제출버튼과 취소버튼이 표시되며 해당 버튼을 통해서 수정 내용을 제출하거나 수정을 취소할 수 있도록 해주세요
  - 투두 리스트의 개별 아이템 우측에 삭제버튼이 존재하고 해당 버튼을 누르면 투두 리스트가 삭제되도록 해주세요

<br/>

## ⚽ Best Practice

Assignment1

```
코드
```

> 설명

Assignment2

```
코드
```

> 설명

Assignment3

```
코드
```

> 설명

Assignment4

```
코드
```

> 설명

Assignment5

```
코드
```

> 설명

<br/>

## ✨ 로컬 구동 방법

1. 레파지토리 클론
   ```sh
   git clone https://github.com/preOnboarding8-team1/todo-list.git
   ```
2. NPM packages 설치
   ```sh
   npm install
   ```
3. 실행
   ```sh
   npm start
   ```

<br/>

## 🧵 배포

설명 AWS
링크 https://fefeafea

<br>

## 📚 폴더 구조

```
⏱ 1차 과제

📂 src
┣ 📂 api
┣ 📂 components
┃ ┣ 📝Button.jsx
┃ ┣ 📝InputBox.jsx
┃ ┣ 📝TodoInput.jsx
┃ ┣ 📝TodoItem.jsx
┃ ┗ 📝TodoList.jsx
┣ 📂 hooks
┃ ┗ 📝useFetch.js
┣ 📂 pages
┃ ┣ 📝Login.jsx
┃ ┗ 📝Todo.jsx
┣ 📂 router
┃ ┗ 📝router.js
┗ 📂 utils
  ┗ 📝httpClient.js
```

</details>
