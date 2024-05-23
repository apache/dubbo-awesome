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
# Warmup Iteration   1: 1.875 ops/ms
Iteration   1: 7.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.732 ops/ms


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
# Warmup Iteration   1: 6.393 ops/ms
Iteration   1: 11.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.684 ops/ms


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
# Warmup Iteration   1: 7.475 ops/ms
Iteration   1: 13.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.093 ops/ms


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
# Warmup Iteration   1: 4.859 ops/ms
Iteration   1: 9.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.092 ops/ms


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.073 ms/op
Iteration   1: 2.515 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.515 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.054 ms/op
Iteration   1: 1.791 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.791 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.055 ms/op
Iteration   1: 1.816 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.816 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.092 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.338 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.085 ms/op
Iteration   1: 2.041 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.544 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 21.160 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15657
  mean =      2.041 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14761 
    [ 2.500,  5.000) = 716 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     21.160 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.090 ms/op
Iteration   1: 2.004 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 11.292 ms/op
                 existUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15992
  mean =      2.004 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 379 
    [ 1.250,  2.500) = 12957 
    [ 2.500,  3.750) = 2461 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     11.292 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


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
# Warmup Iteration   1: 3.082 ±(99.9%) 0.072 ms/op
Iteration   1: 2.209 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.376 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  29.950 ms/op
                 getUser·p0.9999: 30.463 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14523
  mean =      2.209 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12186 
    [ 2.500,  5.000) = 2242 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     29.950 ms/op
     p(99.9900) =     30.463 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.125 ms/op
Iteration   1: 3.821 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.701 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8361
  mean =      3.821 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 303 
    [ 2.500,  3.750) = 3607 
    [ 3.750,  5.000) = 4066 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.701 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     14.877 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.732          ops/ms
ClientSimple.existUser                       thrpt         11.684          ops/ms
ClientSimple.getUser                         thrpt         13.093          ops/ms
ClientSimple.listUser                        thrpt          9.092          ops/ms
ClientSimple.createUser                       avgt          2.515           ms/op
ClientSimple.existUser                        avgt          1.791           ms/op
ClientSimple.getUser                          avgt          1.816           ms/op
ClientSimple.listUser                         avgt          3.338           ms/op
ClientSimple.createUser                     sample  15657   2.041 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.758           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.415           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.709           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.160           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.234           ms/op
ClientSimple.existUser                      sample  15992   2.004 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.428           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.945           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.292           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.321           ms/op
ClientSimple.getUser                        sample  14523   2.209 ± 0.044   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.376           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.194           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.950           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.463           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.507           ms/op
ClientSimple.listUser                       sample   8361   3.821 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.102           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.793           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.701           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.767           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.074           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.877           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.877           ms/op

Benchmark result is saved to 1716423323805.json
