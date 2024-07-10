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
# Warmup Iteration   1: 1.638 ops/ms
Iteration   1: 6.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.781 ops/ms


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
# Warmup Iteration   1: 5.864 ops/ms
Iteration   1: 11.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.315 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ops/ms
Iteration   1: 11.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.601 ops/ms


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
# Warmup Iteration   1: 3.956 ops/ms
Iteration   1: 8.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.362 ops/ms


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.105 ms/op
Iteration   1: 2.476 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.476 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.048 ms/op
Iteration   1: 1.791 ±(99.9%) 0.009 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.265 ±(99.9%) 0.056 ms/op
Iteration   1: 1.984 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.984 ms/op


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
# Warmup Iteration   1: 5.159 ±(99.9%) 0.124 ms/op
Iteration   1: 3.899 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.899 ms/op


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
# Warmup Iteration   1: 3.463 ±(99.9%) 0.103 ms/op
Iteration   1: 2.072 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.400 ms/op
                 createUser·p0.95:   2.609 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  29.837 ms/op
                 createUser·p0.9999: 31.028 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15444
  mean =      2.072 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14380 
    [ 2.500,  5.000) = 866 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     29.837 ms/op
     p(99.9900) =     31.028 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.079 ms/op
Iteration   1: 1.877 ±(99.9%) 0.073 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.339 ms/op
                 existUser·p0.99:   3.626 ms/op
                 existUser·p0.999:  66.257 ms/op
                 existUser·p0.9999: 67.934 ms/op
                 existUser·p1.00:   68.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17032
  mean =      1.877 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16930 
    [ 5.000, 10.000) = 38 
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.339 ms/op
     p(99.0000) =      3.626 ms/op
     p(99.9000) =     66.257 ms/op
     p(99.9900) =     67.934 ms/op
     p(99.9990) =     68.026 ms/op
     p(99.9999) =     68.026 ms/op
    p(100.0000) =     68.026 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.080 ms/op
Iteration   1: 2.049 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.431 ms/op
                 getUser·p0.999:  13.743 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15606
  mean =      2.049 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 13972 
    [ 2.500,  3.750) = 1274 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.431 ms/op
     p(99.9000) =     13.743 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.118 ms/op
Iteration   1: 3.503 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.287 ms/op
                 listUser·p0.90:   4.191 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.743 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9138
  mean =      3.503 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 8921 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.287 ms/op
     p(90.0000) =      4.191 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.743 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.781          ops/ms
ClientSimple.existUser                       thrpt         11.315          ops/ms
ClientSimple.getUser                         thrpt         11.601          ops/ms
ClientSimple.listUser                        thrpt          8.362          ops/ms
ClientSimple.createUser                       avgt          2.476           ms/op
ClientSimple.existUser                        avgt          1.791           ms/op
ClientSimple.getUser                          avgt          1.984           ms/op
ClientSimple.listUser                         avgt          3.899           ms/op
ClientSimple.createUser                     sample  15444   2.072 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.614           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.400           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.962           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.837           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.028           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.064           ms/op
ClientSimple.existUser                      sample  17032   1.877 ± 0.073   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.626           ms/op
ClientSimple.existUser:existUser·p0.999     sample         66.257           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         67.934           ms/op
ClientSimple.existUser:existUser·p1.00      sample         68.026           ms/op
ClientSimple.getUser                        sample  15606   2.049 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.630           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.431           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.743           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.910           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.910           ms/op
ClientSimple.listUser                       sample   9138   3.503 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.026           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.287           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.191           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.775           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.906           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.906           ms/op

Benchmark result is saved to 1720613218273.json
