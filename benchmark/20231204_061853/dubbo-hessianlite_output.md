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
# Warmup Iteration   1: 2.268 ops/ms
Iteration   1: 5.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.761 ops/ms


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
# Warmup Iteration   1: 5.556 ops/ms
Iteration   1: 13.244 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.244 ops/ms


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
# Warmup Iteration   1: 3.671 ops/ms
Iteration   1: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.118 ops/ms


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
# Warmup Iteration   1: 2.054 ops/ms
Iteration   1: 3.681 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.681 ops/ms


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
# Warmup Iteration   1: 5.475 ±(99.9%) 0.076 ms/op
Iteration   1: 3.003 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.003 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.047 ms/op
Iteration   1: 1.881 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.074 ms/op
Iteration   1: 3.285 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.285 ms/op


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
# Warmup Iteration   1: 12.993 ±(99.9%) 0.320 ms/op
Iteration   1: 10.079 ±(99.9%) 0.136 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.079 ms/op


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.186 ms/op
Iteration   1: 3.250 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   10.440 ms/op
                 createUser·p0.999:  14.483 ms/op
                 createUser·p0.9999: 14.615 ms/op
                 createUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9881
  mean =      3.250 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2262 
    [ 2.500,  3.750) = 5673 
    [ 3.750,  5.000) = 1553 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =     10.440 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.062 ms/op
Iteration   1: 1.981 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  36.408 ms/op
                 existUser·p0.9999: 37.628 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16226
  mean =      1.981 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15195 
    [ 2.500,  5.000) = 864 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     36.408 ms/op
     p(99.9900) =     37.628 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.102 ms/op
Iteration   1: 3.319 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  7.179 ms/op
                 getUser·p0.9999: 8.700 ms/op
                 getUser·p1.00:   8.700 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9614
  mean =      3.319 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 50 
    [1.500, 2.000) = 194 
    [2.000, 2.500) = 960 
    [2.500, 3.000) = 1926 
    [3.000, 3.500) = 2650 
    [3.500, 4.000) = 2459 
    [4.000, 4.500) = 905 
    [4.500, 5.000) = 267 
    [5.000, 5.500) = 59 
    [5.500, 6.000) = 84 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 8 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      7.179 ms/op
     p(99.9900) =      8.700 ms/op
     p(99.9990) =      8.700 ms/op
     p(99.9999) =      8.700 ms/op
    p(100.0000) =      8.700 ms/op


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
# Warmup Iteration   1: 15.405 ±(99.9%) 0.641 ms/op
Iteration   1: 8.342 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   3.564 ms/op
                 listUser·p0.50:   7.930 ms/op
                 listUser·p0.90:   10.519 ms/op
                 listUser·p0.95:   12.027 ms/op
                 listUser·p0.99:   21.013 ms/op
                 listUser·p0.999:  25.394 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3838
  mean =      8.342 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 1457 
    [ 7.500, 10.000) = 1812 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      3.564 ms/op
     p(50.0000) =      7.930 ms/op
     p(90.0000) =     10.519 ms/op
     p(95.0000) =     12.027 ms/op
     p(99.0000) =     21.013 ms/op
     p(99.9000) =     25.394 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.761          ops/ms
Client.existUser                       thrpt         13.244          ops/ms
Client.getUser                         thrpt          8.118          ops/ms
Client.listUser                        thrpt          3.681          ops/ms
Client.createUser                       avgt          3.003           ms/op
Client.existUser                        avgt          1.881           ms/op
Client.getUser                          avgt          3.285           ms/op
Client.listUser                         avgt         10.079           ms/op
Client.createUser                     sample   9881   3.250 ± 0.046   ms/op
Client.createUser:createUser·p0.00    sample          1.401           ms/op
Client.createUser:createUser·p0.50    sample          2.949           ms/op
Client.createUser:createUser·p0.90    sample          4.432           ms/op
Client.createUser:createUser·p0.95    sample          4.874           ms/op
Client.createUser:createUser·p0.99    sample         10.440           ms/op
Client.createUser:createUser·p0.999   sample         14.483           ms/op
Client.createUser:createUser·p0.9999  sample         14.615           ms/op
Client.createUser:createUser·p1.00    sample         14.615           ms/op
Client.existUser                      sample  16226   1.981 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample          0.542           ms/op
Client.existUser:existUser·p0.50      sample          1.812           ms/op
Client.existUser:existUser·p0.90      sample          2.322           ms/op
Client.existUser:existUser·p0.95      sample          2.638           ms/op
Client.existUser:existUser·p0.99      sample          5.079           ms/op
Client.existUser:existUser·p0.999     sample         36.408           ms/op
Client.existUser:existUser·p0.9999    sample         37.628           ms/op
Client.existUser:existUser·p1.00      sample         38.076           ms/op
Client.getUser                        sample   9614   3.319 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.729           ms/op
Client.getUser:getUser·p0.50          sample          3.326           ms/op
Client.getUser:getUser·p0.90          sample          4.137           ms/op
Client.getUser:getUser·p0.95          sample          4.473           ms/op
Client.getUser:getUser·p0.99          sample          5.677           ms/op
Client.getUser:getUser·p0.999         sample          7.179           ms/op
Client.getUser:getUser·p0.9999        sample          8.700           ms/op
Client.getUser:getUser·p1.00          sample          8.700           ms/op
Client.listUser                       sample   3838   8.342 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          3.564           ms/op
Client.listUser:listUser·p0.50        sample          7.930           ms/op
Client.listUser:listUser·p0.90        sample         10.519           ms/op
Client.listUser:listUser·p0.95        sample         12.027           ms/op
Client.listUser:listUser·p0.99        sample         21.013           ms/op
Client.listUser:listUser·p0.999       sample         25.394           ms/op
Client.listUser:listUser·p0.9999      sample         26.870           ms/op
Client.listUser:listUser·p1.00        sample         26.870           ms/op
