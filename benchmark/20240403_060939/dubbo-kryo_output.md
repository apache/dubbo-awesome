# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.841 ops/ms
Iteration   1: 6.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.171 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.843 ops/ms
Iteration   1: 11.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.515 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
Iteration   1: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.599 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.172 ops/ms
Iteration   1: 8.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.969 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.096 ms/op
Iteration   1: 2.069 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.069 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ±(99.9%) 0.068 ms/op
Iteration   1: 2.262 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.258 ±(99.9%) 0.067 ms/op
Iteration   1: 2.072 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ±(99.9%) 0.127 ms/op
Iteration   1: 3.774 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.774 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.105 ms/op
Iteration   1: 2.418 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.892 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 25.072 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13597
  mean =      2.418 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10163 
    [ 2.500,  5.000) = 3270 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     25.072 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ±(99.9%) 0.116 ms/op
Iteration   1: 2.025 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15818
  mean =      2.025 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 13882 
    [ 2.500,  3.750) = 1419 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ±(99.9%) 0.091 ms/op
Iteration   1: 1.818 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   1.716 ms/op
                 getUser·p0.90:   2.163 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  15.146 ms/op
                 getUser·p0.9999: 15.627 ms/op
                 getUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17587
  mean =      1.818 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1422 
    [ 1.250,  2.500) = 15345 
    [ 2.500,  3.750) = 457 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     15.146 ms/op
     p(99.9900) =     15.627 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.149 ms/op
Iteration   1: 3.683 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  21.933 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8887
  mean =      3.683 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 407 
    [ 2.500,  5.000) = 8098 
    [ 5.000,  7.500) = 310 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     21.933 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.171          ops/ms
ClientSimple.existUser                       thrpt         11.515          ops/ms
ClientSimple.getUser                         thrpt         12.599          ops/ms
ClientSimple.listUser                        thrpt          8.969          ops/ms
ClientSimple.createUser                       avgt          2.069           ms/op
ClientSimple.existUser                        avgt          2.262           ms/op
ClientSimple.getUser                          avgt          2.072           ms/op
ClientSimple.listUser                         avgt          3.774           ms/op
ClientSimple.createUser                     sample  13597   2.418 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.636           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.892           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.138           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.815           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.052           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.072           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.166           ms/op
ClientSimple.existUser                      sample  15818   2.025 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.834           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.697           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.795           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.795           ms/op
ClientSimple.getUser                        sample  17587   1.818 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.617           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.716           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.163           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.603           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.146           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.627           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.876           ms/op
ClientSimple.listUser                       sample   8887   3.683 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.803           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.933           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.101           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.101           ms/op

Benchmark result is saved to 1712124328351.json
