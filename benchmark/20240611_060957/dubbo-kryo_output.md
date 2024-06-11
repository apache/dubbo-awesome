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
# Warmup Iteration   1: 1.791 ops/ms
Iteration   1: 7.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.210 ops/ms


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
# Warmup Iteration   1: 4.997 ops/ms
Iteration   1: 11.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.848 ops/ms


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
# Warmup Iteration   1: 4.699 ops/ms
Iteration   1: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.648 ops/ms


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
# Warmup Iteration   1: 4.553 ops/ms
Iteration   1: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.654 ops/ms


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.060 ms/op
Iteration   1: 2.115 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.043 ms/op
Iteration   1: 1.856 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.856 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.063 ms/op
Iteration   1: 2.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.090 ms/op
Iteration   1: 3.205 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.205 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.093 ms/op
Iteration   1: 2.209 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.724 ms/op
                 createUser·p0.99:   11.199 ms/op
                 createUser·p0.999:  31.326 ms/op
                 createUser·p0.9999: 32.691 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14467
  mean =      2.209 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13200 
    [ 2.500,  5.000) = 954 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =     11.199 ms/op
     p(99.9000) =     31.326 ms/op
     p(99.9900) =     32.691 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.077 ms/op
Iteration   1: 1.941 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.187 ms/op
                 existUser·p0.999:  10.933 ms/op
                 existUser·p0.9999: 11.485 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16686
  mean =      1.941 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 430 
    [ 1.250,  2.500) = 15095 
    [ 2.500,  3.750) = 1074 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =     10.933 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     11.583 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.090 ms/op
Iteration   1: 2.154 ±(99.9%) 0.078 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  67.050 ms/op
                 getUser·p0.9999: 69.103 ms/op
                 getUser·p1.00:   70.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14900
  mean =      2.154 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14786 
    [ 5.000, 10.000) = 39 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 16 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     67.050 ms/op
     p(99.9900) =     69.103 ms/op
     p(99.9990) =     70.517 ms/op
     p(99.9999) =     70.517 ms/op
    p(100.0000) =     70.517 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.144 ms/op
Iteration   1: 3.426 ±(99.9%) 0.067 ms/op
                 listUser·p0.00:   0.680 ms/op
                 listUser·p0.50:   3.232 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   10.347 ms/op
                 listUser·p0.999:  30.539 ms/op
                 listUser·p0.9999: 31.326 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9345
  mean =      3.426 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1336 
    [ 2.500,  5.000) = 7642 
    [ 5.000,  7.500) = 227 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =     10.347 ms/op
     p(99.9000) =     30.539 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     31.326 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.210          ops/ms
ClientSimple.existUser                       thrpt         11.848          ops/ms
ClientSimple.getUser                         thrpt         10.648          ops/ms
ClientSimple.listUser                        thrpt          8.654          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          1.856           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.205           ms/op
ClientSimple.createUser                     sample  14467   2.209 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.520           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.199           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.326           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.691           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.735           ms/op
ClientSimple.existUser                      sample  16686   1.941 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.187           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.933           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.485           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.583           ms/op
ClientSimple.getUser                        sample  14900   2.154 ± 0.078   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         67.050           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         69.103           ms/op
ClientSimple.getUser:getUser·p1.00          sample         70.517           ms/op
ClientSimple.listUser                       sample   9345   3.426 ± 0.067   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.680           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.232           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.347           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.539           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.326           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.326           ms/op

Benchmark result is saved to 1718085928268.json
