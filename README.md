# Django_React_starterkit

##Overview
Django-React-starterkit은 webpack을 활용하여 Django와 react 간의 연동을 하는 간단한 starterkit입니다.   
webpack 라이브러리를 통해 react와 연동하였으며, react-hot-loader를 통해 브라우저에 소스실시간 코드 반영이 가능합니다.

상세한 설명은 아래의 블로그에서 참고하시기 바랍니다.    
[장고(Django)와 리액트(React) 연동 with webpack](http://www.codegym.xyz/janggo-django-wa-riaegteu-react-yeondonghagi-with-webpack/)

## Getting Started
requirements :
* Python 3.5.1
*  virtualenv (optional)
*  npm
 
git clone:
```
git clone https://github.com/manducku/Django_React_starterkit.git
```

### frontend webApp 설치하기
```
npm install 
```

###backend webApp 설치하기
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py makemigrations && python manage.py migrate
```

###Django 서버 실행하기 
```
python manage.py runserver
```

###webpack dev 서버 실행하기
```
node server.js
```

