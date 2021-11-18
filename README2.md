'''consol
root@DESKTOP-JM4UFFA:~/SW-Platform/apps/big_drawing/draw_chart# bash this_run.sh

1.CSV파일이 저장된 디렉토리 경로를 입력해 주세요. ( EX. CSV ) :
./
./../../../data_files/result_files/EV/2021_09/KONAEV_KST_1368

2.CSV파일 date, time 데이터의 field명을 입력해 주세요. ( Ex. Date_new ) :
Date_new

3-1.평행좌표로 그릴 field명을 입력해 주세요. 2개 이상일 경우 공란없이 붙여서 | 로 구분하세요 (Ex. A|B):
VCU_Accel-Percent|BMS_BattBarTemp-C|BMS_HVPackCurrent-A

3-2.평행좌표에서 GROUP BY 기준이 되는 컬럼을 입력해 주세요. (3번에서 입력한 필드 중 하나여야 함):
BMS_BattBarTemp-C

4.라인 차트로 추출할 필드명을 입력해 주세요. 2개 이상일 경우 공란없이 붙여서 | 로 구분하세요 (Ex. A|B):
VCU_Accel-Percent|BMS_BattBarTemp-C|BMS_SOC-Percent|BMS_HVPackCurrent-A

>>====================================================
실행 관련 주요 정보(this_run.sh)
csv dir path  : ./../../../data_files/result_files/EV/2021_09/KONAEV_KST_1368
time field name  : Date_new
fields of parallelcoordinates: VCU_Accel-Percent|BMS_BattBarTemp-C|BMS_HVPackCurrent-A
standard of parallel coordinates: BMS_BattBarTemp-C
fields of line chart : VCU_Accel-Percent|BMS_BattBarTemp-C|BMS_SOC-Percent|BMS_HVPackCurrent-A
====================================================<<

1. CSV to DataFrame

■ 탐색 파일 개수:  6642
※ CSV를 데이터프레임으로 변환 중 입니다...
Progress |██████████████████████████████████████████████████| 100.0% Complete

----------------------------------------------------------------------------

2. Draw a Parallel Coordinates

■ 평행 좌표 데이터 저장 완료
■ 평행 좌표 PNG 저장 완료

----------------------------------------------------------------------------

3. Draw a Line Chart

※ __timestamp 생성 중입니다...
Progress |██████████████████████████████████████████████████| 100.0% Complete

■ 라인 차트 데이터 저장 완료
■ 라인 차트 PNG 저장 완료

----------------------------------------------------------------------------

프래그램이 종료 되었습니다...
''''
