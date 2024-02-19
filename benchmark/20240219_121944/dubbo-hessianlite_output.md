# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.482 ops/ms
Iteration   1: 6.785 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.785 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ops/ms
Iteration   1: 12.276 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.276 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ops/ms
Iteration   1: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.798 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.260 ops/ms
Iteration   1: 3.746 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.746 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.073 ms/op
Iteration   1: 3.246 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.246 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ±(99.9%) 0.032 ms/op
Iteration   1: 2.012 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.012 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.448 ±(99.9%) 0.041 ms/op
Iteration   1: 2.719 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.719 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.201 ±(99.9%) 0.219 ms/op
Iteration   1: 7.302 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.594 ±(99.9%) 0.096 ms/op
Iteration   1: 2.869 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  29.220 ms/op
                 createUser·p0.9999: 32.921 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11144
  mean =      2.869 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3494 
    [ 2.500,  5.000) = 7418 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     29.220 ms/op
     p(99.9900) =     32.921 ms/op
     p(99.9990) =     32.932 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ±(99.9%) 0.073 ms/op
Iteration   1: 1.927 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.753 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 15.479 ms/op
                 existUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16596
  mean =      1.927 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1170 
    [ 1.250,  2.500) = 12524 
    [ 2.500,  3.750) = 2757 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     15.479 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ±(99.9%) 0.096 ms/op
Iteration   1: 3.230 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   4.045 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  7.586 ms/op
                 getUser·p0.9999: 8.880 ms/op
                 getUser·p1.00:   8.880 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9913
  mean =      3.230 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 89 
    [2.000, 2.500) = 1311 
    [2.500, 3.000) = 2517 
    [3.000, 3.500) = 3037 
    [3.500, 4.000) = 1831 
    [4.000, 4.500) = 706 
    [4.500, 5.000) = 219 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 25 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 17 
    [7.000, 7.500) = 42 
    [7.500, 8.000) = 15 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.045 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =      8.880 ms/op
     p(99.9990) =      8.880 ms/op
     p(99.9999) =      8.880 ms/op
    p(100.0000) =      8.880 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.555 ±(99.9%) 0.518 ms/op
Iteration   1: 7.745 ±(99.9%) 0.107 ms/op
                 listUser·p0.00:   2.822 ms/op
                 listUser·p0.50:   7.447 ms/op
                 listUser·p0.90:   9.978 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   15.360 ms/op
                 listUser·p0.999:  23.675 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4120
  mean =      7.745 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 137 
    [ 5.000,  7.500) = 1992 
    [ 7.500, 10.000) = 1586 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.822 ms/op
     p(50.0000) =      7.447 ms/op
     p(90.0000) =      9.978 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     15.360 ms/op
     p(99.9000) =     23.675 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.785          ops/ms
Client.existUser                       thrpt         12.276          ops/ms
Client.getUser                         thrpt          9.798          ops/ms
Client.listUser                        thrpt          3.746          ops/ms
Client.createUser                       avgt          3.246           ms/op
Client.existUser                        avgt          2.012           ms/op
Client.getUser                          avgt          2.719           ms/op
Client.listUser                         avgt          7.302           ms/op
Client.createUser                     sample  11144   2.869 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          0.949           ms/op
Client.createUser:createUser·p0.50    sample          2.638           ms/op
Client.createUser:createUser·p0.90    sample          3.342           ms/op
Client.createUser:createUser·p0.95    sample          3.899           ms/op
Client.createUser:createUser·p0.99    sample          6.996           ms/op
Client.createUser:createUser·p0.999   sample         29.220           ms/op
Client.createUser:createUser·p0.9999  sample         32.921           ms/op
Client.createUser:createUser·p1.00    sample         32.932           ms/op
Client.existUser                      sample  16596   1.927 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.768           ms/op
Client.existUser:existUser·p0.50      sample          1.722           ms/op
Client.existUser:existUser·p0.90      sample          2.753           ms/op
Client.existUser:existUser·p0.95      sample          3.011           ms/op
Client.existUser:existUser·p0.99      sample          3.502           ms/op
Client.existUser:existUser·p0.999     sample         14.664           ms/op
Client.existUser:existUser·p0.9999    sample         15.479           ms/op
Client.existUser:existUser·p1.00      sample         15.598           ms/op
Client.getUser                        sample   9913   3.230 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.071           ms/op
Client.getUser:getUser·p0.50          sample          3.174           ms/op
Client.getUser:getUser·p0.90          sample          4.045           ms/op
Client.getUser:getUser·p0.95          sample          4.407           ms/op
Client.getUser:getUser·p0.99          sample          5.784           ms/op
Client.getUser:getUser·p0.999         sample          7.586           ms/op
Client.getUser:getUser·p0.9999        sample          8.880           ms/op
Client.getUser:getUser·p1.00          sample          8.880           ms/op
Client.listUser                       sample   4120   7.745 ± 0.107   ms/op
Client.listUser:listUser·p0.00        sample          2.822           ms/op
Client.listUser:listUser·p0.50        sample          7.447           ms/op
Client.listUser:listUser·p0.90        sample          9.978           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         15.360           ms/op
Client.listUser:listUser·p0.999       sample         23.675           ms/op
Client.listUser:listUser·p0.9999      sample         25.461           ms/op
Client.listUser:listUser·p1.00        sample         25.461           ms/op
