# Cloud_AWS_ARRS

 # Cloud-AccountReceivableReportSystem
  ``` 
Getting data from different states in USA (Account receivable data as files)
   Domain : Accounts(Receivable Information)
```

# Source: Flat Files/CSV Files/CSV


# Target : Storage into Amazon RedShift


# Technologies Stacks:

    SOURCE Storage : S3 (Source)
    Job orchestration/Scheduler tools : Airflow
    Processing Engine : EMR (Spark 2.4.2)
    Target Storage: S3 (Partition by PROCESSING_DATE)
    FINAL TARGET STORAGE/REPORTING : AMAZON REDSHIFT
    REPORT SYSTEM : TABLEUE
    AIRFLOW ==> IN DEV CREATE EC2 SERVER.
     IAM Rules ==> S3FULLACCESSRULES

``` NOTE: CREATE ELASTIC IP ```


COST:
        DEV :
            EMR (3 NODES USE ONLY) 
        QA :
            EMR(7-9 NODES CLUSTER ONLY)	
        UAT & PROD:
            Not yet update from Team.
