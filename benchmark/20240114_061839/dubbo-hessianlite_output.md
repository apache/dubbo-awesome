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
# Warmup Iteration   1: 2.583 ops/ms
Iteration   1: 6.872 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.872 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 12.199 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.199 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ops/ms
Iteration   1: 8.453 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.453 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
Iteration   1: 3.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.387 ops/ms


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.060 ms/op
Iteration   1: 3.064 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.064 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.031 ms/op
Iteration   1: 1.991 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.991 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.042 ms/op
Iteration   1: 3.028 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.028 ms/op


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
# Warmup Iteration   1: 12.900 ±(99.9%) 0.263 ms/op
Iteration   1: 8.633 ±(99.9%) 0.119 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.633 ms/op


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
# Warmup Iteration   1: 5.203 ±(99.9%) 0.118 ms/op
Iteration   1: 3.136 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 23.158 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10200
  mean =      3.136 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1971 
    [ 2.500,  5.000) = 7904 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     23.158 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.060 ms/op
Iteration   1: 1.820 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.034 ms/op
                 existUser·p0.999:  3.844 ms/op
                 existUser·p0.9999: 5.736 ms/op
                 existUser·p1.00:   5.997 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17564
  mean =      1.820 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 16 
    [1.000, 1.500) = 2004 
    [1.500, 2.000) = 11805 
    [2.000, 2.500) = 3041 
    [2.500, 3.000) = 516 
    [3.000, 3.500) = 136 
    [3.500, 4.000) = 31 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.034 ms/op
     p(99.9000) =      3.844 ms/op
     p(99.9900) =      5.736 ms/op
     p(99.9990) =      5.997 ms/op
     p(99.9999) =      5.997 ms/op
    p(100.0000) =      5.997 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.097 ms/op
Iteration   1: 3.166 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  20.476 ms/op
                 getUser·p0.9999: 20.839 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10135
  mean =      3.166 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2790 
    [ 2.500,  5.000) = 7145 
    [ 5.000,  7.500) = 136 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     20.476 ms/op
     p(99.9900) =     20.839 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 12.289 ±(99.9%) 0.316 ms/op
Iteration   1: 8.610 ±(99.9%) 0.147 ms/op
                 listUser·p0.00:   3.535 ms/op
                 listUser·p0.50:   8.143 ms/op
                 listUser·p0.90:   11.043 ms/op
                 listUser·p0.95:   12.599 ms/op
                 listUser·p0.99:   19.929 ms/op
                 listUser·p0.999:  29.126 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3789
  mean =      8.610 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51 
    [ 5.000,  7.500) = 1228 
    [ 7.500, 10.000) = 1839 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.535 ms/op
     p(50.0000) =      8.143 ms/op
     p(90.0000) =     11.043 ms/op
     p(95.0000) =     12.599 ms/op
     p(99.0000) =     19.929 ms/op
     p(99.9000) =     29.126 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.872          ops/ms
Client.existUser                       thrpt         12.199          ops/ms
Client.getUser                         thrpt          8.453          ops/ms
Client.listUser                        thrpt          3.387          ops/ms
Client.createUser                       avgt          3.064           ms/op
Client.existUser                        avgt          1.991           ms/op
Client.getUser                          avgt          3.028           ms/op
Client.listUser                         avgt          8.633           ms/op
Client.createUser                     sample  10200   3.136 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          0.962           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          4.153           ms/op
Client.createUser:createUser·p0.95    sample          4.571           ms/op
Client.createUser:createUser·p0.99    sample         10.191           ms/op
Client.createUser:createUser·p0.999   sample         21.627           ms/op
Client.createUser:createUser·p0.9999  sample         23.158           ms/op
Client.createUser:createUser·p1.00    sample         23.167           ms/op
Client.existUser                      sample  17564   1.820 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.755           ms/op
Client.existUser:existUser·p0.50      sample          1.772           ms/op
Client.existUser:existUser·p0.90      sample          2.183           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          3.034           ms/op
Client.existUser:existUser·p0.999     sample          3.844           ms/op
Client.existUser:existUser·p0.9999    sample          5.736           ms/op
Client.existUser:existUser·p1.00      sample          5.997           ms/op
Client.getUser                        sample  10135   3.166 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          1.061           ms/op
Client.getUser:getUser·p0.50          sample          3.125           ms/op
Client.getUser:getUser·p0.90          sample          3.863           ms/op
Client.getUser:getUser·p0.95          sample          4.137           ms/op
Client.getUser:getUser·p0.99          sample          6.111           ms/op
Client.getUser:getUser·p0.999         sample         20.476           ms/op
Client.getUser:getUser·p0.9999        sample         20.839           ms/op
Client.getUser:getUser·p1.00          sample         20.840           ms/op
Client.listUser                       sample   3789   8.610 ± 0.147   ms/op
Client.listUser:listUser·p0.00        sample          3.535           ms/op
Client.listUser:listUser·p0.50        sample          8.143           ms/op
Client.listUser:listUser·p0.90        sample         11.043           ms/op
Client.listUser:listUser·p0.95        sample         12.599           ms/op
Client.listUser:listUser·p0.99        sample         19.929           ms/op
Client.listUser:listUser·p0.999       sample         29.126           ms/op
Client.listUser:listUser·p0.9999      sample         32.539           ms/op
Client.listUser:listUser·p1.00        sample         32.539           ms/op
