## Project
- 이미지 파일에 특수 효과 추가


## Data 
- input : img 파일

## Folder  
```
├── dist
│ └── main
│   └──_internal
│   └── main.exe
├── main.py
└── pyproject.toml
└── README.md
```

## Execution
main.exe 실행

## Environment
- Anaconda Prompt

## Code
0. 가상환경이 없는 경우 다음 명령어로 가상환경 만들기

```
conda create --name <환경 이름> python=3.9
```

1. 가상환경 활성화 및 필요한 라이브러리 설치
```
conda activate <환경 이름>
pip install pyproject.toml
```
(만약 다음과 같은 오류 코드가 출력되었다면 필요한 라이브러리를 직접 설치)
```
pip install <라이브러리 이름>
```
⬇️ e.g.
```
ModuleNotFoundError: No module named 'PyQt5.QtWidgets'
--> pip install PyQt5
ModuleNotFoundError: No module named 'cv2'
--> pip install opencv-python
```


2. 코드 실행
```
python main.py
```
=======
# repository01
>>>>>>> 339e5d7644e26ef7b42dcd7883581e5693f00236
