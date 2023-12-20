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
# Warmup Iteration   1: 2.586 ops/ms
Iteration   1: 6.244 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.244 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 12.059 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.059 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ops/ms
Iteration   1: 8.975 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.975 ops/ms


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
# Warmup Iteration   1: 2.055 ops/ms
Iteration   1: 3.516 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.516 ops/ms


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
# Warmup Iteration   1: 5.774 ±(99.9%) 0.194 ms/op
Iteration   1: 3.223 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.223 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.058 ms/op
Iteration   1: 1.697 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.697 ms/op


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
# Warmup Iteration   1: 4.733 ±(99.9%) 0.061 ms/op
Iteration   1: 3.213 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.213 ms/op


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
# Warmup Iteration   1: 12.943 ±(99.9%) 0.226 ms/op
Iteration   1: 8.863 ±(99.9%) 0.127 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.863 ms/op


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.112 ms/op
Iteration   1: 3.154 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  15.841 ms/op
                 createUser·p0.9999: 17.923 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10136
  mean =      3.154 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1258 
    [ 2.500,  3.750) = 7733 
    [ 3.750,  5.000) = 964 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     15.841 ms/op
     p(99.9900) =     17.923 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 2.887 ±(99.9%) 0.061 ms/op
Iteration   1: 1.788 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  4.956 ms/op
                 existUser·p0.9999: 21.659 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17556
  mean =      1.788 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16183 
    [ 2.500,  5.000) = 1358 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =      4.956 ms/op
     p(99.9900) =     21.659 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.105 ms/op
Iteration   1: 2.807 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.691 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  7.861 ms/op
                 getUser·p0.9999: 8.146 ms/op
                 getUser·p1.00:   8.184 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11391
  mean =      2.807 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 54 
    [1.500, 2.000) = 683 
    [2.000, 2.500) = 3533 
    [2.500, 3.000) = 3416 
    [3.000, 3.500) = 2221 
    [3.500, 4.000) = 989 
    [4.000, 4.500) = 281 
    [4.500, 5.000) = 108 
    [5.000, 5.500) = 21 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 14 
    [7.000, 7.500) = 12 
    [7.500, 8.000) = 39 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.861 ms/op
     p(99.9900) =      8.146 ms/op
     p(99.9990) =      8.184 ms/op
     p(99.9999) =      8.184 ms/op
    p(100.0000) =      8.184 ms/op


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
# Warmup Iteration   1: 12.406 ±(99.9%) 0.439 ms/op
Iteration   1: 8.272 ±(99.9%) 0.108 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   8.004 ms/op
                 listUser·p0.90:   10.468 ms/op
                 listUser·p0.95:   11.566 ms/op
                 listUser·p0.99:   16.016 ms/op
                 listUser·p0.999:  22.755 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3880
  mean =      8.272 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 89 
    [ 5.000,  7.500) = 1260 
    [ 7.500, 10.000) = 1998 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.072 ms/op
     p(50.0000) =      8.004 ms/op
     p(90.0000) =     10.468 ms/op
     p(95.0000) =     11.566 ms/op
     p(99.0000) =     16.016 ms/op
     p(99.9000) =     22.755 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.244          ops/ms
Client.existUser                       thrpt         12.059          ops/ms
Client.getUser                         thrpt          8.975          ops/ms
Client.listUser                        thrpt          3.516          ops/ms
Client.createUser                       avgt          3.223           ms/op
Client.existUser                        avgt          1.697           ms/op
Client.getUser                          avgt          3.213           ms/op
Client.listUser                         avgt          8.863           ms/op
Client.createUser                     sample  10136   3.154 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.945           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          3.842           ms/op
Client.createUser:createUser·p0.95    sample          4.100           ms/op
Client.createUser:createUser·p0.99    sample          7.135           ms/op
Client.createUser:createUser·p0.999   sample         15.841           ms/op
Client.createUser:createUser·p0.9999  sample         17.923           ms/op
Client.createUser:createUser·p1.00    sample         17.924           ms/op
Client.existUser                      sample  17556   1.788 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.391           ms/op
Client.existUser:existUser·p0.50      sample          1.673           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.601           ms/op
Client.existUser:existUser·p0.99      sample          3.277           ms/op
Client.existUser:existUser·p0.999     sample          4.956           ms/op
Client.existUser:existUser·p0.9999    sample         21.659           ms/op
Client.existUser:existUser·p1.00      sample         21.758           ms/op
Client.getUser                        sample  11391   2.807 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.055           ms/op
Client.getUser:getUser·p0.50          sample          2.691           ms/op
Client.getUser:getUser·p0.90          sample          3.613           ms/op
Client.getUser:getUser·p0.95          sample          3.928           ms/op
Client.getUser:getUser·p0.99          sample          4.899           ms/op
Client.getUser:getUser·p0.999         sample          7.861           ms/op
Client.getUser:getUser·p0.9999        sample          8.146           ms/op
Client.getUser:getUser·p1.00          sample          8.184           ms/op
Client.listUser                       sample   3880   8.272 ± 0.108   ms/op
Client.listUser:listUser·p0.00        sample          3.072           ms/op
Client.listUser:listUser·p0.50        sample          8.004           ms/op
Client.listUser:listUser·p0.90        sample         10.468           ms/op
Client.listUser:listUser·p0.95        sample         11.566           ms/op
Client.listUser:listUser·p0.99        sample         16.016           ms/op
Client.listUser:listUser·p0.999       sample         22.755           ms/op
Client.listUser:listUser·p0.9999      sample         24.281           ms/op
Client.listUser:listUser·p1.00        sample         24.281           ms/op
