# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.376 ops/ms
Iteration   1: 6.064 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.064 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.759 ops/ms
Iteration   1: 14.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.387 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.258 ops/ms
Iteration   1: 8.598 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.598 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.322 ops/ms
Iteration   1: 3.469 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.469 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ±(99.9%) 0.067 ms/op
Iteration   1: 3.072 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ±(99.9%) 0.038 ms/op
Iteration   1: 1.778 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.837 ±(99.9%) 0.057 ms/op
Iteration   1: 3.191 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.191 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.488 ±(99.9%) 0.282 ms/op
Iteration   1: 8.061 ±(99.9%) 0.108 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.061 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ±(99.9%) 0.152 ms/op
Iteration   1: 3.106 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  17.910 ms/op
                 createUser·p0.9999: 18.206 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10435
  mean =      3.106 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2384 
    [ 2.500,  3.750) = 6715 
    [ 3.750,  5.000) = 1112 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     17.910 ms/op
     p(99.9900) =     18.206 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.033 ±(99.9%) 0.077 ms/op
Iteration   1: 1.740 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.243 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.076 ms/op
                 existUser·p0.999:  4.773 ms/op
                 existUser·p0.9999: 6.193 ms/op
                 existUser·p1.00:   6.889 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18495
  mean =      1.740 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 8 
    [0.500, 1.000) = 149 
    [1.000, 1.500) = 6081 
    [1.500, 2.000) = 7959 
    [2.000, 2.500) = 3366 
    [2.500, 3.000) = 730 
    [3.000, 3.500) = 118 
    [3.500, 4.000) = 19 
    [4.000, 4.500) = 43 
    [4.500, 5.000) = 9 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.243 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.076 ms/op
     p(99.9000) =      4.773 ms/op
     p(99.9900) =      6.193 ms/op
     p(99.9990) =      6.889 ms/op
     p(99.9999) =      6.889 ms/op
    p(100.0000) =      6.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.471 ±(99.9%) 0.095 ms/op
Iteration   1: 3.389 ±(99.9%) 0.143 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.178 ms/op
                 getUser·p0.999:  79.692 ms/op
                 getUser·p0.9999: 82.575 ms/op
                 getUser·p1.00:   82.575 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9436
  mean =      3.389 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9239 
    [ 5.000, 10.000) = 116 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 4 
    [75.000, 80.000) = 9 
    [80.000, 85.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.178 ms/op
     p(99.9000) =     79.692 ms/op
     p(99.9900) =     82.575 ms/op
     p(99.9990) =     82.575 ms/op
     p(99.9999) =     82.575 ms/op
    p(100.0000) =     82.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.614 ±(99.9%) 0.627 ms/op
Iteration   1: 8.625 ±(99.9%) 0.139 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.256 ms/op
                 listUser·p0.95:   12.937 ms/op
                 listUser·p0.99:   19.399 ms/op
                 listUser·p0.999:  24.898 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3693
  mean =      8.625 ±(99.9%) 0.139 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 72 
    [ 5.000,  7.500) = 1193 
    [ 7.500, 10.000) = 1711 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.256 ms/op
     p(95.0000) =     12.937 ms/op
     p(99.0000) =     19.399 ms/op
     p(99.9000) =     24.898 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.064          ops/ms
Client.existUser                       thrpt         14.387          ops/ms
Client.getUser                         thrpt          8.598          ops/ms
Client.listUser                        thrpt          3.469          ops/ms
Client.createUser                       avgt          3.072           ms/op
Client.existUser                        avgt          1.778           ms/op
Client.getUser                          avgt          3.191           ms/op
Client.listUser                         avgt          8.061           ms/op
Client.createUser                     sample  10435   3.106 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.821           ms/op
Client.createUser:createUser·p0.50    sample          2.933           ms/op
Client.createUser:createUser·p0.90    sample          3.834           ms/op
Client.createUser:createUser·p0.95    sample          4.116           ms/op
Client.createUser:createUser·p0.99    sample          7.119           ms/op
Client.createUser:createUser·p0.999   sample         17.910           ms/op
Client.createUser:createUser·p0.9999  sample         18.206           ms/op
Client.createUser:createUser·p1.00    sample         18.219           ms/op
Client.existUser                      sample  18495   1.740 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.243           ms/op
Client.existUser:existUser·p0.50      sample          1.647           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.503           ms/op
Client.existUser:existUser·p0.99      sample          3.076           ms/op
Client.existUser:existUser·p0.999     sample          4.773           ms/op
Client.existUser:existUser·p0.9999    sample          6.193           ms/op
Client.existUser:existUser·p1.00      sample          6.889           ms/op
Client.getUser                        sample   9436   3.389 ± 0.143   ms/op
Client.getUser:getUser·p0.00          sample          1.053           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          3.949           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample          6.178           ms/op
Client.getUser:getUser·p0.999         sample         79.692           ms/op
Client.getUser:getUser·p0.9999        sample         82.575           ms/op
Client.getUser:getUser·p1.00          sample         82.575           ms/op
Client.listUser                       sample   3693   8.625 ± 0.139   ms/op
Client.listUser:listUser·p0.00        sample          1.657           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.256           ms/op
Client.listUser:listUser·p0.95        sample         12.937           ms/op
Client.listUser:listUser·p0.99        sample         19.399           ms/op
Client.listUser:listUser·p0.999       sample         24.898           ms/op
Client.listUser:listUser·p0.9999      sample         25.494           ms/op
Client.listUser:listUser·p1.00        sample         25.494           ms/op
