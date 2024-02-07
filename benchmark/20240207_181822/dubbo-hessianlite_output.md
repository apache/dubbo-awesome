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
# Warmup Iteration   1: 2.571 ops/ms
Iteration   1: 5.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.680 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 12.177 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.177 ops/ms


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
# Warmup Iteration   1: 4.546 ops/ms
Iteration   1: 9.200 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.200 ops/ms


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
# Warmup Iteration   1: 2.286 ops/ms
Iteration   1: 3.871 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.871 ops/ms


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
# Warmup Iteration   1: 5.844 ±(99.9%) 0.088 ms/op
Iteration   1: 3.151 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.151 ms/op


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
# Warmup Iteration   1: 3.214 ±(99.9%) 0.032 ms/op
Iteration   1: 1.861 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.055 ms/op
Iteration   1: 3.437 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.437 ms/op


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
# Warmup Iteration   1: 14.146 ±(99.9%) 0.351 ms/op
Iteration   1: 7.835 ±(99.9%) 0.204 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.835 ms/op


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
# Warmup Iteration   1: 4.981 ±(99.9%) 0.134 ms/op
Iteration   1: 2.843 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 15.038 ms/op
                 createUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11238
  mean =      2.843 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 3264 
    [ 2.500,  3.750) = 7135 
    [ 3.750,  5.000) = 493 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     15.038 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 2.866 ±(99.9%) 0.063 ms/op
Iteration   1: 1.608 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.561 ms/op
                 existUser·p0.90:   1.970 ms/op
                 existUser·p0.95:   2.163 ms/op
                 existUser·p0.99:   2.978 ms/op
                 existUser·p0.999:  4.695 ms/op
                 existUser·p0.9999: 5.331 ms/op
                 existUser·p1.00:   5.857 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19878
  mean =      1.608 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 167 
    [1.000, 1.500) = 7655 
    [1.500, 2.000) = 10245 
    [2.000, 2.500) = 1478 
    [2.500, 3.000) = 147 
    [3.000, 3.500) = 83 
    [3.500, 4.000) = 15 
    [4.000, 4.500) = 45 
    [4.500, 5.000) = 33 
    [5.000, 5.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.561 ms/op
     p(90.0000) =      1.970 ms/op
     p(95.0000) =      2.163 ms/op
     p(99.0000) =      2.978 ms/op
     p(99.9000) =      4.695 ms/op
     p(99.9900) =      5.331 ms/op
     p(99.9990) =      5.857 ms/op
     p(99.9999) =      5.857 ms/op
    p(100.0000) =      5.857 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.133 ms/op
Iteration   1: 3.118 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.815 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   9.693 ms/op
                 getUser·p0.999:  15.689 ms/op
                 getUser·p0.9999: 16.089 ms/op
                 getUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10434
  mean =      3.118 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 2397 
    [ 2.500,  3.750) = 6808 
    [ 3.750,  5.000) = 1015 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.815 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      9.693 ms/op
     p(99.9000) =     15.689 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 11.601 ±(99.9%) 0.385 ms/op
Iteration   1: 7.682 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.875 ms/op
                 listUser·p0.50:   7.184 ms/op
                 listUser·p0.90:   9.929 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   20.387 ms/op
                 listUser·p0.999:  27.399 ms/op
                 listUser·p0.9999: 29.164 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4170
  mean =      7.682 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 198 
    [ 5.000,  7.500) = 2195 
    [ 7.500, 10.000) = 1381 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.875 ms/op
     p(50.0000) =      7.184 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     20.387 ms/op
     p(99.9000) =     27.399 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.680          ops/ms
Client.existUser                       thrpt         12.177          ops/ms
Client.getUser                         thrpt          9.200          ops/ms
Client.listUser                        thrpt          3.871          ops/ms
Client.createUser                       avgt          3.151           ms/op
Client.existUser                        avgt          1.861           ms/op
Client.getUser                          avgt          3.437           ms/op
Client.listUser                         avgt          7.835           ms/op
Client.createUser                     sample  11238   2.843 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.558           ms/op
Client.createUser:createUser·p0.50    sample          2.621           ms/op
Client.createUser:createUser·p0.90    sample          3.457           ms/op
Client.createUser:createUser·p0.95    sample          3.887           ms/op
Client.createUser:createUser·p0.99    sample          7.889           ms/op
Client.createUser:createUser·p0.999   sample         14.713           ms/op
Client.createUser:createUser·p0.9999  sample         15.038           ms/op
Client.createUser:createUser·p1.00    sample         15.041           ms/op
Client.existUser                      sample  19878   1.608 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.518           ms/op
Client.existUser:existUser·p0.50      sample          1.561           ms/op
Client.existUser:existUser·p0.90      sample          1.970           ms/op
Client.existUser:existUser·p0.95      sample          2.163           ms/op
Client.existUser:existUser·p0.99      sample          2.978           ms/op
Client.existUser:existUser·p0.999     sample          4.695           ms/op
Client.existUser:existUser·p0.9999    sample          5.331           ms/op
Client.existUser:existUser·p1.00      sample          5.857           ms/op
Client.getUser                        sample  10434   3.118 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          0.863           ms/op
Client.getUser:getUser·p0.50          sample          3.068           ms/op
Client.getUser:getUser·p0.90          sample          3.815           ms/op
Client.getUser:getUser·p0.95          sample          4.149           ms/op
Client.getUser:getUser·p0.99          sample          9.693           ms/op
Client.getUser:getUser·p0.999         sample         15.689           ms/op
Client.getUser:getUser·p0.9999        sample         16.089           ms/op
Client.getUser:getUser·p1.00          sample         16.089           ms/op
Client.listUser                       sample   4170   7.682 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.875           ms/op
Client.listUser:listUser·p0.50        sample          7.184           ms/op
Client.listUser:listUser·p0.90        sample          9.929           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         20.387           ms/op
Client.listUser:listUser·p0.999       sample         27.399           ms/op
Client.listUser:listUser·p0.9999      sample         29.164           ms/op
Client.listUser:listUser·p1.00        sample         29.164           ms/op
