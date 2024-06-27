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
# Warmup Iteration   1: 1.727 ops/ms
Iteration   1: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.022 ops/ms


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
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 12.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.103 ops/ms


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
# Warmup Iteration   1: 4.742 ops/ms
Iteration   1: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.085 ops/ms


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
# Warmup Iteration   1: 4.577 ops/ms
Iteration   1: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.363 ops/ms


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.076 ms/op
Iteration   1: 2.036 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.036 ms/op


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
# Warmup Iteration   1: 2.933 ±(99.9%) 0.046 ms/op
Iteration   1: 1.608 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.608 ms/op


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
# Warmup Iteration   1: 3.514 ±(99.9%) 0.068 ms/op
Iteration   1: 2.050 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.050 ms/op


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.100 ms/op
Iteration   1: 3.264 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.264 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.082 ms/op
Iteration   1: 2.280 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.068 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 25.747 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14220
  mean =      2.280 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10642 
    [ 2.500,  5.000) = 3289 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.747 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.074 ms/op
Iteration   1: 1.812 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.089 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   2.880 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 17.807 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17840
  mean =      1.812 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 17393 
    [ 2.500,  3.750) = 295 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      2.880 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     17.807 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.074 ±(99.9%) 0.073 ms/op
Iteration   1: 1.889 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   1.706 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  40.044 ms/op
                 getUser·p0.9999: 41.492 ms/op
                 getUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16972
  mean =      1.889 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16899 
    [ 5.000, 10.000) = 7 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =     40.044 ms/op
     p(99.9900) =     41.492 ms/op
     p(99.9990) =     41.812 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.127 ms/op
Iteration   1: 3.121 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   5.030 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 19.260 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10230
  mean =      3.121 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1855 
    [ 2.500,  3.750) = 6762 
    [ 3.750,  5.000) = 1496 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     19.260 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.022          ops/ms
ClientSimple.existUser                       thrpt         12.103          ops/ms
ClientSimple.getUser                         thrpt         13.085          ops/ms
ClientSimple.listUser                        thrpt          8.363          ops/ms
ClientSimple.createUser                       avgt          2.036           ms/op
ClientSimple.existUser                        avgt          1.608           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          3.264           ms/op
ClientSimple.createUser                     sample  14220   2.280 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.569           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.068           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.634           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.366           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.747           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.788           ms/op
ClientSimple.existUser                      sample  17840   1.812 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.920           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.089           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.880           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.596           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.807           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.859           ms/op
ClientSimple.getUser                        sample  16972   1.889 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.706           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.719           ms/op
ClientSimple.getUser:getUser·p0.999         sample         40.044           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         41.492           ms/op
ClientSimple.getUser:getUser·p1.00          sample         41.812           ms/op
ClientSimple.listUser                       sample  10230   3.121 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.980           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.949           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.030           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.874           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.260           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.268           ms/op

Benchmark result is saved to 1719468363831.json
