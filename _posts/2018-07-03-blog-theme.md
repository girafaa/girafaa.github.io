---
layout: post
title:  "깃허브 블로그 테마 적용하기"
date:   2018-07-03 15:31:00 +0900
categories: 블로그만들기
---

### 깃허브 테마 적용하기

공유할 저장소(사용자이름.github.io)에 공개되어 있는  jekyll 테마를 적용시켜봐요.

대표적으로 많이 사용하는 minimal-mistakes 테마로 변경해봅시다. 



[minimal-mistakes깃허브 저장소로 이동](https://github.com/mmistakes/minimal-mistakes)

위의 저장소로 이동해서 이 사람이 공유한 테마를 가져오겠습니다. 쉬운 방법은 테마를 가져와서 내 저장소의 이름을 공유할 블로그 저장소 이름으로 변경하는 것입니다.(다른 방법은 필요한 파일들만 내 저장소로 가져오는 방식입니다.)

![fork](https://user-images.githubusercontent.com/33653318/42202392-33a36fc0-7ed6-11e8-9ca4-1be4f6c4b996.PNG)


이후, 저장소의 상단메뉴중 setting에서 사용자이름.github.io로 변경해주면 됩니다.

단, 이 테마들이 블로그에만 사용되는 것이 아니기에 그냥 복사해서는 사용할 수 없는 경우도 있습니다. 아래의 설명서를 보면 .github라는 폴더는 필요없다는 등등 손봐야할 것이 조금 있습니다.

[minimal-mistakes 설명서](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

저같은 경우에는 우왕좌왕하면서 블로그 테마를 변경했습니다. 제가 이미 만들어놓은 블로그저장소의 .git폴더를 가져와 해당 저장소에 넣고 설명서에서 제거하라는 폴더 및 파일을 없앴습니다. 그리고, 게시물을 넣을 _posts폴더를 생성해 게시물을 옮겨넣었습니다.

테마에 첫페이지의 블로그 제목이나 알림말 같은 것은 _config.yml파일에서 설정할 수 있습니다. 아직 블로그 화면 구성도 잡히지 않고 메뉴도 없는데요, 계속해서 수정해가며 블로그 모양을 잡아보겠습니다.
