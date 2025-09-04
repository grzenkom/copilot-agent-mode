# Diagnose WAF issue

```text
#file:logs_query_data.csv #file:request_AssistantAPIs.ModifyMessage.trace.txt

The frontend application is failing with the following error when trying
to connect to the backend:

HTTP/1.1 403 Forbidden
Connection: keep-alive
Content-Length: 179
Content-Type: text/html
Date: Wed, 13 Aug 2025 19:29:04 GMT
Server: Microsoft-Azure-Application-Gateway/v2

<html>
<head><title>403 Forbidden</title></head>
<body>
<center><h1>403 Forbidden</h1></center>
<hr><center>Microsoft-Azure-Application-Gateway/v2</center>
</body>
</html>

Why?
```

```text
Do I already have any exclusions defined in this project?
```
