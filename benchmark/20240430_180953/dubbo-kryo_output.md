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
# Warmup Iteration   1: 1.669 ops/ms
Iteration   1: 7.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.002 ops/ms


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
# Warmup Iteration   1: 5.924 ops/ms
Iteration   1: 12.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.741 ops/ms


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
# Warmup Iteration   1: 7.013 ops/ms
Iteration   1: 14.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.433 ops/ms


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
# Warmup Iteration   1: 3.384 ops/ms
Iteration   1: 7.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.789 ops/ms


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.069 ms/op
Iteration   1: 2.148 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.076 ms/op
Iteration   1: 1.849 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.358 ±(99.9%) 0.054 ms/op
Iteration   1: 1.906 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.906 ms/op


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.101 ms/op
Iteration   1: 3.302 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.302 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.083 ms/op
Iteration   1: 2.333 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.079 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   6.579 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 27.271 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13745
  mean =      2.333 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10337 
    [ 2.500,  5.000) = 3222 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.322 ms/op
     p(99.0000) =      6.579 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     27.271 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.072 ms/op
Iteration   1: 1.764 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.310 ms/op
                 existUser·p0.99:   4.025 ms/op
                 existUser·p0.999:  10.961 ms/op
                 existUser·p0.9999: 12.022 ms/op
                 existUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18125
  mean =      1.764 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 17487 
    [ 2.500,  3.750) = 246 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 32 
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
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      4.025 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     12.022 ms/op
     p(99.9990) =     12.075 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.125 ms/op
Iteration   1: 1.960 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   1.640 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  25.443 ms/op
                 getUser·p0.9999: 25.746 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16529
  mean =      1.960 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13604 
    [ 2.500,  5.000) = 2772 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     25.443 ms/op
     p(99.9900) =     25.746 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ±(99.9%) 0.166 ms/op
Iteration   1: 2.928 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.658 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   4.866 ms/op
                 listUser·p0.999:  7.373 ms/op
                 listUser·p0.9999: 9.714 ms/op
                 listUser·p1.00:   9.716 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10977
  mean =      2.928 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 155 
    [ 2.000,  3.000) = 6986 
    [ 3.000,  4.000) = 2845 
    [ 4.000,  5.000) = 903 
    [ 5.000,  6.000) = 47 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 28 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =      9.714 ms/op
     p(99.9990) =      9.716 ms/op
     p(99.9999) =      9.716 ms/op
    p(100.0000) =      9.716 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.002          ops/ms
ClientSimple.existUser                       thrpt         12.741          ops/ms
ClientSimple.getUser                         thrpt         14.433          ops/ms
ClientSimple.listUser                        thrpt          7.789          ops/ms
ClientSimple.createUser                       avgt          2.148           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          1.906           ms/op
ClientSimple.listUser                         avgt          3.302           ms/op
ClientSimple.createUser                     sample  13745   2.333 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.798           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.079           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.322           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.579           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.331           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.271           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.296           ms/op
ClientSimple.existUser                      sample  18125   1.764 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.025           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.961           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.022           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.075           ms/op
ClientSimple.getUser                        sample  16529   1.960 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.462           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.640           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.211           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.547           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.443           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.746           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.788           ms/op
ClientSimple.listUser                       sample  10977   2.928 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.954           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.373           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.714           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.716           ms/op

Benchmark result is saved to 1714500340243.json
