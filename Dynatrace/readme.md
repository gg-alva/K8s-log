
**1. Introduction to Dynatrace**
- Explored Dynatrace as an **observability and application monitoring platform**.
- Understood how it provides visibility into applications, infrastructure, services, and overall system performance.
- Learned how observability data can be used to identify performance issues and understand application health.

**2. Exploring the Dynatrace UI**
- Explored the different components and sections available in the Dynatrace user interface.
- Learned how the UI brings together monitoring and observability information in a centralized platform.
- Explored how different views can be used to analyze applications, services, infrastructure, and system health.
- Familiarized myself with navigating through the platform and locating relevant monitoring information.



```
fetch logs
| filter loglevel == "ERROR"
| summarize error_count = count()
```

```
fetch logs 
| filter loglevel == "WARN"
| summarize warn = count(), by:{loglevel}
```

```
fetch logs
| filter loglevel == "NONE"
| summarize None = count() , by:{loglevel}
```

```
fetch logs
| summarize log_count = count() ,  by:{loglevel}
```

```
fetch logs
| filter loglevel == "ERROR"
| fields timestamp, loglevel, content
```

