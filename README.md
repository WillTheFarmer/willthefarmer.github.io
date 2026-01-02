Current purpose of this repository is to promote `apache-logs-to-mysql` repository and in development `mysql-to-apache-echarts` 
repository on search engines by implementing Search Engine Optimization (SEO). 

`HTTPlogs2MySQL` repository had barely been found in [GitHub search](https://github.com/search) regardless of 
Topics added to Repository.

No search engines were listing the `HTTPlogs2MySQL` repository regardless of the Keywords used.

Poor search results possibly due to one or both of the following:

- Repository name - Renamed from ApacheLogs2MySQL to apache-logs-to-mysql on 1/9/2025.
- Repository name - Renamed HTTPlogs2MySQL - http-logs-to-mysql on 1/1/2026.


or 

- SQL - A large majority of repository codebase is SQL language.

GitHub does not recognize SQL as a language and requires adding code to `.gitattributes` for SQL to appear on repository. 
```
*.sql linguist-detectable=true
*.sql linguist-language=sql
```
## Apache Log Parser and Data Normalization Application
[HTTPlogs2MySQL](https://github.com/willthefarmer/http-logs-to-mysql) consists of two Python Modules & one Database Schema that parse and import 
Access & Error log files and normalizes data into database designed for reports & data analysis.

Application automates consolidation of log files from multiple Servers and unlimited Domains with audit trail & error logging.
### Python handles File Processing & MySQL or MariaDB handles Data Processing
<p align="center">
  <img width="250" height="250" src="/assets/Apache_Python_MySQL.png">
</p>

## Apache Log Management and Visualization Application
[MySQL2ApacheECharts](https://github.com/willthefarmer/mysql-to-apache-echarts) is a Web interface that consists of Express.js web application 
frameworks with Drill Down Capability & Apache ECharts frameworks for Log Data Visualization in charts, reports & data analysis 
interfaces of Database Schema created by [HTTPlogs2MySQL](https://github.com/willthefarmer/http-logs-to-mysql).

### Express handles Data Querying & ECharts handles Data Visualization of MySQL or MariaDB Schema
<p align="center">
  <img width="250" height="250" src="/assets/MySQL_Node_Express_Apache_Echarts.png">
</p>
Hopefully repository rename and creating this repository, website and images improves `http-logs-to-mysql` repository visibility 
and `mysql-to-apache-echarts` repository awareness. All feedback welcomed!