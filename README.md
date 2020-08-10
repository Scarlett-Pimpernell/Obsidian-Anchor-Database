# Obsidian
Intelligent Enterprise Architecture - Human Interaction Interface, Search Engine, and Artificial Intelligence Agent.

I will not be releasing any more code until the moral and ethical state of the world has improved.

Current Development Focus Is On the Core Search Engine Algorithm. I haven't thoroughly tested the queries yet, so be aware that there may be minor bugs. Also, I am now well advanced in coding v01.04, which includes the ability to understand relationships within the text of a given document. Unfortunately, once again, may have to wait a while for this one, as I need to upgrade my hardware in order to continue... also dealing with an extremely complex technique which will most probably take a few weeks to get right at current rates of development.

The latest upload includes a technique for fragment purposym matching within the search engine algorithm. Run the appropriate queries on your SQL Server 2017/2019 database, using either SSMS or Visual Studio 2017/2019. Set-up steps include: 1.Execute the synonym_thesaurus_integration query and the purposym_thesaurus_integration query (once you have sourced a representative set of important enterprise Text files and/or Microsoft Word documents); 2.Finally execute the text_search_algorithm query. The results should display in the appropriate panel. If you're feeling brave, consider integrating these steps into your existing or new product/service/experience, but bare in mind that there will be incremental changes going forward.

Over the coming weeks and months, I will gradually add to the back-end, API gateway, and front-end code, with the aim of producing an open-source high-performance (effective and efficient), feautre-rich library of configure and integrate code, in order for companies of any size to optimally plan, transform, and run their organisation via a robust enterprise architecture digital twin paradigm.

I won't be dealing with parameter binding, indexes, or query execution plans until much later in development, when I build the UI. 

Upon further reflection, I believe that the SQL injection and Powershell injection vulnerabilities which exist whenever you use dynamic SQL in a query, have not been suitably fixed. There is still the possibility to exploit even after removing the key clauses. The hacker who has public access to the code could simply insert whetever SQL or Powershell they wanted into the filenames that are extracted and used in the query. I think Micrsoft may have to do something about this vulnerability, like disabling/replacing any T-SQL or Powershell syntax in all dynamic variables before it is processed and turned into a string prior to execution.
