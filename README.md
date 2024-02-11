# basic_python

- This is to project as we learn to python's project
- 이 프로젝트는 python 입문을 위한 프로젝트 입니다.

<br/>

## 사용 목적

- 백엔드 개발을 목적으로 합니다.
- 혹은 통계 프로그램, 빅데이터 등 라이브러리가 방대하여 Python을 많이 애용합니다.
- Django, Fast API, Tensionflow, PyTorch 등 사용이 가능합니다.

## 프로젝트 진행 계기

- 필자는 웹 개발자이지만, 향후 웹 개발 뿐만 아니라 통계 프로그램을 내보는 것을 시도 해보기 위해 제작하였습니다.
- 이 프로젝트는 컴퓨터학과 전공자 및 국비지원 수료 이후 Python으로 전환하고자 하는 용도로 작성하였습니다.
- Python으로 기본 테스트를 진행하며, Fast API와 기타 라이브러리 등 활용하는 방법을 습득하고자 합니다.

<br/>


## FAST API 설치 진행 시

### window 환경에서 python 최초 설치 후, 진행 방법

- 현재, uvicorn은 설치가 불가능 하며, fastapi만 설치하고 아래와 같이 실행합ㄴ디ㅏ.

```
pip install fastapi
python -m uvicorn main:app --reload
```

### 그 이외

- window를 제외한 나머지는 아래와 같이 실행이 가능합니다.

```
pip install fastapi
pip install uvicorn
uvicorn main:app --reload
```
