# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.297 ops/ms
Iteration   1: 4.138 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.138 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.678 ops/ms
Iteration   1: 12.093 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.093 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.721 ops/ms
Iteration   1: 5.197 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.197 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.104 ops/ms
Iteration   1: 1.656 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.656 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.931 ±(99.9%) 0.327 ms/op
Iteration   1: 5.902 ±(99.9%) 0.251 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.902 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.193 ±(99.9%) 0.080 ms/op
Iteration   1: 2.114 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.445 ±(99.9%) 0.145 ms/op
Iteration   1: 4.114 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 25.004 ±(99.9%) 0.457 ms/op
Iteration   1: 17.730 ±(99.9%) 0.349 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.509 ±(99.9%) 0.228 ms/op
Iteration   1: 2.996 ±(99.9%) 0.076 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.995 ms/op
                 createUser·p0.99:   11.485 ms/op
                 createUser·p0.999:  35.237 ms/op
                 createUser·p0.9999: 36.233 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10664
  mean =      2.996 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4096 
    [ 2.500,  5.000) = 6036 
    [ 5.000,  7.500) = 227 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.995 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     35.237 ms/op
     p(99.9900) =     36.233 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.199 ±(99.9%) 0.148 ms/op
Iteration   1: 2.059 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  22.765 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15539
  mean =      2.059 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13607 
    [ 2.500,  5.000) = 1518 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 190 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      3.404 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     22.765 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.307 ms/op
Iteration   1: 3.231 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   5.462 ms/op
                 getUser·p0.99:   11.407 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 19.919 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10043
  mean =      3.231 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1644 
    [ 2.500,  3.750) = 7298 
    [ 3.750,  5.000) = 541 
    [ 5.000,  6.250) = 197 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      5.462 ms/op
     p(99.0000) =     11.407 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     19.919 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 30.285 ±(99.9%) 1.911 ms/op
Iteration   1: 17.323 ±(99.9%) 0.492 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   16.048 ms/op
                 listUser·p0.90:   24.979 ms/op
                 listUser·p0.95:   28.808 ms/op
                 listUser·p0.99:   45.241 ms/op
                 listUser·p0.999:  59.162 ms/op
                 listUser·p0.9999: 61.866 ms/op
                 listUser·p1.00:   61.866 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1896
  mean =     17.323 ±(99.9%) 0.492 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5 
    [ 5.000, 10.000) = 98 
    [10.000, 15.000) = 673 
    [15.000, 20.000) = 670 
    [20.000, 25.000) = 261 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 6 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.150 ms/op
     p(50.0000) =     16.048 ms/op
     p(90.0000) =     24.979 ms/op
     p(95.0000) =     28.808 ms/op
     p(99.0000) =     45.241 ms/op
     p(99.9000) =     59.162 ms/op
     p(99.9900) =     61.866 ms/op
     p(99.9990) =     61.866 ms/op
     p(99.9999) =     61.866 ms/op
    p(100.0000) =     61.866 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.138          ops/ms
Client.existUser                       thrpt         12.093          ops/ms
Client.getUser                         thrpt          5.197          ops/ms
Client.listUser                        thrpt          1.656          ops/ms
Client.createUser                       avgt          5.902           ms/op
Client.existUser                        avgt          2.114           ms/op
Client.getUser                          avgt          4.114           ms/op
Client.listUser                         avgt         17.730           ms/op
Client.createUser                     sample  10664   2.996 ± 0.076   ms/op
Client.createUser:createUser·p0.00    sample          0.743           ms/op
Client.createUser:createUser·p0.50    sample          2.597           ms/op
Client.createUser:createUser·p0.90    sample          3.703           ms/op
Client.createUser:createUser·p0.95    sample          4.995           ms/op
Client.createUser:createUser·p0.99    sample         11.485           ms/op
Client.createUser:createUser·p0.999   sample         35.237           ms/op
Client.createUser:createUser·p0.9999  sample         36.233           ms/op
Client.createUser:createUser·p1.00    sample         36.241           ms/op
Client.existUser                      sample  15539   2.059 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample          0.686           ms/op
Client.existUser:existUser·p0.50      sample          1.683           ms/op
Client.existUser:existUser·p0.90      sample          2.662           ms/op
Client.existUser:existUser·p0.95      sample          3.404           ms/op
Client.existUser:existUser·p0.99      sample          9.241           ms/op
Client.existUser:existUser·p0.999     sample         22.765           ms/op
Client.existUser:existUser·p0.9999    sample         23.265           ms/op
Client.existUser:existUser·p1.00      sample         23.265           ms/op
Client.getUser                        sample  10043   3.231 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          0.898           ms/op
Client.getUser:getUser·p0.50          sample          2.916           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          5.462           ms/op
Client.getUser:getUser·p0.99          sample         11.407           ms/op
Client.getUser:getUser·p0.999         sample         18.678           ms/op
Client.getUser:getUser·p0.9999        sample         19.919           ms/op
Client.getUser:getUser·p1.00          sample         19.923           ms/op
Client.listUser                       sample   1896  17.323 ± 0.492   ms/op
Client.listUser:listUser·p0.00        sample          3.150           ms/op
Client.listUser:listUser·p0.50        sample         16.048           ms/op
Client.listUser:listUser·p0.90        sample         24.979           ms/op
Client.listUser:listUser·p0.95        sample         28.808           ms/op
Client.listUser:listUser·p0.99        sample         45.241           ms/op
Client.listUser:listUser·p0.999       sample         59.162           ms/op
Client.listUser:listUser·p0.9999      sample         61.866           ms/op
Client.listUser:listUser·p1.00        sample         61.866           ms/op
