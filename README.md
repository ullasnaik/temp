`DROP USER 'root'@'localhost';`
`CREATE USER 'root'@'%' IDENTIFIED BY 'Root@123';`
`GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' WITH GRANT OPTION;`
`FLUSH PRIVILEGES;`
then login mysql without sudo.....
`mysql -u root -p`
