# Description
- face detection of son heung-min with yolo v5
- Train with Custom datasets
# Results
- 꽤 좋은 detection 성능을 보였지만, 가끔 다른 선수를 손흥민으로 인식한다.
- validation set의 detection 성능이 100 epoch 부터는 상승하지 않은 것으로 보아 데이터셋의 부족이 원인으로 보인다.
1. validation set의 loss (100epoch 부터는 성능 향상이 거의 없다.)
<img width="708" alt="스크린샷 2020-11-17 오후 4 53 21" src="https://user-images.githubusercontent.com/53213397/99361771-f7894880-28f5-11eb-9369-e521071c1926.png">
2. detection sample 1
<img width="842" alt="스크린샷 2020-11-17 오후 3 48 38" src="https://user-images.githubusercontent.com/53213397/99360530-11c22700-28f4-11eb-9a08-8ce468b2b813.png">
3. detection sample 2
<img width="560" alt="스크린샷 2020-11-12 오전 10 38 17" src="https://user-images.githubusercontent.com/53213397/99360539-14bd1780-28f4-11eb-8b65-45517bc2fe6f.png">
4. detection sample 3
<img width="691" alt="스크린샷 2020-11-12 오전 10 25 31" src="https://user-images.githubusercontent.com/53213397/99360550-1981cb80-28f4-11eb-83b6-9c04a69a67c5.png">

