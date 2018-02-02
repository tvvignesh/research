## Jasper

### Outline

Reporting utility

### Underlying technology

Java

### Reference Links

https://community.jaspersoft.com/documentation

https://itblackbelt.wordpress.com/2008/02/29/generating-huge-reports-in-jasperreports/

https://docs.tibco.com/pub/js-jrs/6.2.4/doc/pdf/JasperReports-Server-REST-API-Reference.pdf

https://www.ibm.com/developerworks/websphere/library/techarticles/0505_olivieri/0505_olivieri-pdf.pdf

http://thinkinginsoftware.blogspot.in/2011/06/ireport-dynamically-hide-show-columns.html

https://www.tutorialspoint.com/jasper_reports

Sample jrxml - https://www.tutorialspoint.com/jasper_reports/jasper_report_designs.htm

passing jrxml as reportunit - https://community.jaspersoft.com/documentation/tibco-jasperreports-server-rest-api-reference/v630/resource-descriptors

Execute reportunit - https://community.jaspersoft.com/documentation/jasperreports-server-web-services-guide/v56/running-report-asynchronously

Launch Report - https://community.jaspersoft.com/documentation/jasperreports-server-web-services-guide/v56/requesting-report-output

### Samples

https://sourceforge.net/p/jasperreports/code/ci/jr-6-5-0/tree/jasperreports/demo/samples/

### Videos

https://www.youtube.com/watch?v=21UbluQDQK8

### Pros

1. Ability to define custom reports via JRXML

2. Ability to do everything via REST APIs

3. Ability to specify multiple data sources and ability to use JDBC and relevant driver connections to get data.

### Cons

1. Too slow for large datasets with large number of rows and columns 
(Generating CSV via Jasper for a recordset took 17 minutes whereas it took 1.5 minutes through NodeJS code for the same dataset)

### Licence

JasperReports library is LGPL.

Jaspersoft Studio is EPL.

JasperReports Server is GPL.