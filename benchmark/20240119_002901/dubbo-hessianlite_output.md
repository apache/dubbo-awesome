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
# Warmup Iteration   1: 2.209 ops/ms
Iteration   1: 5.613 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.613 ops/ms


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
# Warmup Iteration   1: 5.421 ops/ms
Iteration   1: 12.226 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.226 ops/ms


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
# Warmup Iteration   1: 4.213 ops/ms
Iteration   1: 9.009 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.009 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
Iteration   1: 3.784 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.784 ops/ms


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.072 ms/op
Iteration   1: 3.373 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.373 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.045 ms/op
Iteration   1: 1.781 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.781 ms/op


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
# Warmup Iteration   1: 5.729 ±(99.9%) 0.070 ms/op
Iteration   1: 3.025 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.025 ms/op


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
# Warmup Iteration   1: 11.566 ±(99.9%) 0.145 ms/op
Iteration   1: 8.508 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.508 ms/op


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
# Warmup Iteration   1: 5.068 ±(99.9%) 0.108 ms/op
Iteration   1: 3.001 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.859 ms/op
                 createUser·p0.90:   3.471 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  16.597 ms/op
                 createUser·p0.9999: 16.725 ms/op
                 createUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10665
  mean =      3.001 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1927 
    [ 2.500,  3.750) = 8001 
    [ 3.750,  5.000) = 527 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.471 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     16.725 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.075 ms/op
Iteration   1: 2.069 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.683 ms/op
                 existUser·p0.95:   2.900 ms/op
                 existUser·p0.99:   4.239 ms/op
                 existUser·p0.999:  13.468 ms/op
                 existUser·p0.9999: 13.906 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15458
  mean =      2.069 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 12436 
    [ 2.500,  3.750) = 2376 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.239 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     13.906 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.097 ms/op
Iteration   1: 3.205 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.386 ms/op
                 getUser·p0.99:   6.277 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 12.698 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9970
  mean =      3.205 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1259 
    [ 2.500,  3.750) = 6958 
    [ 3.750,  5.000) = 1492 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.386 ms/op
     p(99.0000) =      6.277 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 12.746 ±(99.9%) 0.443 ms/op
Iteration   1: 8.108 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   7.717 ms/op
                 listUser·p0.90:   11.403 ms/op
                 listUser·p0.95:   12.960 ms/op
                 listUser·p0.99:   15.983 ms/op
                 listUser·p0.999:  20.215 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3948
  mean =      8.108 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 198 
    [ 5.000,  7.500) = 1606 
    [ 7.500, 10.000) = 1464 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.036 ms/op
     p(50.0000) =      7.717 ms/op
     p(90.0000) =     11.403 ms/op
     p(95.0000) =     12.960 ms/op
     p(99.0000) =     15.983 ms/op
     p(99.9000) =     20.215 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.613          ops/ms
Client.existUser                       thrpt         12.226          ops/ms
Client.getUser                         thrpt          9.009          ops/ms
Client.listUser                        thrpt          3.784          ops/ms
Client.createUser                       avgt          3.373           ms/op
Client.existUser                        avgt          1.781           ms/op
Client.getUser                          avgt          3.025           ms/op
Client.listUser                         avgt          8.508           ms/op
Client.createUser                     sample  10665   3.001 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.005           ms/op
Client.createUser:createUser·p0.50    sample          2.859           ms/op
Client.createUser:createUser·p0.90    sample          3.471           ms/op
Client.createUser:createUser·p0.95    sample          4.235           ms/op
Client.createUser:createUser·p0.99    sample          8.995           ms/op
Client.createUser:createUser·p0.999   sample         16.597           ms/op
Client.createUser:createUser·p0.9999  sample         16.725           ms/op
Client.createUser:createUser·p1.00    sample         16.728           ms/op
Client.existUser                      sample  15458   2.069 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.481           ms/op
Client.existUser:existUser·p0.50      sample          1.958           ms/op
Client.existUser:existUser·p0.90      sample          2.683           ms/op
Client.existUser:existUser·p0.95      sample          2.900           ms/op
Client.existUser:existUser·p0.99      sample          4.239           ms/op
Client.existUser:existUser·p0.999     sample         13.468           ms/op
Client.existUser:existUser·p0.9999    sample         13.906           ms/op
Client.existUser:existUser·p1.00      sample         13.959           ms/op
Client.getUser                        sample   9970   3.205 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.904           ms/op
Client.getUser:getUser·p0.50          sample          3.076           ms/op
Client.getUser:getUser·p0.90          sample          4.043           ms/op
Client.getUser:getUser·p0.95          sample          4.386           ms/op
Client.getUser:getUser·p0.99          sample          6.277           ms/op
Client.getUser:getUser·p0.999         sample          8.487           ms/op
Client.getUser:getUser·p0.9999        sample         12.698           ms/op
Client.getUser:getUser·p1.00          sample         12.698           ms/op
Client.listUser                       sample   3948   8.108 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          2.036           ms/op
Client.listUser:listUser·p0.50        sample          7.717           ms/op
Client.listUser:listUser·p0.90        sample         11.403           ms/op
Client.listUser:listUser·p0.95        sample         12.960           ms/op
Client.listUser:listUser·p0.99        sample         15.983           ms/op
Client.listUser:listUser·p0.999       sample         20.215           ms/op
Client.listUser:listUser·p0.9999      sample         21.725           ms/op
Client.listUser:listUser·p1.00        sample         21.725           ms/op
