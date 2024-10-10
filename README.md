# Read me

The original idea is from  
https://medium.com/@ruth.kurniawati/using-custom-micrometer-meter-filters-in-a-spring-boot-application-a58aff7dbe4d

We can directly see metrics or see the metrics using prometheus. We can enable/disable some metrics

# Directly See Metrics

http://localhost:8080/actuator/metrics

# See Metrics Using Prometheus

http://localhost:8080/actuator/prometheus

# Disabled CPU Metrics

Verify that these metrics are disabled
http://localhost:8080/actuator/metrics/system.cpu.usage
http://localhost:8080/actuator/metrics/process.cpu.usage
