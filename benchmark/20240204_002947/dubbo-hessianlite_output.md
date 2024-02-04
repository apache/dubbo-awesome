# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.132 ops/ms
Iteration   1: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.163 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.041 ops/ms
Iteration   1: 11.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.695 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ops/ms
Iteration   1: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.793 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.432 ops/ms
Iteration   1: 3.703 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.703 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ±(99.9%) 0.072 ms/op
Iteration   1: 2.876 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.237 ±(99.9%) 0.031 ms/op
Iteration   1: 1.886 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ±(99.9%) 0.050 ms/op
Iteration   1: 2.886 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.429 ±(99.9%) 0.229 ms/op
Iteration   1: 8.119 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.119 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.121 ms/op
Iteration   1: 3.196 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.214 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10012
  mean =      3.196 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 2184 
    [ 2.500,  3.750) = 6158 
    [ 3.750,  5.000) = 1364 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.214 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     12.206 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.451 ±(99.9%) 0.086 ms/op
Iteration   1: 1.921 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.453 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.168 ms/op
                 existUser·p0.999:  6.030 ms/op
                 existUser·p0.9999: 6.693 ms/op
                 existUser·p1.00:   6.726 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16644
  mean =      1.921 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 66 
    [1.000, 1.500) = 3710 
    [1.500, 2.000) = 6078 
    [2.000, 2.500) = 5188 
    [2.500, 3.000) = 1376 
    [3.000, 3.500) = 93 
    [3.500, 4.000) = 19 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 38 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.168 ms/op
     p(99.9000) =      6.030 ms/op
     p(99.9900) =      6.693 ms/op
     p(99.9990) =      6.726 ms/op
     p(99.9999) =      6.726 ms/op
    p(100.0000) =      6.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.105 ms/op
Iteration   1: 3.135 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   4.965 ms/op
                 getUser·p0.999:  5.920 ms/op
                 getUser·p0.9999: 6.873 ms/op
                 getUser·p1.00:   6.881 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10196
  mean =      3.135 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 140 
    [2.000, 2.500) = 1232 
    [2.500, 3.000) = 2897 
    [3.000, 3.500) = 3422 
    [3.500, 4.000) = 1811 
    [4.000, 4.500) = 401 
    [4.500, 5.000) = 170 
    [5.000, 5.500) = 76 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.965 ms/op
     p(99.9000) =      5.920 ms/op
     p(99.9900) =      6.873 ms/op
     p(99.9990) =      6.881 ms/op
     p(99.9999) =      6.881 ms/op
    p(100.0000) =      6.881 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.601 ±(99.9%) 0.396 ms/op
Iteration   1: 7.634 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   7.348 ms/op
                 listUser·p0.90:   9.650 ms/op
                 listUser·p0.95:   10.946 ms/op
                 listUser·p0.99:   18.013 ms/op
                 listUser·p0.999:  23.652 ms/op
                 listUser·p0.9999: 30.671 ms/op
                 listUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4228
  mean =      7.634 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 160 
    [ 5.000,  7.500) = 2160 
    [ 7.500, 10.000) = 1568 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      7.348 ms/op
     p(90.0000) =      9.650 ms/op
     p(95.0000) =     10.946 ms/op
     p(99.0000) =     18.013 ms/op
     p(99.9000) =     23.652 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.163          ops/ms
Client.existUser                       thrpt         11.695          ops/ms
Client.getUser                         thrpt          7.793          ops/ms
Client.listUser                        thrpt          3.703          ops/ms
Client.createUser                       avgt          2.876           ms/op
Client.existUser                        avgt          1.886           ms/op
Client.getUser                          avgt          2.886           ms/op
Client.listUser                         avgt          8.119           ms/op
Client.createUser                     sample  10012   3.196 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.818           ms/op
Client.createUser:createUser·p0.50    sample          3.039           ms/op
Client.createUser:createUser·p0.90    sample          3.916           ms/op
Client.createUser:createUser·p0.95    sample          4.214           ms/op
Client.createUser:createUser·p0.99    sample          9.175           ms/op
Client.createUser:createUser·p0.999   sample         12.009           ms/op
Client.createUser:createUser·p0.9999  sample         12.206           ms/op
Client.createUser:createUser·p1.00    sample         12.206           ms/op
Client.existUser                      sample  16644   1.921 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.453           ms/op
Client.existUser:existUser·p0.50      sample          1.909           ms/op
Client.existUser:existUser·p0.90      sample          2.494           ms/op
Client.existUser:existUser·p0.95      sample          2.630           ms/op
Client.existUser:existUser·p0.99      sample          3.168           ms/op
Client.existUser:existUser·p0.999     sample          6.030           ms/op
Client.existUser:existUser·p0.9999    sample          6.693           ms/op
Client.existUser:existUser·p1.00      sample          6.726           ms/op
Client.getUser                        sample  10196   3.135 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.952           ms/op
Client.getUser:getUser·p0.50          sample          3.125           ms/op
Client.getUser:getUser·p0.90          sample          3.834           ms/op
Client.getUser:getUser·p0.95          sample          4.145           ms/op
Client.getUser:getUser·p0.99          sample          4.965           ms/op
Client.getUser:getUser·p0.999         sample          5.920           ms/op
Client.getUser:getUser·p0.9999        sample          6.873           ms/op
Client.getUser:getUser·p1.00          sample          6.881           ms/op
Client.listUser                       sample   4228   7.634 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          1.915           ms/op
Client.listUser:listUser·p0.50        sample          7.348           ms/op
Client.listUser:listUser·p0.90        sample          9.650           ms/op
Client.listUser:listUser·p0.95        sample         10.946           ms/op
Client.listUser:listUser·p0.99        sample         18.013           ms/op
Client.listUser:listUser·p0.999       sample         23.652           ms/op
Client.listUser:listUser·p0.9999      sample         30.671           ms/op
Client.listUser:listUser·p1.00        sample         30.671           ms/op
