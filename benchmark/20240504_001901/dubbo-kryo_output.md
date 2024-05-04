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
# Warmup Iteration   1: 2.137 ops/ms
Iteration   1: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.759 ops/ms


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
# Warmup Iteration   1: 6.456 ops/ms
Iteration   1: 14.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.838 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ops/ms
Iteration   1: 15.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.665 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ops/ms
Iteration   1: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.265 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ±(99.9%) 0.057 ms/op
Iteration   1: 2.004 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.004 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.755 ±(99.9%) 0.045 ms/op
Iteration   1: 1.774 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.774 ms/op


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
# Warmup Iteration   1: 2.739 ±(99.9%) 0.043 ms/op
Iteration   1: 1.754 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.754 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.070 ms/op
Iteration   1: 2.859 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.859 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.084 ms/op
Iteration   1: 2.028 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   1.726 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15814
  mean =      2.028 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13694 
    [ 2.500,  5.000) = 1863 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ±(99.9%) 0.059 ms/op
Iteration   1: 1.914 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.046 ms/op
                 existUser·p0.999:  15.434 ms/op
                 existUser·p0.9999: 16.776 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16736
  mean =      1.914 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 270 
    [ 1.250,  2.500) = 14744 
    [ 2.500,  3.750) = 1660 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.046 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     16.776 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ±(99.9%) 0.083 ms/op
Iteration   1: 1.700 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.525 ms/op
                 getUser·p0.50:   1.605 ms/op
                 getUser·p0.90:   2.050 ms/op
                 getUser·p0.95:   2.281 ms/op
                 getUser·p0.99:   2.891 ms/op
                 getUser·p0.999:  11.092 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18812
  mean =      1.700 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 17913 
    [ 2.500,  3.750) = 263 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      1.605 ms/op
     p(90.0000) =      2.050 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      2.891 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     11.567 ms/op
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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.093 ms/op
Iteration   1: 3.395 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.428 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.856 ms/op
                 listUser·p0.999:  26.116 ms/op
                 listUser·p0.9999: 26.575 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9416
  mean =      3.395 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2097 
    [ 2.500,  5.000) = 7022 
    [ 5.000,  7.500) = 231 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.856 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.759          ops/ms
ClientSimple.existUser                       thrpt         14.838          ops/ms
ClientSimple.getUser                         thrpt         15.665          ops/ms
ClientSimple.listUser                        thrpt          9.265          ops/ms
ClientSimple.createUser                       avgt          2.004           ms/op
ClientSimple.existUser                        avgt          1.774           ms/op
ClientSimple.getUser                          avgt          1.754           ms/op
ClientSimple.listUser                         avgt          2.859           ms/op
ClientSimple.createUser                     sample  15814   2.028 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.692           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.726           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.072           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.536           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.201           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.234           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.234           ms/op
ClientSimple.existUser                      sample  16736   1.914 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.466           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.046           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.434           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.776           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.876           ms/op
ClientSimple.getUser                        sample  18812   1.700 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.525           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.605           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.050           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.281           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.891           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.092           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.567           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.928           ms/op
ClientSimple.listUser                       sample   9416   3.395 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.468           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.428           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.856           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.116           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.575           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.575           ms/op

Benchmark result is saved to 1714781694656.json
