# apks_to_csv
가지고 있는 데이터 셋에 대한 중복 제거 및 없어진 파일들에 대한 갱신해주는 파이썬 스크립트

# crosscheck.py
  virus_total을 토대로 family 교차 검증 진행용
  VT라는 컬럼이 새로 생성되며, sha256으로 검증 진행

# malcsv.py
  악성 앱들에 대한 csv 파일 정리
  hash값들(md5, sha1, sha256) + family
  대신 패밀리로 분류하는 조건이 내부 디렉토리에 따라 다르므로 주의 필요
# norcsv.py
  정상 앱들에 대한 csv 파일 정리
  hash값들(md5, sha1, sha256)
