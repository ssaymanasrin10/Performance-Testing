# Performance-Testing

Dear, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

20 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 80 And Total Concurrent API requested: 80.
60 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 240 And Total Concurrent API requested: 240.
100 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 400 And Total Concurrent API requested: 400.
200 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 800 And Total Concurrent API requested: 800.
460 Concurrent Request with 0 Loop Count; Avg TPS for Total Samples is ~ 1840 And Total Concurrent API requested: 1840.



While executed 460 concurrent requests, found 9 request got connection timeout and error rate is 0.49%. 

Summary: Server can handle almost concurrent 1000 API call with almost zero (0) error rate.
