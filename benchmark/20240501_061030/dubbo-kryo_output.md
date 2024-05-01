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
# Warmup Iteration   1: 1.688 ops/ms
Iteration   1: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.882 ops/ms


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
# Warmup Iteration   1: 5.375 ops/ms
Iteration   1: 11.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.585 ops/ms


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
# Warmup Iteration   1: 4.998 ops/ms
Iteration   1: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.762 ops/ms


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
# Warmup Iteration   1: 4.482 ops/ms
Iteration   1: 8.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.758 ops/ms


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.082 ms/op
Iteration   1: 1.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.993 ms/op


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
# Warmup Iteration   1: 2.999 ±(99.9%) 0.049 ms/op
Iteration   1: 1.892 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.063 ms/op
Iteration   1: 1.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.078 ms/op
Iteration   1: 2.874 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.874 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.078 ms/op
Iteration   1: 2.228 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.732 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  16.421 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14343
  mean =      2.228 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 10976 
    [ 2.500,  3.750) = 2934 
    [ 3.750,  5.000) = 147 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     16.421 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 2.952 ±(99.9%) 0.069 ms/op
Iteration   1: 1.858 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.243 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 16.191 ms/op
                 existUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17200
  mean =      1.858 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 16351 
    [ 2.500,  3.750) = 579 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.243 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     16.191 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.077 ms/op
Iteration   1: 1.896 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   1.745 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   5.172 ms/op
                 getUser·p0.999:  21.009 ms/op
                 getUser·p0.9999: 21.265 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16861
  mean =      1.896 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15781 
    [ 2.500,  5.000) = 901 
    [ 5.000,  7.500) = 104 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      5.172 ms/op
     p(99.9000) =     21.009 ms/op
     p(99.9900) =     21.265 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.108 ms/op
Iteration   1: 3.199 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.138 ms/op
                 listUser·p0.999:  7.677 ms/op
                 listUser·p0.9999: 10.240 ms/op
                 listUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9991
  mean =      3.199 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 68 
    [ 2.000,  3.000) = 5331 
    [ 3.000,  4.000) = 3346 
    [ 4.000,  5.000) = 1128 
    [ 5.000,  6.000) = 43 
    [ 6.000,  7.000) = 19 
    [ 7.000,  8.000) = 49 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.138 ms/op
     p(99.9000) =      7.677 ms/op
     p(99.9900) =     10.240 ms/op
     p(99.9990) =     10.240 ms/op
     p(99.9999) =     10.240 ms/op
    p(100.0000) =     10.240 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.882          ops/ms
ClientSimple.existUser                       thrpt         11.585          ops/ms
ClientSimple.getUser                         thrpt         12.762          ops/ms
ClientSimple.listUser                        thrpt          8.758          ops/ms
ClientSimple.createUser                       avgt          1.993           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          2.874           ms/op
ClientSimple.createUser                     sample  14343   2.228 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.308           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.421           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.366           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  17200   1.858 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.718           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.767           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.222           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.191           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.286           ms/op
ClientSimple.getUser                        sample  16861   1.896 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.644           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.745           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.172           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.009           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.265           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.332           ms/op
ClientSimple.listUser                       sample   9991   3.199 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.826           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.138           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.677           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.240           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.240           ms/op

Benchmark result is saved to 1714543565392.json
