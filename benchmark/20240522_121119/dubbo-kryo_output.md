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
# Warmup Iteration   1: 1.539 ops/ms
Iteration   1: 5.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.473 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.435 ops/ms
Iteration   1: 12.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.019 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.213 ops/ms
Iteration   1: 10.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.797 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.425 ops/ms
Iteration   1: 7.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.646 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.091 ms/op
Iteration   1: 2.507 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.507 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.381 ±(99.9%) 0.074 ms/op
Iteration   1: 2.284 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.284 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ±(99.9%) 0.062 ms/op
Iteration   1: 2.458 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.458 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ±(99.9%) 0.130 ms/op
Iteration   1: 3.540 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.540 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.124 ms/op
Iteration   1: 2.316 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  23.237 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13924
  mean =      2.316 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11409 
    [ 2.500,  5.000) = 2189 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     23.237 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.079 ms/op
Iteration   1: 1.739 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   2.953 ms/op
                 existUser·p0.999:  16.384 ms/op
                 existUser·p0.9999: 16.850 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18804
  mean =      1.739 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2129 
    [ 1.250,  2.500) = 15759 
    [ 2.500,  3.750) = 845 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     16.850 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.437 ±(99.9%) 0.094 ms/op
Iteration   1: 1.918 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   1.634 ms/op
                 getUser·p0.90:   2.756 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   4.748 ms/op
                 getUser·p0.999:  24.247 ms/op
                 getUser·p0.9999: 25.299 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17040
  mean =      1.918 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14528 
    [ 2.500,  5.000) = 2388 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.756 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      4.748 ms/op
     p(99.9000) =     24.247 ms/op
     p(99.9900) =     25.299 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.131 ms/op
Iteration   1: 3.412 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  18.271 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9403
  mean =      3.412 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 789 
    [ 2.500,  3.750) = 5840 
    [ 3.750,  5.000) = 2495 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     18.271 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.473          ops/ms
ClientSimple.existUser                       thrpt         12.019          ops/ms
ClientSimple.getUser                         thrpt         10.797          ops/ms
ClientSimple.listUser                        thrpt          7.646          ops/ms
ClientSimple.createUser                       avgt          2.507           ms/op
ClientSimple.existUser                        avgt          2.284           ms/op
ClientSimple.getUser                          avgt          2.458           ms/op
ClientSimple.listUser                         avgt          3.540           ms/op
ClientSimple.createUser                     sample  13924   2.316 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.523           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.011           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.052           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.052           ms/op
ClientSimple.existUser                      sample  18804   1.739 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.467           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.628           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.953           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.384           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.850           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.990           ms/op
ClientSimple.getUser                        sample  17040   1.918 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.624           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.634           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.756           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.748           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.247           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.299           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.461           ms/op
ClientSimple.listUser                       sample   9403   3.412 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.719           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.382           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.271           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.776           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.776           ms/op

Benchmark result is saved to 1716379614611.json
