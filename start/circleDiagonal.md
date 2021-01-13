# SCENE 만들기
MFPlayer 의 연출은 시나리오와 SCENE 으로 구성되어 있습니다.
이미지를 흐르게 하는 예제를 통해 시나리오와 SCENE 의 기본 구성 방식을 소개하겠습니다.

## 이미지 흐름 연출
아이콘 형태의 이미지가 설정된 방향으로 흐르는 연출입니다.
예시에서는 원 아이콘이 대각선으로 움직이는 연출을 작성하겠습니다.

<img src="./img/icon/circleDiagonal.jpg" width="1000"/>

## 시나리오 추가
MFPlayer 는 시나리오 단위로 연출을 재생합니다.
새로운 연출 작성은 새로운 시나리오를 만드는 것으로 시작합니다.
편집창의 홈 화면에서 `시나리오 추가` 버튼을 클릭합니다.

<img src="./img/icon/addScenario.jpg" style="border: 1px solid"/>

## SCENE 추가 
시나리오는 SCENE 들의 모음으로 구성되어 있습니다.
SCENE 은 MFPlayer 연출의 가장 최소 단위로, 시나리오는 최소 하나 이상의 SCENE 으로 구성됩니다.

`새로운 SCENE 추가` 버튼을 눌러 새로운 SCENE을 추가합니다.

<img src="./img/icon/addNewScene.jpg" style="border: 1px solid"/>

## SCENE 설정
SCENE 설정 화면은 아래와 같습니다.
순서에 맞게 SCENE 연출 설정을 하고 `미리보기`로 설정 내역을 확인합니다.
설정이 완료되면, `저장` 버튼을 눌러 시나리오에 새로운 SCENE 을 추가합니다.  

### 연출 타입 선택
MFPlayer 의 기본 연출 타입을 선택합니다.
**영상 파일**, **이미지 흐름**, **색상 흐름** 의 연출 타입이 있습니다.
아이콘을 설정하기 위해서 `이미지 흐름`을 선택합니다.

<img src="./img/icon/setScene.jpg" style="border: 1px solid"/>

### SCENE 미리보기
SCENE 편집 완료 후 `미리보기` 버튼을 누르면 재생 화면이 나타나 편집 결과를 확인할 수 있고,
`미리보기 정지` 버튼으로 재생 화면을 닫을수 있습니다.

원하는 형태의 연출이 될때까지 **편집-미리보기** 를 통해 반복적으로 빠른 **수정-확인** 작업이 가능합니다.

<img src="./img/icon/previewScene.jpg" style="border: 1px solid"/>

## SCENE 저장
`저장` 버튼을 누르면 설정된 SCENE 저장되고 시나리오에 추가됩니다.

<img src="./img/icon/saveScene.jpg" style="border: 1px solid"/>

시나리오에 SCENE이 추가된 것을 확인할 수 있습니다.

<img src="./img/icon/scenarioScenes.jpg" style="border: 1px solid"/>

## 시나리오 저장
`저장` 버튼을 눌러 시나리오를 저장합니다.

<img src="./img/icon/saveScenario.jpg" style="border: 1px solid"/>

시나리오 목록에 시나리오가 추가된 것을 확인할 수 있습니다.

<img src="./img/icon/scenarioList.jpg" style="border: 1px solid"/>

## 재생
`단독 재생` 버튼을 눌러 편집 내용을 확인합니다.
원 대각선 흐름이 5 초간 재생되고 시나리오 내 SCENE이 1개이므로 같은 SCENE이 계속 반복됩니다.

<img src="./img/icon/playScenario.jpg" style="border: 1px solid"/>

제어창에서 `정지` 버튼을 눌러 다시 편집창으로 돌아갑니다.

<img src="./img/scenario/stopScenario.jpg" style="border: 1px solid"/>

원 대각선 흐름 SCENE 작성이 **완료**되었습니다.  

MFPlayer 는 시나리오-SCENE 편집을 통해 연출을 작성합니다.
이어서 시나리오에 새로운 SCENE 을 더하는 방법을 설명하겠습니다.
