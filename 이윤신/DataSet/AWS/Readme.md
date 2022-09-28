# AWS

+ **(aws_a)** 
  + DB_AWS_CLOUD_DD 
  + 시각(TMA), 지점번호(STN_ID), 평균전윤량(AVG_TCA)
<br/>

+ **(aws_b)** 
  + DB_AWS_ICSR_SS_DD 
  + 시각(TMA), 지점번호(STN_ID), 합계일조시간(SUM_SS_HR), 일조율(SSRATE)
<br/>

+ **(aws_c)**	   
  + DB_AWS_PRSR_DD	
  + 시각(TMA), 지점번호(STN_ID), 평균 현지기압(AVG_PA), 최고 현지기압(MAX_PA), 최저 현지기압(MIN_PA)
<br/>

+ **(aws_d)**		
  + DB_AWS_RHM_DD
  + 시각(TMA), 지점번호(STN_ID), 평균 상대습도(AVG_RHM), 최소 상대습도(MIN_RHM)
<br/>

+ **(aws_e)**
  + DB_AWS_RN_DD		
  + 시각(TMA), 지점번호(STN_ID), 합계 강수량(SUM_RN), 합계 강수 계속시간(SUM_RN_DUR), 10분 최다 강수량(MI10_MAX_RN), 1시간 최다 강수량(HR1_MAX_RN), 6시간 최다 강수량(HR6_MAX_RN)
<br/>

+	**(aws_f)**
	+ DB_AWS_TE_DD	
	+ 시각(TMA), 지점번호(STN_ID), 평균 1_0M 지중온도(AVG_M1_0_TE), 최고 1_0M 지중온도(MAX_M1_0_TE), 최저 1_0M 지중온도(MIN_M1_0_TE), 평균 1_5M 지중온도(AVG_M1_5_TE), 최고 1_5M 지중온도(MAX_M1_5_TE), 최저 1_5M 지중온도(MIN_M1_5_TE), 평균 3_0M 지중온도(AVG_M3_0_TE), 최고 3_0M 지중온도(MAX_M3_0_TE), 최저 3_0M 지중온도(MIN_M3_0_TE)
<br/>

+	**(aws_g)**
	+ DB_AWS_WIND_DD
	+ 시각(TMA), 지점번호(STN_ID), 평균 풍속(AVG_WS), 합성 풍속(MIX_WS), 최대 풍속(MAX_WS) , 최다 풍향(MAX_WD), 합성 풍향(MIX_WD)
<br/>

+ **(aws_h)**
  +  DB_AWS_LWT_TG_DD
  + 시각(TMA), 지점번호(STN_ID), 평균 최저 초상온도(AVG_MIN_TG), 최저 초상온도(MIN_TG)
<br/>

+ **(aws_i)**
  + DB_AWS_TA_DD		
  + 시각(TMA), 지점번호(STN_ID), 평균 기온(AVG_TA), 최고 기온(MAX_TA), 최저 기온(MIN_TA),아침 최저 기온(MIN_MRNG_TA),낮 최고 기온(MAX_DYTM_TA),밤 최저 기온(MIN_NGHT_TA )
<br/>

+ **(AWS)**
  +  방재기상관측(AWS)지점
  + 지점번호, 지점명(한글)
<br/>

+ **(gisang_zizum)**
  + DB_COMN_KMA_STN		
  + 지점번호(STN_ID), 지점 한글 명(STN_KOR_NM)
<br/>


## Detail
+ **(aws_*_area_1)**
	+ aws_* 와 gisang_zizum 을(를) 지점번호(STN_ID) 기준으로 병합한 데이터

+ **(aws_*_area_2)**
	+ aws_* 와 AWS 를 지점번호(STN_ID) 기준으로 병합한 데이터
	
