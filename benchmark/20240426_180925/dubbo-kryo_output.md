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
# Warmup Iteration   1: 1.980 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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
# Warmup Iteration   1: 5.854 ops/ms
Iteration   1: 13.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.353 ops/ms


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
# Warmup Iteration   1: 5.971 ops/ms
Iteration   1: 11.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.583 ops/ms


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
# Warmup Iteration   1: 4.717 ops/ms
Iteration   1: 7.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.938 ops/ms


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.060 ms/op
Iteration   1: 2.420 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.420 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.059 ms/op
Iteration   1: 1.842 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.842 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.056 ms/op
Iteration   1: 1.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.848 ms/op


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.079 ms/op
Iteration   1: 3.351 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.351 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.089 ms/op
Iteration   1: 1.837 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   1.640 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.650 ms/op
                 createUser·p0.99:   5.862 ms/op
                 createUser·p0.999:  13.216 ms/op
                 createUser·p0.9999: 14.714 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17369
  mean =      1.837 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 785 
    [ 1.250,  2.500) = 15146 
    [ 2.500,  3.750) = 1206 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      5.862 ms/op
     p(99.9000) =     13.216 ms/op
     p(99.9900) =     14.714 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.063 ms/op
Iteration   1: 2.125 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.407 ms/op
                 existUser·p0.50:   2.048 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.863 ms/op
                 existUser·p0.99:   3.313 ms/op
                 existUser·p0.999:  30.147 ms/op
                 existUser·p0.9999: 32.242 ms/op
                 existUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15072
  mean =      2.125 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12559 
    [ 2.500,  5.000) = 2441 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.313 ms/op
     p(99.9000) =     30.147 ms/op
     p(99.9900) =     32.242 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.071 ms/op
Iteration   1: 1.867 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   3.301 ms/op
                 getUser·p0.999:  10.123 ms/op
                 getUser·p0.9999: 11.330 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17125
  mean =      1.867 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1219 
    [ 1.250,  2.500) = 14657 
    [ 2.500,  3.750) = 1157 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.301 ms/op
     p(99.9000) =     10.123 ms/op
     p(99.9900) =     11.330 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.189 ms/op
Iteration   1: 3.267 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.384 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  37.618 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9795
  mean =      3.267 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 797 
    [ 2.500,  5.000) = 8745 
    [ 5.000,  7.500) = 209 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.384 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     37.618 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.868          ops/ms
ClientSimple.existUser                       thrpt         13.353          ops/ms
ClientSimple.getUser                         thrpt         11.583          ops/ms
ClientSimple.listUser                        thrpt          7.938          ops/ms
ClientSimple.createUser                       avgt          2.420           ms/op
ClientSimple.existUser                        avgt          1.842           ms/op
ClientSimple.getUser                          avgt          1.848           ms/op
ClientSimple.listUser                         avgt          3.351           ms/op
ClientSimple.createUser                     sample  17369   1.837 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.640           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.862           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.216           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.714           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.876           ms/op
ClientSimple.existUser                      sample  15072   2.125 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.407           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.863           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.313           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.147           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.242           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.342           ms/op
ClientSimple.getUser                        sample  17125   1.867 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.464           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.301           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.123           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.330           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.878           ms/op
ClientSimple.listUser                       sample   9795   3.267 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.384           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.529           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.814           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.814           ms/op

Benchmark result is saved to 1714154691818.json
