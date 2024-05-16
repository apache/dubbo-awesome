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
# Warmup Iteration   1: 1.090 ops/ms
Iteration   1: 6.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.420 ops/ms


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
# Warmup Iteration   1: 6.151 ops/ms
Iteration   1: 13.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.581 ops/ms


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
# Warmup Iteration   1: 5.084 ops/ms
Iteration   1: 12.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.239 ops/ms


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
# Warmup Iteration   1: 4.772 ops/ms
Iteration   1: 8.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.451 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.086 ms/op
Iteration   1: 2.365 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.365 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.059 ms/op
Iteration   1: 2.234 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.234 ms/op


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
# Warmup Iteration   1: 3.231 ±(99.9%) 0.061 ms/op
Iteration   1: 2.100 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.100 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.098 ms/op
Iteration   1: 3.548 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.548 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.094 ms/op
Iteration   1: 2.270 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  33.052 ms/op
                 createUser·p0.9999: 34.837 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14519
  mean =      2.270 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12011 
    [ 2.500,  5.000) = 2270 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     33.052 ms/op
     p(99.9900) =     34.837 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 2.916 ±(99.9%) 0.067 ms/op
Iteration   1: 2.013 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.228 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   4.531 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 9.710 ms/op
                 existUser·p1.00:   9.748 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15894
  mean =      2.013 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 239 
    [ 1.000,  2.000) = 8142 
    [ 2.000,  3.000) = 7031 
    [ 3.000,  4.000) = 252 
    [ 4.000,  5.000) = 101 
    [ 5.000,  6.000) = 99 
    [ 6.000,  7.000) = 16 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.228 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      4.531 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =      9.710 ms/op
     p(99.9990) =      9.748 ms/op
     p(99.9999) =      9.748 ms/op
    p(100.0000) =      9.748 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.109 ms/op
Iteration   1: 2.124 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.384 ms/op
                 getUser·p0.999:  12.534 ms/op
                 getUser·p0.9999: 13.007 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15129
  mean =      2.124 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 12406 
    [ 2.500,  3.750) = 2303 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.384 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     13.007 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 6.084 ±(99.9%) 0.171 ms/op
Iteration   1: 3.898 ±(99.9%) 0.075 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   9.263 ms/op
                 listUser·p0.999:  29.360 ms/op
                 listUser·p0.9999: 30.081 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8232
  mean =      3.898 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 434 
    [ 2.500,  5.000) = 7257 
    [ 5.000,  7.500) = 370 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      9.263 ms/op
     p(99.9000) =     29.360 ms/op
     p(99.9900) =     30.081 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.420          ops/ms
ClientSimple.existUser                       thrpt         13.581          ops/ms
ClientSimple.getUser                         thrpt         12.239          ops/ms
ClientSimple.listUser                        thrpt          8.451          ops/ms
ClientSimple.createUser                       avgt          2.365           ms/op
ClientSimple.existUser                        avgt          2.234           ms/op
ClientSimple.getUser                          avgt          2.100           ms/op
ClientSimple.listUser                         avgt          3.548           ms/op
ClientSimple.createUser                     sample  14519   2.270 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.324           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.052           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.837           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  15894   2.013 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.228           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.531           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.767           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          9.710           ms/op
ClientSimple.existUser:existUser·p1.00      sample          9.748           ms/op
ClientSimple.getUser                        sample  15129   2.124 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.547           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.384           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.534           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.007           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.074           ms/op
ClientSimple.listUser                       sample   8232   3.898 ± 0.075   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.983           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.707           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.263           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.360           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.081           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.081           ms/op

Benchmark result is saved to 1715861194634.json
