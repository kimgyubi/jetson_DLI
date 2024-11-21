# jetson_DLI
https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write
https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2-KR&unit=block-v1:DLI+S-RX-02+V2-KR+type@vertical+block@aba5104413ae454c8c63a6f301925337

1. jetpack : Download the Jetson Nano Developer Kit SD Card Image
  -
3. sd memory card formatter, balena etcher로 sd카드 굽기
  - 
1. 한글 설치
2. 웹캠 사용하는 방법

3. deeplearning (nvidia 영상 시청)
   
1. 독코 설치? 컨테이너 박스 와 같은 존재.
2. 스왑... jetson은 4기가 -> 주피터 못 연다. 가상 공간. / 설치안하면 동영상이 아닌 사진으로밖에 보지 못한다. 
3. 주소 들어가면 주피터 노트북 classification
   > interactive
   > camera : usb/csi
   > !ls- ltrh/dev/video : video 0
   
5. 아이파이 위젯. by구글 버튼 구현 방법
   
7. jetson을 내 노트북에 연동? termius SSH

8. 프로젝트
   - 더스트 센서
   - 검은색: 마이너스
   - 암수점퍼선
   - 하프 브레드보드
     ![image](https://github.com/user-attachments/assets/6fe21930-fc17-447b-ba11-083dfa41cd6a)
     파란선, 빨간선을 따라서 옆으로 전류가 흐른다. 뒷면 철판을 보면 알 수 있다.
     파란선: 마이너스, 빨간선: 플러스
     J에 점퍼선 연결 -> 그러면 나머지에서 원하는 볼트로 전류가 흐른다. 
   - 아두이노 uno rev3 
     ![image](https://github.com/user-attachments/assets/312fe35c-3f5d-4aad-81c1-b8e335905463)
      어댑터에 파란선으로 잿슨에 연결해 파워를 가져다 쓸 수 있다.
      아나로그 핀 0~5 : LCD 연결 SDA SCL 통신을 주고 받는다. 0,1 serial 통신.
     ~PWM핀 : 서브모터를 돌릴때 사용
     GND : 마이너스 그라운드
     5v 3.3v
     
   - 잿슨나노의 보드는? 암으로 되어있다....
  
   - sd카드에 다운받을것? 
