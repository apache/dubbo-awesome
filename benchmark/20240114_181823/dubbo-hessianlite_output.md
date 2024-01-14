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
# Warmup Iteration   1: 2.193 ops/ms
Iteration   1: 6.278 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.278 ops/ms


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
# Warmup Iteration   1: 6.137 ops/ms
Iteration   1: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.789 ops/ms


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
# Warmup Iteration   1: 4.579 ops/ms
Iteration   1: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.549 ops/ms


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
# Warmup Iteration   1: 2.428 ops/ms
Iteration   1: 4.024 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.024 ops/ms


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.057 ms/op
Iteration   1: 2.787 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.787 ms/op


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
# Warmup Iteration   1: 2.974 ±(99.9%) 0.028 ms/op
Iteration   1: 2.082 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.082 ms/op


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
# Warmup Iteration   1: 5.195 ±(99.9%) 0.066 ms/op
Iteration   1: 2.956 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.956 ms/op


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
# Warmup Iteration   1: 12.407 ±(99.9%) 0.194 ms/op
Iteration   1: 7.432 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.432 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.093 ms/op
Iteration   1: 3.142 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  28.836 ms/op
                 createUser·p0.9999: 29.261 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10301
  mean =      3.142 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2026 
    [ 2.500,  5.000) = 7906 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     28.836 ms/op
     p(99.9900) =     29.261 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.156 ms/op
Iteration   1: 1.841 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   4.721 ms/op
                 existUser·p0.999:  7.457 ms/op
                 existUser·p0.9999: 9.732 ms/op
                 existUser·p1.00:   9.732 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17711
  mean =      1.841 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 151 
    [ 1.000,  2.000) = 12408 
    [ 2.000,  3.000) = 4781 
    [ 3.000,  4.000) = 154 
    [ 4.000,  5.000) = 95 
    [ 5.000,  6.000) = 84 
    [ 6.000,  7.000) = 19 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.721 ms/op
     p(99.9000) =      7.457 ms/op
     p(99.9900) =      9.732 ms/op
     p(99.9990) =      9.732 ms/op
     p(99.9999) =      9.732 ms/op
    p(100.0000) =      9.732 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.135 ms/op
Iteration   1: 2.847 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.666 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.371 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 18.986 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11231
  mean =      2.847 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 3686 
    [ 2.500,  3.750) = 7007 
    [ 3.750,  5.000) = 376 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.371 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     18.986 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 12.622 ±(99.9%) 0.492 ms/op
Iteration   1: 7.409 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   7.160 ms/op
                 listUser·p0.90:   9.400 ms/op
                 listUser·p0.95:   10.401 ms/op
                 listUser·p0.99:   17.236 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 20.251 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4302
  mean =      7.409 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 225 
    [ 5.000,  7.500) = 2275 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      7.160 ms/op
     p(90.0000) =      9.400 ms/op
     p(95.0000) =     10.401 ms/op
     p(99.0000) =     17.236 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.278          ops/ms
Client.existUser                       thrpt         12.789          ops/ms
Client.getUser                         thrpt          8.549          ops/ms
Client.listUser                        thrpt          4.024          ops/ms
Client.createUser                       avgt          2.787           ms/op
Client.existUser                        avgt          2.082           ms/op
Client.getUser                          avgt          2.956           ms/op
Client.listUser                         avgt          7.432           ms/op
Client.createUser                     sample  10301   3.142 ± 0.058   ms/op
Client.createUser:createUser·p0.00    sample          0.951           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.813           ms/op
Client.createUser:createUser·p0.95    sample          4.317           ms/op
Client.createUser:createUser·p0.99    sample         10.240           ms/op
Client.createUser:createUser·p0.999   sample         28.836           ms/op
Client.createUser:createUser·p0.9999  sample         29.261           ms/op
Client.createUser:createUser·p1.00    sample         29.262           ms/op
Client.existUser                      sample  17711   1.841 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.568           ms/op
Client.existUser:existUser·p0.50      sample          1.737           ms/op
Client.existUser:existUser·p0.90      sample          2.376           ms/op
Client.existUser:existUser·p0.95      sample          2.572           ms/op
Client.existUser:existUser·p0.99      sample          4.721           ms/op
Client.existUser:existUser·p0.999     sample          7.457           ms/op
Client.existUser:existUser·p0.9999    sample          9.732           ms/op
Client.existUser:existUser·p1.00      sample          9.732           ms/op
Client.getUser                        sample  11231   2.847 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.046           ms/op
Client.getUser:getUser·p0.50          sample          2.666           ms/op
Client.getUser:getUser·p0.90          sample          3.461           ms/op
Client.getUser:getUser·p0.95          sample          3.723           ms/op
Client.getUser:getUser·p0.99          sample          5.371           ms/op
Client.getUser:getUser·p0.999         sample         18.285           ms/op
Client.getUser:getUser·p0.9999        sample         18.986           ms/op
Client.getUser:getUser·p1.00          sample         19.038           ms/op
Client.listUser                       sample   4302   7.409 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          1.530           ms/op
Client.listUser:listUser·p0.50        sample          7.160           ms/op
Client.listUser:listUser·p0.90        sample          9.400           ms/op
Client.listUser:listUser·p0.95        sample         10.401           ms/op
Client.listUser:listUser·p0.99        sample         17.236           ms/op
Client.listUser:listUser·p0.999       sample         19.595           ms/op
Client.listUser:listUser·p0.9999      sample         20.251           ms/op
Client.listUser:listUser·p1.00        sample         20.251           ms/op
