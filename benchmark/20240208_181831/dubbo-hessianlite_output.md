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
# Warmup Iteration   1: 2.127 ops/ms
Iteration   1: 6.018 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.018 ops/ms


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
# Warmup Iteration   1: 6.309 ops/ms
Iteration   1: 13.180 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.180 ops/ms


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
# Warmup Iteration   1: 4.595 ops/ms
Iteration   1: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.401 ops/ms


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
# Warmup Iteration   1: 1.965 ops/ms
Iteration   1: 3.572 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.572 ops/ms


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
# Warmup Iteration   1: 5.586 ±(99.9%) 0.077 ms/op
Iteration   1: 3.269 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.269 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.052 ms/op
Iteration   1: 1.750 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.750 ms/op


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.098 ms/op
Iteration   1: 3.219 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.219 ms/op


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
# Warmup Iteration   1: 13.222 ±(99.9%) 0.271 ms/op
Iteration   1: 9.127 ±(99.9%) 0.150 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.127 ms/op


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.145 ms/op
Iteration   1: 3.035 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.867 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  11.168 ms/op
                 createUser·p0.9999: 11.631 ms/op
                 createUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10577
  mean =      3.035 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 3125 
    [ 2.500,  3.750) = 6124 
    [ 3.750,  5.000) = 1068 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     11.168 ms/op
     p(99.9900) =     11.631 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


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
# Warmup Iteration   1: 2.863 ±(99.9%) 0.062 ms/op
Iteration   1: 2.008 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.161 ms/op
                 existUser·p0.999:  6.318 ms/op
                 existUser·p0.9999: 7.211 ms/op
                 existUser·p1.00:   8.176 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15917
  mean =      2.008 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 66 
    [1.000, 1.500) = 1551 
    [1.500, 2.000) = 6251 
    [2.000, 2.500) = 6496 
    [2.500, 3.000) = 1331 
    [3.000, 3.500) = 110 
    [3.500, 4.000) = 45 
    [4.000, 4.500) = 10 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.161 ms/op
     p(99.9000) =      6.318 ms/op
     p(99.9900) =      7.211 ms/op
     p(99.9990) =      8.176 ms/op
     p(99.9999) =      8.176 ms/op
    p(100.0000) =      8.176 ms/op


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.117 ms/op
Iteration   1: 2.956 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   2.879 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.020 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 10.543 ms/op
                 getUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10873
  mean =      2.956 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 367 
    [ 2.000,  3.000) = 5858 
    [ 3.000,  4.000) = 4131 
    [ 4.000,  5.000) = 408 
    [ 5.000,  6.000) = 44 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 32 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.020 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     10.543 ms/op
     p(99.9990) =     10.568 ms/op
     p(99.9999) =     10.568 ms/op
    p(100.0000) =     10.568 ms/op


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
# Warmup Iteration   1: 12.471 ±(99.9%) 0.423 ms/op
Iteration   1: 7.937 ±(99.9%) 0.157 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   10.191 ms/op
                 listUser·p0.95:   11.905 ms/op
                 listUser·p0.99:   21.037 ms/op
                 listUser·p0.999:  31.981 ms/op
                 listUser·p0.9999: 33.817 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4007
  mean =      7.937 ±(99.9%) 0.157 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 204 
    [ 5.000,  7.500) = 1793 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =     10.191 ms/op
     p(95.0000) =     11.905 ms/op
     p(99.0000) =     21.037 ms/op
     p(99.9000) =     31.981 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.018          ops/ms
Client.existUser                       thrpt         13.180          ops/ms
Client.getUser                         thrpt          8.401          ops/ms
Client.listUser                        thrpt          3.572          ops/ms
Client.createUser                       avgt          3.269           ms/op
Client.existUser                        avgt          1.750           ms/op
Client.getUser                          avgt          3.219           ms/op
Client.listUser                         avgt          9.127           ms/op
Client.createUser                     sample  10577   3.035 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.106           ms/op
Client.createUser:createUser·p0.50    sample          2.867           ms/op
Client.createUser:createUser·p0.90    sample          3.908           ms/op
Client.createUser:createUser·p0.95    sample          4.268           ms/op
Client.createUser:createUser·p0.99    sample          7.184           ms/op
Client.createUser:createUser·p0.999   sample         11.168           ms/op
Client.createUser:createUser·p0.9999  sample         11.631           ms/op
Client.createUser:createUser·p1.00    sample         11.633           ms/op
Client.existUser                      sample  15917   2.008 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.346           ms/op
Client.existUser:existUser·p0.50      sample          2.005           ms/op
Client.existUser:existUser·p0.90      sample          2.494           ms/op
Client.existUser:existUser·p0.95      sample          2.638           ms/op
Client.existUser:existUser·p0.99      sample          3.161           ms/op
Client.existUser:existUser·p0.999     sample          6.318           ms/op
Client.existUser:existUser·p0.9999    sample          7.211           ms/op
Client.existUser:existUser·p1.00      sample          8.176           ms/op
Client.getUser                        sample  10873   2.956 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.030           ms/op
Client.getUser:getUser·p0.50          sample          2.879           ms/op
Client.getUser:getUser·p0.90          sample          3.727           ms/op
Client.getUser:getUser·p0.95          sample          3.977           ms/op
Client.getUser:getUser·p0.99          sample          5.020           ms/op
Client.getUser:getUser·p0.999         sample          9.716           ms/op
Client.getUser:getUser·p0.9999        sample         10.543           ms/op
Client.getUser:getUser·p1.00          sample         10.568           ms/op
Client.listUser                       sample   4007   7.937 ± 0.157   ms/op
Client.listUser:listUser·p0.00        sample          1.882           ms/op
Client.listUser:listUser·p0.50        sample          7.504           ms/op
Client.listUser:listUser·p0.90        sample         10.191           ms/op
Client.listUser:listUser·p0.95        sample         11.905           ms/op
Client.listUser:listUser·p0.99        sample         21.037           ms/op
Client.listUser:listUser·p0.999       sample         31.981           ms/op
Client.listUser:listUser·p0.9999      sample         33.817           ms/op
Client.listUser:listUser·p1.00        sample         33.817           ms/op
