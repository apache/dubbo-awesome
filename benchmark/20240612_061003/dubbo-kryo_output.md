# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.106 ops/ms
Iteration   1: 6.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.398 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.785 ops/ms
Iteration   1: 12.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.300 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.046 ops/ms
Iteration   1: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.981 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.317 ops/ms
Iteration   1: 7.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.802 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.093 ms/op
Iteration   1: 2.097 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.060 ±(99.9%) 0.055 ms/op
Iteration   1: 1.996 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ±(99.9%) 0.068 ms/op
Iteration   1: 2.153 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.134 ms/op
Iteration   1: 3.930 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.930 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.385 ±(99.9%) 0.167 ms/op
Iteration   1: 2.411 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.736 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   11.746 ms/op
                 createUser·p0.999:  26.763 ms/op
                 createUser·p0.9999: 39.812 ms/op
                 createUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13253
  mean =      2.411 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12758 
    [ 5.000, 10.000) = 320 
    [10.000, 15.000) = 84 
    [15.000, 20.000) = 39 
    [20.000, 25.000) = 24 
    [25.000, 30.000) = 25 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =     11.746 ms/op
     p(99.9000) =     26.763 ms/op
     p(99.9900) =     39.812 ms/op
     p(99.9990) =     43.778 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.195 ±(99.9%) 0.086 ms/op
Iteration   1: 2.078 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.032 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  13.451 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15394
  mean =      2.078 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 13334 
    [ 2.500,  3.750) = 1650 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ±(99.9%) 0.084 ms/op
Iteration   1: 1.888 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   1.774 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  12.209 ms/op
                 getUser·p0.9999: 13.007 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16936
  mean =      1.888 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 295 
    [ 1.250,  2.500) = 15419 
    [ 2.500,  3.750) = 1036 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =     12.209 ms/op
     p(99.9900) =     13.007 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ±(99.9%) 0.193 ms/op
Iteration   1: 3.510 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.408 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.633 ms/op
                 listUser·p0.999:  11.846 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9124
  mean =      3.510 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 311 
    [ 2.500,  3.750) = 5831 
    [ 3.750,  5.000) = 2602 
    [ 5.000,  6.250) = 254 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.633 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     11.977 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.398          ops/ms
ClientSimple.existUser                       thrpt         12.300          ops/ms
ClientSimple.getUser                         thrpt         10.981          ops/ms
ClientSimple.listUser                        thrpt          7.802          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          1.996           ms/op
ClientSimple.getUser                          avgt          2.153           ms/op
ClientSimple.listUser                         avgt          3.930           ms/op
ClientSimple.createUser                     sample  13253   2.411 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.891           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.746           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.763           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.812           ms/op
ClientSimple.createUser:createUser·p1.00    sample         43.778           ms/op
ClientSimple.existUser                      sample  15394   2.078 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.659           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.032           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.010           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.451           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.959           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.959           ms/op
ClientSimple.getUser                        sample  16936   1.888 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.774           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.777           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.209           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.007           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9124   3.510 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.106           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.408           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.633           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.846           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.977           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.977           ms/op

Benchmark result is saved to 1718172345486.json
