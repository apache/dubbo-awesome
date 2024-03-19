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
# Warmup Iteration   1: 1.978 ops/ms
Iteration   1: 7.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.692 ops/ms


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
# Warmup Iteration   1: 6.410 ops/ms
Iteration   1: 12.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.676 ops/ms


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
# Warmup Iteration   1: 6.134 ops/ms
Iteration   1: 13.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.149 ops/ms


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
# Warmup Iteration   1: 5.123 ops/ms
Iteration   1: 9.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.105 ops/ms


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.067 ms/op
Iteration   1: 2.461 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.461 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.053 ms/op
Iteration   1: 1.822 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.822 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.055 ms/op
Iteration   1: 1.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.911 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ±(99.9%) 0.081 ms/op
Iteration   1: 3.646 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.646 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.092 ms/op
Iteration   1: 2.262 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   4.307 ms/op
                 createUser·p0.999:  28.934 ms/op
                 createUser·p0.9999: 30.367 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14131
  mean =      2.262 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11028 
    [ 2.500,  5.000) = 3000 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      4.307 ms/op
     p(99.9000) =     28.934 ms/op
     p(99.9900) =     30.367 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.072 ms/op
Iteration   1: 2.018 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.206 ms/op
                 existUser·p0.50:   1.950 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.716 ms/op
                 existUser·p0.99:   3.281 ms/op
                 existUser·p0.999:  10.963 ms/op
                 existUser·p0.9999: 11.099 ms/op
                 existUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15846
  mean =      2.018 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 266 
    [ 1.250,  2.500) = 14023 
    [ 2.500,  3.750) = 1473 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.206 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     10.963 ms/op
     p(99.9900) =     11.099 ms/op
     p(99.9990) =     11.108 ms/op
     p(99.9999) =     11.108 ms/op
    p(100.0000) =     11.108 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.082 ms/op
Iteration   1: 1.933 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.515 ms/op
                 getUser·p0.99:   2.953 ms/op
                 getUser·p0.999:  21.519 ms/op
                 getUser·p0.9999: 23.899 ms/op
                 getUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16643
  mean =      1.933 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15751 
    [ 2.500,  5.000) = 859 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =     21.519 ms/op
     p(99.9900) =     23.899 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.121 ms/op
Iteration   1: 3.318 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.121 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.115 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9647
  mean =      3.318 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1082 
    [ 2.500,  3.750) = 6217 
    [ 3.750,  5.000) = 2130 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.115 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.692          ops/ms
ClientSimple.existUser                       thrpt         12.676          ops/ms
ClientSimple.getUser                         thrpt         13.149          ops/ms
ClientSimple.listUser                        thrpt          9.105          ops/ms
ClientSimple.createUser                       avgt          2.461           ms/op
ClientSimple.existUser                        avgt          1.822           ms/op
ClientSimple.getUser                          avgt          1.911           ms/op
ClientSimple.listUser                         avgt          3.646           ms/op
ClientSimple.createUser                     sample  14131   2.262 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.694           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.307           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.934           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.367           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.638           ms/op
ClientSimple.existUser                      sample  15846   2.018 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.206           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.950           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.716           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.281           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.963           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.099           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.108           ms/op
ClientSimple.getUser                        sample  16643   1.933 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.649           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.515           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.519           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.899           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.986           ms/op
ClientSimple.listUser                       sample   9647   3.318 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.303           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.121           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.115           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.564           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.564           ms/op

Benchmark result is saved to 1710871496860.json
