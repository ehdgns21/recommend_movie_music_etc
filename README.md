# 영화추천  

무비렌즈 : 협업 필터링 > 아이템 기반  

https://lsjsj92.tistory.com/568
  
  

논문 : 멘토기반의 영화추천 시스템  


    
주피터 : 단축키  
https://kkokkilkon.tistory.com/151    


현재문제점  
from sklearn.decomposition import TruncatedSVD

SVD = TruncatedSVD(n_components=12)
matrix = SVD.fit_transform(movie_user_rating)
matrix.shape
  
  
