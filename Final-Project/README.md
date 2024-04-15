# FASTCAMPUS_EXPORT2
패스트캠퍼스 데이터분석 Export 2기 과정에서 수행한 과제들을 정리하였습니다. 

## Final Project : 패스트캠퍼스 데이터 분석 
### 목적
```
· 패스트캠퍼스의 Customer, User, Order, Course, Refund 데이터를 통해 2022년도 현황을 분석
· 각각의 데이터에서 확인할 수 있는 추세를 확인하여 향후 사업에 도움이 될 수 있는 인사이트를 도출
```

### EDA
```
1. 2022년 1월 중 총매출액이 가장 높았던 날은 3일 / 7일 / 5일이며, 가장 낮았던 날은 1일 / 22일 / 29일입니다.
   가장 높은 3일과 가장 낮은 1일의 총매출액 및 주문 수는 약 9배 차이가 있습니다. 
2. 강의 키워드에서 가장 많이 등장한 단어는 '평생소장'입니다.
3. 환불이 가장 적게 된 강의의 환불 횟수는 1회이며, 가장 많이 된 강의는 'THE RED : '로 670회 환불되었습니다.
4. 강의를 가장 많이 신청한 고객은 ID 793571 이며, 338회 신청하였습니다. 총 금액은 8,650,000원입니다.
   가장 적게 신청한 기록은 1회 20,000원의 강의를 신청한 고객들입니다. 
5. 요일별 강의 신청횟수는 월요일이 가장 많고 토요일이 가장 적었습니다. 신청이 많았던 순서대로 월-일-수-금-목-화-토요일입니다.
6. 시간대별 회원가입 수를 계산하였을 때, 오전 7시가 가장 많고 오후 8시가 가장 적었습니다.
   오전 11시 ~ 오후 1시 사이에 증가하였다가 오후 8시까지 급감하는 양상을 보입니다.
   오전 7시 ~ 9시에 감소하는 이유는 출근시간의 영향이 있기 때문으로 추측됩니다. 
7. 시간대별 회원가입 수를 월별로 살펴보았을 때, 5월 오전 7시에 두드러지게 회원가입수가 증가한 모습을 보였습니다. 
8. 강의 신청을 완료한 유저는 약 63%이며 취소한 유저는 21%입니다. 
9. 휴면 회원은 ID 생성 후 마지막 로그인까지 평균 154.11일이 소요되었습니다. 
```
📊 [상세 내용 확인](https://github.com/HANISY/FASTCAMPUS_EXPORT2/blob/main/EXPORT2_FINAL_PROJECT.ipynb](https://github.com/HANISY/FastCampus-EXPORT-Data-Analysis/blob/main/Final-Project/Final_Project.ipynb)

</br>

### 분석 결과

<p>
<img src="https://github.com/HANISY/FASTCAMPUS_EXPORT2/blob/main/img/result_1.png?raw=true" width="800">
<img src="https://github.com/HANISY/FASTCAMPUS_EXPORT2/blob/main/img/result_2.png?raw=true" width="800">
</p>



### 분석 보완 방향
```
· 'list_price - discount_price ≠ sale_price' 인 데이터 처리 방안이 필요함 (전체 데이터의 약 26.59% 차지)
· 강의 금액의 94.1%가 50,000원 미만으로 해당 데이터를 분석하여 활용할 방안 모색
```
