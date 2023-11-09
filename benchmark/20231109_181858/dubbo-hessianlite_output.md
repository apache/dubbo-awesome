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
# Warmup Iteration   1: 2.245 ops/ms
Iteration   1: 6.366 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.366 ops/ms


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
# Warmup Iteration   1: 6.600 ops/ms
Iteration   1: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.651 ops/ms


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
# Warmup Iteration   1: 4.793 ops/ms
Iteration   1: 9.116 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.116 ops/ms


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
# Warmup Iteration   1: 2.272 ops/ms
Iteration   1: 4.364 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.364 ops/ms


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.077 ms/op
Iteration   1: 3.026 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.026 ms/op


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
# Warmup Iteration   1: 2.968 ±(99.9%) 0.035 ms/op
Iteration   1: 1.928 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.057 ms/op
Iteration   1: 2.567 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.567 ms/op


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
# Warmup Iteration   1: 11.391 ±(99.9%) 0.204 ms/op
Iteration   1: 8.554 ±(99.9%) 0.147 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.554 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.102 ms/op
Iteration   1: 3.185 ±(99.9%) 0.086 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   7.947 ms/op
                 createUser·p0.999:  46.790 ms/op
                 createUser·p0.9999: 47.055 ms/op
                 createUser·p1.00:   47.055 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10042
  mean =      3.185 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9853 
    [ 5.000, 10.000) = 109 
    [10.000, 15.000) = 48 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      7.947 ms/op
     p(99.9000) =     46.790 ms/op
     p(99.9900) =     47.055 ms/op
     p(99.9990) =     47.055 ms/op
     p(99.9999) =     47.055 ms/op
    p(100.0000) =     47.055 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.197 ms/op
Iteration   1: 1.828 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.477 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  15.368 ms/op
                 existUser·p0.9999: 15.615 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17484
  mean =      1.828 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 705 
    [ 1.250,  2.500) = 15978 
    [ 2.500,  3.750) = 657 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.477 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     15.615 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.132 ms/op
Iteration   1: 2.833 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.761 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.872 ms/op
                 getUser·p0.999:  11.422 ms/op
                 getUser·p0.9999: 12.311 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11430
  mean =      2.833 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 4099 
    [ 2.500,  3.750) = 6522 
    [ 3.750,  5.000) = 697 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.872 ms/op
     p(99.9000) =     11.422 ms/op
     p(99.9900) =     12.311 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


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
# Warmup Iteration   1: 10.766 ±(99.9%) 0.359 ms/op
Iteration   1: 7.959 ±(99.9%) 0.100 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   7.635 ms/op
                 listUser·p0.90:   10.502 ms/op
                 listUser·p0.95:   11.719 ms/op
                 listUser·p0.99:   14.098 ms/op
                 listUser·p0.999:  20.236 ms/op
                 listUser·p0.9999: 26.182 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4054
  mean =      7.959 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 93 
    [ 5.000,  7.500) = 1787 
    [ 7.500, 10.000) = 1631 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      7.635 ms/op
     p(90.0000) =     10.502 ms/op
     p(95.0000) =     11.719 ms/op
     p(99.0000) =     14.098 ms/op
     p(99.9000) =     20.236 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.366          ops/ms
Client.existUser                       thrpt         12.651          ops/ms
Client.getUser                         thrpt          9.116          ops/ms
Client.listUser                        thrpt          4.364          ops/ms
Client.createUser                       avgt          3.026           ms/op
Client.existUser                        avgt          1.928           ms/op
Client.getUser                          avgt          2.567           ms/op
Client.listUser                         avgt          8.554           ms/op
Client.createUser                     sample  10042   3.185 ± 0.086   ms/op
Client.createUser:createUser·p0.00    sample          1.221           ms/op
Client.createUser:createUser·p0.50    sample          3.015           ms/op
Client.createUser:createUser·p0.90    sample          3.617           ms/op
Client.createUser:createUser·p0.95    sample          4.010           ms/op
Client.createUser:createUser·p0.99    sample          7.947           ms/op
Client.createUser:createUser·p0.999   sample         46.790           ms/op
Client.createUser:createUser·p0.9999  sample         47.055           ms/op
Client.createUser:createUser·p1.00    sample         47.055           ms/op
Client.existUser                      sample  17484   1.828 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.551           ms/op
Client.existUser:existUser·p0.50      sample          1.763           ms/op
Client.existUser:existUser·p0.90      sample          2.269           ms/op
Client.existUser:existUser·p0.95      sample          2.477           ms/op
Client.existUser:existUser·p0.99      sample          3.441           ms/op
Client.existUser:existUser·p0.999     sample         15.368           ms/op
Client.existUser:existUser·p0.9999    sample         15.615           ms/op
Client.existUser:existUser·p1.00      sample         16.056           ms/op
Client.getUser                        sample  11430   2.833 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.909           ms/op
Client.getUser:getUser·p0.50          sample          2.761           ms/op
Client.getUser:getUser·p0.90          sample          3.580           ms/op
Client.getUser:getUser·p0.95          sample          3.883           ms/op
Client.getUser:getUser·p0.99          sample          4.872           ms/op
Client.getUser:getUser·p0.999         sample         11.422           ms/op
Client.getUser:getUser·p0.9999        sample         12.311           ms/op
Client.getUser:getUser·p1.00          sample         12.354           ms/op
Client.listUser                       sample   4054   7.959 ± 0.100   ms/op
Client.listUser:listUser·p0.00        sample          1.786           ms/op
Client.listUser:listUser·p0.50        sample          7.635           ms/op
Client.listUser:listUser·p0.90        sample         10.502           ms/op
Client.listUser:listUser·p0.95        sample         11.719           ms/op
Client.listUser:listUser·p0.99        sample         14.098           ms/op
Client.listUser:listUser·p0.999       sample         20.236           ms/op
Client.listUser:listUser·p0.9999      sample         26.182           ms/op
Client.listUser:listUser·p1.00        sample         26.182           ms/op
