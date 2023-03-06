# drf_todo

### Todo 전체 조회 API
![image](https://user-images.githubusercontent.com/110436172/223025502-112d5b55-b634-49e6-b02d-c8ab804be607.png)

### Todo 상세 조회 API
![image](https://user-images.githubusercontent.com/110436172/223025549-71e04747-efd5-4b0c-b674-ebfc3bc75c95.png)

### Todo 생성 API (Postman사용)
![image](https://user-images.githubusercontent.com/110436172/223025657-c3be8b31-b983-47a0-ae43-4cf7a36f1a1d.png)
(127.0.0.1:8000/todo에 post 요청)
![image](https://user-images.githubusercontent.com/110436172/223025739-45ceee2d-31b2-4827-849d-6201a954df81.png)
(다섯번째 목록이 생겼음을 확인)

### Todo 수정 API
![image](https://user-images.githubusercontent.com/110436172/223025942-750e2f8f-4c79-42fc-aacb-c258e23d5ecf.png)
(127.0.0.1:8000/todo/5/에 put 요청)
![image](https://user-images.githubusercontent.com/110436172/223025996-54b0aea6-32b7-4b09-ab71-720ceebc23e6.png)
(다섯번째 목록이 변경되었음을 확인)

### Todo 완료 API
![image](https://user-images.githubusercontent.com/110436172/223026196-f02965e3-6a14-4b10-af68-c768085eb8dc.png)
(127.0.0.1:8000/done/에 get 요청 : 완료된 목록 확인)
![image](https://user-images.githubusercontent.com/110436172/223026343-82c37648-9095-4772-8371-8ce6b883bb3a.png)
(127.0.0.1:8000/done/5/에 get 요청 : 다섯번째 목록이 완료된 목록으로 변경)
![image](https://user-images.githubusercontent.com/110436172/223026429-5465b95c-ed6b-4280-b6c8-fbfc158ae60f.png)
(127.0.0.1:8000/done/에 get 요청 : 완료된 목록 확인(완료된 목록에 다섯번째 목록이 추가된 것을 확인))
