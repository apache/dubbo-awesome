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
# Warmup Iteration   1: 2.601 ops/ms
Iteration   1: 5.902 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.902 ops/ms


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
# Warmup Iteration   1: 6.718 ops/ms
Iteration   1: 12.019 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.019 ops/ms


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
# Warmup Iteration   1: 4.331 ops/ms
Iteration   1: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.419 ops/ms


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
# Warmup Iteration   1: 2.098 ops/ms
Iteration   1: 4.147 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.147 ops/ms


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
# Warmup Iteration   1: 5.960 ±(99.9%) 0.075 ms/op
Iteration   1: 3.253 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.253 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.039 ms/op
Iteration   1: 1.962 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.962 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.049 ms/op
Iteration   1: 3.061 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.061 ms/op


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
# Warmup Iteration   1: 12.493 ±(99.9%) 0.199 ms/op
Iteration   1: 8.182 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.182 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.104 ms/op
Iteration   1: 3.014 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.871 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 11.811 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10645
  mean =      3.014 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2991 
    [ 2.500,  3.750) = 6651 
    [ 3.750,  5.000) = 749 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     11.811 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.094 ms/op
Iteration   1: 1.846 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.901 ms/op
                 existUser·p0.9999: 6.661 ms/op
                 existUser·p1.00:   6.709 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17308
  mean =      1.846 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 2 
    [0.500, 1.000) = 68 
    [1.000, 1.500) = 3342 
    [1.500, 2.000) = 9566 
    [2.000, 2.500) = 2827 
    [2.500, 3.000) = 1151 
    [3.000, 3.500) = 195 
    [3.500, 4.000) = 53 
    [4.000, 4.500) = 13 
    [4.500, 5.000) = 28 
    [5.000, 5.500) = 21 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =      5.901 ms/op
     p(99.9900) =      6.661 ms/op
     p(99.9990) =      6.709 ms/op
     p(99.9999) =      6.709 ms/op
    p(100.0000) =      6.709 ms/op


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.106 ms/op
Iteration   1: 3.023 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  9.886 ms/op
                 getUser·p0.9999: 10.138 ms/op
                 getUser·p1.00:   10.142 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10582
  mean =      3.023 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 13 
    [ 1.000,  2.000) = 581 
    [ 2.000,  3.000) = 4761 
    [ 3.000,  4.000) = 4543 
    [ 4.000,  5.000) = 536 
    [ 5.000,  6.000) = 64 
    [ 6.000,  7.000) = 48 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 6 
    [ 9.000, 10.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.886 ms/op
     p(99.9900) =     10.138 ms/op
     p(99.9990) =     10.142 ms/op
     p(99.9999) =     10.142 ms/op
    p(100.0000) =     10.142 ms/op


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
# Warmup Iteration   1: 11.433 ±(99.9%) 0.376 ms/op
Iteration   1: 8.132 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   7.725 ms/op
                 listUser·p0.90:   10.830 ms/op
                 listUser·p0.95:   12.091 ms/op
                 listUser·p0.99:   16.885 ms/op
                 listUser·p0.999:  22.519 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3969
  mean =      8.132 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 128 
    [ 5.000,  7.500) = 1631 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      7.725 ms/op
     p(90.0000) =     10.830 ms/op
     p(95.0000) =     12.091 ms/op
     p(99.0000) =     16.885 ms/op
     p(99.9000) =     22.519 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.902          ops/ms
Client.existUser                       thrpt         12.019          ops/ms
Client.getUser                         thrpt          9.419          ops/ms
Client.listUser                        thrpt          4.147          ops/ms
Client.createUser                       avgt          3.253           ms/op
Client.existUser                        avgt          1.962           ms/op
Client.getUser                          avgt          3.061           ms/op
Client.listUser                         avgt          8.182           ms/op
Client.createUser                     sample  10645   3.014 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          0.993           ms/op
Client.createUser:createUser·p0.50    sample          2.871           ms/op
Client.createUser:createUser·p0.90    sample          3.727           ms/op
Client.createUser:createUser·p0.95    sample          4.284           ms/op
Client.createUser:createUser·p0.99    sample          9.175           ms/op
Client.createUser:createUser·p0.999   sample         11.600           ms/op
Client.createUser:createUser·p0.9999  sample         11.811           ms/op
Client.createUser:createUser·p1.00    sample         11.813           ms/op
Client.existUser                      sample  17308   1.846 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.425           ms/op
Client.existUser:existUser·p0.50      sample          1.769           ms/op
Client.existUser:existUser·p0.90      sample          2.441           ms/op
Client.existUser:existUser·p0.95      sample          2.695           ms/op
Client.existUser:existUser·p0.99      sample          3.457           ms/op
Client.existUser:existUser·p0.999     sample          5.901           ms/op
Client.existUser:existUser·p0.9999    sample          6.661           ms/op
Client.existUser:existUser·p1.00      sample          6.709           ms/op
Client.getUser                        sample  10582   3.023 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.820           ms/op
Client.getUser:getUser·p0.50          sample          2.990           ms/op
Client.getUser:getUser·p0.90          sample          3.817           ms/op
Client.getUser:getUser·p0.95          sample          4.162           ms/op
Client.getUser:getUser·p0.99          sample          5.751           ms/op
Client.getUser:getUser·p0.999         sample          9.886           ms/op
Client.getUser:getUser·p0.9999        sample         10.138           ms/op
Client.getUser:getUser·p1.00          sample         10.142           ms/op
Client.listUser                       sample   3969   8.132 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          1.542           ms/op
Client.listUser:listUser·p0.50        sample          7.725           ms/op
Client.listUser:listUser·p0.90        sample         10.830           ms/op
Client.listUser:listUser·p0.95        sample         12.091           ms/op
Client.listUser:listUser·p0.99        sample         16.885           ms/op
Client.listUser:listUser·p0.999       sample         22.519           ms/op
Client.listUser:listUser·p0.9999      sample         26.870           ms/op
Client.listUser:listUser·p1.00        sample         26.870           ms/op
