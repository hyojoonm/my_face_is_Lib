
# 얼굴분석 API를 활용한 어린이용 책 추천 서비스 프로젝트 "내 얼굴은 도서관!"

## 메인 화면 

![image](https://user-images.githubusercontent.com/105473305/206640406-b6a9ee0f-b764-43c5-88cb-173ca755c6e5.png)

## 설명창 

![image](https://user-images.githubusercontent.com/105473305/206640552-66cca776-2a05-4349-800d-f295e159aeeb.png)

## 촬영 페이지

![image](https://user-images.githubusercontent.com/105473305/206640703-bd7fb11b-ba6b-488b-bcec-616755326210.png)

5초의 카운트 후에 카메라를 통해 사진이 촬영되고, 해당 사진은 S3서버에 업로드 됩니다.

## 결과창

![image](https://user-images.githubusercontent.com/105473305/206640793-f70e4472-82d7-4fe2-98fc-4714dd7f2e1a.png)

사진이 업로드 되면 Aws Lambda 트리거를 통해 Aws Rekognition Detect-face Api 를 거쳐서 나오는 결과값이 DB로 전송됩니다.
전송된 DB값을 페이지에 렌더링 합니다.

## 리뷰창

![image](https://user-images.githubusercontent.com/105473305/206641037-5546fec7-3fd6-434e-b63a-d14d64a7546d.png)

책에 대한 간단한 리뷰를 작성이 가능합니다.
