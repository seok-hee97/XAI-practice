## 2. JAFFE 감정분석 데이터(Emotion)

![JAFFE example](http://www.kasrl.org/KA_004.jpg)

JAFFE 감정분석 데이터 중 놀람(SUP)에 대응하는 이미지 한 장.

### 2.1. 데이터 설명

JAFFE(The Japanese Femail Facial Expression) 데이터베이스는 일본인 여성(학생들)의 얼굴 사진과 감정을 정량적인 수치로 표시한 데이터베이스다.

### 2.2. 데이터 다운로드 방법

JAFFE 데이터베이스는 연구 목적으로만 자유롭게 사용될 수 있으며, 각 사용자들은 모두 라이센스에 동의해야 한다. 라이센스에 대한 동의는 [이 링크](http://www.kasrl.org/jaffedb_info.html)에서 하고 다운 받을 수 있다.

위 링크에서 라이센스 사용에 대한 동의를 한 이후 이미지를 다운 받고 "./Ch2.emotion/jaffe"라는 하위폴더에 이미지를 삽입한다.

### 2.3. 칼럼 설명

이미지에 대응하는 데이터 칼럼이 텍스트파일 형태로 저장되어 있다. 텍스트파일은 "./Ch2.emotion/jaffe/jaffe_labels.txt"에 저장되어 있다.

데이터의 첫 번째와 두 번째 행은 이미지에 대한 설명이다. 이후 행에 대하여 각 칼럼별로 의미하는 바는 다음과 같다.

1. id: 이미지 고유값
2. HAP: 행복
3. SAD: 슬픔
4. SUR: 놀람
5. ANG: 분노
6. DIS: 실망
7. FEA: 두려움
8. PIC: 이미지 이름

### 2.4. 기타

JAFFE 이미지 라이센스는 Michel J. Lyons 교수에게 있다. 이미지를 다운받은 사용자들의 이미지 사용에 대한 책임은 전적으로 이용자에게 있음을 고지한다.

Michael J. Lyons, Shigeru Akemastu, Miyuki Kamachi, Jiro Gyoba.
Coding Facial Expressions with Gabor Wavelets, 3rd IEEE International Conference on Automatic Face and Gesture Recognition, pp. 200-205 (1998).