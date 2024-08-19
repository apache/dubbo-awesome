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
# Warmup Iteration   1: 1.840 ops/ms
Iteration   1: 7.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.380 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.993 ops/ms
Iteration   1: 11.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.432 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.259 ops/ms
Iteration   1: 14.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.719 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.912 ops/ms
Iteration   1: 8.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.500 ops/ms


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.104 ms/op
Iteration   1: 2.162 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.162 ms/op


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
# Warmup Iteration   1: 2.917 ±(99.9%) 0.045 ms/op
Iteration   1: 1.672 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.672 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.057 ms/op
Iteration   1: 1.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.953 ms/op


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
# Warmup Iteration   1: 4.545 ±(99.9%) 0.108 ms/op
Iteration   1: 3.678 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.678 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.110 ms/op
Iteration   1: 2.412 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   9.100 ms/op
                 createUser·p0.999:  34.324 ms/op
                 createUser·p0.9999: 35.548 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13256
  mean =      2.412 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9791 
    [ 2.500,  5.000) = 3198 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      9.100 ms/op
     p(99.9000) =     34.324 ms/op
     p(99.9900) =     35.548 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.108 ms/op
Iteration   1: 2.307 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.175 ms/op
                 existUser·p0.90:   2.765 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  20.054 ms/op
                 existUser·p0.9999: 20.429 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13890
  mean =      2.307 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10884 
    [ 2.500,  5.000) = 2834 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     20.429 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.076 ms/op
Iteration   1: 2.180 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   0.439 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  62.194 ms/op
                 getUser·p0.9999: 77.991 ms/op
                 getUser·p1.00:   81.789 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14749
  mean =      2.180 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14618 
    [ 5.000, 10.000) = 47 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 4 
    [65.000, 70.000) = 2 
    [70.000, 75.000) = 9 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     62.194 ms/op
     p(99.9900) =     77.991 ms/op
     p(99.9990) =     81.789 ms/op
     p(99.9999) =     81.789 ms/op
    p(100.0000) =     81.789 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.141 ms/op
Iteration   1: 3.229 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.707 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  14.518 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9894
  mean =      3.229 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 509 
    [ 2.500,  3.750) = 7163 
    [ 3.750,  5.000) = 2017 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     14.518 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.380          ops/ms
ClientSimple.existUser                       thrpt         11.432          ops/ms
ClientSimple.getUser                         thrpt         14.719          ops/ms
ClientSimple.listUser                        thrpt          8.500          ops/ms
ClientSimple.createUser                       avgt          2.162           ms/op
ClientSimple.existUser                        avgt          1.672           ms/op
ClientSimple.getUser                          avgt          1.953           ms/op
ClientSimple.listUser                         avgt          3.678           ms/op
ClientSimple.createUser                     sample  13256   2.412 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.100           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.324           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.548           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.783           ms/op
ClientSimple.existUser                      sample  13890   2.307 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.831           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.765           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.015           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.054           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.429           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.480           ms/op
ClientSimple.getUser                        sample  14749   2.180 ± 0.079   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.439           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.571           ms/op
ClientSimple.getUser:getUser·p0.999         sample         62.194           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         77.991           ms/op
ClientSimple.getUser:getUser·p1.00          sample         81.789           ms/op
ClientSimple.listUser                       sample   9894   3.229 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.707           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.884           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.382           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.518           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.908           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.908           ms/op

Benchmark result is saved to 1724026645978.json
