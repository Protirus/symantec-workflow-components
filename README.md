# Symantec Workflow Components

[![Symantec](https://img.shields.io/badge/tag-symantec-yellow.svg)](https://www.symantec.com/)
[![Endpoint Management](https://img.shields.io/badge/tag-endpointmanagement-yellow.svg)](https://www.symantec.com/products/endpoint-management)
[![C#](https://img.shields.io/badge/language-csharp-green.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)

### Symantec [Connect](https://www.symantec.com/connect/) Articles

- [Connect Product Page](https://www.symantec.com/connect/product/workflow-solution-0)
- [Workflow Article](https://www.symantec.com/connect/articles/workflow)
  - A list of Workflow Articles which will get you started with the Solution.
- [Workflow Component Developer Guide](https://www.symantec.com/connect/articles/workflow-component-developer-guide)
  - If you wish to learn how to build your own Components follow the above guide.

---

For any enquiries about [Protirus](https://protirus.com/) and what we can offer, please contact info@protirus.com

---

Over the years working with Symantec Workflow we've created a number of Components to help build our solutions, below are some of them

- [Concat](#Concat)
- [DecryptConnectionString](#DecryptConnectionString)
- [DNSName](#DNSName)
- [ExtractNumberFromText](#ExtractNumberFromText)
- [IPAddress](#IPAddress)
- [HTMLCoding](#HTMLCoding) (HTML Coding - Encode / Decode)
- [NearestServer](#NearestServer)
- [NumberToTimeInWords](#NumberToTimeInWords)
- [PackageServer](#PackageServer)
- [RemoveWhitespace](#RemoveWhitespace)
- [ReverseBoolean](#ReverseBoolean)
- [SendEmailComponent](#SendEmailComponent)
- [SetTheory](#SetTheory)
- [SubnetMask](#SubnetMask)
- [URLCoding](#URLCoding) (URL Coding - Encode / Decode)
- [WorkflowConnections](#WorkflowConnections)
- [WorkflowPort](#WorkflowPort)
- [WorkflowServer](#WorkflowServer)
- [WorkflowSQLConnectionString](#WorkflowSQLConnectionString)

---

### Concat
> This component joins two Strings.

> `String a = 'Hello'` `String b = 'World'`, this will return `'Hello World'`, if `Add Space` is True.

---

### DecryptConnectionString

> Decrypt Connection String

> Get the ConnectionString from the web.config

Get the ConnectionString from the web.config instead of a Project/Profile Property or local.orm
https://www.symantec.com/connect/articles/servicedesk-75-track-assignments-process-type-actions
Track Assignments - Forms (Web)

---

### DNSName

> Get the DNS Name of the current machine

> https://www.symantec.com/connect/articles/how-get-dns-name-and-ip-address-remote-computer-using-workflow-solution

---

### ExtractNumberFromText
> `'Serial123'` => `'123'`

---

### IPAddress
> https://www.symantec.com/connect/articles/how-get-dns-name-and-ip-address-remote-computer-using-workflow-solution

---

### HTMLCoding

> HTML Coding - Encode / Decode

> `&lt;` => `<`

---

### NearestServer
> Get the nearest Server given the Computer's IP and the SMP - Package or Task

> http://localhost/Altiris/Deployment/Agent/GetNearestPackageServerInfo.aspx
>  ?xml=URLENCODED

---

### NumberToTimeInWords
> Convert a number in minutes or seconds to a Time in Words = `1658 =>` `'1 days, 3 hours, 38 minutes, 0 seconds'`

---

### PackageServer
> Use principles from http://localhost/Altiris/Deployment/Agent/GetNearestPackageServerInfo.aspx but in SQL

---

### RemoveWhitespace
> `'Hello, World!'` => `'Hello,World!'`

---

### ReverseBoolean
> `bool a = True` => `a = False`

---

### SendEmailComponent
> 

---

### SetTheory
> Custom component for using Set Theory Operations - `Union`, `Except` & `Intersect`.

> This can be used to compare the original list to the new list to see which items to add and remove

See [Workflow Set Theory Component](https://www.symantec.com/connect/articles/workflow-set-theory-component) on Connect.

See [List Maintenance](https://www.symantec.com/connect/articles/workflow-list-maintenance) for an alternative.

---

### SubnetMask
> Get the IP Address then the SubnetMask from that

---

### URLCoding
> URL Coding - Encode / Decode

---

### WorkflowConnections
> Workflow Connections

> Get the Default Endpoint Address for the given Connection

> `LogicBase.Components.ActiveDirectory.dll`
>   `Logicbase.Component.ActiveDirectory.GetAllADConnectionProfilesComponent`

> `Symantec.Workflow.Core.dll`
>   `Symantec.Workflow.Core.ActiveDirectory.ADConnectionProfileManager`

---

### WorkflowPort
> Get the Workflow Port and check if it's in Debug

>  https://www.symantec.com/connect/articles/determine-if-workflow-running-debug

---

### WorkflowServer
> Get the Workflow Server install path

---

### WorkflowSQLConnectionString
> Workflow SQL Connection String from the local.orm

> https://www.symantec.com/connect/blogs/workflowservicedesk-how-extract-localorm-sql-connection-string
