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
# Warmup Iteration   1: 2.569 ops/ms
Iteration   1: 6.357 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.357 ops/ms


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
# Warmup Iteration   1: 5.702 ops/ms
Iteration   1: 12.879 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.879 ops/ms


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
# Warmup Iteration   1: 4.661 ops/ms
Iteration   1: 9.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.463 ops/ms


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
# Warmup Iteration   1: 2.061 ops/ms
Iteration   1: 3.819 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.819 ops/ms


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.092 ms/op
Iteration   1: 2.987 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.987 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.035 ms/op
Iteration   1: 1.746 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.746 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.055 ms/op
Iteration   1: 3.176 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.176 ms/op


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
# Warmup Iteration   1: 12.768 ±(99.9%) 0.240 ms/op
Iteration   1: 8.407 ±(99.9%) 0.158 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.407 ms/op


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
# Warmup Iteration   1: 5.042 ±(99.9%) 0.101 ms/op
Iteration   1: 3.271 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  8.004 ms/op
                 createUser·p0.9999: 8.536 ms/op
                 createUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9777
  mean =      3.271 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 51 
    [2.000, 2.500) = 744 
    [2.500, 3.000) = 2875 
    [3.000, 3.500) = 3518 
    [3.500, 4.000) = 1300 
    [4.000, 4.500) = 791 
    [4.500, 5.000) = 255 
    [5.000, 5.500) = 93 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 39 
    [7.000, 7.500) = 32 
    [7.500, 8.000) = 16 
    [8.000, 8.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =      8.536 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.067 ms/op
Iteration   1: 1.985 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   3.590 ms/op
                 existUser·p0.999:  23.724 ms/op
                 existUser·p0.9999: 24.326 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16180
  mean =      1.985 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14139 
    [ 2.500,  5.000) = 2000 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.590 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     24.326 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.105 ms/op
Iteration   1: 3.197 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  10.156 ms/op
                 getUser·p0.9999: 13.945 ms/op
                 getUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10054
  mean =      3.197 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 1452 
    [ 2.500,  3.750) = 7015 
    [ 3.750,  5.000) = 1217 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.156 ms/op
     p(99.9900) =     13.945 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 14.934 ±(99.9%) 0.682 ms/op
Iteration   1: 7.631 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   3.129 ms/op
                 listUser·p0.50:   7.283 ms/op
                 listUser·p0.90:   9.945 ms/op
                 listUser·p0.95:   11.060 ms/op
                 listUser·p0.99:   15.090 ms/op
                 listUser·p0.999:  18.881 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4198
  mean =      7.631 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 125 
    [ 5.000,  7.500) = 2220 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.129 ms/op
     p(50.0000) =      7.283 ms/op
     p(90.0000) =      9.945 ms/op
     p(95.0000) =     11.060 ms/op
     p(99.0000) =     15.090 ms/op
     p(99.9000) =     18.881 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.357          ops/ms
Client.existUser                       thrpt         12.879          ops/ms
Client.getUser                         thrpt          9.463          ops/ms
Client.listUser                        thrpt          3.819          ops/ms
Client.createUser                       avgt          2.987           ms/op
Client.existUser                        avgt          1.746           ms/op
Client.getUser                          avgt          3.176           ms/op
Client.listUser                         avgt          8.407           ms/op
Client.createUser                     sample   9777   3.271 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.632           ms/op
Client.createUser:createUser·p0.50    sample          3.125           ms/op
Client.createUser:createUser·p0.90    sample          4.162           ms/op
Client.createUser:createUser·p0.95    sample          4.514           ms/op
Client.createUser:createUser·p0.99    sample          6.504           ms/op
Client.createUser:createUser·p0.999   sample          8.004           ms/op
Client.createUser:createUser·p0.9999  sample          8.536           ms/op
Client.createUser:createUser·p1.00    sample          8.536           ms/op
Client.existUser                      sample  16180   1.985 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.621           ms/op
Client.existUser:existUser·p0.50      sample          1.909           ms/op
Client.existUser:existUser·p0.90      sample          2.572           ms/op
Client.existUser:existUser·p0.95      sample          2.781           ms/op
Client.existUser:existUser·p0.99      sample          3.590           ms/op
Client.existUser:existUser·p0.999     sample         23.724           ms/op
Client.existUser:existUser·p0.9999    sample         24.326           ms/op
Client.existUser:existUser·p1.00      sample         24.347           ms/op
Client.getUser                        sample  10054   3.197 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.898           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          4.116           ms/op
Client.getUser:getUser·p0.95          sample          4.628           ms/op
Client.getUser:getUser·p0.99          sample          6.742           ms/op
Client.getUser:getUser·p0.999         sample         10.156           ms/op
Client.getUser:getUser·p0.9999        sample         13.945           ms/op
Client.getUser:getUser·p1.00          sample         13.959           ms/op
Client.listUser                       sample   4198   7.631 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          3.129           ms/op
Client.listUser:listUser·p0.50        sample          7.283           ms/op
Client.listUser:listUser·p0.90        sample          9.945           ms/op
Client.listUser:listUser·p0.95        sample         11.060           ms/op
Client.listUser:listUser·p0.99        sample         15.090           ms/op
Client.listUser:listUser·p0.999       sample         18.881           ms/op
Client.listUser:listUser·p0.9999      sample         20.480           ms/op
Client.listUser:listUser·p1.00        sample         20.480           ms/op
