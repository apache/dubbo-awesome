# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.873 ops/ms
Iteration   1: 6.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.865 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.008 ops/ms
Iteration   1: 12.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.130 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.176 ops/ms
Iteration   1: 12.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.502 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ops/ms
Iteration   1: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.996 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.067 ms/op
Iteration   1: 1.992 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.992 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.047 ms/op
Iteration   1: 1.802 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ±(99.9%) 0.043 ms/op
Iteration   1: 2.141 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.141 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.092 ms/op
Iteration   1: 3.770 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.093 ms/op
Iteration   1: 2.467 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   13.140 ms/op
                 createUser·p0.999:  27.853 ms/op
                 createUser·p0.9999: 31.289 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13004
  mean =      2.467 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9744 
    [ 2.500,  5.000) = 2846 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     27.853 ms/op
     p(99.9900) =     31.289 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.976 ±(99.9%) 0.069 ms/op
Iteration   1: 1.881 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.486 ms/op
                 existUser·p0.99:   2.900 ms/op
                 existUser·p0.999:  14.417 ms/op
                 existUser·p0.9999: 14.973 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17038
  mean =      1.881 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 859 
    [ 1.250,  2.500) = 15365 
    [ 2.500,  3.750) = 747 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.486 ms/op
     p(99.0000) =      2.900 ms/op
     p(99.9000) =     14.417 ms/op
     p(99.9900) =     14.973 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ±(99.9%) 0.095 ms/op
Iteration   1: 2.081 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  18.168 ms/op
                 getUser·p0.9999: 18.656 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15565
  mean =      2.081 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 13334 
    [ 2.500,  3.750) = 1652 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =     18.168 ms/op
     p(99.9900) =     18.656 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ±(99.9%) 0.109 ms/op
Iteration   1: 3.271 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.295 ms/op
                 listUser·p0.999:  7.766 ms/op
                 listUser·p0.9999: 8.053 ms/op
                 listUser·p1.00:   8.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9752
  mean =      3.271 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 28 
    [2.000, 2.500) = 375 
    [2.500, 3.000) = 4103 
    [3.000, 3.500) = 2041 
    [3.500, 4.000) = 2050 
    [4.000, 4.500) = 832 
    [4.500, 5.000) = 157 
    [5.000, 5.500) = 19 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 41 
    [6.500, 7.000) = 33 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 22 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.295 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =      8.053 ms/op
     p(99.9990) =      8.053 ms/op
     p(99.9999) =      8.053 ms/op
    p(100.0000) =      8.053 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.865          ops/ms
ClientSimple.existUser                       thrpt         12.130          ops/ms
ClientSimple.getUser                         thrpt         12.502          ops/ms
ClientSimple.listUser                        thrpt          8.996          ops/ms
ClientSimple.createUser                       avgt          1.992           ms/op
ClientSimple.existUser                        avgt          1.802           ms/op
ClientSimple.getUser                          avgt          2.141           ms/op
ClientSimple.listUser                         avgt          3.770           ms/op
ClientSimple.createUser                     sample  13004   2.467 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.600           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.140           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.853           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.289           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.752           ms/op
ClientSimple.existUser                      sample  17038   1.881 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.597           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.417           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.973           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.122           ms/op
ClientSimple.getUser                        sample  15565   2.081 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.702           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.703           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.168           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.656           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.711           ms/op
ClientSimple.listUser                       sample   9752   3.271 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.161           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.295           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.766           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.053           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.053           ms/op

Benchmark result is saved to 1710720937720.json
