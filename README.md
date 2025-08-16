# aws-rds-mysql-backup-restore
Backing up database from on-premises and restoring into rds 

Structure:

mysql-rds-migration/
 ├── README.md
 ├── backup/
 │    ├── mysqldump_command.sh      # script to take backup
 │    ├── upload_to_s3.sh           # script to upload to S3
 ├── restore/
 │    ├── restore_to_rds         # script to restore from EC2 to RDS
 ├── docs/
 │    ├── architecture-diagram.png  # diagram of process
 │    ├── steps.md                  # detailed step-by-step
