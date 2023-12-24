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
# Warmup Iteration   1: 2.435 ops/ms
Iteration   1: 5.965 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.965 ops/ms


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
# Warmup Iteration   1: 6.148 ops/ms
Iteration   1: 12.559 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.559 ops/ms


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
# Warmup Iteration   1: 4.707 ops/ms
Iteration   1: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.261 ops/ms


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
# Warmup Iteration   1: 1.957 ops/ms
Iteration   1: 3.244 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.244 ops/ms


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
# Warmup Iteration   1: 5.870 ±(99.9%) 0.087 ms/op
Iteration   1: 3.266 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.266 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.037 ms/op
Iteration   1: 1.755 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.079 ms/op
Iteration   1: 3.422 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.422 ms/op


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
# Warmup Iteration   1: 13.771 ±(99.9%) 0.292 ms/op
Iteration   1: 9.738 ±(99.9%) 0.146 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.738 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.102 ms/op
Iteration   1: 3.116 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.847 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   10.296 ms/op
                 createUser·p0.999:  16.052 ms/op
                 createUser·p0.9999: 16.187 ms/op
                 createUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10258
  mean =      3.116 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 3186 
    [ 2.500,  3.750) = 5475 
    [ 3.750,  5.000) = 1163 
    [ 5.000,  6.250) = 173 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =     10.296 ms/op
     p(99.9000) =     16.052 ms/op
     p(99.9900) =     16.187 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 2.966 ±(99.9%) 0.066 ms/op
Iteration   1: 1.638 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   1.483 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   2.952 ms/op
                 existUser·p0.999:  3.981 ms/op
                 existUser·p0.9999: 4.677 ms/op
                 existUser·p1.00:   5.538 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19723
  mean =      1.638 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 249 
    [1.000, 1.500) = 10177 
    [1.500, 2.000) = 5321 
    [2.000, 2.500) = 2841 
    [2.500, 3.000) = 980 
    [3.000, 3.500) = 112 
    [3.500, 4.000) = 24 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.483 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      2.952 ms/op
     p(99.9000) =      3.981 ms/op
     p(99.9900) =      4.677 ms/op
     p(99.9990) =      5.538 ms/op
     p(99.9999) =      5.538 ms/op
    p(100.0000) =      5.538 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.116 ms/op
Iteration   1: 3.383 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.553 ms/op
                 getUser·p0.999:  7.860 ms/op
                 getUser·p0.9999: 9.781 ms/op
                 getUser·p1.00:   9.781 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9504
  mean =      3.383 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 28 
    [ 1.000,  2.000) = 156 
    [ 2.000,  3.000) = 2753 
    [ 3.000,  4.000) = 4906 
    [ 4.000,  5.000) = 1485 
    [ 5.000,  6.000) = 125 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.553 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =      9.781 ms/op
     p(99.9990) =      9.781 ms/op
     p(99.9999) =      9.781 ms/op
    p(100.0000) =      9.781 ms/op


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
# Warmup Iteration   1: 13.260 ±(99.9%) 0.504 ms/op
Iteration   1: 8.569 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   8.389 ms/op
                 listUser·p0.90:   11.197 ms/op
                 listUser·p0.95:   12.386 ms/op
                 listUser·p0.99:   14.123 ms/op
                 listUser·p0.999:  20.478 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3775
  mean =      8.569 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 1152 
    [ 7.500, 10.000) = 1814 
    [10.000, 12.500) = 576 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.761 ms/op
     p(50.0000) =      8.389 ms/op
     p(90.0000) =     11.197 ms/op
     p(95.0000) =     12.386 ms/op
     p(99.0000) =     14.123 ms/op
     p(99.9000) =     20.478 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.965          ops/ms
Client.existUser                       thrpt         12.559          ops/ms
Client.getUser                         thrpt          8.261          ops/ms
Client.listUser                        thrpt          3.244          ops/ms
Client.createUser                       avgt          3.266           ms/op
Client.existUser                        avgt          1.755           ms/op
Client.getUser                          avgt          3.422           ms/op
Client.listUser                         avgt          9.738           ms/op
Client.createUser                     sample  10258   3.116 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          2.847           ms/op
Client.createUser:createUser·p0.90    sample          4.137           ms/op
Client.createUser:createUser·p0.95    sample          4.735           ms/op
Client.createUser:createUser·p0.99    sample         10.296           ms/op
Client.createUser:createUser·p0.999   sample         16.052           ms/op
Client.createUser:createUser·p0.9999  sample         16.187           ms/op
Client.createUser:createUser·p1.00    sample         16.187           ms/op
Client.existUser                      sample  19723   1.638 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.582           ms/op
Client.existUser:existUser·p0.50      sample          1.483           ms/op
Client.existUser:existUser·p0.90      sample          2.306           ms/op
Client.existUser:existUser·p0.95      sample          2.568           ms/op
Client.existUser:existUser·p0.99      sample          2.952           ms/op
Client.existUser:existUser·p0.999     sample          3.981           ms/op
Client.existUser:existUser·p0.9999    sample          4.677           ms/op
Client.existUser:existUser·p1.00      sample          5.538           ms/op
Client.getUser                        sample   9504   3.383 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.417           ms/op
Client.getUser:getUser·p0.50          sample          3.318           ms/op
Client.getUser:getUser·p0.90          sample          4.252           ms/op
Client.getUser:getUser·p0.95          sample          4.563           ms/op
Client.getUser:getUser·p0.99          sample          5.553           ms/op
Client.getUser:getUser·p0.999         sample          7.860           ms/op
Client.getUser:getUser·p0.9999        sample          9.781           ms/op
Client.getUser:getUser·p1.00          sample          9.781           ms/op
Client.listUser                       sample   3775   8.569 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.761           ms/op
Client.listUser:listUser·p0.50        sample          8.389           ms/op
Client.listUser:listUser·p0.90        sample         11.197           ms/op
Client.listUser:listUser·p0.95        sample         12.386           ms/op
Client.listUser:listUser·p0.99        sample         14.123           ms/op
Client.listUser:listUser·p0.999       sample         20.478           ms/op
Client.listUser:listUser·p0.9999      sample         23.822           ms/op
Client.listUser:listUser·p1.00        sample         23.822           ms/op
