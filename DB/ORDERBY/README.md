# ORDER BY

데이터 조회 시 정렬을 설정할 수 있다.

## 기본 오름차순 정렬

```sql
SELECT * FROM test ORDER BY id (ASC 생략);
```

## 내림차순 정렬

```sql
SELECT * FROM test ORDER BY id DESC;
```

## 두개의 정렬 만들기
id 값이 똑같은 경우 다른 컬럼으로 정렬하도록 하기
```sql
SELECT * FROM test ORDER BY id, name;
```

오름차순 정렬은 `ASC`를 생략할 수 있고, 여러 정렬을 설정 할 수 있다.