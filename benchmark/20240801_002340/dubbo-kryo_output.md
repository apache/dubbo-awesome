# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.901 ops/ms
Iteration   1: 6.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.858 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.990 ops/ms
Iteration   1: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.913 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.041 ops/ms
Iteration   1: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.494 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ops/ms
Iteration   1: 9.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.298 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.077 ms/op
Iteration   1: 2.080 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ±(99.9%) 0.051 ms/op
Iteration   1: 1.761 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.461 ±(99.9%) 0.063 ms/op
Iteration   1: 2.129 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.129 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.642 ±(99.9%) 0.096 ms/op
Iteration   1: 3.335 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.118 ms/op
Iteration   1: 1.995 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   1.800 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.728 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  17.234 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16057
  mean =      1.995 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 394 
    [ 1.250,  2.500) = 14383 
    [ 2.500,  3.750) = 882 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     17.234 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ±(99.9%) 0.072 ms/op
Iteration   1: 1.692 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.380 ms/op
                 existUser·p0.50:   1.587 ms/op
                 existUser·p0.90:   2.062 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   2.757 ms/op
                 existUser·p0.999:  12.338 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18953
  mean =      1.692 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 764 
    [ 1.250,  2.500) = 17862 
    [ 2.500,  3.750) = 227 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.380 ms/op
     p(50.0000) =      1.587 ms/op
     p(90.0000) =      2.062 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      2.757 ms/op
     p(99.9000) =     12.338 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.227 ms/op
Iteration   1: 2.156 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.387 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  13.470 ms/op
                 getUser·p0.9999: 13.558 ms/op
                 getUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14841
  mean =      2.156 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 12029 
    [ 2.500,  3.750) = 2357 
    [ 3.750,  5.000) = 261 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.387 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     13.470 ms/op
     p(99.9900) =     13.558 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.024 ±(99.9%) 0.159 ms/op
Iteration   1: 3.617 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.779 ms/op
                 listUser·p0.999:  22.249 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8846
  mean =      3.617 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 745 
    [ 2.500,  5.000) = 7791 
    [ 5.000,  7.500) = 213 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.779 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.858          ops/ms
ClientSimple.existUser                       thrpt         10.913          ops/ms
ClientSimple.getUser                         thrpt         10.494          ops/ms
ClientSimple.listUser                        thrpt          9.298          ops/ms
ClientSimple.createUser                       avgt          2.080           ms/op
ClientSimple.existUser                        avgt          1.761           ms/op
ClientSimple.getUser                          avgt          2.129           ms/op
ClientSimple.listUser                         avgt          3.335           ms/op
ClientSimple.createUser                     sample  16057   1.995 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.557           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.800           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.529           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.234           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.269           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.269           ms/op
ClientSimple.existUser                      sample  18953   1.692 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.380           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.587           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.062           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.338           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.271           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.271           ms/op
ClientSimple.getUser                        sample  14841   2.156 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.504           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.387           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.522           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.470           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.558           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.566           ms/op
ClientSimple.listUser                       sample   8846   3.617 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.900           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.779           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.249           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.413           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.413           ms/op

Benchmark result is saved to 1722471520742.json
