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
# Warmup Iteration   1: 1.748 ops/ms
Iteration   1: 7.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.066 ops/ms


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
# Warmup Iteration   1: 7.036 ops/ms
Iteration   1: 14.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.269 ops/ms


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
# Warmup Iteration   1: 6.769 ops/ms
Iteration   1: 14.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.952 ops/ms


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
# Warmup Iteration   1: 4.677 ops/ms
Iteration   1: 8.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.739 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.062 ms/op
Iteration   1: 2.288 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.288 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.027 ±(99.9%) 0.046 ms/op
Iteration   1: 1.726 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.726 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.337 ±(99.9%) 0.060 ms/op
Iteration   1: 2.188 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.188 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.546 ±(99.9%) 0.093 ms/op
Iteration   1: 3.474 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.474 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.591 ±(99.9%) 0.099 ms/op
Iteration   1: 2.338 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.543 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.388 ms/op
                 createUser·p0.99:   4.640 ms/op
                 createUser·p0.999:  14.776 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14114
  mean =      2.338 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 205 
    [ 1.250,  2.500) = 9349 
    [ 2.500,  3.750) = 4268 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.388 ms/op
     p(99.0000) =      4.640 ms/op
     p(99.9000) =     14.776 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.025 ±(99.9%) 0.070 ms/op
Iteration   1: 1.857 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   4.234 ms/op
                 existUser·p0.999:  22.701 ms/op
                 existUser·p0.9999: 23.671 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17219
  mean =      1.857 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15665 
    [ 2.500,  5.000) = 1399 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      4.234 ms/op
     p(99.9000) =     22.701 ms/op
     p(99.9900) =     23.671 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.073 ms/op
Iteration   1: 1.933 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.310 ms/op
                 getUser·p0.95:   2.511 ms/op
                 getUser·p0.99:   3.285 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16549
  mean =      1.933 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 324 
    [ 1.250,  2.500) = 15367 
    [ 2.500,  3.750) = 737 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.285 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.113 ms/op
Iteration   1: 3.182 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.085 ms/op
                 listUser·p0.999:  13.793 ms/op
                 listUser·p0.9999: 16.448 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10114
  mean =      3.182 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 436 
    [ 2.500,  3.750) = 7978 
    [ 3.750,  5.000) = 1483 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.085 ms/op
     p(99.9000) =     13.793 ms/op
     p(99.9900) =     16.448 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.066          ops/ms
ClientSimple.existUser                       thrpt         14.269          ops/ms
ClientSimple.getUser                         thrpt         14.952          ops/ms
ClientSimple.listUser                        thrpt          8.739          ops/ms
ClientSimple.createUser                       avgt          2.288           ms/op
ClientSimple.existUser                        avgt          1.726           ms/op
ClientSimple.getUser                          avgt          2.188           ms/op
ClientSimple.listUser                         avgt          3.474           ms/op
ClientSimple.createUser                     sample  14114   2.338 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.543           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.138           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.388           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.640           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.776           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.860           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.860           ms/op
ClientSimple.existUser                      sample  17219   1.857 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.234           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.701           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.671           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.790           ms/op
ClientSimple.getUser                        sample  16549   1.933 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.658           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.285           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.005           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.268           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.268           ms/op
ClientSimple.listUser                       sample  10114   3.182 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.803           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.085           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.793           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.448           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.466           ms/op

Benchmark result is saved to 1716509754820.json
