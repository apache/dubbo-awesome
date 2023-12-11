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
# Warmup Iteration   1: 2.171 ops/ms
Iteration   1: 6.364 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.364 ops/ms


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
# Warmup Iteration   1: 5.878 ops/ms
Iteration   1: 12.200 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.200 ops/ms


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
# Warmup Iteration   1: 4.591 ops/ms
Iteration   1: 9.511 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.511 ops/ms


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
# Warmup Iteration   1: 1.676 ops/ms
Iteration   1: 3.766 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.766 ops/ms


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.059 ms/op
Iteration   1: 2.694 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.694 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.031 ms/op
Iteration   1: 2.037 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.037 ms/op


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.040 ms/op
Iteration   1: 3.093 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.093 ms/op


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
# Warmup Iteration   1: 12.415 ±(99.9%) 0.371 ms/op
Iteration   1: 7.693 ±(99.9%) 0.132 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.693 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.124 ms/op
Iteration   1: 3.206 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.581 ms/op
                 createUser·p0.999:  9.314 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9969
  mean =      3.206 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 982 
    [ 2.500,  3.750) = 7691 
    [ 3.750,  5.000) = 1006 
    [ 5.000,  6.250) = 151 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.581 ms/op
     p(99.9000) =      9.314 ms/op
     p(99.9900) =     12.648 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.070 ms/op
Iteration   1: 1.864 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   2.841 ms/op
                 existUser·p0.999:  21.355 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17144
  mean =      1.864 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16552 
    [ 2.500,  5.000) = 560 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      2.841 ms/op
     p(99.9000) =     21.355 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.096 ms/op
Iteration   1: 2.873 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.871 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.783 ms/op
                 getUser·p0.99:   4.985 ms/op
                 getUser·p0.999:  6.746 ms/op
                 getUser·p0.9999: 10.207 ms/op
                 getUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11125
  mean =      2.873 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 468 
    [ 2.000,  3.000) = 6385 
    [ 3.000,  4.000) = 3913 
    [ 4.000,  5.000) = 250 
    [ 5.000,  6.000) = 83 
    [ 6.000,  7.000) = 23 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.783 ms/op
     p(99.0000) =      4.985 ms/op
     p(99.9000) =      6.746 ms/op
     p(99.9900) =     10.207 ms/op
     p(99.9990) =     10.584 ms/op
     p(99.9999) =     10.584 ms/op
    p(100.0000) =     10.584 ms/op


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
# Warmup Iteration   1: 12.337 ±(99.9%) 0.399 ms/op
Iteration   1: 7.186 ±(99.9%) 0.102 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   6.889 ms/op
                 listUser·p0.90:   9.437 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   14.296 ms/op
                 listUser·p0.999:  21.077 ms/op
                 listUser·p0.9999: 29.753 ms/op
                 listUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4448
  mean =      7.186 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 358 
    [ 5.000,  7.500) = 2512 
    [ 7.500, 10.000) = 1273 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      6.889 ms/op
     p(90.0000) =      9.437 ms/op
     p(95.0000) =     10.371 ms/op
     p(99.0000) =     14.296 ms/op
     p(99.9000) =     21.077 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.364          ops/ms
Client.existUser                       thrpt         12.200          ops/ms
Client.getUser                         thrpt          9.511          ops/ms
Client.listUser                        thrpt          3.766          ops/ms
Client.createUser                       avgt          2.694           ms/op
Client.existUser                        avgt          2.037           ms/op
Client.getUser                          avgt          3.093           ms/op
Client.listUser                         avgt          7.693           ms/op
Client.createUser                     sample   9969   3.206 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          0.927           ms/op
Client.createUser:createUser·p0.50    sample          3.117           ms/op
Client.createUser:createUser·p0.90    sample          3.875           ms/op
Client.createUser:createUser·p0.95    sample          4.317           ms/op
Client.createUser:createUser·p0.99    sample          6.581           ms/op
Client.createUser:createUser·p0.999   sample          9.314           ms/op
Client.createUser:createUser·p0.9999  sample         12.648           ms/op
Client.createUser:createUser·p1.00    sample         12.648           ms/op
Client.existUser                      sample  17144   1.864 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.683           ms/op
Client.existUser:existUser·p0.50      sample          1.767           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.417           ms/op
Client.existUser:existUser·p0.99      sample          2.841           ms/op
Client.existUser:existUser·p0.999     sample         21.355           ms/op
Client.existUser:existUser·p0.9999    sample         21.856           ms/op
Client.existUser:existUser·p1.00      sample         22.020           ms/op
Client.getUser                        sample  11125   2.873 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.673           ms/op
Client.getUser:getUser·p0.50          sample          2.871           ms/op
Client.getUser:getUser·p0.90          sample          3.473           ms/op
Client.getUser:getUser·p0.95          sample          3.783           ms/op
Client.getUser:getUser·p0.99          sample          4.985           ms/op
Client.getUser:getUser·p0.999         sample          6.746           ms/op
Client.getUser:getUser·p0.9999        sample         10.207           ms/op
Client.getUser:getUser·p1.00          sample         10.584           ms/op
Client.listUser                       sample   4448   7.186 ± 0.102   ms/op
Client.listUser:listUser·p0.00        sample          2.232           ms/op
Client.listUser:listUser·p0.50        sample          6.889           ms/op
Client.listUser:listUser·p0.90        sample          9.437           ms/op
Client.listUser:listUser·p0.95        sample         10.371           ms/op
Client.listUser:listUser·p0.99        sample         14.296           ms/op
Client.listUser:listUser·p0.999       sample         21.077           ms/op
Client.listUser:listUser·p0.9999      sample         29.753           ms/op
Client.listUser:listUser·p1.00        sample         29.753           ms/op
