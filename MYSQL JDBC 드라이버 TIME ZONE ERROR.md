## MySQL JDBC 드라이버 Time Zone 에러


#### ‘?serverTimezone=UTC’ 추가


- ERROR : The server time zone value 'KST' is unrecognized or represents

- Reasons : My SQL 5.1X 이후 버전 부터 KST 타임존 인식하지 못하는 이슈

- SOL : JDBC url parameter에 add
