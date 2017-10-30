## About study

<p align="justify">This web page presents a large-scale empirical study (based on 3,290 systems) to investigate whether and how thresholds vary among systems of different domains. We argue that the definition of appropriate thresholds needs to be tailored to each metric by the software domain. Therefore, we defend the idea of domain-specific thresholds, given that systems from different domains may have distinct characteristics and, it may impair the derived metric thresholds. As consequence, it can increase the number of false positive anomalies, for instance.</p> 


<p align="justify">This study relies on fifteen software domains composed of object-oriented Java systems. We apply to each system a set of eight well-known source code metrics. After applying the measurements, we derived 90% and 95% thresholds for each metric per domain, compared, and analyzed them in different ways. For instance, we compared the thresholds among domains and analyzed the effectiveness of code smell detection between domain-specific and generic thresholds; i.e., derived from heterogeneous systems from several domains. </p>

We available all data used in this study. To download spreadsheet about software domains, click in [link](https://github.com/saner2018/eds/blob/master/Oracle.xlsx). 

To download of the thresholds derivations in this study, click in [link](https://github.com/saner2018/eds/blob/master/Thresholds.xlsx). 


To download of the metrics of each  software domains used in this study, click in [link](https://github.com/saner2018/eds/blob/master/Metrics.rar)

Teste You can use the [editor on GitHub](https://github.com/saner2018/eds/edit/master/README.md) to maintain and preview the content for your website in Markdown files. [Teste](https://github.com/saner2018/eds/blob/master/Table%20V%20-%20Thresholds.xlsx)


## Research Questions

To conducted this study, we defined four research questions (RQs) as follows.

```markdown
RQ1. Do thresholds for the same metric vary among different software domains?

RQ2. Are there metrics with the same thresholds regardless of the software domain?

RQ3. Does the system size impact on the derived thresholds?

RQ4. Are domain-specific thresholds better than general thresholds for code smell detection?
```
## Selected Systems and Domains
<p align="justify">The following table presents and describes the fifteen domains explored in this study with the number of systems per domain (last column). We choose these domains for the following reasons. First, they are well-defined in terms of requirements and, therefore, we believe that their different requirements might reflect in varying thresholds among systems of each domain. Second, they encompass several types of systems, for instance, frameworks, libraries, and tools. Third , there is a significant number of systems in these domains publicly available in GitHub. Forth, most of these domains have been used in previous studies.</p>



|            Domain           	|                                                                      Description                                                                     	|  #  	|
|:---------------------------:	|:----------------------------------------------------------------------------------------------------------------------------------------------------:	|:---:	|
|       Accounting (Acc)      	| Systems that record and process accounting transactions, such as accounts payable and receivable, payroll, and trial balance.                        	| 318 	|
|        Business (Bus)       	| Systems that implement validation, calculation, and law regulations of business requirements, such as pricing, purchasing, and inventory management. 	| 383 	|
|     Communication (Com)     	| Systems that manage connections between server and clients, using protocols to share information.                                                    	| 298 	|
|      Development (Dev)      	| Software tools that support developers to implement projects in general.                                                                             	| 531 	|
|      Dictionaries (Dic)     	| Software tools used to translate a variety of languages.                                                                                             	| 130 	|
|       E-commerce (EC)       	| Systems in charge of supporting the transactions of products buying and selling, as well as providing services to consumers.                         	| 36  	|
|       Education (Edu)       	| Systems used by students to manage their study life and by managers to administrate their schools.                                                   	| 172 	|
|       Free Time  (FT)       	| Entertain systems or any software which provides information for joy, such as travel information.                                                    	| 28  	|
|         Games  (Gam)        	| Entertainment games that can be played alone or in colaboration.                                                                                     	| 453 	|
|        Health  (Hea)        	| Systems that offer health-related services to people in general.                                                                                     	| 282 	|
|          Home (Hom)         	| Systems that control basic many home devices and services.                                                                                           	| 164 	|
|      Localization (Loc)     	| Show local information normally based on GPS. Some of them display maps and location sensitive data for users.                                       	| 76  	|
|       Messaging (Mes)       	| Systems that allow the users to send messages from one client to another.                                                                            	| 66  	|
|       Restaurant (Res)      	| Systems that provide different services for both managers and users of food houses.                                                                  	| 333 	|
| Science & Engineering (ScE) 	| Systems designed to aid users in several fields of science and engineering, such as 3D visualization and data analysis.                              	| 22  	|
