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
# Warmup Iteration   1: 1.697 ops/ms
Iteration   1: 6.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.604 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.896 ops/ms
Iteration   1: 12.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.143 ops/ms


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
# Warmup Iteration   1: 4.643 ops/ms
Iteration   1: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.719 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ops/ms
Iteration   1: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.256 ops/ms


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.076 ms/op
Iteration   1: 2.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.160 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.069 ms/op
Iteration   1: 2.013 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.013 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.053 ms/op
Iteration   1: 1.907 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.907 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.092 ms/op
Iteration   1: 3.495 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.495 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.122 ms/op
Iteration   1: 2.236 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.580 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   12.536 ms/op
                 createUser·p0.999:  35.286 ms/op
                 createUser·p0.9999: 36.185 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14287
  mean =      2.236 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12604 
    [ 2.500,  5.000) = 1396 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =     12.536 ms/op
     p(99.9000) =     35.286 ms/op
     p(99.9900) =     36.185 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 3.033 ±(99.9%) 0.079 ms/op
Iteration   1: 1.878 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.872 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 12.555 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17014
  mean =      1.878 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1147 
    [ 1.250,  2.500) = 13565 
    [ 2.500,  3.750) = 2114 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.872 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     12.555 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.086 ms/op
Iteration   1: 2.182 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.942 ms/op
                 getUser·p0.99:   5.501 ms/op
                 getUser·p0.999:  29.657 ms/op
                 getUser·p0.9999: 30.302 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14654
  mean =      2.182 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12222 
    [ 2.500,  5.000) = 2191 
    [ 5.000,  7.500) = 169 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.942 ms/op
     p(99.0000) =      5.501 ms/op
     p(99.9000) =     29.657 ms/op
     p(99.9900) =     30.302 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.130 ms/op
Iteration   1: 4.047 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.249 ms/op
                 listUser·p0.999:  11.504 ms/op
                 listUser·p0.9999: 11.665 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7917
  mean =      4.047 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 194 
    [ 2.500,  3.750) = 2295 
    [ 3.750,  5.000) = 4902 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.249 ms/op
     p(99.9000) =     11.504 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.604          ops/ms
ClientSimple.existUser                       thrpt         12.143          ops/ms
ClientSimple.getUser                         thrpt         10.719          ops/ms
ClientSimple.listUser                        thrpt          8.256          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          2.013           ms/op
ClientSimple.getUser                          avgt          1.907           ms/op
ClientSimple.listUser                         avgt          3.495           ms/op
ClientSimple.createUser                     sample  14287   2.236 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.674           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.580           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.536           ms/op
ClientSimple.createUser:createUser·p0.999   sample         35.286           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.185           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.241           ms/op
ClientSimple.existUser                      sample  17014   1.878 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.535           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.978           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.872           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.304           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.555           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.567           ms/op
ClientSimple.getUser                        sample  14654   2.182 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.614           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.942           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.501           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.657           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.302           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.409           ms/op
ClientSimple.listUser                       sample   7917   4.047 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.071           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.249           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.504           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.665           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.665           ms/op

Benchmark result is saved to 1714651622557.json
