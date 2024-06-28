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
# Warmup Iteration   1: 1.939 ops/ms
Iteration   1: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.908 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.970 ops/ms
Iteration   1: 12.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.644 ops/ms


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
# Warmup Iteration   1: 6.321 ops/ms
Iteration   1: 15.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.132 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ops/ms
Iteration   1: 8.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.885 ops/ms


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.062 ms/op
Iteration   1: 2.264 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.264 ms/op


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.062 ms/op
Iteration   1: 1.967 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.967 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.064 ms/op
Iteration   1: 2.209 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.209 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.078 ms/op
Iteration   1: 3.180 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.180 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.106 ms/op
Iteration   1: 2.010 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   1.804 ms/op
                 createUser·p0.90:   2.392 ms/op
                 createUser·p0.95:   2.572 ms/op
                 createUser·p0.99:   5.719 ms/op
                 createUser·p0.999:  27.414 ms/op
                 createUser·p0.9999: 32.793 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16193
  mean =      2.010 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15122 
    [ 2.500,  5.000) = 882 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      5.719 ms/op
     p(99.9000) =     27.414 ms/op
     p(99.9900) =     32.793 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.081 ms/op
Iteration   1: 2.004 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.581 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  20.677 ms/op
                 existUser·p0.9999: 20.722 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15995
  mean =      2.004 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14770 
    [ 2.500,  5.000) = 1134 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.581 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     20.722 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.072 ms/op
Iteration   1: 2.071 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.048 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.215 ms/op
                 getUser·p0.999:  12.361 ms/op
                 getUser·p0.9999: 13.284 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15543
  mean =      2.071 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 13892 
    [ 2.500,  3.750) = 1449 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.215 ms/op
     p(99.9000) =     12.361 ms/op
     p(99.9900) =     13.284 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.108 ms/op
Iteration   1: 3.375 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.121 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  23.226 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9597
  mean =      3.375 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 9001 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     23.226 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.908          ops/ms
ClientSimple.existUser                       thrpt         12.644          ops/ms
ClientSimple.getUser                         thrpt         15.132          ops/ms
ClientSimple.listUser                        thrpt          8.885          ops/ms
ClientSimple.createUser                       avgt          2.264           ms/op
ClientSimple.existUser                        avgt          1.967           ms/op
ClientSimple.getUser                          avgt          2.209           ms/op
ClientSimple.listUser                         avgt          3.180           ms/op
ClientSimple.createUser                     sample  16193   2.010 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.648           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.804           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.392           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.719           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.414           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.793           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.834           ms/op
ClientSimple.existUser                      sample  15995   2.004 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.470           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.581           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.580           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.677           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.722           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.742           ms/op
ClientSimple.getUser                        sample  15543   2.071 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.936           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.048           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.215           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.361           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.284           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.320           ms/op
ClientSimple.listUser                       sample   9597   3.375 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.952           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.121           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.480           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.226           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.953           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.953           ms/op

Benchmark result is saved to 1719576385965.json
