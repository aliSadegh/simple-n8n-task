# N8N Postgres Credential

We choose Supabase Postgres as database because we can simply connect to that without any VPN.
## Add Postgres Credential

You can add new postgres credential for connect to database:

- Host: `aws-0-eu-north-1.pooler.supabase.com`
- Database: `postgres`
- User: `read_only_user.rdnvsuoxbvvxleoeoxax`
- Password: `My$uperRead0nlyPwd`
- SSL: `Disable`
- Post: `5432`

## Add Postgres node 
In N8N add `postgres` node and choose Operation `select` on table `processed_posts`
