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
# Warmup Iteration   1: 1.467 ops/ms
Iteration   1: 6.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.218 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 13.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.672 ops/ms


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
# Warmup Iteration   1: 4.928 ops/ms
Iteration   1: 12.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.708 ops/ms


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
# Warmup Iteration   1: 5.141 ops/ms
Iteration   1: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.787 ops/ms


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.066 ms/op
Iteration   1: 2.222 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.054 ms/op
Iteration   1: 1.755 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.061 ±(99.9%) 0.055 ms/op
Iteration   1: 2.050 ±(99.9%) 0.005 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ±(99.9%) 0.104 ms/op
Iteration   1: 2.989 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.989 ms/op


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.099 ms/op
Iteration   1: 2.134 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   4.622 ms/op
                 createUser·p0.999:  25.821 ms/op
                 createUser·p0.9999: 27.214 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14982
  mean =      2.134 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11782 
    [ 2.500,  5.000) = 3083 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.622 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     27.214 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.138 ms/op
Iteration   1: 1.954 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.761 ms/op
                 existUser·p0.95:   3.071 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  13.238 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16366
  mean =      1.954 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 786 
    [ 1.250,  2.500) = 12540 
    [ 2.500,  3.750) = 2901 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.071 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.082 ms/op
Iteration   1: 2.192 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   2.163 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.943 ms/op
                 getUser·p0.99:   3.433 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 11.914 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14588
  mean =      2.192 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 11156 
    [ 2.500,  3.750) = 3153 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.943 ms/op
     p(99.0000) =      3.433 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     11.914 ms/op
     p(99.9990) =     11.944 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.117 ms/op
Iteration   1: 3.169 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  18.478 ms/op
                 listUser·p0.9999: 18.546 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10095
  mean =      3.169 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1557 
    [ 2.500,  3.750) = 6559 
    [ 3.750,  5.000) = 1765 
    [ 5.000,  6.250) = 133 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.478 ms/op
     p(99.9900) =     18.546 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.218          ops/ms
ClientSimple.existUser                       thrpt         13.672          ops/ms
ClientSimple.getUser                         thrpt         12.708          ops/ms
ClientSimple.listUser                        thrpt          8.787          ops/ms
ClientSimple.createUser                       avgt          2.222           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          2.989           ms/op
ClientSimple.createUser                     sample  14982   2.134 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.955           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.622           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.821           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.214           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.329           ms/op
ClientSimple.existUser                      sample  16366   1.954 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.768           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.071           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.662           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.337           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.337           ms/op
ClientSimple.getUser                        sample  14588   2.192 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.597           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.163           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.943           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.433           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.961           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.914           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.944           ms/op
ClientSimple.listUser                       sample  10095   3.169 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.425           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.851           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.478           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.546           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.547           ms/op

Benchmark result is saved to 1720937198881.json
