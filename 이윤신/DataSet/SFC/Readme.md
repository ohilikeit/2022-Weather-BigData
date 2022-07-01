# AWS

+ **(sfc_a)** 
  + DB_SFC_EV_DD
  + 시각(TMA), 지점번호(STN_ID), 합계 소형 증발량(SUM_SML_EV), 합계 대형 증발량(SUM_LRG_EV)
<br/>

+ **(sfc_b)** 
  + DB_SFC_FOG_DD
  + 시각(TMA), 지점번호(STN_ID), 합계 안개 계속시간(SUM_FOG_DUR)
<br/>

+ **(sfc_c)**	   
  + DB_SFC_CLOUD_DD	
  + 시각(TMA), 지점번호(STN_ID), 평균 중하층운량(AVG_LMAC), 평균 전운량(AVG_TCA), 최저 운고(MIN_CH), 최다 운량(MAX_CA)
<br/>

+ **(sfc_d)**		
  + DB_SFC_RHM_DD	
  + 시각(TMA), 지점번호(STN_ID), 평균 상대습도(AVG_RHM), 최소 상대습도(MIN_RHM)
<br/>

+ **(sfc_e)**
  + DB_SFC_TD_DD	
  + 시각(TMA), 지점번호(STN_ID), 평균 이슬점온도(AVG_TD), 최고 이슬점온도(MAX_TD), 최저 이슬점온도(MIN_TD)
<br/>

+ **(gisang_zizum)**
  + DB_COMN_KMA_STN		
  + 지점번호(STN_ID), 지점 한글 명(STN_KOR_NM)
<br/>


## Detail
+ **(sfc_*_area)**
	+ aws_* 와 gisang_zizum 을(를) 지점번호(STN_ID) 기준으로 병합한 데이터
