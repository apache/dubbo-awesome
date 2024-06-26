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
# Warmup Iteration   1: 1.943 ops/ms
Iteration   1: 6.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.536 ops/ms


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
# Warmup Iteration   1: 6.541 ops/ms
Iteration   1: 11.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.431 ops/ms


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
# Warmup Iteration   1: 6.598 ops/ms
Iteration   1: 15.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.427 ops/ms


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
# Warmup Iteration   1: 4.527 ops/ms
Iteration   1: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.197 ops/ms


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.086 ms/op
Iteration   1: 2.185 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.058 ms/op
Iteration   1: 1.873 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.873 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.057 ms/op
Iteration   1: 1.851 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.851 ms/op


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
# Warmup Iteration   1: 5.456 ±(99.9%) 0.140 ms/op
Iteration   1: 3.479 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.479 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.098 ms/op
Iteration   1: 2.386 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.318 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  33.516 ms/op
                 createUser·p0.9999: 36.525 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13398
  mean =      2.386 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10670 
    [ 2.500,  5.000) = 2461 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     33.516 ms/op
     p(99.9900) =     36.525 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.083 ms/op
Iteration   1: 1.823 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.979 ms/op
                 existUser·p0.999:  12.795 ms/op
                 existUser·p0.9999: 13.099 ms/op
                 existUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17538
  mean =      1.823 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1023 
    [ 1.250,  2.500) = 15220 
    [ 2.500,  3.750) = 1109 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.979 ms/op
     p(99.9000) =     12.795 ms/op
     p(99.9900) =     13.099 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.371 ms/op
Iteration   1: 2.121 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   1.925 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.972 ms/op
                 getUser·p0.99:   4.697 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 17.367 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15065
  mean =      2.121 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 12448 
    [ 2.500,  3.750) = 2248 
    [ 3.750,  5.000) = 182 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.972 ms/op
     p(99.0000) =      4.697 ms/op
     p(99.9000) =     17.269 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ±(99.9%) 0.117 ms/op
Iteration   1: 3.130 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.136 ms/op
                 listUser·p0.999:  6.915 ms/op
                 listUser·p0.9999: 11.527 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10213
  mean =      3.130 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 865 
    [ 2.500,  3.750) = 7851 
    [ 3.750,  5.000) = 1303 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      6.915 ms/op
     p(99.9900) =     11.527 ms/op
     p(99.9990) =     11.583 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.536          ops/ms
ClientSimple.existUser                       thrpt         11.431          ops/ms
ClientSimple.getUser                         thrpt         15.427          ops/ms
ClientSimple.listUser                        thrpt          8.197          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          1.873           ms/op
ClientSimple.getUser                          avgt          1.851           ms/op
ClientSimple.listUser                         avgt          3.479           ms/op
ClientSimple.createUser                     sample  13398   2.386 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.318           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.257           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.516           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.525           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.569           ms/op
ClientSimple.existUser                      sample  17538   1.823 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.668           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.979           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.795           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.099           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.173           ms/op
ClientSimple.getUser                        sample  15065   2.121 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.575           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.925           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.972           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.697           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.269           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.367           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.367           ms/op
ClientSimple.listUser                       sample  10213   3.130 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.781           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.136           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.915           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.527           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.583           ms/op

Benchmark result is saved to 1719360948301.json
