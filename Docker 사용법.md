## Docker 사용법

1. 컨테이너 실행
    docker run -i -t mlearn:init /bin/bash

2. 컨테이너에서 일시적으로 나오기
    CTRL + P, Q

3. 실행 중인 컨테이너 프로세스 확인하기
    docker ps

4. 실행 중인 컨테이너로 돌아가기
    docker attach 컨테이너ID

5. 폴더를 마운트해서 실행
    docker run -i -t -v /c/Work/Pycharm/PythonMachineLearning:/sample mlearn:init /bin/bash
