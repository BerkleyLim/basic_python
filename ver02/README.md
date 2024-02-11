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
