pg_ctl -D "C:\Program Files\PostgreSQL\18\data" -l "C:\Program Files\PostgreSQL\18\data\logfile" start
 
initdb.exe -U postgres -A password -E utf8 -W -D "C:\Program Files\PostgreSQL\18\data"
 
NEXT_PUBLIC_API_URL=http://localhost:3001
NEXT_PUBLIC_APP_NAME=MyApp
HCAPTCHA_SECRET=
NEXT_PUBLIC_HCAPTCHA_SITEKEY=
NEXT_PUBLIC_BACKEND_URL=http://localhost:3000
 
 
DATABASE_URL="postgresql://postgres:kavya@localhost:5432/bap_prod6"
JWT_SECRET="your-secret-key-change-in-production"
JWT_EXPIRATION="3600"
NODE_ENV="development"
PORT=3001
FRONTEND_URL=http://localhost:3000
 
