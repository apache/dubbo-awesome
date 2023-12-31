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
# Warmup Iteration   1: 2.154 ops/ms
Iteration   1: 5.979 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.979 ops/ms


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
# Warmup Iteration   1: 5.757 ops/ms
Iteration   1: 12.310 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.310 ops/ms


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
# Warmup Iteration   1: 3.632 ops/ms
Iteration   1: 8.526 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.526 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.888 ops/ms
Iteration   1: 3.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.344 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ±(99.9%) 0.067 ms/op
Iteration   1: 2.869 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.869 ms/op


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
# Warmup Iteration   1: 2.985 ±(99.9%) 0.028 ms/op
Iteration   1: 1.949 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.949 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.049 ms/op
Iteration   1: 3.205 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.205 ms/op


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
# Warmup Iteration   1: 12.840 ±(99.9%) 0.428 ms/op
Iteration   1: 8.531 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.531 ms/op


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.134 ms/op
Iteration   1: 2.806 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   6.276 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 16.073 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11388
  mean =      2.806 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 3454 
    [ 2.500,  3.750) = 7410 
    [ 3.750,  5.000) = 370 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      6.276 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.135 ±(99.9%) 0.077 ms/op
Iteration   1: 1.666 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.554 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.290 ms/op
                 existUser·p0.99:   2.771 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 21.108 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19249
  mean =      1.666 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18829 
    [ 2.500,  5.000) = 335 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.554 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.290 ms/op
     p(99.0000) =      2.771 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     21.108 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.102 ms/op
Iteration   1: 2.971 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.842 ms/op
                 getUser·p0.9999: 7.125 ms/op
                 getUser·p1.00:   7.127 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10755
  mean =      2.971 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 202 
    [2.000, 2.500) = 1957 
    [2.500, 3.000) = 3926 
    [3.000, 3.500) = 2866 
    [3.500, 4.000) = 1340 
    [4.000, 4.500) = 301 
    [4.500, 5.000) = 39 
    [5.000, 5.500) = 35 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      6.842 ms/op
     p(99.9900) =      7.125 ms/op
     p(99.9990) =      7.127 ms/op
     p(99.9999) =      7.127 ms/op
    p(100.0000) =      7.127 ms/op


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
# Warmup Iteration   1: 12.457 ±(99.9%) 0.472 ms/op
Iteration   1: 7.954 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   7.356 ms/op
                 listUser·p0.90:   11.403 ms/op
                 listUser·p0.95:   12.943 ms/op
                 listUser·p0.99:   15.593 ms/op
                 listUser·p0.999:  20.866 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4114
  mean =      7.954 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 234 
    [ 5.000,  7.500) = 1944 
    [ 7.500, 10.000) = 1208 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.564 ms/op
     p(50.0000) =      7.356 ms/op
     p(90.0000) =     11.403 ms/op
     p(95.0000) =     12.943 ms/op
     p(99.0000) =     15.593 ms/op
     p(99.9000) =     20.866 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.979          ops/ms
Client.existUser                       thrpt         12.310          ops/ms
Client.getUser                         thrpt          8.526          ops/ms
Client.listUser                        thrpt          3.344          ops/ms
Client.createUser                       avgt          2.869           ms/op
Client.existUser                        avgt          1.949           ms/op
Client.getUser                          avgt          3.205           ms/op
Client.listUser                         avgt          8.531           ms/op
Client.createUser                     sample  11388   2.806 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.001           ms/op
Client.createUser:createUser·p0.50    sample          2.626           ms/op
Client.createUser:createUser·p0.90    sample          3.211           ms/op
Client.createUser:createUser·p0.95    sample          3.604           ms/op
Client.createUser:createUser·p0.99    sample          6.276           ms/op
Client.createUser:createUser·p0.999   sample         16.040           ms/op
Client.createUser:createUser·p0.9999  sample         16.073           ms/op
Client.createUser:createUser·p1.00    sample         16.073           ms/op
Client.existUser                      sample  19249   1.666 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.665           ms/op
Client.existUser:existUser·p0.50      sample          1.554           ms/op
Client.existUser:existUser·p0.90      sample          2.101           ms/op
Client.existUser:existUser·p0.95      sample          2.290           ms/op
Client.existUser:existUser·p0.99      sample          2.771           ms/op
Client.existUser:existUser·p0.999     sample         20.120           ms/op
Client.existUser:existUser·p0.9999    sample         21.108           ms/op
Client.existUser:existUser·p1.00      sample         21.168           ms/op
Client.getUser                        sample  10755   2.971 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.771           ms/op
Client.getUser:getUser·p0.50          sample          2.900           ms/op
Client.getUser:getUser·p0.90          sample          3.690           ms/op
Client.getUser:getUser·p0.95          sample          3.903           ms/op
Client.getUser:getUser·p0.99          sample          4.637           ms/op
Client.getUser:getUser·p0.999         sample          6.842           ms/op
Client.getUser:getUser·p0.9999        sample          7.125           ms/op
Client.getUser:getUser·p1.00          sample          7.127           ms/op
Client.listUser                       sample   4114   7.954 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.564           ms/op
Client.listUser:listUser·p0.50        sample          7.356           ms/op
Client.listUser:listUser·p0.90        sample         11.403           ms/op
Client.listUser:listUser·p0.95        sample         12.943           ms/op
Client.listUser:listUser·p0.99        sample         15.593           ms/op
Client.listUser:listUser·p0.999       sample         20.866           ms/op
Client.listUser:listUser·p0.9999      sample         24.052           ms/op
Client.listUser:listUser·p1.00        sample         24.052           ms/op
