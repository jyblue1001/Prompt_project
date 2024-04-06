
파일 실행시키시려면

1. 본인의 로컬 환경에 있는 파일 중, 이 리포지토리를 받을 곳을 지정하신 다음 pull하고,
2. 본인의 로컬 환경(저는 VS code로 합니다)에서 run code하고, "Debugger is active" 문구가 터미널에 뜨는 것까지 확인한 다음
3. 본인의 컴퓨터에 크롬창 키고, "localhost:3000" 를 입력하시면 실행화면이 보일 겁니다.

p.s. 
코드 자체에 문제가 많아 제대로 실행되진 않을 겁니다.

또한 app.py line 9,11에 있는 구문을 실행하기 위해선 "my_model.h5" 파일이 필요한데, 그 크기가 200메가가 넘어서 깃허브에 못 올렸습니다. 
"my_model.h5" 파일을 다운 받으려면 "everyone2_lenet5_tensorflowmodel.ipynb" 을 본인 pc에서 한번 실행한 다음,

아래 사진을 참고해서 다운 받으시고, app.py가 존재하는 경로에 추가해주셔야 됩니다.

![image](https://github.com/jyblue1001/prompt_project_real/assets/113050588/c17c853b-4b70-425f-9632-a41cbc14fbea)
