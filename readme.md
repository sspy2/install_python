## pyenv 

**install **

```
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
```

**환경변수 설정 **

```comman
$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc
$ echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc
$ echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bashrc
$ source ~/.bashrc
```


 ### 환경변수 추가후 bashrc 실행 => 터미널 새로고침 



### Install python

```command
$ pyenv install 3.6.1 # pyenv를 통해서 python 3.6.1을 설치 
$ pyenv global 3.6.1 # 전역으로 버전 설정
$ python -V # 파이썬 버전 확인
$ pyenv versions # 사용가능한 파이썬 버전 리스트 출력
```



### Install packages

```command
$ pip install bs4 # beautiful soup
$ pip install requests
```





