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
# Warmup Iteration   1: 2.176 ops/ms
Iteration   1: 6.673 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.673 ops/ms


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
# Warmup Iteration   1: 5.901 ops/ms
Iteration   1: 11.632 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.632 ops/ms


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
# Warmup Iteration   1: 4.152 ops/ms
Iteration   1: 8.939 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.939 ops/ms


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
# Warmup Iteration   1: 2.105 ops/ms
Iteration   1: 3.544 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.544 ops/ms


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
# Warmup Iteration   1: 5.346 ±(99.9%) 0.067 ms/op
Iteration   1: 3.049 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.049 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.037 ms/op
Iteration   1: 2.042 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.066 ms/op
Iteration   1: 2.861 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.861 ms/op


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
# Warmup Iteration   1: 11.936 ±(99.9%) 0.201 ms/op
Iteration   1: 7.897 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.897 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.113 ms/op
Iteration   1: 3.200 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   4.028 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  16.909 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9984
  mean =      3.200 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1801 
    [ 2.500,  3.750) = 6699 
    [ 3.750,  5.000) = 1184 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.028 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.909 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.029 ±(99.9%) 0.082 ms/op
Iteration   1: 1.720 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.387 ms/op
                 existUser·p0.50:   1.585 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.933 ms/op
                 existUser·p0.999:  12.781 ms/op
                 existUser·p0.9999: 12.981 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18629
  mean =      1.720 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 17535 
    [ 2.500,  3.750) = 629 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.933 ms/op
     p(99.9000) =     12.781 ms/op
     p(99.9900) =     12.981 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.117 ms/op
Iteration   1: 2.560 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.244 ms/op
                 getUser·p0.95:   3.497 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 7.756 ms/op
                 getUser·p1.00:   7.774 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12526
  mean =      2.560 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 7 
    [1.000, 1.500) = 84 
    [1.500, 2.000) = 1082 
    [2.000, 2.500) = 5472 
    [2.500, 3.000) = 3584 
    [3.000, 3.500) = 1675 
    [3.500, 4.000) = 436 
    [4.000, 4.500) = 102 
    [4.500, 5.000) = 18 
    [5.000, 5.500) = 19 
    [5.500, 6.000) = 8 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.497 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.475 ms/op
     p(99.9900) =      7.756 ms/op
     p(99.9990) =      7.774 ms/op
     p(99.9999) =      7.774 ms/op
    p(100.0000) =      7.774 ms/op


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
# Warmup Iteration   1: 12.737 ±(99.9%) 0.435 ms/op
Iteration   1: 9.226 ±(99.9%) 0.155 ms/op
                 listUser·p0.00:   3.695 ms/op
                 listUser·p0.50:   8.782 ms/op
                 listUser·p0.90:   12.075 ms/op
                 listUser·p0.95:   13.302 ms/op
                 listUser·p0.99:   20.054 ms/op
                 listUser·p0.999:  25.053 ms/op
                 listUser·p0.9999: 27.492 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3480
  mean =      9.226 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 39 
    [ 5.000,  7.500) = 958 
    [ 7.500, 10.000) = 1364 
    [10.000, 12.500) = 842 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.695 ms/op
     p(50.0000) =      8.782 ms/op
     p(90.0000) =     12.075 ms/op
     p(95.0000) =     13.302 ms/op
     p(99.0000) =     20.054 ms/op
     p(99.9000) =     25.053 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.673          ops/ms
Client.existUser                       thrpt         11.632          ops/ms
Client.getUser                         thrpt          8.939          ops/ms
Client.listUser                        thrpt          3.544          ops/ms
Client.createUser                       avgt          3.049           ms/op
Client.existUser                        avgt          2.042           ms/op
Client.getUser                          avgt          2.861           ms/op
Client.listUser                         avgt          7.897           ms/op
Client.createUser                     sample   9984   3.200 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          1.319           ms/op
Client.createUser:createUser·p0.50    sample          3.052           ms/op
Client.createUser:createUser·p0.90    sample          4.028           ms/op
Client.createUser:createUser·p0.95    sample          4.497           ms/op
Client.createUser:createUser·p0.99    sample          7.791           ms/op
Client.createUser:createUser·p0.999   sample         16.909           ms/op
Client.createUser:createUser·p0.9999  sample         17.727           ms/op
Client.createUser:createUser·p1.00    sample         17.727           ms/op
Client.existUser                      sample  18629   1.720 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.387           ms/op
Client.existUser:existUser·p0.50      sample          1.585           ms/op
Client.existUser:existUser·p0.90      sample          2.216           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          2.933           ms/op
Client.existUser:existUser·p0.999     sample         12.781           ms/op
Client.existUser:existUser·p0.9999    sample         12.981           ms/op
Client.existUser:existUser·p1.00      sample         13.009           ms/op
Client.getUser                        sample  12526   2.560 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          0.591           ms/op
Client.getUser:getUser·p0.50          sample          2.454           ms/op
Client.getUser:getUser·p0.90          sample          3.244           ms/op
Client.getUser:getUser·p0.95          sample          3.497           ms/op
Client.getUser:getUser·p0.99          sample          4.219           ms/op
Client.getUser:getUser·p0.999         sample          7.475           ms/op
Client.getUser:getUser·p0.9999        sample          7.756           ms/op
Client.getUser:getUser·p1.00          sample          7.774           ms/op
Client.listUser                       sample   3480   9.226 ± 0.155   ms/op
Client.listUser:listUser·p0.00        sample          3.695           ms/op
Client.listUser:listUser·p0.50        sample          8.782           ms/op
Client.listUser:listUser·p0.90        sample         12.075           ms/op
Client.listUser:listUser·p0.95        sample         13.302           ms/op
Client.listUser:listUser·p0.99        sample         20.054           ms/op
Client.listUser:listUser·p0.999       sample         25.053           ms/op
Client.listUser:listUser·p0.9999      sample         27.492           ms/op
Client.listUser:listUser·p1.00        sample         27.492           ms/op
