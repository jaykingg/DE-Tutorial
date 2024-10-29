### Python 설치
> https://www.python.org/downloads/

### Alias (Iterm2) 
> zshconfig -> alias python="python3" 추가
 
### Intellj Python 설정
> PlugIn -> Python 설치
> SDK -> Python 설정

### 패키지 관리자 설치
~~~
python -m pip install --upgrade pip
~~~
### 가상 환경설정
프로젝트로 이동 후
~~~
python -m venv venv
pip3 install -r requirements.txt
~~~
### 필수 패키지 설치
~~~
pip3 install numpy pandas matplotlib scikit-learn
~~~

### 문제 발생 시 추가 설정
~~~
xcode-select --install
python3 -m pip config set global.break-system-packages true
~~~
