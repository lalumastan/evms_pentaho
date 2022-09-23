
# Step by Step Guide to Create Employee Vaccination Report using Open Source Pentaho Report Designer

### Workflow
![Alt text](wf.png)
<details>
<summary></summary>

```mermaid
graph LR
A((Download<br/>Pentaho<br/>Report Designer)) -->
C[Configure Pentaho<br/>Report Designer] --> F{Open Pentaho Report Designer<br/>Load And Run<br/>Employee Vaccine Report<br/>'employee-vaccination-report.prpt'}
B((Download<br/>MySQL<br/>Connector/J)) --> C
D((Checkout<br/>'evms_pentaho'<br/>code from Git))  --> 
E[Import<br/>'employee_vaccine.csv'<br/>to 'evms'<br/>MySQL Database]  --> 
F
F -- export --> pdf
F -- export --> csv
F -- export --> excel
F -- export --> text
F -- export --> rtf
F -- export --> html

```
</details>

### References
<ul>
 <li><a href="https://jdk.java.net/17/">Open JDK 17</a></li>
 <li><a href="https://sourceforge.net/projects/pentaho/files/Pentaho-9.3/client-tools/prd-ce-9.3.0.0-428.zip/download">Open Source Pentaho Report Designer (Free)</a></li>
 <li><a href="https://mvnrepository.com/artifact/mysql/mysql-connector-java/8.0.30">MySQL J Connector</a></li>
 <li><a href="https://evmsall.herokuapp.com">Fully Functional Employee Vaccination Management System</a></li>
</ul>

### Tutorial
<a href="http://www.youtube.com/watch?feature=player_embedded&v=LzUwuxK0JD8" target="_blank"><img src="http://img.youtube.com/vi/LzUwuxK0JD8/0.jpg" alt="Step by Step Guide to Create Employee Vaccination Report using Open Source Pentaho Report Designer" width="240" height="180" border="10" /></a>

