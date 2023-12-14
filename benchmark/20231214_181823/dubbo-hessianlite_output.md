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
# Warmup Iteration   1: 2.018 ops/ms
Iteration   1: 5.645 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.645 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ops/ms
Iteration   1: 11.847 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.847 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ops/ms
Iteration   1: 7.638 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.638 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.454 ops/ms
Iteration   1: 3.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.825 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ±(99.9%) 0.065 ms/op
Iteration   1: 3.229 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.229 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ±(99.9%) 0.041 ms/op
Iteration   1: 1.984 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.984 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.300 ±(99.9%) 0.064 ms/op
Iteration   1: 3.028 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.028 ms/op


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
# Warmup Iteration   1: 11.624 ±(99.9%) 0.213 ms/op
Iteration   1: 9.331 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.331 ms/op


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
# Warmup Iteration   1: 5.324 ±(99.9%) 0.137 ms/op
Iteration   1: 3.178 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   9.461 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 21.233 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10054
  mean =      3.178 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2089 
    [ 2.500,  5.000) = 7706 
    [ 5.000,  7.500) = 125 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      9.461 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     21.233 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ±(99.9%) 0.088 ms/op
Iteration   1: 1.983 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   4.046 ms/op
                 existUser·p0.999:  9.912 ms/op
                 existUser·p0.9999: 10.101 ms/op
                 existUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16116
  mean =      1.983 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 10815 
    [ 2.000,  3.000) = 4955 
    [ 3.000,  4.000) = 177 
    [ 4.000,  5.000) = 33 
    [ 5.000,  6.000) = 78 
    [ 6.000,  7.000) = 21 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      4.046 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     10.101 ms/op
     p(99.9990) =     10.191 ms/op
     p(99.9999) =     10.191 ms/op
    p(100.0000) =     10.191 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 5.075 ±(99.9%) 0.144 ms/op
Iteration   1: 3.268 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.326 ms/op
                 getUser·p0.999:  8.318 ms/op
                 getUser·p0.9999: 9.437 ms/op
                 getUser·p1.00:   9.437 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9789
  mean =      3.268 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 112 
    [ 2.000,  3.000) = 3514 
    [ 3.000,  4.000) = 4951 
    [ 4.000,  5.000) = 1036 
    [ 5.000,  6.000) = 147 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 15 
    [ 8.000,  9.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.326 ms/op
     p(99.9000) =      8.318 ms/op
     p(99.9900) =      9.437 ms/op
     p(99.9990) =      9.437 ms/op
     p(99.9999) =      9.437 ms/op
    p(100.0000) =      9.437 ms/op


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
# Warmup Iteration   1: 12.511 ±(99.9%) 0.470 ms/op
Iteration   1: 8.859 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   3.240 ms/op
                 listUser·p0.50:   8.438 ms/op
                 listUser·p0.90:   11.862 ms/op
                 listUser·p0.95:   12.845 ms/op
                 listUser·p0.99:   14.906 ms/op
                 listUser·p0.999:  20.130 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3606
  mean =      8.859 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 48 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 1693 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.240 ms/op
     p(50.0000) =      8.438 ms/op
     p(90.0000) =     11.862 ms/op
     p(95.0000) =     12.845 ms/op
     p(99.0000) =     14.906 ms/op
     p(99.9000) =     20.130 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.645          ops/ms
Client.existUser                       thrpt         11.847          ops/ms
Client.getUser                         thrpt          7.638          ops/ms
Client.listUser                        thrpt          3.825          ops/ms
Client.createUser                       avgt          3.229           ms/op
Client.existUser                        avgt          1.984           ms/op
Client.getUser                          avgt          3.028           ms/op
Client.listUser                         avgt          9.331           ms/op
Client.createUser                     sample  10054   3.178 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          2.982           ms/op
Client.createUser:createUser·p0.90    sample          3.977           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          9.461           ms/op
Client.createUser:createUser·p0.999   sample         20.251           ms/op
Client.createUser:createUser·p0.9999  sample         21.233           ms/op
Client.createUser:createUser·p1.00    sample         21.234           ms/op
Client.existUser                      sample  16116   1.983 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.778           ms/op
Client.existUser:existUser·p0.50      sample          1.892           ms/op
Client.existUser:existUser·p0.90      sample          2.343           ms/op
Client.existUser:existUser·p0.95      sample          2.519           ms/op
Client.existUser:existUser·p0.99      sample          4.046           ms/op
Client.existUser:existUser·p0.999     sample          9.912           ms/op
Client.existUser:existUser·p0.9999    sample         10.101           ms/op
Client.existUser:existUser·p1.00      sample         10.191           ms/op
Client.getUser                        sample   9789   3.268 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.781           ms/op
Client.getUser:getUser·p0.50          sample          3.232           ms/op
Client.getUser:getUser·p0.90          sample          4.076           ms/op
Client.getUser:getUser·p0.95          sample          4.334           ms/op
Client.getUser:getUser·p0.99          sample          5.326           ms/op
Client.getUser:getUser·p0.999         sample          8.318           ms/op
Client.getUser:getUser·p0.9999        sample          9.437           ms/op
Client.getUser:getUser·p1.00          sample          9.437           ms/op
Client.listUser                       sample   3606   8.859 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          3.240           ms/op
Client.listUser:listUser·p0.50        sample          8.438           ms/op
Client.listUser:listUser·p0.90        sample         11.862           ms/op
Client.listUser:listUser·p0.95        sample         12.845           ms/op
Client.listUser:listUser·p0.99        sample         14.906           ms/op
Client.listUser:listUser·p0.999       sample         20.130           ms/op
Client.listUser:listUser·p0.9999      sample         22.512           ms/op
Client.listUser:listUser·p1.00        sample         22.512           ms/op
