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
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 6.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.955 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.630 ops/ms
Iteration   1: 13.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.681 ops/ms


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
# Warmup Iteration   1: 5.429 ops/ms
Iteration   1: 13.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.893 ops/ms


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
# Warmup Iteration   1: 4.928 ops/ms
Iteration   1: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.835 ops/ms


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.091 ms/op
Iteration   1: 2.126 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.058 ms/op
Iteration   1: 1.799 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.799 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.061 ms/op
Iteration   1: 2.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.086 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.094 ms/op
Iteration   1: 3.609 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.609 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.085 ms/op
Iteration   1: 2.041 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.306 ms/op
                 createUser·p0.95:   2.535 ms/op
                 createUser·p0.99:   4.863 ms/op
                 createUser·p0.999:  29.852 ms/op
                 createUser·p0.9999: 30.179 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15670
  mean =      2.041 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14788 
    [ 2.500,  5.000) = 743 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      4.863 ms/op
     p(99.9000) =     29.852 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 3.008 ±(99.9%) 0.083 ms/op
Iteration   1: 2.071 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.999 ms/op
                 existUser·p0.90:   2.593 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  15.679 ms/op
                 existUser·p0.9999: 16.700 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15445
  mean =      2.071 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 479 
    [ 1.250,  2.500) = 12803 
    [ 2.500,  3.750) = 2006 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     16.700 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.148 ms/op
Iteration   1: 1.958 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.411 ms/op
                 getUser·p0.50:   1.829 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.523 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  14.359 ms/op
                 getUser·p0.9999: 15.315 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16349
  mean =      1.958 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 15340 
    [ 2.500,  3.750) = 725 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =     14.359 ms/op
     p(99.9900) =     15.315 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.138 ms/op
Iteration   1: 3.562 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.567 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  7.005 ms/op
                 listUser·p0.9999: 8.298 ms/op
                 listUser·p1.00:   8.298 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8978
  mean =      3.562 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 78 
    [2.000, 2.500) = 631 
    [2.500, 3.000) = 1668 
    [3.000, 3.500) = 1352 
    [3.500, 4.000) = 2813 
    [4.000, 4.500) = 1579 
    [4.500, 5.000) = 540 
    [5.000, 5.500) = 177 
    [5.500, 6.000) = 36 
    [6.000, 6.500) = 42 
    [6.500, 7.000) = 18 
    [7.000, 7.500) = 7 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      7.005 ms/op
     p(99.9900) =      8.298 ms/op
     p(99.9990) =      8.298 ms/op
     p(99.9999) =      8.298 ms/op
    p(100.0000) =      8.298 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.955          ops/ms
ClientSimple.existUser                       thrpt         13.681          ops/ms
ClientSimple.getUser                         thrpt         13.893          ops/ms
ClientSimple.listUser                        thrpt          7.835          ops/ms
ClientSimple.createUser                       avgt          2.126           ms/op
ClientSimple.existUser                        avgt          1.799           ms/op
ClientSimple.getUser                          avgt          2.086           ms/op
ClientSimple.listUser                         avgt          3.609           ms/op
ClientSimple.createUser                     sample  15670   2.041 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.462           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.306           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.863           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.852           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.179           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.179           ms/op
ClientSimple.existUser                      sample  15445   2.071 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.999           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.789           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.679           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.700           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.941           ms/op
ClientSimple.getUser                        sample  16349   1.958 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.411           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.829           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.174           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.359           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.315           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.335           ms/op
ClientSimple.listUser                       sample   8978   3.562 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.567           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.658           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.767           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.005           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.298           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.298           ms/op

Benchmark result is saved to 1721304428402.json
