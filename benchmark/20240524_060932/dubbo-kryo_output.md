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
# Warmup Iteration   1: 2.271 ops/ms
Iteration   1: 6.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.769 ops/ms


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
# Warmup Iteration   1: 7.366 ops/ms
Iteration   1: 12.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.245 ops/ms


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
# Warmup Iteration   1: 4.856 ops/ms
Iteration   1: 13.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.217 ops/ms


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
# Warmup Iteration   1: 4.473 ops/ms
Iteration   1: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.927 ops/ms


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.066 ms/op
Iteration   1: 2.195 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.195 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.049 ms/op
Iteration   1: 2.036 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ±(99.9%) 0.058 ms/op
Iteration   1: 1.910 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.910 ms/op


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
# Warmup Iteration   1: 5.887 ±(99.9%) 0.127 ms/op
Iteration   1: 3.277 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.277 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.105 ms/op
Iteration   1: 2.309 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   9.167 ms/op
                 createUser·p0.999:  18.720 ms/op
                 createUser·p0.9999: 21.298 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13850
  mean =      2.309 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10808 
    [ 2.500,  5.000) = 2789 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      9.167 ms/op
     p(99.9000) =     18.720 ms/op
     p(99.9900) =     21.298 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 2.918 ±(99.9%) 0.064 ms/op
Iteration   1: 1.837 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.004 ms/op
                 existUser·p0.999:  13.091 ms/op
                 existUser·p0.9999: 13.160 ms/op
                 existUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17493
  mean =      1.837 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 785 
    [ 1.250,  2.500) = 16314 
    [ 2.500,  3.750) = 277 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.004 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     13.160 ms/op
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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.082 ms/op
Iteration   1: 2.109 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.087 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.628 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 11.868 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15159
  mean =      2.109 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 12434 
    [ 2.500,  3.750) = 2469 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.628 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     11.868 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.124 ms/op
Iteration   1: 3.273 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.046 ms/op
                 listUser·p0.999:  17.441 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9755
  mean =      3.273 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1876 
    [ 2.500,  3.750) = 4832 
    [ 3.750,  5.000) = 2848 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     17.441 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.769          ops/ms
ClientSimple.existUser                       thrpt         12.245          ops/ms
ClientSimple.getUser                         thrpt         13.217          ops/ms
ClientSimple.listUser                        thrpt          8.927          ops/ms
ClientSimple.createUser                       avgt          2.195           ms/op
ClientSimple.existUser                        avgt          2.036           ms/op
ClientSimple.getUser                          avgt          1.910           ms/op
ClientSimple.listUser                         avgt          3.277           ms/op
ClientSimple.createUser                     sample  13850   2.309 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.600           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.158           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.167           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.720           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.298           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.610           ms/op
ClientSimple.existUser                      sample  17493   1.837 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.695           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.004           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.091           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.160           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.173           ms/op
ClientSimple.getUser                        sample  15159   2.109 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.604           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.087           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.628           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.436           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.868           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.928           ms/op
ClientSimple.listUser                       sample   9755   3.273 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.194           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.046           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.441           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.498           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.498           ms/op

Benchmark result is saved to 1716530720125.json
