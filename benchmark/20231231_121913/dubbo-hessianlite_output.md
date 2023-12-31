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
# Warmup Iteration   1: 2.670 ops/ms
Iteration   1: 6.295 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.295 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ops/ms
Iteration   1: 12.359 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.359 ops/ms


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
# Warmup Iteration   1: 4.366 ops/ms
Iteration   1: 9.260 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.260 ops/ms


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
# Warmup Iteration   1: 2.229 ops/ms
Iteration   1: 4.022 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.022 ops/ms


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.091 ms/op
Iteration   1: 2.974 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.974 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.028 ms/op
Iteration   1: 1.712 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.712 ms/op


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.050 ms/op
Iteration   1: 3.102 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.102 ms/op


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
# Warmup Iteration   1: 13.751 ±(99.9%) 0.307 ms/op
Iteration   1: 8.997 ±(99.9%) 0.155 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.997 ms/op


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.111 ms/op
Iteration   1: 3.145 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.878 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 14.059 ms/op
                 createUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10145
  mean =      3.145 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1743 
    [ 2.500,  3.750) = 6949 
    [ 3.750,  5.000) = 1168 
    [ 5.000,  6.250) = 150 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.878 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     14.059 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.076 ms/op
Iteration   1: 1.951 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   4.745 ms/op
                 existUser·p0.999:  6.099 ms/op
                 existUser·p0.9999: 7.006 ms/op
                 existUser·p1.00:   7.242 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16381
  mean =      1.951 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 62 
    [1.000, 1.500) = 1868 
    [1.500, 2.000) = 8348 
    [2.000, 2.500) = 5027 
    [2.500, 3.000) = 532 
    [3.000, 3.500) = 180 
    [3.500, 4.000) = 72 
    [4.000, 4.500) = 93 
    [4.500, 5.000) = 117 
    [5.000, 5.500) = 36 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.745 ms/op
     p(99.9000) =      6.099 ms/op
     p(99.9900) =      7.006 ms/op
     p(99.9990) =      7.242 ms/op
     p(99.9999) =      7.242 ms/op
    p(100.0000) =      7.242 ms/op


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.127 ms/op
Iteration   1: 3.309 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.121 ms/op
                 getUser·p0.999:  7.995 ms/op
                 getUser·p0.9999: 12.337 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9682
  mean =      3.309 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1271 
    [ 2.500,  3.750) = 6284 
    [ 3.750,  5.000) = 1848 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.121 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     12.337 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


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
# Warmup Iteration   1: 12.523 ±(99.9%) 0.460 ms/op
Iteration   1: 7.826 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   7.438 ms/op
                 listUser·p0.90:   10.486 ms/op
                 listUser·p0.95:   11.757 ms/op
                 listUser·p0.99:   16.645 ms/op
                 listUser·p0.999:  20.473 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4107
  mean =      7.826 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 188 
    [ 5.000,  7.500) = 1923 
    [ 7.500, 10.000) = 1462 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.777 ms/op
     p(50.0000) =      7.438 ms/op
     p(90.0000) =     10.486 ms/op
     p(95.0000) =     11.757 ms/op
     p(99.0000) =     16.645 ms/op
     p(99.9000) =     20.473 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.295          ops/ms
Client.existUser                       thrpt         12.359          ops/ms
Client.getUser                         thrpt          9.260          ops/ms
Client.listUser                        thrpt          4.022          ops/ms
Client.createUser                       avgt          2.974           ms/op
Client.existUser                        avgt          1.712           ms/op
Client.getUser                          avgt          3.102           ms/op
Client.listUser                         avgt          8.997           ms/op
Client.createUser                     sample  10145   3.145 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.059           ms/op
Client.createUser:createUser·p0.50    sample          3.002           ms/op
Client.createUser:createUser·p0.90    sample          3.928           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          6.878           ms/op
Client.createUser:createUser·p0.999   sample         11.420           ms/op
Client.createUser:createUser·p0.9999  sample         14.059           ms/op
Client.createUser:createUser·p1.00    sample         14.090           ms/op
Client.existUser                      sample  16381   1.951 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.673           ms/op
Client.existUser:existUser·p0.50      sample          1.892           ms/op
Client.existUser:existUser·p0.90      sample          2.372           ms/op
Client.existUser:existUser·p0.95      sample          2.634           ms/op
Client.existUser:existUser·p0.99      sample          4.745           ms/op
Client.existUser:existUser·p0.999     sample          6.099           ms/op
Client.existUser:existUser·p0.9999    sample          7.006           ms/op
Client.existUser:existUser·p1.00      sample          7.242           ms/op
Client.getUser                        sample   9682   3.309 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.983           ms/op
Client.getUser:getUser·p0.50          sample          3.297           ms/op
Client.getUser:getUser·p0.90          sample          4.071           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          6.121           ms/op
Client.getUser:getUser·p0.999         sample          7.995           ms/op
Client.getUser:getUser·p0.9999        sample         12.337           ms/op
Client.getUser:getUser·p1.00          sample         12.337           ms/op
Client.listUser                       sample   4107   7.826 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.777           ms/op
Client.listUser:listUser·p0.50        sample          7.438           ms/op
Client.listUser:listUser·p0.90        sample         10.486           ms/op
Client.listUser:listUser·p0.95        sample         11.757           ms/op
Client.listUser:listUser·p0.99        sample         16.645           ms/op
Client.listUser:listUser·p0.999       sample         20.473           ms/op
Client.listUser:listUser·p0.9999      sample         21.823           ms/op
Client.listUser:listUser·p1.00        sample         21.823           ms/op
