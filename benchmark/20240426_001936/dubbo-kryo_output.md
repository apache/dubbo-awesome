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
# Warmup Iteration   1: 2.221 ops/ms
Iteration   1: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.931 ops/ms


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
# Warmup Iteration   1: 6.687 ops/ms
Iteration   1: 13.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.438 ops/ms


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
# Warmup Iteration   1: 5.992 ops/ms
Iteration   1: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.660 ops/ms


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
# Warmup Iteration   1: 4.974 ops/ms
Iteration   1: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.861 ops/ms


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.056 ms/op
Iteration   1: 1.866 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.866 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.055 ms/op
Iteration   1: 2.068 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.061 ms/op
Iteration   1: 2.177 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.177 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.132 ms/op
Iteration   1: 3.680 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.680 ms/op


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
# Warmup Iteration   1: 3.461 ±(99.9%) 0.076 ms/op
Iteration   1: 2.063 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 19.934 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15500
  mean =      2.063 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 436 
    [ 1.250,  2.500) = 13306 
    [ 2.500,  3.750) = 1517 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     19.934 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.888 ±(99.9%) 0.063 ms/op
Iteration   1: 1.640 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.509 ms/op
                 existUser·p0.90:   1.907 ms/op
                 existUser·p0.95:   2.101 ms/op
                 existUser·p0.99:   2.851 ms/op
                 existUser·p0.999:  29.655 ms/op
                 existUser·p0.9999: 29.988 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19488
  mean =      1.640 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19141 
    [ 2.500,  5.000) = 283 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.509 ms/op
     p(90.0000) =      1.907 ms/op
     p(95.0000) =      2.101 ms/op
     p(99.0000) =      2.851 ms/op
     p(99.9000) =     29.655 ms/op
     p(99.9900) =     29.988 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.069 ms/op
Iteration   1: 1.997 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   1.927 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  11.665 ms/op
                 getUser·p0.9999: 12.415 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16099
  mean =      1.997 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 455 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1870 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 107 
    [ 6.250,  7.500) = 25 
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
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     12.415 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


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
# Warmup Iteration   1: 4.749 ±(99.9%) 0.140 ms/op
Iteration   1: 3.349 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.165 ms/op
                 listUser·p0.999:  19.348 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9537
  mean =      3.349 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1938 
    [ 2.500,  5.000) = 7315 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.165 ms/op
     p(99.9000) =     19.348 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.931          ops/ms
ClientSimple.existUser                       thrpt         13.438          ops/ms
ClientSimple.getUser                         thrpt         10.660          ops/ms
ClientSimple.listUser                        thrpt          8.861          ops/ms
ClientSimple.createUser                       avgt          1.866           ms/op
ClientSimple.existUser                        avgt          2.068           ms/op
ClientSimple.getUser                          avgt          2.177           ms/op
ClientSimple.listUser                         avgt          3.680           ms/op
ClientSimple.createUser                     sample  15500   2.063 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.701           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.719           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.285           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.934           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  19488   1.640 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.509           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.851           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.655           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.988           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.081           ms/op
ClientSimple.getUser                        sample  16099   1.997 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.628           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.927           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.415           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.435           ms/op
ClientSimple.listUser                       sample   9537   3.349 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.982           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.165           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.348           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.332           ms/op

Benchmark result is saved to 1714090498897.json
