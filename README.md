# swagger

Springfox Swagger2 와 Springfox Swagger UI 를 사용해도 되지만 요즘은 Springfox Boot Starter 사용
run시 에러가 발생할 경우 application.properties 에  spring.mvc.pathmatch.matching-strategy=ant_path_matcher 를 default 값으로 추가해준다.

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled. 에러 발생시
--> run -> Edit Configurations -> modify options 클릭 -> enable debug output 체크표시
