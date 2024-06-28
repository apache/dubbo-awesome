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
# Warmup Iteration   1: 1.945 ops/ms
Iteration   1: 7.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.249 ops/ms


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
# Warmup Iteration   1: 6.050 ops/ms
Iteration   1: 14.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.467 ops/ms


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
# Warmup Iteration   1: 5.844 ops/ms
Iteration   1: 14.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.496 ops/ms


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
# Warmup Iteration   1: 4.772 ops/ms
Iteration   1: 8.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.655 ops/ms


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.067 ms/op
Iteration   1: 2.199 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.199 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.049 ms/op
Iteration   1: 1.793 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.793 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.061 ms/op
Iteration   1: 1.986 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.986 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.091 ms/op
Iteration   1: 3.258 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.258 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.112 ms/op
Iteration   1: 2.046 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.363 ms/op
                 createUser·p0.95:   2.593 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  15.573 ms/op
                 createUser·p0.9999: 16.697 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15619
  mean =      2.046 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 14577 
    [ 2.500,  3.750) = 770 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     15.573 ms/op
     p(99.9900) =     16.697 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.095 ms/op
Iteration   1: 1.753 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   1.544 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   5.206 ms/op
                 existUser·p0.999:  13.323 ms/op
                 existUser·p0.9999: 13.624 ms/op
                 existUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18224
  mean =      1.753 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 975 
    [ 1.250,  2.500) = 16111 
    [ 2.500,  3.750) = 892 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.544 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      5.206 ms/op
     p(99.9000) =     13.323 ms/op
     p(99.9900) =     13.624 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.091 ms/op
Iteration   1: 2.033 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.328 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.775 ms/op
                 getUser·p0.99:   4.785 ms/op
                 getUser·p0.999:  29.957 ms/op
                 getUser·p0.9999: 30.792 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15789
  mean =      2.033 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14149 
    [ 2.500,  5.000) = 1504 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.775 ms/op
     p(99.0000) =      4.785 ms/op
     p(99.9000) =     29.957 ms/op
     p(99.9900) =     30.792 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.128 ms/op
Iteration   1: 2.861 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   2.593 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   4.628 ms/op
                 listUser·p0.999:  7.583 ms/op
                 listUser·p0.9999: 7.634 ms/op
                 listUser·p1.00:   7.635 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11179
  mean =      2.861 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 28 
    [1.500, 2.000) = 135 
    [2.000, 2.500) = 4011 
    [2.500, 3.000) = 3473 
    [3.000, 3.500) = 1380 
    [3.500, 4.000) = 1448 
    [4.000, 4.500) = 557 
    [4.500, 5.000) = 88 
    [5.000, 5.500) = 26 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.583 ms/op
     p(99.9900) =      7.634 ms/op
     p(99.9990) =      7.635 ms/op
     p(99.9999) =      7.635 ms/op
    p(100.0000) =      7.635 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.249          ops/ms
ClientSimple.existUser                       thrpt         14.467          ops/ms
ClientSimple.getUser                         thrpt         14.496          ops/ms
ClientSimple.listUser                        thrpt          8.655          ops/ms
ClientSimple.createUser                       avgt          2.199           ms/op
ClientSimple.existUser                        avgt          1.793           ms/op
ClientSimple.getUser                          avgt          1.986           ms/op
ClientSimple.listUser                         avgt          3.258           ms/op
ClientSimple.createUser                     sample  15619   2.046 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.974           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.573           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.697           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  18224   1.753 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.544           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.206           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.323           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.624           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.664           ms/op
ClientSimple.getUser                        sample  15789   2.033 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.328           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.775           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.785           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.957           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.792           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.867           ms/op
ClientSimple.listUser                       sample  11179   2.861 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.015           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.593           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.583           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.634           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.635           ms/op

Benchmark result is saved to 1719554751796.json
