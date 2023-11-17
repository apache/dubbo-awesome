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
# Warmup Iteration   1: 2.514 ops/ms
Iteration   1: 5.981 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.981 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ops/ms
Iteration   1: 13.465 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.465 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ops/ms
Iteration   1: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.705 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
Iteration   1: 3.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.615 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.864 ±(99.9%) 0.089 ms/op
Iteration   1: 3.487 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.487 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ±(99.9%) 0.047 ms/op
Iteration   1: 2.003 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.003 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.073 ms/op
Iteration   1: 2.829 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.829 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.204 ±(99.9%) 0.223 ms/op
Iteration   1: 8.774 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.774 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.097 ms/op
Iteration   1: 3.161 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10075
  mean =      3.161 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1382 
    [ 2.500,  3.750) = 7484 
    [ 3.750,  5.000) = 915 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.061 ms/op
Iteration   1: 1.744 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 15.313 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18443
  mean =      1.744 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1757 
    [ 1.250,  2.500) = 15814 
    [ 2.500,  3.750) = 704 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     15.313 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.099 ms/op
Iteration   1: 3.240 ±(99.9%) 0.047 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.004 ms/op
                 getUser·p0.99:   10.357 ms/op
                 getUser·p0.999:  15.368 ms/op
                 getUser·p0.9999: 15.598 ms/op
                 getUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9883
  mean =      3.240 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 2106 
    [ 2.500,  3.750) = 5708 
    [ 3.750,  5.000) = 1414 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.004 ms/op
     p(99.0000) =     10.357 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     15.598 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 13.503 ±(99.9%) 0.471 ms/op
Iteration   1: 8.056 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   7.758 ms/op
                 listUser·p0.90:   10.532 ms/op
                 listUser·p0.95:   11.911 ms/op
                 listUser·p0.99:   16.244 ms/op
                 listUser·p0.999:  23.305 ms/op
                 listUser·p0.9999: 28.770 ms/op
                 listUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3951
  mean =      8.056 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 107 
    [ 5.000,  7.500) = 1628 
    [ 7.500, 10.000) = 1684 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      7.758 ms/op
     p(90.0000) =     10.532 ms/op
     p(95.0000) =     11.911 ms/op
     p(99.0000) =     16.244 ms/op
     p(99.9000) =     23.305 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.981          ops/ms
Client.existUser                       thrpt         13.465          ops/ms
Client.getUser                         thrpt          7.705          ops/ms
Client.listUser                        thrpt          3.615          ops/ms
Client.createUser                       avgt          3.487           ms/op
Client.existUser                        avgt          2.003           ms/op
Client.getUser                          avgt          2.829           ms/op
Client.listUser                         avgt          8.774           ms/op
Client.createUser                     sample  10075   3.161 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          0.741           ms/op
Client.createUser:createUser·p0.50    sample          2.945           ms/op
Client.createUser:createUser·p0.90    sample          3.817           ms/op
Client.createUser:createUser·p0.95    sample          4.133           ms/op
Client.createUser:createUser·p0.99    sample          7.537           ms/op
Client.createUser:createUser·p0.999   sample         18.547           ms/op
Client.createUser:createUser·p0.9999  sample         18.678           ms/op
Client.createUser:createUser·p1.00    sample         18.678           ms/op
Client.existUser                      sample  18443   1.744 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.751           ms/op
Client.existUser:existUser·p0.50      sample          1.589           ms/op
Client.existUser:existUser·p0.90      sample          2.249           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          3.572           ms/op
Client.existUser:existUser·p0.999     sample         15.155           ms/op
Client.existUser:existUser·p0.9999    sample         15.313           ms/op
Client.existUser:existUser·p1.00      sample         15.368           ms/op
Client.getUser                        sample   9883   3.240 ± 0.047   ms/op
Client.getUser:getUser·p0.00          sample          0.609           ms/op
Client.getUser:getUser·p0.50          sample          3.076           ms/op
Client.getUser:getUser·p0.90          sample          4.366           ms/op
Client.getUser:getUser·p0.95          sample          5.004           ms/op
Client.getUser:getUser·p0.99          sample         10.357           ms/op
Client.getUser:getUser·p0.999         sample         15.368           ms/op
Client.getUser:getUser·p0.9999        sample         15.598           ms/op
Client.getUser:getUser·p1.00          sample         15.598           ms/op
Client.listUser                       sample   3951   8.056 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          1.450           ms/op
Client.listUser:listUser·p0.50        sample          7.758           ms/op
Client.listUser:listUser·p0.90        sample         10.532           ms/op
Client.listUser:listUser·p0.95        sample         11.911           ms/op
Client.listUser:listUser·p0.99        sample         16.244           ms/op
Client.listUser:listUser·p0.999       sample         23.305           ms/op
Client.listUser:listUser·p0.9999      sample         28.770           ms/op
Client.listUser:listUser·p1.00        sample         28.770           ms/op
