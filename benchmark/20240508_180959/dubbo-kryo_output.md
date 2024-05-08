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
# Warmup Iteration   1: 1.990 ops/ms
Iteration   1: 7.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.096 ops/ms


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
# Warmup Iteration   1: 6.743 ops/ms
Iteration   1: 13.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.551 ops/ms


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
# Warmup Iteration   1: 5.321 ops/ms
Iteration   1: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.695 ops/ms


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
# Warmup Iteration   1: 5.593 ops/ms
Iteration   1: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.402 ops/ms


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.065 ms/op
Iteration   1: 2.254 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.254 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.072 ms/op
Iteration   1: 1.615 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.615 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.052 ms/op
Iteration   1: 1.756 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.756 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.094 ms/op
Iteration   1: 3.602 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.602 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.097 ms/op
Iteration   1: 2.248 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 20.363 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14199
  mean =      2.248 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11532 
    [ 2.500,  5.000) = 2439 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     20.363 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 2.940 ±(99.9%) 0.077 ms/op
Iteration   1: 2.270 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.258 ms/op
                 existUser·p0.50:   2.224 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   4.461 ms/op
                 existUser·p0.999:  17.629 ms/op
                 existUser·p0.9999: 17.897 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14072
  mean =      2.270 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 10704 
    [ 2.500,  3.750) = 2816 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.258 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.461 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     17.897 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.073 ms/op
Iteration   1: 2.061 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.425 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  17.315 ms/op
                 getUser·p0.9999: 17.671 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15599
  mean =      2.061 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 13190 
    [ 2.500,  3.750) = 1992 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     17.315 ms/op
     p(99.9900) =     17.671 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.128 ms/op
Iteration   1: 3.291 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.252 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.953 ms/op
                 listUser·p0.999:  19.295 ms/op
                 listUser·p0.9999: 28.246 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9719
  mean =      3.291 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1880 
    [ 2.500,  5.000) = 7613 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.953 ms/op
     p(99.9000) =     19.295 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.096          ops/ms
ClientSimple.existUser                       thrpt         13.551          ops/ms
ClientSimple.getUser                         thrpt         12.695          ops/ms
ClientSimple.listUser                        thrpt          8.402          ops/ms
ClientSimple.createUser                       avgt          2.254           ms/op
ClientSimple.existUser                        avgt          1.615           ms/op
ClientSimple.getUser                          avgt          1.756           ms/op
ClientSimple.listUser                         avgt          3.602           ms/op
ClientSimple.createUser                     sample  14199   2.248 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.344           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.111           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.547           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.363           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.037           ms/op
ClientSimple.existUser                      sample  14072   2.270 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.258           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.461           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.629           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.897           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.924           ms/op
ClientSimple.getUser                        sample  15599   2.061 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.425           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.325           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.315           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.671           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.891           ms/op
ClientSimple.listUser                       sample   9719   3.291 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.785           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.252           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.953           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.295           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.246           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.246           ms/op

Benchmark result is saved to 1715191554795.json
