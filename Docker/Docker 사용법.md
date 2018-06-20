## Docker 사용법

1. 컨테이너 실행
    <pre><code>docker run -i -t mlearn:init /bin/bash</code></pre>
    
2. 컨테이너에서 일시적으로 나오기
    <pre><code>CTRL + P, Q</code></pre>

3. 실행 중인 컨테이너 프로세스 확인하기
    <pre><code>docker ps</code></pre>

4. 실행 중인 컨테이너로 돌아가기
    <pre><code>docker attach 컨테이너ID</code></pre>

5. 폴더를 마운트해서 실행
    <pre><code>docker run -i -t -v /c/Work/Pycharm/PythonMachineLearning:/sample mlearn:init /bin/bash</code></pre>
    
