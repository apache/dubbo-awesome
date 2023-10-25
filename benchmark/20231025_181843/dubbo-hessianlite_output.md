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
# Warmup Iteration   1: 1.533 ops/ms
Iteration   1: 4.331 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.331 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ops/ms
Iteration   1: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.600 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.725 ops/ms
Iteration   1: 5.766 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.766 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.186 ops/ms
Iteration   1: 1.704 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.704 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 10.901 ±(99.9%) 0.292 ms/op
Iteration   1: 5.382 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.382 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.807 ±(99.9%) 0.174 ms/op
Iteration   1: 2.250 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.250 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.897 ±(99.9%) 0.137 ms/op
Iteration   1: 3.685 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.685 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 24.255 ±(99.9%) 0.775 ms/op
Iteration   1: 16.783 ±(99.9%) 0.172 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.783 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.365 ±(99.9%) 0.211 ms/op
Iteration   1: 3.325 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   2.632 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   12.583 ms/op
                 createUser·p0.999:  25.723 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9632
  mean =      3.325 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4089 
    [ 2.500,  5.000) = 4673 
    [ 5.000,  7.500) = 544 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      2.632 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     25.723 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ±(99.9%) 0.153 ms/op
Iteration   1: 1.814 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.550 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.908 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  18.756 ms/op
                 existUser·p0.9999: 19.224 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17620
  mean =      1.814 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1235 
    [ 1.250,  2.500) = 15241 
    [ 2.500,  3.750) = 508 
    [ 3.750,  5.000) = 230 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.550 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     18.756 ms/op
     p(99.9900) =     19.224 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.359 ±(99.9%) 0.220 ms/op
Iteration   1: 3.090 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.695 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   6.006 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 21.200 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10467
  mean =      3.090 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3278 
    [ 2.500,  5.000) = 6500 
    [ 5.000,  7.500) = 375 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      6.006 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     21.200 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.926 ±(99.9%) 1.109 ms/op
Iteration   1: 13.987 ±(99.9%) 0.295 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   13.091 ms/op
                 listUser·p0.90:   19.772 ms/op
                 listUser·p0.95:   23.134 ms/op
                 listUser·p0.99:   26.606 ms/op
                 listUser·p0.999:  35.792 ms/op
                 listUser·p0.9999: 42.467 ms/op
                 listUser·p1.00:   42.467 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2275
  mean =     13.987 ±(99.9%) 0.295 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6 
    [ 5.000, 10.000) = 273 
    [10.000, 15.000) = 1257 
    [15.000, 20.000) = 532 
    [20.000, 25.000) = 158 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.941 ms/op
     p(50.0000) =     13.091 ms/op
     p(90.0000) =     19.772 ms/op
     p(95.0000) =     23.134 ms/op
     p(99.0000) =     26.606 ms/op
     p(99.9000) =     35.792 ms/op
     p(99.9900) =     42.467 ms/op
     p(99.9990) =     42.467 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.331          ops/ms
Client.existUser                       thrpt         10.600          ops/ms
Client.getUser                         thrpt          5.766          ops/ms
Client.listUser                        thrpt          1.704          ops/ms
Client.createUser                       avgt          5.382           ms/op
Client.existUser                        avgt          2.250           ms/op
Client.getUser                          avgt          3.685           ms/op
Client.listUser                         avgt         16.783           ms/op
Client.createUser                     sample   9632   3.325 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample          1.241           ms/op
Client.createUser:createUser·p0.50    sample          2.632           ms/op
Client.createUser:createUser·p0.90    sample          4.841           ms/op
Client.createUser:createUser·p0.95    sample          6.005           ms/op
Client.createUser:createUser·p0.99    sample         12.583           ms/op
Client.createUser:createUser·p0.999   sample         25.723           ms/op
Client.createUser:createUser·p0.9999  sample         27.132           ms/op
Client.createUser:createUser·p1.00    sample         27.132           ms/op
Client.existUser                      sample  17620   1.814 ± 0.035   ms/op
Client.existUser:existUser·p0.00      sample          0.535           ms/op
Client.existUser:existUser·p0.50      sample          1.550           ms/op
Client.existUser:existUser·p0.90      sample          2.095           ms/op
Client.existUser:existUser·p0.95      sample          2.908           ms/op
Client.existUser:existUser·p0.99      sample          7.840           ms/op
Client.existUser:existUser·p0.999     sample         18.756           ms/op
Client.existUser:existUser·p0.9999    sample         19.224           ms/op
Client.existUser:existUser·p1.00      sample         19.399           ms/op
Client.getUser                        sample  10467   3.090 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          1.033           ms/op
Client.getUser:getUser·p0.50          sample          2.695           ms/op
Client.getUser:getUser·p0.90          sample          4.059           ms/op
Client.getUser:getUser·p0.95          sample          6.006           ms/op
Client.getUser:getUser·p0.99          sample         10.748           ms/op
Client.getUser:getUser·p0.999         sample         18.416           ms/op
Client.getUser:getUser·p0.9999        sample         21.200           ms/op
Client.getUser:getUser·p1.00          sample         21.234           ms/op
Client.listUser                       sample   2275  13.987 ± 0.295   ms/op
Client.listUser:listUser·p0.00        sample          2.941           ms/op
Client.listUser:listUser·p0.50        sample         13.091           ms/op
Client.listUser:listUser·p0.90        sample         19.772           ms/op
Client.listUser:listUser·p0.95        sample         23.134           ms/op
Client.listUser:listUser·p0.99        sample         26.606           ms/op
Client.listUser:listUser·p0.999       sample         35.792           ms/op
Client.listUser:listUser·p0.9999      sample         42.467           ms/op
Client.listUser:listUser·p1.00        sample         42.467           ms/op
