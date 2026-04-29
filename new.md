//create db on local machine
"C:\Program Files\PostgreSQL\15\bin\psql.exe" -U postgres -h localhost -c "CREATE DATABASE bap_local;"
 
// import db on local machine
"C:\Program Files\PostgreSQL\18\bin\psql.exe" -U postgres -h localhost -d bap_local -f "C:\Users\Downloads\preprod-bap-backup-2026-04-29.sql"
 
Dear Team,
 
I have just help
Devulapalli Tapasvi for setup DB and follow above commands for setup production and pre-production DB
