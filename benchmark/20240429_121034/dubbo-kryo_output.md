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
# Warmup Iteration   1: 1.672 ops/ms
Iteration   1: 7.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.011 ops/ms


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
# Warmup Iteration   1: 5.501 ops/ms
Iteration   1: 13.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.777 ops/ms


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
# Warmup Iteration   1: 5.731 ops/ms
Iteration   1: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.863 ops/ms


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
# Warmup Iteration   1: 4.214 ops/ms
Iteration   1: 7.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.772 ops/ms


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.091 ms/op
Iteration   1: 2.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.017 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.065 ms/op
Iteration   1: 1.810 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.056 ms/op
Iteration   1: 1.892 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.478 ±(99.9%) 0.089 ms/op
Iteration   1: 3.286 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.286 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.097 ms/op
Iteration   1: 2.183 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  13.746 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14837
  mean =      2.183 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 12771 
    [ 2.500,  3.750) = 1509 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 2.902 ±(99.9%) 0.069 ms/op
Iteration   1: 2.121 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.109 ms/op
                 existUser·p0.90:   2.621 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   4.647 ms/op
                 existUser·p0.999:  11.237 ms/op
                 existUser·p0.9999: 11.395 ms/op
                 existUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15176
  mean =      2.121 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 12443 
    [ 2.500,  3.750) = 2077 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.647 ms/op
     p(99.9000) =     11.237 ms/op
     p(99.9900) =     11.395 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ±(99.9%) 0.096 ms/op
Iteration   1: 2.368 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.359 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.594 ms/op
                 getUser·p0.999:  11.930 ms/op
                 getUser·p0.9999: 13.103 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13565
  mean =      2.368 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 183 
    [ 1.250,  2.500) = 8124 
    [ 2.500,  3.750) = 5144 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.594 ms/op
     p(99.9000) =     11.930 ms/op
     p(99.9900) =     13.103 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.147 ms/op
Iteration   1: 3.725 ±(99.9%) 0.164 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.310 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   18.118 ms/op
                 listUser·p0.999:  74.449 ms/op
                 listUser·p0.9999: 74.973 ms/op
                 listUser·p1.00:   74.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8606
  mean =      3.725 ±(99.9%) 0.164 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8285 
    [ 5.000, 10.000) = 195 
    [10.000, 15.000) = 5 
    [15.000, 20.000) = 85 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =     18.118 ms/op
     p(99.9000) =     74.449 ms/op
     p(99.9900) =     74.973 ms/op
     p(99.9990) =     74.973 ms/op
     p(99.9999) =     74.973 ms/op
    p(100.0000) =     74.973 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.011          ops/ms
ClientSimple.existUser                       thrpt         13.777          ops/ms
ClientSimple.getUser                         thrpt         12.863          ops/ms
ClientSimple.listUser                        thrpt          7.772          ops/ms
ClientSimple.createUser                       avgt          2.017           ms/op
ClientSimple.existUser                        avgt          1.810           ms/op
ClientSimple.getUser                          avgt          1.892           ms/op
ClientSimple.listUser                         avgt          3.286           ms/op
ClientSimple.createUser                     sample  14837   2.183 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.719           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.746           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.828           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.828           ms/op
ClientSimple.existUser                      sample  15176   2.121 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.600           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.109           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.647           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.237           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.395           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.403           ms/op
ClientSimple.getUser                        sample  13565   2.368 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.703           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.359           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.594           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.930           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.103           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   8606   3.725 ± 0.164   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.947           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.310           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.99        sample         18.118           ms/op
ClientSimple.listUser:listUser·p0.999       sample         74.449           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         74.973           ms/op
ClientSimple.listUser:listUser·p1.00        sample         74.973           ms/op

Benchmark result is saved to 1714392399646.json
