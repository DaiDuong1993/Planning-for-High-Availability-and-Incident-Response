# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability |  Total successful requests / total requests	  | 99%                                                                                                         |
| Latency      |  requests shows 90th percentile over the last 30 seconds	   | 90% of requests below 100ms                                                                                 |
| Error Budget |  The percentage of all unsuccessful requests to the percentage of all failed requests used   | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   |  Amount of successful requests over a given time period (ex: 5 minutes)  | 5 RPS indicates the application is functioning                                                              |