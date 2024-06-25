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
# Warmup Iteration   1: 1.622 ops/ms
Iteration   1: 6.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.127 ops/ms


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
# Warmup Iteration   1: 6.498 ops/ms
Iteration   1: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.816 ops/ms


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
# Warmup Iteration   1: 5.813 ops/ms
Iteration   1: 13.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.326 ops/ms


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
# Warmup Iteration   1: 5.876 ops/ms
Iteration   1: 8.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.756 ops/ms


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.078 ms/op
Iteration   1: 2.141 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.141 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.080 ms/op
Iteration   1: 1.946 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.064 ms/op
Iteration   1: 1.885 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.885 ms/op


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
# Warmup Iteration   1: 4.545 ±(99.9%) 0.093 ms/op
Iteration   1: 3.405 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.405 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.094 ms/op
Iteration   1: 2.454 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   8.436 ms/op
                 createUser·p0.999:  36.110 ms/op
                 createUser·p0.9999: 46.187 ms/op
                 createUser·p1.00:   46.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13116
  mean =      2.454 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12922 
    [ 5.000, 10.000) = 73 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      8.436 ms/op
     p(99.9000) =     36.110 ms/op
     p(99.9900) =     46.187 ms/op
     p(99.9990) =     46.268 ms/op
     p(99.9999) =     46.268 ms/op
    p(100.0000) =     46.268 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.071 ms/op
Iteration   1: 1.741 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.730 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 13.407 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18618
  mean =      1.741 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2532 
    [ 1.250,  2.500) = 15087 
    [ 2.500,  3.750) = 815 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.730 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.407 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.104 ms/op
Iteration   1: 2.173 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.025 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.622 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14703
  mean =      2.173 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 12684 
    [ 2.500,  3.750) = 1618 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.622 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.128 ms/op
Iteration   1: 3.572 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  6.931 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8948
  mean =      3.572 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 232 
    [ 2.000,  3.000) = 1870 
    [ 3.000,  4.000) = 4091 
    [ 4.000,  5.000) = 2499 
    [ 5.000,  6.000) = 194 
    [ 6.000,  7.000) = 54 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      6.931 ms/op
     p(99.9900) =     10.879 ms/op
     p(99.9990) =     10.879 ms/op
     p(99.9999) =     10.879 ms/op
    p(100.0000) =     10.879 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.127          ops/ms
ClientSimple.existUser                       thrpt         12.816          ops/ms
ClientSimple.getUser                         thrpt         13.326          ops/ms
ClientSimple.listUser                        thrpt          8.756          ops/ms
ClientSimple.createUser                       avgt          2.141           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          1.885           ms/op
ClientSimple.listUser                         avgt          3.405           ms/op
ClientSimple.createUser                     sample  13116   2.454 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.663           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.436           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.110           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         46.187           ms/op
ClientSimple.createUser:createUser·p1.00    sample         46.268           ms/op
ClientSimple.existUser                      sample  18618   1.741 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.503           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.730           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.304           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.407           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.435           ms/op
ClientSimple.getUser                        sample  14703   2.173 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.915           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.025           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.865           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.622           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.711           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.711           ms/op
ClientSimple.listUser                       sample   8948   3.572 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.503           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.650           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.931           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.879           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.879           ms/op

Benchmark result is saved to 1719295546654.json
