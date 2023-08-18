SELECT * 
FROM users_emails
WHERE data_cadastro >= NOW() - INTERVAL 30 DAY;