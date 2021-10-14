## Multiserver - by Joshua Austin



### Multiserver

The function is used to simulate customers being served at a bank.
The arrival time of each customer, how long their service will take, and how many servers are working, are the 3 factors that can be atken as input in the function. The arrival and service times must both be vectors of the same length, while number of servers will default to 1 unless specified to have more.



### Installing
To download from github use the following;
```{r install}
# install.packages("devtools")
devtools::install_github("MQ-STAT1378/assignment2-question2-Joshua-Austin")
```

### Using Multiserver
Entries need to be in the form;
Multiserver(arrival_times, service_times, servers)

```{r}
Multiserver(100:110, 110:100, 1)
```


