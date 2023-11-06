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
# Warmup Iteration   1: 1.632 ops/ms
Iteration   1: 4.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.235 ops/ms


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
# Warmup Iteration   1: 4.302 ops/ms
Iteration   1: 11.209 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.209 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.444 ops/ms
Iteration   1: 3.266 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.266 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.227 ops/ms
Iteration   1: 1.886 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.886 ops/ms


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
# Warmup Iteration   1: 9.227 ±(99.9%) 0.149 ms/op
Iteration   1: 5.138 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.138 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.548 ±(99.9%) 0.143 ms/op
Iteration   1: 2.670 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.670 ms/op


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
# Warmup Iteration   1: 8.515 ±(99.9%) 0.120 ms/op
Iteration   1: 3.483 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.483 ms/op


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
# Warmup Iteration   1: 20.537 ±(99.9%) 0.383 ms/op
Iteration   1: 16.645 ±(99.9%) 0.298 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.645 ms/op


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
# Warmup Iteration   1: 7.871 ±(99.9%) 0.235 ms/op
Iteration   1: 3.268 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   14.065 ms/op
                 createUser·p0.999:  32.467 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9910
  mean =      3.268 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3611 
    [ 2.500,  5.000) = 5318 
    [ 5.000,  7.500) = 685 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =     14.065 ms/op
     p(99.9000) =     32.467 ms/op
     p(99.9900) =     32.768 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 5.822 ±(99.9%) 0.163 ms/op
Iteration   1: 2.197 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   4.736 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 24.715 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14568
  mean =      2.197 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12505 
    [ 2.500,  5.000) = 1364 
    [ 5.000,  7.500) = 309 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      4.736 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     24.715 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 8.320 ±(99.9%) 0.245 ms/op
Iteration   1: 4.184 ±(99.9%) 0.107 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   7.389 ms/op
                 getUser·p0.99:   14.347 ms/op
                 getUser·p0.999:  40.436 ms/op
                 getUser·p0.9999: 40.501 ms/op
                 getUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7666
  mean =      4.184 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6823 
    [ 5.000, 10.000) = 709 
    [10.000, 15.000) = 68 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     14.347 ms/op
     p(99.9000) =     40.436 ms/op
     p(99.9900) =     40.501 ms/op
     p(99.9990) =     40.501 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 21.519 ±(99.9%) 0.762 ms/op
Iteration   1: 13.581 ±(99.9%) 0.270 ms/op
                 listUser·p0.00:   4.514 ms/op
                 listUser·p0.50:   12.485 ms/op
                 listUser·p0.90:   18.927 ms/op
                 listUser·p0.95:   21.103 ms/op
                 listUser·p0.99:   28.406 ms/op
                 listUser·p0.999:  31.857 ms/op
                 listUser·p0.9999: 32.113 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2403
  mean =     13.581 ±(99.9%) 0.270 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 900 
    [12.500, 15.000) = 518 
    [15.000, 17.500) = 320 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.514 ms/op
     p(50.0000) =     12.485 ms/op
     p(90.0000) =     18.927 ms/op
     p(95.0000) =     21.103 ms/op
     p(99.0000) =     28.406 ms/op
     p(99.9000) =     31.857 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.235          ops/ms
Client.existUser                       thrpt         11.209          ops/ms
Client.getUser                         thrpt          3.266          ops/ms
Client.listUser                        thrpt          1.886          ops/ms
Client.createUser                       avgt          5.138           ms/op
Client.existUser                        avgt          2.670           ms/op
Client.getUser                          avgt          3.483           ms/op
Client.listUser                         avgt         16.645           ms/op
Client.createUser                     sample   9910   3.268 ± 0.078   ms/op
Client.createUser:createUser·p0.00    sample          1.266           ms/op
Client.createUser:createUser·p0.50    sample          2.638           ms/op
Client.createUser:createUser·p0.90    sample          4.997           ms/op
Client.createUser:createUser·p0.95    sample          6.365           ms/op
Client.createUser:createUser·p0.99    sample         14.065           ms/op
Client.createUser:createUser·p0.999   sample         32.467           ms/op
Client.createUser:createUser·p0.9999  sample         32.768           ms/op
Client.createUser:createUser·p1.00    sample         32.768           ms/op
Client.existUser                      sample  14568   2.197 ± 0.054   ms/op
Client.existUser:existUser·p0.00      sample          0.696           ms/op
Client.existUser:existUser·p0.50      sample          1.712           ms/op
Client.existUser:existUser·p0.90      sample          3.068           ms/op
Client.existUser:existUser·p0.95      sample          4.736           ms/op
Client.existUser:existUser·p0.99      sample         11.567           ms/op
Client.existUser:existUser·p0.999     sample         20.611           ms/op
Client.existUser:existUser·p0.9999    sample         24.715           ms/op
Client.existUser:existUser·p1.00      sample         24.969           ms/op
Client.getUser                        sample   7666   4.184 ± 0.107   ms/op
Client.getUser:getUser·p0.00          sample          1.182           ms/op
Client.getUser:getUser·p0.50          sample          3.707           ms/op
Client.getUser:getUser·p0.90          sample          5.267           ms/op
Client.getUser:getUser·p0.95          sample          7.389           ms/op
Client.getUser:getUser·p0.99          sample         14.347           ms/op
Client.getUser:getUser·p0.999         sample         40.436           ms/op
Client.getUser:getUser·p0.9999        sample         40.501           ms/op
Client.getUser:getUser·p1.00          sample         40.501           ms/op
Client.listUser                       sample   2403  13.581 ± 0.270   ms/op
Client.listUser:listUser·p0.00        sample          4.514           ms/op
Client.listUser:listUser·p0.50        sample         12.485           ms/op
Client.listUser:listUser·p0.90        sample         18.927           ms/op
Client.listUser:listUser·p0.95        sample         21.103           ms/op
Client.listUser:listUser·p0.99        sample         28.406           ms/op
Client.listUser:listUser·p0.999       sample         31.857           ms/op
Client.listUser:listUser·p0.9999      sample         32.113           ms/op
Client.listUser:listUser·p1.00        sample         32.113           ms/op
