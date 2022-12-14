# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.054 ops/ms
Iteration   1: 2.522 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.522 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
Iteration   1: 5.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.597 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.163 ops/ms
Iteration   1: 4.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.606 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.757 ops/ms
Iteration   1: 1.117 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.117 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 19.646 ±(99.9%) 0.315 ms/op
Iteration   1: 8.092 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.092 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.232 ±(99.9%) 0.121 ms/op
Iteration   1: 4.424 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.424 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.914 ±(99.9%) 0.189 ms/op
Iteration   1: 4.407 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.407 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.870 ±(99.9%) 0.407 ms/op
Iteration   1: 17.232 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.232 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.509 ±(99.9%) 0.549 ms/op
Iteration   1: 7.601 ±(99.9%) 0.132 ms/op
                 createUser·p0.00:   3.068 ms/op
                 createUser·p0.50:   7.152 ms/op
                 createUser·p0.90:   8.233 ms/op
                 createUser·p0.95:   10.158 ms/op
                 createUser·p0.99:   19.005 ms/op
                 createUser·p0.999:  29.557 ms/op
                 createUser·p0.9999: 29.590 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4222
  mean =      7.601 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 94 
    [ 5.000,  7.500) = 2866 
    [ 7.500, 10.000) = 1048 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.068 ms/op
     p(50.0000) =      7.152 ms/op
     p(90.0000) =      8.233 ms/op
     p(95.0000) =     10.158 ms/op
     p(99.0000) =     19.005 ms/op
     p(99.9000) =     29.557 ms/op
     p(99.9900) =     29.590 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.228 ms/op
Iteration   1: 4.527 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.083 ms/op
                 existUser·p0.99:   16.222 ms/op
                 existUser·p0.999:  33.554 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7109
  mean =      4.527 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 6349 
    [ 5.000,  7.500) = 347 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.083 ms/op
     p(99.0000) =     16.222 ms/op
     p(99.9000) =     33.554 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.572 ±(99.9%) 0.392 ms/op
Iteration   1: 4.769 ±(99.9%) 0.078 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   12.839 ms/op
                 getUser·p0.999:  25.826 ms/op
                 getUser·p0.9999: 47.383 ms/op
                 getUser·p1.00:   47.383 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6837
  mean =      4.769 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5485 
    [ 5.000, 10.000) = 1269 
    [10.000, 15.000) = 19 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =     12.839 ms/op
     p(99.9000) =     25.826 ms/op
     p(99.9900) =     47.383 ms/op
     p(99.9990) =     47.383 ms/op
     p(99.9999) =     47.383 ms/op
    p(100.0000) =     47.383 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 31.249 ±(99.9%) 1.301 ms/op
Iteration   1: 19.806 ±(99.9%) 0.382 ms/op
                 listUser·p0.00:   8.307 ms/op
                 listUser·p0.50:   18.383 ms/op
                 listUser·p0.90:   26.070 ms/op
                 listUser·p0.95:   30.212 ms/op
                 listUser·p0.99:   41.615 ms/op
                 listUser·p0.999:  50.315 ms/op
                 listUser·p0.9999: 51.446 ms/op
                 listUser·p1.00:   51.446 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1615
  mean =     19.806 ±(99.9%) 0.382 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 11 
    [10.000, 15.000) = 54 
    [15.000, 20.000) = 1228 
    [20.000, 25.000) = 129 
    [25.000, 30.000) = 104 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 14 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      8.307 ms/op
     p(50.0000) =     18.383 ms/op
     p(90.0000) =     26.070 ms/op
     p(95.0000) =     30.212 ms/op
     p(99.0000) =     41.615 ms/op
     p(99.9000) =     50.315 ms/op
     p(99.9900) =     51.446 ms/op
     p(99.9990) =     51.446 ms/op
     p(99.9999) =     51.446 ms/op
    p(100.0000) =     51.446 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.522          ops/ms
Client.existUser                       thrpt         5.597          ops/ms
Client.getUser                         thrpt         4.606          ops/ms
Client.listUser                        thrpt         1.117          ops/ms
Client.createUser                       avgt         8.092           ms/op
Client.existUser                        avgt         4.424           ms/op
Client.getUser                          avgt         4.407           ms/op
Client.listUser                         avgt        17.232           ms/op
Client.createUser                     sample  4222   7.601 ± 0.132   ms/op
Client.createUser:createUser·p0.00    sample         3.068           ms/op
Client.createUser:createUser·p0.50    sample         7.152           ms/op
Client.createUser:createUser·p0.90    sample         8.233           ms/op
Client.createUser:createUser·p0.95    sample        10.158           ms/op
Client.createUser:createUser·p0.99    sample        19.005           ms/op
Client.createUser:createUser·p0.999   sample        29.557           ms/op
Client.createUser:createUser·p0.9999  sample        29.590           ms/op
Client.createUser:createUser·p1.00    sample        29.590           ms/op
Client.existUser                      sample  7109   4.527 ± 0.095   ms/op
Client.existUser:existUser·p0.00      sample         1.626           ms/op
Client.existUser:existUser·p0.50      sample         4.448           ms/op
Client.existUser:existUser·p0.90      sample         4.948           ms/op
Client.existUser:existUser·p0.95      sample         5.083           ms/op
Client.existUser:existUser·p0.99      sample        16.222           ms/op
Client.existUser:existUser·p0.999     sample        33.554           ms/op
Client.existUser:existUser·p0.9999    sample        33.948           ms/op
Client.existUser:existUser·p1.00      sample        33.948           ms/op
Client.getUser                        sample  6837   4.769 ± 0.078   ms/op
Client.getUser:getUser·p0.00          sample         1.473           ms/op
Client.getUser:getUser·p0.50          sample         4.473           ms/op
Client.getUser:getUser·p0.90          sample         5.505           ms/op
Client.getUser:getUser·p0.95          sample         6.046           ms/op
Client.getUser:getUser·p0.99          sample        12.839           ms/op
Client.getUser:getUser·p0.999         sample        25.826           ms/op
Client.getUser:getUser·p0.9999        sample        47.383           ms/op
Client.getUser:getUser·p1.00          sample        47.383           ms/op
Client.listUser                       sample  1615  19.806 ± 0.382   ms/op
Client.listUser:listUser·p0.00        sample         8.307           ms/op
Client.listUser:listUser·p0.50        sample        18.383           ms/op
Client.listUser:listUser·p0.90        sample        26.070           ms/op
Client.listUser:listUser·p0.95        sample        30.212           ms/op
Client.listUser:listUser·p0.99        sample        41.615           ms/op
Client.listUser:listUser·p0.999       sample        50.315           ms/op
Client.listUser:listUser·p0.9999      sample        51.446           ms/op
Client.listUser:listUser·p1.00        sample        51.446           ms/op
