(출처: https://juyoung-1008.tistory.com/17?category=689425)

# 컬럼명 변경
`ALTER TABLE 테이블 CHANGE 기존컬럼 변경컬럼 컬럼타입;`

# 컬럼 순서 변경
`ALTER TABLE 테이블 MODIFY 순서변경컬럼 컬럼타입 AFTER 앞에오는컬럼;`

# 컬럼 타입 변경
`ALTER TABLE 테이블 MODIFY 컬럼명 변경할컬럼타입;`

# 컬럼 추가
`ALTER TABLE 테이블 추가할컬럼명 컬럼타입 DEFAULT 디폴트값`
`ALTER TABLE 테이블 ADD COLUMN 추가할컬럼명 컬럼타입 DEFAULT 디폴트값 컬럼위치;`

# 컬럼 삭제
`ALTER TABLE 테이블 DROP COLUMN 컬럼명;`
