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
# Warmup Iteration   1: 1.233 ops/ms
Iteration   1: 3.101 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.101 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.476 ops/ms
Iteration   1: 7.620 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.620 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
Iteration   1: 5.188 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.188 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 0.797 ops/ms
Iteration   1: 1.096 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.096 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 14.835 ±(99.9%) 0.511 ms/op
Iteration   1: 5.464 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.464 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 10.716 ±(99.9%) 0.226 ms/op
Iteration   1: 3.553 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.553 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.725 ±(99.9%) 0.217 ms/op
Iteration   1: 7.020 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.020 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 26.648 ±(99.9%) 0.866 ms/op
Iteration   1: 20.658 ±(99.9%) 0.571 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.658 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 11.644 ±(99.9%) 0.365 ms/op
Iteration   1: 4.938 ±(99.9%) 0.142 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   8.274 ms/op
                 createUser·p0.95:   10.895 ms/op
                 createUser·p0.99:   25.723 ms/op
                 createUser·p0.999:  29.069 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6436
  mean =      4.938 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 5183 
    [ 5.000,  7.500) = 519 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      8.274 ms/op
     p(95.0000) =     10.895 ms/op
     p(99.0000) =     25.723 ms/op
     p(99.9000) =     29.069 ms/op
     p(99.9900) =     29.458 ms/op
     p(99.9990) =     29.458 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.190 ±(99.9%) 0.225 ms/op
Iteration   1: 3.126 ±(99.9%) 0.090 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   6.520 ms/op
                 existUser·p0.99:   12.993 ms/op
                 existUser·p0.999:  30.860 ms/op
                 existUser·p0.9999: 52.119 ms/op
                 existUser·p1.00:   52.167 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10220
  mean =      3.126 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9418 
    [ 5.000, 10.000) = 548 
    [10.000, 15.000) = 183 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      6.520 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     30.860 ms/op
     p(99.9900) =     52.119 ms/op
     p(99.9990) =     52.167 ms/op
     p(99.9999) =     52.167 ms/op
    p(100.0000) =     52.167 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 12.244 ±(99.9%) 0.289 ms/op
Iteration   1: 6.109 ±(99.9%) 0.145 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   5.345 ms/op
                 getUser·p0.90:   9.042 ms/op
                 getUser·p0.95:   12.009 ms/op
                 getUser·p0.99:   16.237 ms/op
                 getUser·p0.999:  33.817 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5300
  mean =      6.109 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 2157 
    [ 5.000,  7.500) = 2278 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      5.345 ms/op
     p(90.0000) =      9.042 ms/op
     p(95.0000) =     12.009 ms/op
     p(99.0000) =     16.237 ms/op
     p(99.9000) =     33.817 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 28.170 ±(99.9%) 1.166 ms/op
Iteration   1: 17.807 ±(99.9%) 0.519 ms/op
                 listUser·p0.00:   3.138 ms/op
                 listUser·p0.50:   16.212 ms/op
                 listUser·p0.90:   26.499 ms/op
                 listUser·p0.95:   31.611 ms/op
                 listUser·p0.99:   38.778 ms/op
                 listUser·p0.999:  57.029 ms/op
                 listUser·p0.9999: 60.621 ms/op
                 listUser·p1.00:   60.621 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1782
  mean =     17.807 ±(99.9%) 0.519 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 64 
    [10.000, 15.000) = 633 
    [15.000, 20.000) = 613 
    [20.000, 25.000) = 256 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 62 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.138 ms/op
     p(50.0000) =     16.212 ms/op
     p(90.0000) =     26.499 ms/op
     p(95.0000) =     31.611 ms/op
     p(99.0000) =     38.778 ms/op
     p(99.9000) =     57.029 ms/op
     p(99.9900) =     60.621 ms/op
     p(99.9990) =     60.621 ms/op
     p(99.9999) =     60.621 ms/op
    p(100.0000) =     60.621 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.101          ops/ms
Client.existUser                       thrpt          7.620          ops/ms
Client.getUser                         thrpt          5.188          ops/ms
Client.listUser                        thrpt          1.096          ops/ms
Client.createUser                       avgt          5.464           ms/op
Client.existUser                        avgt          3.553           ms/op
Client.getUser                          avgt          7.020           ms/op
Client.listUser                         avgt         20.658           ms/op
Client.createUser                     sample   6436   4.938 ± 0.142   ms/op
Client.createUser:createUser·p0.00    sample          1.974           ms/op
Client.createUser:createUser·p0.50    sample          3.920           ms/op
Client.createUser:createUser·p0.90    sample          8.274           ms/op
Client.createUser:createUser·p0.95    sample         10.895           ms/op
Client.createUser:createUser·p0.99    sample         25.723           ms/op
Client.createUser:createUser·p0.999   sample         29.069           ms/op
Client.createUser:createUser·p0.9999  sample         29.458           ms/op
Client.createUser:createUser·p1.00    sample         29.458           ms/op
Client.existUser                      sample  10220   3.126 ± 0.090   ms/op
Client.existUser:existUser·p0.00      sample          0.815           ms/op
Client.existUser:existUser·p0.50      sample          2.503           ms/op
Client.existUser:existUser·p0.90      sample          4.227           ms/op
Client.existUser:existUser·p0.95      sample          6.520           ms/op
Client.existUser:existUser·p0.99      sample         12.993           ms/op
Client.existUser:existUser·p0.999     sample         30.860           ms/op
Client.existUser:existUser·p0.9999    sample         52.119           ms/op
Client.existUser:existUser·p1.00      sample         52.167           ms/op
Client.getUser                        sample   5300   6.109 ± 0.145   ms/op
Client.getUser:getUser·p0.00          sample          1.518           ms/op
Client.getUser:getUser·p0.50          sample          5.345           ms/op
Client.getUser:getUser·p0.90          sample          9.042           ms/op
Client.getUser:getUser·p0.95          sample         12.009           ms/op
Client.getUser:getUser·p0.99          sample         16.237           ms/op
Client.getUser:getUser·p0.999         sample         33.817           ms/op
Client.getUser:getUser·p0.9999        sample         33.882           ms/op
Client.getUser:getUser·p1.00          sample         33.882           ms/op
Client.listUser                       sample   1782  17.807 ± 0.519   ms/op
Client.listUser:listUser·p0.00        sample          3.138           ms/op
Client.listUser:listUser·p0.50        sample         16.212           ms/op
Client.listUser:listUser·p0.90        sample         26.499           ms/op
Client.listUser:listUser·p0.95        sample         31.611           ms/op
Client.listUser:listUser·p0.99        sample         38.778           ms/op
Client.listUser:listUser·p0.999       sample         57.029           ms/op
Client.listUser:listUser·p0.9999      sample         60.621           ms/op
Client.listUser:listUser·p1.00        sample         60.621           ms/op
