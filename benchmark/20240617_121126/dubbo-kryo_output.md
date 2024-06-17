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
# Warmup Iteration   1: 1.880 ops/ms
Iteration   1: 7.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.057 ops/ms


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
# Warmup Iteration   1: 6.869 ops/ms
Iteration   1: 13.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.768 ops/ms


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
# Warmup Iteration   1: 6.493 ops/ms
Iteration   1: 13.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.807 ops/ms


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
# Warmup Iteration   1: 5.799 ops/ms
Iteration   1: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.236 ops/ms


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.099 ms/op
Iteration   1: 2.189 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.189 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.050 ms/op
Iteration   1: 1.836 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.836 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.053 ms/op
Iteration   1: 1.763 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.763 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.097 ms/op
Iteration   1: 3.184 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.184 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.090 ms/op
Iteration   1: 2.139 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   1.829 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   7.652 ms/op
                 createUser·p0.999:  27.169 ms/op
                 createUser·p0.9999: 28.000 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14936
  mean =      2.139 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13334 
    [ 2.500,  5.000) = 1282 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      7.652 ms/op
     p(99.9000) =     27.169 ms/op
     p(99.9900) =     28.000 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 3.012 ±(99.9%) 0.072 ms/op
Iteration   1: 2.322 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.277 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   2.896 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  13.864 ms/op
                 existUser·p0.9999: 14.014 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13778
  mean =      2.322 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 9755 
    [ 2.500,  3.750) = 3789 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =     13.864 ms/op
     p(99.9900) =     14.014 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.093 ms/op
Iteration   1: 1.909 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   1.710 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.868 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16771
  mean =      1.909 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 285 
    [ 1.250,  2.500) = 14600 
    [ 2.500,  3.750) = 1706 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.868 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.132 ms/op
Iteration   1: 3.466 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.494 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.317 ms/op
                 listUser·p0.999:  6.349 ms/op
                 listUser·p0.9999: 9.191 ms/op
                 listUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9228
  mean =      3.466 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 36 
    [ 1.500,  2.000) = 88 
    [ 2.000,  2.500) = 410 
    [ 2.500,  3.000) = 2064 
    [ 3.000,  3.500) = 2038 
    [ 3.500,  4.000) = 2705 
    [ 4.000,  4.500) = 1233 
    [ 4.500,  5.000) = 504 
    [ 5.000,  5.500) = 78 
    [ 5.500,  6.000) = 55 
    [ 6.000,  6.500) = 11 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 1 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =      6.349 ms/op
     p(99.9900) =      9.191 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.057          ops/ms
ClientSimple.existUser                       thrpt         13.768          ops/ms
ClientSimple.getUser                         thrpt         13.807          ops/ms
ClientSimple.listUser                        thrpt          9.236          ops/ms
ClientSimple.createUser                       avgt          2.189           ms/op
ClientSimple.existUser                        avgt          1.836           ms/op
ClientSimple.getUser                          avgt          1.763           ms/op
ClientSimple.listUser                         avgt          3.184           ms/op
ClientSimple.createUser                     sample  14936   2.139 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.678           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.829           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.277           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.652           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.169           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.000           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.017           ms/op
ClientSimple.existUser                      sample  13778   2.322 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.896           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.781           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.864           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.014           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.057           ms/op
ClientSimple.getUser                        sample  16771   1.909 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.799           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.710           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.868           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.940           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.104           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.104           ms/op
ClientSimple.listUser                       sample   9228   3.466 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.013           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.494           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.317           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.349           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.191           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.191           ms/op

Benchmark result is saved to 1718626015465.json
