
- **database-credentials.md**  
```markdown
# Supabase Read-Only Connection

## Environment Variables

You can export these in your shell or in n8n Credentials:

- SUPABASE_DB_HOST=<your-ref>.db.supabase.co  
- SUPABASE_DB_PORT=5432  
- SUPABASE_DB_NAME=your_db  
- SUPABASE_DB_USER=read_only_user  
- SUPABASE_DB_PASSWORD=My$uperRead0nlyPwd  
- SUPABASE_DB_SCHEMA=public  

## Full Connection String

postgres://read_only_user:My$uperRead0nlyPwd@<your-ref>.db.supabase.co:5432/your_db

## Usage

Pass the above into your n8n Supabase node (or any Postgres client).  
This user has only SELECT permissions and cannot INSERT, UPDATE, or DELETE.

