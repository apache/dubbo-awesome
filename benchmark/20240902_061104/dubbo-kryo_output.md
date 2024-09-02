# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.763 ops/ms
Iteration   1: 7.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.436 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ops/ms
Iteration   1: 13.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.282 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.380 ops/ms
Iteration   1: 14.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.007 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ops/ms
Iteration   1: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.643 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.061 ms/op
Iteration   1: 2.081 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.788 ±(99.9%) 0.045 ms/op
Iteration   1: 1.679 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.057 ms/op
Iteration   1: 2.403 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.403 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.141 ms/op
Iteration   1: 3.567 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ±(99.9%) 0.133 ms/op
Iteration   1: 2.618 ±(99.9%) 0.081 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.363 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  52.872 ms/op
                 createUser·p0.9999: 62.623 ms/op
                 createUser·p1.00:   62.652 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12207
  mean =      2.618 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12043 
    [ 5.000, 10.000) = 80 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.363 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     52.872 ms/op
     p(99.9900) =     62.623 ms/op
     p(99.9990) =     62.652 ms/op
     p(99.9999) =     62.652 ms/op
    p(100.0000) =     62.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ±(99.9%) 0.076 ms/op
Iteration   1: 1.992 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  15.188 ms/op
                 existUser·p0.9999: 16.403 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16092
  mean =      1.992 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 15218 
    [ 2.500,  3.750) = 577 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     16.403 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ±(99.9%) 0.076 ms/op
Iteration   1: 2.030 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   1.891 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  15.454 ms/op
                 getUser·p0.9999: 16.430 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15742
  mean =      2.030 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 290 
    [ 1.250,  2.500) = 12627 
    [ 2.500,  3.750) = 2518 
    [ 3.750,  5.000) = 187 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      1.891 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     15.454 ms/op
     p(99.9900) =     16.430 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.129 ms/op
Iteration   1: 3.020 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.437 ms/op
                 listUser·p0.95:   3.809 ms/op
                 listUser·p0.99:   4.899 ms/op
                 listUser·p0.999:  7.075 ms/op
                 listUser·p0.9999: 8.883 ms/op
                 listUser·p1.00:   8.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10589
  mean =      3.020 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 7 
    [2.000, 2.500) = 103 
    [2.500, 3.000) = 6733 
    [3.000, 3.500) = 2764 
    [3.500, 4.000) = 621 
    [4.000, 4.500) = 135 
    [4.500, 5.000) = 150 
    [5.000, 5.500) = 44 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 8 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =      8.883 ms/op
     p(99.9990) =      8.897 ms/op
     p(99.9999) =      8.897 ms/op
    p(100.0000) =      8.897 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.436          ops/ms
ClientSimple.existUser                       thrpt         13.282          ops/ms
ClientSimple.getUser                         thrpt         14.007          ops/ms
ClientSimple.listUser                        thrpt          8.643          ops/ms
ClientSimple.createUser                       avgt          2.081           ms/op
ClientSimple.existUser                        avgt          1.679           ms/op
ClientSimple.getUser                          avgt          2.403           ms/op
ClientSimple.listUser                         avgt          3.567           ms/op
ClientSimple.createUser                     sample  12207   2.618 ± 0.081   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.995           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.232           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.210           ms/op
ClientSimple.createUser:createUser·p0.999   sample         52.872           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         62.623           ms/op
ClientSimple.createUser:createUser·p1.00    sample         62.652           ms/op
ClientSimple.existUser                      sample  16092   1.992 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.765           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.871           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.188           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.403           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.433           ms/op
ClientSimple.getUser                        sample  15742   2.030 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.900           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.891           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.121           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.454           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.430           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.515           ms/op
ClientSimple.listUser                       sample  10589   3.020 ± 0.014   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.800           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.912           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.075           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.883           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.897           ms/op

Benchmark result is saved to 1725257202773.json
