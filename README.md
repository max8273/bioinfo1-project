# bioinfo1-project
< 자유프로젝트 과제 >

선정한 과제

![image](https://user-images.githubusercontent.com/100824329/170662107-e181b52f-11ef-44ab-82eb-bf1f4f74f9d7.png)


Fig S2A 재현해보기 - error가 많이 나오는 부분의 unique sequence들의 각각 개수를 세서 genome browser로 표현하고, 점수 트랙을 같이 표시합니다.

아이디어 구상 및 계획

1. 사용할 데이터 선정 

9주차 실습 프로젝트 시작용 노트북 파일에 들어있는 가공된 ‘ Cho, J., Chang, H., Kwon, S. C., Kim, B., Kim, Y., Choe, J., ... & Kim, V. N. (2012). LIN28A is a suppressor of ER-associated translation in embryonic stem cells. Cell, 151(4), 765-777. ‘ 데이터를 사용

2. 논문 정독 및 Fig S2A 요소 파악

Mirlet7d locus와 the Mirlet7f-1 locus에 맟춰 정렬된 LIN28A CLIP 라이브러리의 시퀀스입니다. 이전에 알려진 LIN28A의 결합 부위인 Mirlet7d locus와 the Mirlet7f-1 locus의 말단 루프에 있는 CTCC 모티프는 빨간색 상자로 표시되어 있습니다. 각 고유 시퀀스는 왼쪽에 표시된 read 수와 함께 검은색 가로 막대로 표시됩니다. 일치하지 않는 시퀀스는 흰색 문자로 표시됩니다. 사이트 돌연변이율은 Shannon의 엔트로피를 사용하여 정량화되며 하단에 파란색 막대로 표시됩니다. Less frequent tags (<7 reads)는 가시성을 향상시키기 위해 생략됩니다.

3. Mirlet7d locus 위치 파악

(6/3)까지

4. bam filtering

(6/3)까지

5. Shannon entropy 산출

(6/3)까지

6. visualization

(6/3)까지

7. 미비된 사항 추가 및 응용
 Add Custom Tracks 시도

 발표 전(6/10)까지 진행 예정
