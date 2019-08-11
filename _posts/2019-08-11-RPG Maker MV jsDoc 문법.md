---
layout:     post
title:      RPG MAKER MV jsDoc 문법정리
subtitle:   의외로 간단합니다.
date:       2019-08-11
author:     한빛가람
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - RPG Maker MV
    - MV Plugin
    - MV jsDoc
---

# jsDoc이 하는 것
* RPG MV Plugin 설정에서 파라미터를 받아오고, 설정을 추가하는 등의 행위를 함
* 플러그인 설정에 기본 값을 삽입할 수 있음
* 플러그인 설정에 필수 값을 지정할 수 있음
* 자바스크립트 문법에 구애받지 않음
* 다국어 설명을 작성할 수 있음

# jsDoc 기본 문법
* `/*:`(으)로 시작해서 `*/`(으)로 끝남
* Doc 시작시 `/*:ko` 형식으로 언어명을 뒤에 작성하면 한국어 전용 Doc 생성 가능

# jsDoc 예시문법
```js
// 다국어 전용 설명 - 영어로 작성하길 추천합니다.
/*:
 * NOTE: My Plugin hahahaha
 */

// 한국어 전용 설명
/*:ko
 * NOTE: 내 플러그인이다 으하하하하
 */
```

***

# jsDoc 문법
<details>
<summary>NOTE</summary>

| 속성이름 | 필수유무 |
|:--------:|:--------:|
| NOTE | 무 |


**설명**

NOTE는 개발자에게 간단한 정보를 제공하기 위해 사용하는 RPG Maker MV 에디터 상에서는 안보이는 설명구문입니다.

별도의 행위를 하지 않으며 그저 일종의 주석 역할을 합니다.

**시용방법**

```js
/*:
 * NOTE: Note note note argo note
 */
/*:ko
 * NOTE: 노트노트노트 아르고 노트
 */
```

</details>