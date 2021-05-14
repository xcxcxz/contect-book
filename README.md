1. DB연결은 앱이 실행되면 단 한번만 일어나느 이벤트 : db.once 사용  
error는 다양한 경우에 발생할 수 있기 때문에 : db.on 사용  
2. body-parser : POST request data의 body에서 parameter를 편리하게 추출  
3. 모델.create는 DB에 data를 생성하는 함수.  
4. method override패키지 - query로 method 값을 받아서 req의 HTTP method를 바꿔주는 역할을 함  
5. 모델.findOne함수 : DB에서 해당 모델의 document를 하나 찾는 함수  
6. 모델.findOneAndUpdate : DB에서 해당 모델의 document를 하나 찾고 그 data를 수정하는 함수.  
7. 모델.deleteOne : DB에서 해당 모델의 document를 하나 찾아서 삭제하는 함수.  