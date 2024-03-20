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
# Warmup Iteration   1: 1.664 ops/ms
Iteration   1: 6.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.657 ops/ms


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
# Warmup Iteration   1: 5.830 ops/ms
Iteration   1: 13.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.063 ops/ms


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
# Warmup Iteration   1: 6.393 ops/ms
Iteration   1: 13.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.888 ops/ms


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
# Warmup Iteration   1: 5.209 ops/ms
Iteration   1: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.163 ops/ms


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.072 ms/op
Iteration   1: 2.093 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.093 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.047 ms/op
Iteration   1: 1.698 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.698 ms/op


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
# Warmup Iteration   1: 2.940 ±(99.9%) 0.065 ms/op
Iteration   1: 2.244 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.244 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.111 ms/op
Iteration   1: 3.507 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.507 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.100 ms/op
Iteration   1: 2.376 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   2.236 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 23.024 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13499
  mean =      2.376 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9829 
    [ 2.500,  5.000) = 3472 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     23.024 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 2.776 ±(99.9%) 0.064 ms/op
Iteration   1: 1.927 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.708 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  28.894 ms/op
                 existUser·p0.9999: 29.329 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16618
  mean =      1.927 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14964 
    [ 2.500,  5.000) = 1605 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.708 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =     28.894 ms/op
     p(99.9900) =     29.329 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.078 ms/op
Iteration   1: 1.874 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.236 ms/op
                 getUser·p0.95:   2.396 ms/op
                 getUser·p0.99:   3.092 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 12.534 ms/op
                 getUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17097
  mean =      1.874 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 16348 
    [ 2.500,  3.750) = 507 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.092 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     12.534 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.147 ms/op
Iteration   1: 3.205 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 8.602 ms/op
                 listUser·p1.00:   8.602 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9986
  mean =      3.205 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 173 
    [2.000, 2.500) = 2050 
    [2.500, 3.000) = 1833 
    [3.000, 3.500) = 2225 
    [3.500, 4.000) = 2590 
    [4.000, 4.500) = 747 
    [4.500, 5.000) = 192 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =      8.602 ms/op
     p(99.9990) =      8.602 ms/op
     p(99.9999) =      8.602 ms/op
    p(100.0000) =      8.602 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.657          ops/ms
ClientSimple.existUser                       thrpt         13.063          ops/ms
ClientSimple.getUser                         thrpt         13.888          ops/ms
ClientSimple.listUser                        thrpt          8.163          ops/ms
ClientSimple.createUser                       avgt          2.093           ms/op
ClientSimple.existUser                        avgt          1.698           ms/op
ClientSimple.getUser                          avgt          2.244           ms/op
ClientSimple.listUser                         avgt          3.507           ms/op
ClientSimple.createUser                     sample  13499   2.376 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.563           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.236           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.291           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.741           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.024           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.036           ms/op
ClientSimple.existUser                      sample  16618   1.927 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.639           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.708           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.568           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.894           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.329           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.590           ms/op
ClientSimple.getUser                        sample  17097   1.874 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.092           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.288           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.534           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.534           ms/op
ClientSimple.listUser                       sample   9986   3.205 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.034           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.431           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.569           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.602           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.602           ms/op

Benchmark result is saved to 1710957891428.json
