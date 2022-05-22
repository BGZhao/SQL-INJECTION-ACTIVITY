## Questions for Activity (iam-2-sql-injection-demo)

### 1.-Given what you already know about SQL, can you spot our vulnerability?

The log-in is keeping memory of the user ID for other people to see

### 2.-What happened?

I try the unknown or '1'='1 but it just said an error occurred

### 3—Taking your best guess, what do you think happened?

It looks like the username gets a new password every time you enter a new one: username: Chihiro
password: 123456
query: SELECT title FROM user where username = 'Chihiro' and password = '123456'
username: Chihiro
password: 789456
query: SELECT title FROM user where username = 'Chihiro' and password = '789456'




