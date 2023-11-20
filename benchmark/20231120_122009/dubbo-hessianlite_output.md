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
# Warmup Iteration   1: 2.675 ops/ms
Iteration   1: 6.125 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.125 ops/ms


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
# Warmup Iteration   1: 6.639 ops/ms
Iteration   1: 13.938 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.938 ops/ms


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
# Warmup Iteration   1: 4.835 ops/ms
Iteration   1: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.586 ops/ms


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
# Warmup Iteration   1: 2.365 ops/ms
Iteration   1: 4.028 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.028 ops/ms


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
# Warmup Iteration   1: 6.249 ±(99.9%) 0.113 ms/op
Iteration   1: 3.260 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.260 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.042 ms/op
Iteration   1: 1.816 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.816 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.062 ms/op
Iteration   1: 3.085 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.085 ms/op


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
# Warmup Iteration   1: 14.152 ±(99.9%) 0.586 ms/op
Iteration   1: 8.347 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.347 ms/op


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.107 ms/op
Iteration   1: 3.152 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.531 ms/op
                 createUser·p0.999:  13.777 ms/op
                 createUser·p0.9999: 13.860 ms/op
                 createUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10139
  mean =      3.152 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3046 
    [ 2.500,  3.750) = 5025 
    [ 3.750,  5.000) = 1667 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.531 ms/op
     p(99.9000) =     13.777 ms/op
     p(99.9900) =     13.860 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 2.809 ±(99.9%) 0.049 ms/op
Iteration   1: 1.833 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   4.214 ms/op
                 existUser·p0.999:  23.349 ms/op
                 existUser·p0.9999: 23.725 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17456
  mean =      1.833 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16752 
    [ 2.500,  5.000) = 594 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      4.214 ms/op
     p(99.9000) =     23.349 ms/op
     p(99.9900) =     23.725 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.096 ms/op
Iteration   1: 2.733 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.344 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.376 ms/op
                 getUser·p0.999:  23.047 ms/op
                 getUser·p0.9999: 23.434 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11674
  mean =      2.733 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5254 
    [ 2.500,  5.000) = 6277 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.344 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.376 ms/op
     p(99.9000) =     23.047 ms/op
     p(99.9900) =     23.434 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 11.252 ±(99.9%) 0.385 ms/op
Iteration   1: 7.998 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   7.610 ms/op
                 listUser·p0.90:   11.223 ms/op
                 listUser·p0.95:   12.147 ms/op
                 listUser·p0.99:   13.894 ms/op
                 listUser·p0.999:  17.215 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3991
  mean =      7.998 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 14 
    [ 3.750,  5.000) = 210 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 1080 
    [ 7.500,  8.750) = 854 
    [ 8.750, 10.000) = 477 
    [10.000, 11.250) = 358 
    [11.250, 12.500) = 260 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      7.610 ms/op
     p(90.0000) =     11.223 ms/op
     p(95.0000) =     12.147 ms/op
     p(99.0000) =     13.894 ms/op
     p(99.9000) =     17.215 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.125          ops/ms
Client.existUser                       thrpt         13.938          ops/ms
Client.getUser                         thrpt          9.586          ops/ms
Client.listUser                        thrpt          4.028          ops/ms
Client.createUser                       avgt          3.260           ms/op
Client.existUser                        avgt          1.816           ms/op
Client.getUser                          avgt          3.085           ms/op
Client.listUser                         avgt          8.347           ms/op
Client.createUser                     sample  10139   3.152 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.221           ms/op
Client.createUser:createUser·p0.50    sample          2.896           ms/op
Client.createUser:createUser·p0.90    sample          4.375           ms/op
Client.createUser:createUser·p0.95    sample          4.784           ms/op
Client.createUser:createUser·p0.99    sample          6.531           ms/op
Client.createUser:createUser·p0.999   sample         13.777           ms/op
Client.createUser:createUser·p0.9999  sample         13.860           ms/op
Client.createUser:createUser·p1.00    sample         13.861           ms/op
Client.existUser                      sample  17456   1.833 ± 0.030   ms/op
Client.existUser:existUser·p0.00      sample          0.592           ms/op
Client.existUser:existUser·p0.50      sample          1.698           ms/op
Client.existUser:existUser·p0.90      sample          2.183           ms/op
Client.existUser:existUser·p0.95      sample          2.413           ms/op
Client.existUser:existUser·p0.99      sample          4.214           ms/op
Client.existUser:existUser·p0.999     sample         23.349           ms/op
Client.existUser:existUser·p0.9999    sample         23.725           ms/op
Client.existUser:existUser·p1.00      sample         23.822           ms/op
Client.getUser                        sample  11674   2.733 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.714           ms/op
Client.getUser:getUser·p0.50          sample          2.535           ms/op
Client.getUser:getUser·p0.90          sample          3.344           ms/op
Client.getUser:getUser·p0.95          sample          3.625           ms/op
Client.getUser:getUser·p0.99          sample          5.376           ms/op
Client.getUser:getUser·p0.999         sample         23.047           ms/op
Client.getUser:getUser·p0.9999        sample         23.434           ms/op
Client.getUser:getUser·p1.00          sample         23.462           ms/op
Client.listUser                       sample   3991   7.998 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.087           ms/op
Client.listUser:listUser·p0.50        sample          7.610           ms/op
Client.listUser:listUser·p0.90        sample         11.223           ms/op
Client.listUser:listUser·p0.95        sample         12.147           ms/op
Client.listUser:listUser·p0.99        sample         13.894           ms/op
Client.listUser:listUser·p0.999       sample         17.215           ms/op
Client.listUser:listUser·p0.9999      sample         19.661           ms/op
Client.listUser:listUser·p1.00        sample         19.661           ms/op
