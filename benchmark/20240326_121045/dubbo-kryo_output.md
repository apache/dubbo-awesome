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
# Warmup Iteration   1: 2.265 ops/ms
Iteration   1: 6.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.693 ops/ms


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
# Warmup Iteration   1: 5.409 ops/ms
Iteration   1: 12.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.443 ops/ms


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
# Warmup Iteration   1: 5.472 ops/ms
Iteration   1: 13.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.339 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ops/ms
Iteration   1: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.610 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ±(99.9%) 0.066 ms/op
Iteration   1: 2.275 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.275 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ±(99.9%) 0.042 ms/op
Iteration   1: 1.773 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.773 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ±(99.9%) 0.058 ms/op
Iteration   1: 2.391 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.391 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.073 ms/op
Iteration   1: 3.496 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.496 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.074 ms/op
Iteration   1: 2.123 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   1.903 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.695 ms/op
                 createUser·p0.99:   4.726 ms/op
                 createUser·p0.999:  36.438 ms/op
                 createUser·p0.9999: 37.468 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15408
  mean =      2.123 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14071 
    [ 2.500,  5.000) = 1192 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.726 ms/op
     p(99.9000) =     36.438 ms/op
     p(99.9900) =     37.468 ms/op
     p(99.9990) =     38.142 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ±(99.9%) 0.074 ms/op
Iteration   1: 2.079 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.040 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.335 ms/op
                 existUser·p0.999:  15.574 ms/op
                 existUser·p0.9999: 16.030 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15416
  mean =      2.079 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 258 
    [ 1.250,  2.500) = 13935 
    [ 2.500,  3.750) = 1114 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.335 ms/op
     p(99.9000) =     15.574 ms/op
     p(99.9900) =     16.030 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ±(99.9%) 0.095 ms/op
Iteration   1: 1.937 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   1.840 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   3.970 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 12.577 ms/op
                 getUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16608
  mean =      1.937 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 482 
    [ 1.250,  2.500) = 14609 
    [ 2.500,  3.750) = 1342 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.840 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.970 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     12.577 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.122 ms/op
Iteration   1: 3.716 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  26.280 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8601
  mean =      3.716 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1114 
    [ 2.500,  5.000) = 7096 
    [ 5.000,  7.500) = 340 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     26.280 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.693          ops/ms
ClientSimple.existUser                       thrpt         12.443          ops/ms
ClientSimple.getUser                         thrpt         13.339          ops/ms
ClientSimple.listUser                        thrpt          8.610          ops/ms
ClientSimple.createUser                       avgt          2.275           ms/op
ClientSimple.existUser                        avgt          1.773           ms/op
ClientSimple.getUser                          avgt          2.391           ms/op
ClientSimple.listUser                         avgt          3.496           ms/op
ClientSimple.createUser                     sample  15408   2.123 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.903           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.438           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.468           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.142           ms/op
ClientSimple.existUser                      sample  15416   2.079 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.621           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.040           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.335           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.574           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.030           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.269           ms/op
ClientSimple.getUser                        sample  16608   1.937 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.594           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.840           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.970           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.732           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.577           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.779           ms/op
ClientSimple.listUser                       sample   8601   3.716 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.856           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.756           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.275           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.280           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.673           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.673           ms/op

Benchmark result is saved to 1711454810879.json
