# Django Blog

## Django로 만든 웹 블로그입니다.
주로 글을 쓸 수 있는 공간이며 로그인도 가능합니다.
sqlite와 PostgreSQL을 사용했으며,
Pythonanywhere 에 배포했으며 Heroku에 배포하려고 하는 중 입니다.

첫 화면 입니다. 허용된 사용자만 글을 쓸 수 있습니다. 자물쇠 그림을 누르면 로그인 화면으로 넘어갑니다.
![20210813_235215_1](https://user-images.githubusercontent.com/20348923/129480378-30f0a501-e890-44b2-83fe-f2a2846cf6d5.png)

로그인 화면에서 허용된 Username과 Password로 로그인 할 수 있습니다.
![20210813_235215_2](https://user-images.githubusercontent.com/20348923/129480379-9aa2fd9b-bf75-4c79-be3d-d455b65caf1f.png)

로그인이 성공하면 "Hello 이름"이라는 문장이 로그아웃 기능과 함께 publish, write 기능이 가능하게 됩니다.
![20210813_235215_3](https://user-images.githubusercontent.com/20348923/129480380-3ea3d370-3cd1-4a2b-a7a7-926fcc0d6a65.png)

write기능을 누르면 Title칸과 Text칸에 글을 쓸 수 있으며 Save버튼으로 publish 페이지에 등록할 수 있습니다.
![20210813_235215_4](https://user-images.githubusercontent.com/20348923/129480381-b8f37bce-119f-434a-9c4e-93dd485e3101.png)

이는 publish 페이지인데, publish 버튼을 누르면 글이 메인 페이지에 올라가고 연필 버튼 혹은 x버튼을 누르면, 각각 재작성이나 글 삭제가 가능합니다. 아래에 Add comment로 댓글을 작성할 수 있습니다.
![20210813_235215_5](https://user-images.githubusercontent.com/20348923/129480383-8336be08-767d-467d-8b3c-40e780856eef.png)

Add comment를 누르겠습니다.
![20210813_235215_6](https://user-images.githubusercontent.com/20348923/129480384-452f9576-0596-44a5-8d94-957bcc6ddf51.png)

New comment페이지에서는 Author과 Text 칸에 원하는 작성자 이름과 글을 쓰고 Send 버튼으로 댓글을 올릴 수 있습니다.
![20210813_235215_7](https://user-images.githubusercontent.com/20348923/129480385-8e002d5c-a18a-409e-8916-db7881db5489.png)

댓글 또한 삭제 혹은 등록을 할 수 있습니다. 등록을 눌러보았습니다.
![20210813_235215_8](https://user-images.githubusercontent.com/20348923/129480386-19fa1bee-5d37-4f50-825e-0b0c28fc17b0.png)

그러면 댓글 작성자와 내용이 연결된 글에 올라갑니다.
![20210813_235215_9](https://user-images.githubusercontent.com/20348923/129480388-0f9fb86d-3fe1-41f5-8c4c-2c35c50c4889.png)

댓글 Comments에 1로 댓글이 추가된 것을 볼 수 있으며, 글의 제목을 누르면 허가된 사용자는 글을 수정하거나 삭제하는 기능을 할 수 있습니다.
![20210813_235215_10](https://user-images.githubusercontent.com/20348923/129480389-eb8d282f-15c0-4b92-a66b-862b41095dc9.png)

Log out을 눌러 로그아웃이 가능합니다.
![20210813_235215_11](https://user-images.githubusercontent.com/20348923/129480391-cb707dda-d5d8-4aa0-8775-763b208e8499.png)

로그아웃시 메인화면으로 돌아갑니다. 새로운 글이 작성된 것을 볼 수 있습니다.
![20210813_235215_12](https://user-images.githubusercontent.com/20348923/129480393-b9701b56-50e9-417a-be41-e7bd1da5395e.png)