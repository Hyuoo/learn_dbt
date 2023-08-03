# BigQuery_ServiceAccount

1. IAM에서 서비스 어카운트 생성   
   ![menu](../images/2.bq/iam_service_account_menu.png)
2. 필요 권한
   - BigQuery 작업 사용자 (roles/bigquery.jobUser)
   - BigQuery 데이터 뷰어 (roles/bigquery.dataViewer)
   ![permi](../images/2.bq/iam_service_account_permission.png)
3. 키 생성 (JSON)   
   -> {project}-388303-54e554e9738f.json 대충 이런 키 생성

![key](../images/2.bq/iam_service_account_key.png)
