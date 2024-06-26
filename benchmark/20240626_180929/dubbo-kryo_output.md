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
# Warmup Iteration   1: 1.621 ops/ms
Iteration   1: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.749 ops/ms


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
# Warmup Iteration   1: 4.815 ops/ms
Iteration   1: 12.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.096 ops/ms


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
# Warmup Iteration   1: 5.305 ops/ms
Iteration   1: 11.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.144 ops/ms


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
# Warmup Iteration   1: 4.131 ops/ms
Iteration   1: 8.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.816 ops/ms


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.065 ms/op
Iteration   1: 2.281 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.281 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.056 ms/op
Iteration   1: 1.809 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.809 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.056 ms/op
Iteration   1: 1.861 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.096 ms/op
Iteration   1: 3.944 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.944 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.084 ms/op
Iteration   1: 2.151 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  20.086 ms/op
                 createUser·p0.9999: 23.383 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14866
  mean =      2.151 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12695 
    [ 2.500,  5.000) = 1938 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     20.086 ms/op
     p(99.9900) =     23.383 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 2.748 ±(99.9%) 0.067 ms/op
Iteration   1: 2.055 ±(99.9%) 0.071 ms/op
                 existUser·p0.00:   0.266 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  49.734 ms/op
                 existUser·p0.9999: 53.914 ms/op
                 existUser·p1.00:   55.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15556
  mean =      2.055 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15416 
    [ 5.000, 10.000) = 40 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     49.734 ms/op
     p(99.9900) =     53.914 ms/op
     p(99.9990) =     55.116 ms/op
     p(99.9999) =     55.116 ms/op
    p(100.0000) =     55.116 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.071 ms/op
Iteration   1: 1.850 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   1.772 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.458 ms/op
                 getUser·p0.99:   3.465 ms/op
                 getUser·p0.999:  10.937 ms/op
                 getUser·p0.9999: 11.293 ms/op
                 getUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17459
  mean =      1.850 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 430 
    [ 1.250,  2.500) = 16262 
    [ 2.500,  3.750) = 604 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =     10.937 ms/op
     p(99.9900) =     11.293 ms/op
     p(99.9990) =     11.403 ms/op
     p(99.9999) =     11.403 ms/op
    p(100.0000) =     11.403 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.139 ms/op
Iteration   1: 3.422 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  10.529 ms/op
                 listUser·p0.9999: 11.338 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9340
  mean =      3.422 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 926 
    [ 2.500,  3.750) = 5779 
    [ 3.750,  5.000) = 2280 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     10.529 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     11.338 ms/op
     p(99.9999) =     11.338 ms/op
    p(100.0000) =     11.338 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.749          ops/ms
ClientSimple.existUser                       thrpt         12.096          ops/ms
ClientSimple.getUser                         thrpt         11.144          ops/ms
ClientSimple.listUser                        thrpt          8.816          ops/ms
ClientSimple.createUser                       avgt          2.281           ms/op
ClientSimple.existUser                        avgt          1.809           ms/op
ClientSimple.getUser                          avgt          1.861           ms/op
ClientSimple.listUser                         avgt          3.944           ms/op
ClientSimple.createUser                     sample  14866   2.151 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.560           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.971           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.086           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.383           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.495           ms/op
ClientSimple.existUser                      sample  15556   2.055 ± 0.071   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.266           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.768           ms/op
ClientSimple.existUser:existUser·p0.999     sample         49.734           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         53.914           ms/op
ClientSimple.existUser:existUser·p1.00      sample         55.116           ms/op
ClientSimple.getUser                        sample  17459   1.850 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.573           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.772           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.465           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.937           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.293           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.403           ms/op
ClientSimple.listUser                       sample   9340   3.422 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.325           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.610           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.529           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.338           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.338           ms/op

Benchmark result is saved to 1719425123251.json
