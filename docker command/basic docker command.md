## Docker Command Basic
```shell
$ docker {{command(상위/하위)}} {{option}} {{target}} {{args}}
$ docker container run -d redis
```
#### command
상위 커맨드는 container, image와 같은 대상의 종류가 들어가며, '무엇을', '어떻게' 할 것인지 지정한다.
예를 들면 컨테이너를 실행하고 싶을 때는 container run을 사용하면 된다.
#### option
옵션은 커맨드에 세세한 설정을 지정하는 용도로 사용된다.
#### target
커맨드와 옵션을 통해 실행할 이미지를 실행할 때 사용된다.
#### args
대상에 전달할 값을 지정한다.
