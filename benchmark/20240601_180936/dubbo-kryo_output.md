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
# Warmup Iteration   1: 1.813 ops/ms
Iteration   1: 6.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.440 ops/ms


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
# Warmup Iteration   1: 5.809 ops/ms
Iteration   1: 16.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  16.411 ops/ms


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
# Warmup Iteration   1: 5.699 ops/ms
Iteration   1: 11.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.838 ops/ms


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
# Warmup Iteration   1: 4.704 ops/ms
Iteration   1: 8.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.693 ops/ms


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.068 ms/op
Iteration   1: 2.101 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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
# Warmup Iteration   1: 2.976 ±(99.9%) 0.042 ms/op
Iteration   1: 1.697 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.697 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.071 ms/op
Iteration   1: 1.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.832 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.088 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.006 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.075 ms/op
Iteration   1: 2.220 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.590 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   9.724 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14515
  mean =      2.220 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 12568 
    [ 2.500,  3.750) = 1203 
    [ 3.750,  5.000) = 235 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      9.724 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.084 ms/op
Iteration   1: 1.753 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  11.821 ms/op
                 existUser·p0.9999: 12.211 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18389
  mean =      1.753 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 599 
    [ 1.250,  2.500) = 16758 
    [ 2.500,  3.750) = 918 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.412 ms/op
     p(99.9000) =     11.821 ms/op
     p(99.9900) =     12.211 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.079 ms/op
Iteration   1: 1.946 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.277 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  25.461 ms/op
                 getUser·p0.9999: 26.130 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16421
  mean =      1.946 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15574 
    [ 2.500,  5.000) = 647 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     26.130 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.122 ms/op
Iteration   1: 3.575 ±(99.9%) 0.072 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.745 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  33.491 ms/op
                 listUser·p0.9999: 36.569 ms/op
                 listUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8974
  mean =      3.575 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 775 
    [ 2.500,  5.000) = 7870 
    [ 5.000,  7.500) = 210 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.745 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     33.491 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.440          ops/ms
ClientSimple.existUser                       thrpt         16.411          ops/ms
ClientSimple.getUser                         thrpt         11.838          ops/ms
ClientSimple.listUser                        thrpt          8.693          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.697           ms/op
ClientSimple.getUser                          avgt          1.832           ms/op
ClientSimple.listUser                         avgt          3.006           ms/op
ClientSimple.createUser                     sample  14515   2.220 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.590           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.109           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.724           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.367           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  18389   1.753 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.559           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.412           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.821           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.211           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.239           ms/op
ClientSimple.getUser                        sample  16421   1.946 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.327           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.792           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.461           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.130           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.214           ms/op
ClientSimple.listUser                       sample   8974   3.575 ± 0.072   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.745           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.938           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.491           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.569           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.569           ms/op

Benchmark result is saved to 1717265112423.json
