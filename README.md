camel-sendmail
==============
A random project to show camel capabilities. This project does following:

1) Scan a table using JDBC dataSource. 
2) Split records - one record per row
3) Transform record to Email String using mustache template
4) Send email using gmail transport.

To run this sample, use maven 

mvn camel:run
