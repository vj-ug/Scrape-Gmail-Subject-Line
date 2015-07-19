import maillib

f=open('subjectline.txt', 'w')
account=gmaillib.account('your-username', 'your-password')
emails = account.inbox(start=0, amount=5000)

for email in emails:
    if email.subject is not None:
        f.write(email.subject + '\n')
f.close()
