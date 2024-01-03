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
# Warmup Iteration   1: 2.501 ops/ms
Iteration   1: 6.505 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.505 ops/ms


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
# Warmup Iteration   1: 5.362 ops/ms
Iteration   1: 16.029 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  16.029 ops/ms


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
# Warmup Iteration   1: 3.845 ops/ms
Iteration   1: 7.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.315 ops/ms


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
# Warmup Iteration   1: 2.207 ops/ms
Iteration   1: 3.550 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.550 ops/ms


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.073 ms/op
Iteration   1: 3.109 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.109 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.030 ms/op
Iteration   1: 1.917 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.917 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.056 ms/op
Iteration   1: 3.005 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.005 ms/op


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
# Warmup Iteration   1: 11.303 ±(99.9%) 0.197 ms/op
Iteration   1: 7.828 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.828 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.101 ms/op
Iteration   1: 2.850 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.744 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.614 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  11.269 ms/op
                 createUser·p0.9999: 12.528 ms/op
                 createUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11173
  mean =      2.850 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2870 
    [ 2.500,  3.750) = 7846 
    [ 3.750,  5.000) = 236 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      2.744 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.614 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     11.269 ms/op
     p(99.9900) =     12.528 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.063 ms/op
Iteration   1: 1.923 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.099 ms/op
                 existUser·p0.999:  21.496 ms/op
                 existUser·p0.9999: 21.770 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16615
  mean =      1.923 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15801 
    [ 2.500,  5.000) = 774 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.099 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     21.770 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.116 ms/op
Iteration   1: 3.242 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  6.954 ms/op
                 getUser·p0.9999: 9.650 ms/op
                 getUser·p1.00:   9.650 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9896
  mean =      3.242 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 140 
    [ 2.000,  3.000) = 3563 
    [ 3.000,  4.000) = 5074 
    [ 4.000,  5.000) = 924 
    [ 5.000,  6.000) = 99 
    [ 6.000,  7.000) = 86 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =      6.954 ms/op
     p(99.9900) =      9.650 ms/op
     p(99.9990) =      9.650 ms/op
     p(99.9999) =      9.650 ms/op
    p(100.0000) =      9.650 ms/op


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
# Warmup Iteration   1: 11.655 ±(99.9%) 0.388 ms/op
Iteration   1: 8.299 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   7.946 ms/op
                 listUser·p0.90:   10.945 ms/op
                 listUser·p0.95:   11.963 ms/op
                 listUser·p0.99:   16.362 ms/op
                 listUser·p0.999:  27.034 ms/op
                 listUser·p0.9999: 30.704 ms/op
                 listUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3856
  mean =      8.299 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 127 
    [ 5.000,  7.500) = 1389 
    [ 7.500, 10.000) = 1675 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.728 ms/op
     p(50.0000) =      7.946 ms/op
     p(90.0000) =     10.945 ms/op
     p(95.0000) =     11.963 ms/op
     p(99.0000) =     16.362 ms/op
     p(99.9000) =     27.034 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.505          ops/ms
Client.existUser                       thrpt         16.029          ops/ms
Client.getUser                         thrpt          7.315          ops/ms
Client.listUser                        thrpt          3.550          ops/ms
Client.createUser                       avgt          3.109           ms/op
Client.existUser                        avgt          1.917           ms/op
Client.getUser                          avgt          3.005           ms/op
Client.listUser                         avgt          7.828           ms/op
Client.createUser                     sample  11173   2.850 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.159           ms/op
Client.createUser:createUser·p0.50    sample          2.744           ms/op
Client.createUser:createUser·p0.90    sample          3.318           ms/op
Client.createUser:createUser·p0.95    sample          3.614           ms/op
Client.createUser:createUser·p0.99    sample          6.816           ms/op
Client.createUser:createUser·p0.999   sample         11.269           ms/op
Client.createUser:createUser·p0.9999  sample         12.528           ms/op
Client.createUser:createUser·p1.00    sample         12.599           ms/op
Client.existUser                      sample  16615   1.923 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.624           ms/op
Client.existUser:existUser·p0.50      sample          1.810           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.490           ms/op
Client.existUser:existUser·p0.99      sample          3.099           ms/op
Client.existUser:existUser·p0.999     sample         21.496           ms/op
Client.existUser:existUser·p0.9999    sample         21.770           ms/op
Client.existUser:existUser·p1.00      sample         21.856           ms/op
Client.getUser                        sample   9896   3.242 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.874           ms/op
Client.getUser:getUser·p0.50          sample          3.203           ms/op
Client.getUser:getUser·p0.90          sample          4.047           ms/op
Client.getUser:getUser·p0.95          sample          4.301           ms/op
Client.getUser:getUser·p0.99          sample          5.915           ms/op
Client.getUser:getUser·p0.999         sample          6.954           ms/op
Client.getUser:getUser·p0.9999        sample          9.650           ms/op
Client.getUser:getUser·p1.00          sample          9.650           ms/op
Client.listUser                       sample   3856   8.299 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          2.728           ms/op
Client.listUser:listUser·p0.50        sample          7.946           ms/op
Client.listUser:listUser·p0.90        sample         10.945           ms/op
Client.listUser:listUser·p0.95        sample         11.963           ms/op
Client.listUser:listUser·p0.99        sample         16.362           ms/op
Client.listUser:listUser·p0.999       sample         27.034           ms/op
Client.listUser:listUser·p0.9999      sample         30.704           ms/op
Client.listUser:listUser·p1.00        sample         30.704           ms/op
