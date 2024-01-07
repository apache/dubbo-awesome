# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.436 ops/ms
Iteration   1: 5.739 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.739 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.556 ops/ms
Iteration   1: 14.876 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.876 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ops/ms
Iteration   1: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.891 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.496 ops/ms
Iteration   1: 4.159 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.159 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.138 ±(99.9%) 0.069 ms/op
Iteration   1: 2.712 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ±(99.9%) 0.027 ms/op
Iteration   1: 1.921 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.394 ±(99.9%) 0.042 ms/op
Iteration   1: 2.901 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.912 ±(99.9%) 0.277 ms/op
Iteration   1: 8.634 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.634 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.018 ±(99.9%) 0.104 ms/op
Iteration   1: 3.060 ±(99.9%) 0.063 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   5.039 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  31.359 ms/op
                 createUser·p0.9999: 31.944 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10457
  mean =      3.060 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3037 
    [ 2.500,  5.000) = 6890 
    [ 5.000,  7.500) = 343 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      5.039 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     31.359 ms/op
     p(99.9900) =     31.944 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ±(99.9%) 0.060 ms/op
Iteration   1: 2.156 ±(99.9%) 0.098 ms/op
                 existUser·p0.00:   0.480 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  68.585 ms/op
                 existUser·p0.9999: 70.268 ms/op
                 existUser·p1.00:   70.779 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14869
  mean =      2.156 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14736 
    [ 5.000, 10.000) = 44 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 24 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 18 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     68.585 ms/op
     p(99.9900) =     70.268 ms/op
     p(99.9990) =     70.779 ms/op
     p(99.9999) =     70.779 ms/op
    p(100.0000) =     70.779 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.102 ms/op
Iteration   1: 3.032 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.610 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 19.329 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10616
  mean =      3.032 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 2561 
    [ 2.500,  3.750) = 6816 
    [ 3.750,  5.000) = 956 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.610 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.329 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.834 ±(99.9%) 0.360 ms/op
Iteration   1: 7.554 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   7.242 ms/op
                 listUser·p0.90:   9.748 ms/op
                 listUser·p0.95:   10.746 ms/op
                 listUser·p0.99:   18.743 ms/op
                 listUser·p0.999:  23.667 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4241
  mean =      7.554 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 224 
    [ 5.000,  7.500) = 2175 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      7.242 ms/op
     p(90.0000) =      9.748 ms/op
     p(95.0000) =     10.746 ms/op
     p(99.0000) =     18.743 ms/op
     p(99.9000) =     23.667 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.739          ops/ms
Client.existUser                       thrpt         14.876          ops/ms
Client.getUser                         thrpt          9.891          ops/ms
Client.listUser                        thrpt          4.159          ops/ms
Client.createUser                       avgt          2.712           ms/op
Client.existUser                        avgt          1.921           ms/op
Client.getUser                          avgt          2.901           ms/op
Client.listUser                         avgt          8.634           ms/op
Client.createUser                     sample  10457   3.060 ± 0.063   ms/op
Client.createUser:createUser·p0.00    sample          1.159           ms/op
Client.createUser:createUser·p0.50    sample          2.671           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          5.039           ms/op
Client.createUser:createUser·p0.99    sample          8.667           ms/op
Client.createUser:createUser·p0.999   sample         31.359           ms/op
Client.createUser:createUser·p0.9999  sample         31.944           ms/op
Client.createUser:createUser·p1.00    sample         31.949           ms/op
Client.existUser                      sample  14869   2.156 ± 0.098   ms/op
Client.existUser:existUser·p0.00      sample          0.480           ms/op
Client.existUser:existUser·p0.50      sample          1.892           ms/op
Client.existUser:existUser·p0.90      sample          2.306           ms/op
Client.existUser:existUser·p0.95      sample          2.449           ms/op
Client.existUser:existUser·p0.99      sample          4.538           ms/op
Client.existUser:existUser·p0.999     sample         68.585           ms/op
Client.existUser:existUser·p0.9999    sample         70.268           ms/op
Client.existUser:existUser·p1.00      sample         70.779           ms/op
Client.getUser                        sample  10616   3.032 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          0.798           ms/op
Client.getUser:getUser·p0.50          sample          2.916           ms/op
Client.getUser:getUser·p0.90          sample          3.809           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          6.610           ms/op
Client.getUser:getUser·p0.999         sample         19.202           ms/op
Client.getUser:getUser·p0.9999        sample         19.329           ms/op
Client.getUser:getUser·p1.00          sample         19.333           ms/op
Client.listUser                       sample   4241   7.554 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          1.475           ms/op
Client.listUser:listUser·p0.50        sample          7.242           ms/op
Client.listUser:listUser·p0.90        sample          9.748           ms/op
Client.listUser:listUser·p0.95        sample         10.746           ms/op
Client.listUser:listUser·p0.99        sample         18.743           ms/op
Client.listUser:listUser·p0.999       sample         23.667           ms/op
Client.listUser:listUser·p0.9999      sample         26.280           ms/op
Client.listUser:listUser·p1.00        sample         26.280           ms/op
