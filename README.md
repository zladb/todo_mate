# TODO MATE

## 📝 프로젝트 소개

이 프로젝트는 HTML/CSS/JavaScript로 TODO MATE라는 일정관리 서비스를 클론한 프로젝트입니다. 
라이브러리 없이 순수 JavaScript로 구현한 뒤, React 라이브러리를 추가하여 코드를 리팩토링하는 중입니다.
-

<br/>

## 🫡 try TODO MATE
- link: https://zladb.github.io  

<br/>

## ⭐ 주요 기능

1. 달력 구현: 달력의 날짜마다 해결해야 하는 TODO의 갯수를 표시합니다.
2. TODO 추가: 'TODO 추가하기' 버튼을 눌러서 새로운 TODO를 추가합니다.
3. TODO 수정 및 삭제: TODO의 더보기 버튼을 누르면 모달 창이 뜨며, TODO를 수정 및 삭제할 수 있습니다.

<br/>

**✔️ 달력**  
- 달력의 각 날짜마다 하지 않은 TODO의 갯수가 표시됩니다.
- 모든 TODO를 모두 체크하면 달력에도 체크 표시가 뜹니다.
<img src="https://github.com/zladb/chatting_application/assets/68093782/792d3aab-f00c-45d2-867b-5643682d5933" width=30% />

<br/>
<br/>

**✔️ TODO 추가**
- 'TODO 추가하기' 버든을 누르면 새로운 TODO를 입력할 수 있는 칸이 생성됩니다.
- 원하는 TODO 목표를 적고 ENTER 키를 누릅니다.
<img src="https://github.com/zladb/chatting_application/assets/68093782/852a3c33-f164-45c7-a8ae-374aefef9d1e" width=30% />


<br/>
<br/>

**✔️ TODO 수정 및 삭제**
- TODO의 더보기 버튼을 누르면, TODO 수정 버튼과 삭제 버튼이 포함된 모달이 올라옵니다.
- 수정 버튼을 누르면 TODO를 수정할 수 있도록 INPUT이 생깁니다.
- 삭제 버튼을 누르면 TODO가 삭제됩니다.
<img src="https://github.com/zladb/chatting_application/assets/68093782/8edc8b9d-531f-4856-a5a0-33576d67dbb6" width=30% />

<br/>
<br/>

## 🔧 Stack

**Frontend(Web)**
- **Language** : HTML, CSS, JavaScript
- **Library & Framework** : React, Webpack, Babel, Styled-components
- **IDE** : VSCode
<br />

**Backend**
- **Database** : localStorage
- **Deploy**: github Action

<br/>

## 🐚 프로젝트 directory 구성

```
├─docs
│  ├─docs
│  ├─node_modules
│  │  └─bootstrap-icons
│  │      ├─font
│  │      │  └─fonts
│  │      └─icons
│  ├─public
│  ├─specifications
│  └─src
│      ├─assets
│      │  ├─fonts
│      │  └─images
│      ├─components
│      │  ├─calendar
│      │  └─todo
│      ├─contexts
│      ├─hooks
│      ├─pages
│      │  └─main_page
│      ├─styles
│      └─utils
├─.eslintrc.json
├─.prettierrc.js
├─babel.config.json
├─package.json
├─README.md
└─webpack.config.js

```

<br/>

## 🙋‍♂️ Developer

* **Yujin KIM** - 프로젝트 기획, 개발, 배포, 관리 - [zladb](https://github.com/zladb)

<br/>

## 👾 Source
**TodoMate** - [app-store]https://apps.apple.com/us/app/todo-mate/id1505220130


<br/>

## ✅ License

MIT License

Copyright (c) 2024 Yujin KIM

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

