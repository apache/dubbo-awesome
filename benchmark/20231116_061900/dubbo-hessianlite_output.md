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
# Warmup Iteration   1: 2.358 ops/ms
Iteration   1: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.415 ops/ms


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
# Warmup Iteration   1: 5.784 ops/ms
Iteration   1: 13.182 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.182 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ops/ms
Iteration   1: 9.531 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.531 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.136 ops/ms
Iteration   1: 3.270 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.270 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ±(99.9%) 0.071 ms/op
Iteration   1: 3.026 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.026 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.417 ±(99.9%) 0.040 ms/op
Iteration   1: 1.892 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.892 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.067 ms/op
Iteration   1: 2.892 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.892 ms/op


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
# Warmup Iteration   1: 10.418 ±(99.9%) 0.181 ms/op
Iteration   1: 7.915 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.915 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.102 ms/op
Iteration   1: 2.924 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   7.870 ms/op
                 createUser·p0.999:  19.696 ms/op
                 createUser·p0.9999: 21.524 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10932
  mean =      2.924 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4667 
    [ 2.500,  5.000) = 5908 
    [ 5.000,  7.500) = 213 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.870 ms/op
     p(99.9000) =     19.696 ms/op
     p(99.9900) =     21.524 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ±(99.9%) 0.078 ms/op
Iteration   1: 2.023 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.011 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.782 ms/op
                 existUser·p0.99:   3.935 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 10.378 ms/op
                 existUser·p1.00:   10.387 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15937
  mean =      2.023 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 32 
    [ 1.000,  2.000) = 7809 
    [ 2.000,  3.000) = 7628 
    [ 3.000,  4.000) = 326 
    [ 4.000,  5.000) = 67 
    [ 5.000,  6.000) = 26 
    [ 6.000,  7.000) = 11 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.782 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     10.378 ms/op
     p(99.9990) =     10.387 ms/op
     p(99.9999) =     10.387 ms/op
    p(100.0000) =     10.387 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.096 ms/op
Iteration   1: 3.149 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   10.680 ms/op
                 getUser·p0.999:  14.921 ms/op
                 getUser·p0.9999: 16.660 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10155
  mean =      3.149 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 2735 
    [ 2.500,  3.750) = 5913 
    [ 3.750,  5.000) = 1073 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     10.680 ms/op
     p(99.9000) =     14.921 ms/op
     p(99.9900) =     16.660 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.899 ±(99.9%) 0.310 ms/op
Iteration   1: 8.095 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   7.692 ms/op
                 listUser·p0.90:   10.715 ms/op
                 listUser·p0.95:   11.715 ms/op
                 listUser·p0.99:   15.491 ms/op
                 listUser·p0.999:  17.004 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3947
  mean =      8.095 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 8 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 1198 
    [ 7.500,  8.750) = 1013 
    [ 8.750, 10.000) = 563 
    [10.000, 11.250) = 349 
    [11.250, 12.500) = 154 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.941 ms/op
     p(50.0000) =      7.692 ms/op
     p(90.0000) =     10.715 ms/op
     p(95.0000) =     11.715 ms/op
     p(99.0000) =     15.491 ms/op
     p(99.9000) =     17.004 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.415          ops/ms
Client.existUser                       thrpt         13.182          ops/ms
Client.getUser                         thrpt          9.531          ops/ms
Client.listUser                        thrpt          3.270          ops/ms
Client.createUser                       avgt          3.026           ms/op
Client.existUser                        avgt          1.892           ms/op
Client.getUser                          avgt          2.892           ms/op
Client.listUser                         avgt          7.915           ms/op
Client.createUser                     sample  10932   2.924 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.985           ms/op
Client.createUser:createUser·p0.50    sample          2.683           ms/op
Client.createUser:createUser·p0.90    sample          3.916           ms/op
Client.createUser:createUser·p0.95    sample          4.506           ms/op
Client.createUser:createUser·p0.99    sample          7.870           ms/op
Client.createUser:createUser·p0.999   sample         19.696           ms/op
Client.createUser:createUser·p0.9999  sample         21.524           ms/op
Client.createUser:createUser·p1.00    sample         21.594           ms/op
Client.existUser                      sample  15937   2.023 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.489           ms/op
Client.existUser:existUser·p0.50      sample          2.011           ms/op
Client.existUser:existUser·p0.90      sample          2.523           ms/op
Client.existUser:existUser·p0.95      sample          2.782           ms/op
Client.existUser:existUser·p0.99      sample          3.935           ms/op
Client.existUser:existUser·p0.999     sample         10.207           ms/op
Client.existUser:existUser·p0.9999    sample         10.378           ms/op
Client.existUser:existUser·p1.00      sample         10.387           ms/op
Client.getUser                        sample  10155   3.149 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample          0.650           ms/op
Client.getUser:getUser·p0.50          sample          2.933           ms/op
Client.getUser:getUser·p0.90          sample          4.026           ms/op
Client.getUser:getUser·p0.95          sample          4.719           ms/op
Client.getUser:getUser·p0.99          sample         10.680           ms/op
Client.getUser:getUser·p0.999         sample         14.921           ms/op
Client.getUser:getUser·p0.9999        sample         16.660           ms/op
Client.getUser:getUser·p1.00          sample         16.663           ms/op
Client.listUser                       sample   3947   8.095 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.941           ms/op
Client.listUser:listUser·p0.50        sample          7.692           ms/op
Client.listUser:listUser·p0.90        sample         10.715           ms/op
Client.listUser:listUser·p0.95        sample         11.715           ms/op
Client.listUser:listUser·p0.99        sample         15.491           ms/op
Client.listUser:listUser·p0.999       sample         17.004           ms/op
Client.listUser:listUser·p0.9999      sample         18.711           ms/op
Client.listUser:listUser·p1.00        sample         18.711           ms/op
