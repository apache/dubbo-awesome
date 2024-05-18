# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 7.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.534 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.568 ops/ms
Iteration   1: 12.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.383 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.161 ops/ms
Iteration   1: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.877 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ops/ms
Iteration   1: 8.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.954 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ±(99.9%) 0.073 ms/op
Iteration   1: 2.111 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.319 ±(99.9%) 0.058 ms/op
Iteration   1: 1.839 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.245 ±(99.9%) 0.054 ms/op
Iteration   1: 2.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ±(99.9%) 0.072 ms/op
Iteration   1: 3.134 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.088 ms/op
Iteration   1: 2.202 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.079 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  25.313 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14504
  mean =      2.202 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12445 
    [ 2.500,  5.000) = 1927 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =     25.313 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ±(99.9%) 0.075 ms/op
Iteration   1: 1.864 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 13.065 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17157
  mean =      1.864 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 762 
    [ 1.250,  2.500) = 15236 
    [ 2.500,  3.750) = 1008 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.461 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.065 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ±(99.9%) 0.087 ms/op
Iteration   1: 2.142 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  25.756 ms/op
                 getUser·p0.9999: 26.527 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14934
  mean =      2.142 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12692 
    [ 2.500,  5.000) = 2058 
    [ 5.000,  7.500) = 87 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     26.527 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.116 ms/op
Iteration   1: 3.505 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.477 ms/op
                 listUser·p0.99:   5.519 ms/op
                 listUser·p0.999:  6.879 ms/op
                 listUser·p0.9999: 9.224 ms/op
                 listUser·p1.00:   9.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9230
  mean =      3.505 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 13 
    [ 1.500,  2.000) = 41 
    [ 2.000,  2.500) = 536 
    [ 2.500,  3.000) = 1532 
    [ 3.000,  3.500) = 2338 
    [ 3.500,  4.000) = 2823 
    [ 4.000,  4.500) = 1516 
    [ 4.500,  5.000) = 223 
    [ 5.000,  5.500) = 114 
    [ 5.500,  6.000) = 49 
    [ 6.000,  6.500) = 13 
    [ 6.500,  7.000) = 29 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.477 ms/op
     p(99.0000) =      5.519 ms/op
     p(99.9000) =      6.879 ms/op
     p(99.9900) =      9.224 ms/op
     p(99.9990) =      9.224 ms/op
     p(99.9999) =      9.224 ms/op
    p(100.0000) =      9.224 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.534          ops/ms
ClientSimple.existUser                       thrpt         12.383          ops/ms
ClientSimple.getUser                         thrpt         12.877          ops/ms
ClientSimple.listUser                        thrpt          8.954          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          1.839           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.134           ms/op
ClientSimple.createUser                     sample  14504   2.202 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.855           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.079           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.092           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.313           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.821           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.821           ms/op
ClientSimple.existUser                      sample  17157   1.864 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.679           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.461           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.911           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.065           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.206           ms/op
ClientSimple.getUser                        sample  14934   2.142 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.784           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.756           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.527           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.608           ms/op
ClientSimple.listUser                       sample   9230   3.505 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.208           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.523           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.477           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.519           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.879           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.224           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.224           ms/op

Benchmark result is saved to 1715991309138.json
