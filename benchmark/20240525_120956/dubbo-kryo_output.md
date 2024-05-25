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
# Warmup Iteration   1: 1.208 ops/ms
Iteration   1: 6.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.339 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ops/ms
Iteration   1: 13.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.229 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.850 ops/ms
Iteration   1: 13.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.554 ops/ms


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
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 9.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.181 ops/ms


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.084 ms/op
Iteration   1: 2.248 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.248 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.056 ms/op
Iteration   1: 1.933 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.933 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.059 ms/op
Iteration   1: 1.947 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.947 ms/op


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.114 ms/op
Iteration   1: 3.601 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.601 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.120 ms/op
Iteration   1: 2.228 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   6.711 ms/op
                 createUser·p0.999:  16.704 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14493
  mean =      2.228 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 11918 
    [ 2.500,  3.750) = 2064 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      6.711 ms/op
     p(99.9000) =     16.704 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.077 ms/op
Iteration   1: 1.803 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.290 ms/op
                 existUser·p0.999:  17.671 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17724
  mean =      1.803 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 815 
    [ 1.250,  2.500) = 16097 
    [ 2.500,  3.750) = 687 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.290 ms/op
     p(99.9000) =     17.671 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.086 ms/op
Iteration   1: 2.174 ±(99.9%) 0.078 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   5.299 ms/op
                 getUser·p0.999:  61.866 ms/op
                 getUser·p0.9999: 64.875 ms/op
                 getUser·p1.00:   65.864 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14715
  mean =      2.174 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14564 
    [ 5.000, 10.000) = 87 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      5.299 ms/op
     p(99.9000) =     61.866 ms/op
     p(99.9900) =     64.875 ms/op
     p(99.9990) =     65.864 ms/op
     p(99.9999) =     65.864 ms/op
    p(100.0000) =     65.864 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.118 ms/op
Iteration   1: 3.282 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.871 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 14.221 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9802
  mean =      3.282 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 457 
    [ 2.500,  3.750) = 7431 
    [ 3.750,  5.000) = 1649 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.871 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.339          ops/ms
ClientSimple.existUser                       thrpt         13.229          ops/ms
ClientSimple.getUser                         thrpt         13.554          ops/ms
ClientSimple.listUser                        thrpt          9.181          ops/ms
ClientSimple.createUser                       avgt          2.248           ms/op
ClientSimple.existUser                        avgt          1.933           ms/op
ClientSimple.getUser                          avgt          1.947           ms/op
ClientSimple.listUser                         avgt          3.601           ms/op
ClientSimple.createUser                     sample  14493   2.228 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.483           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.711           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.704           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.055           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.055           ms/op
ClientSimple.existUser                      sample  17724   1.803 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.468           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.290           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.671           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.038           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.038           ms/op
ClientSimple.getUser                        sample  14715   2.174 ± 0.078   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.839           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.299           ms/op
ClientSimple.getUser:getUser·p0.999         sample         61.866           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         64.875           ms/op
ClientSimple.getUser:getUser·p1.00          sample         65.864           ms/op
ClientSimple.listUser                       sample   9802   3.282 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.102           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.015           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.871           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.090           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.221           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.221           ms/op

Benchmark result is saved to 1716638743371.json
