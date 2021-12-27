# toastmessage
플러터 Toast Message 사용

## 실행 화면
![image](https://user-images.githubusercontent.com/77111523/147487010-347c26e3-54f4-4209-b531-580899afb36f.png)

## 설명
사용법
- 우선 기본적으로 Toast Message는 fluttertoast라는 라이브러리를 import한 후에 사용이 가능함.
- 그러니까 pubspec.yaml의 dependencies: 에다가 추가하고 pub get 한 후에 main.dart에 import해서 사용하시길

유의사항
- 버튼을 만들고 그 버튼의 `onPressed()` 메서드 안에 새로 만든 `flutterToast()` 함수를 넣어주면 됨
- `flutterToast()` 함수는 MyPage 위젯 밖에서 정의해주어야 함
