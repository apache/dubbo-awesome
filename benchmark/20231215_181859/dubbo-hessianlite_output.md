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
# Warmup Iteration   1: 2.316 ops/ms
Iteration   1: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.556 ops/ms


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
# Warmup Iteration   1: 5.925 ops/ms
Iteration   1: 10.977 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.977 ops/ms


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
# Warmup Iteration   1: 4.144 ops/ms
Iteration   1: 8.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.379 ops/ms


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
# Warmup Iteration   1: 2.044 ops/ms
Iteration   1: 3.621 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.621 ops/ms


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
# Warmup Iteration   1: 5.427 ±(99.9%) 0.079 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.258 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.032 ms/op
Iteration   1: 2.010 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.087 ms/op
Iteration   1: 3.219 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.219 ms/op


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
# Warmup Iteration   1: 12.723 ±(99.9%) 0.256 ms/op
Iteration   1: 8.332 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.332 ms/op


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
# Warmup Iteration   1: 5.451 ±(99.9%) 0.179 ms/op
Iteration   1: 3.059 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.765 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.979 ms/op
                 createUser·p0.999:  21.907 ms/op
                 createUser·p0.9999: 23.113 ms/op
                 createUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10456
  mean =      3.059 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3194 
    [ 2.500,  5.000) = 7018 
    [ 5.000,  7.500) = 178 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.979 ms/op
     p(99.9000) =     21.907 ms/op
     p(99.9900) =     23.113 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.058 ms/op
Iteration   1: 1.971 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.683 ms/op
                 existUser·p0.95:   2.916 ms/op
                 existUser·p0.99:   3.859 ms/op
                 existUser·p0.999:  5.815 ms/op
                 existUser·p0.9999: 11.582 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16215
  mean =      1.971 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 388 
    [ 1.250,  2.500) = 13458 
    [ 2.500,  3.750) = 2200 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      3.859 ms/op
     p(99.9000) =      5.815 ms/op
     p(99.9900) =     11.582 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.122 ms/op
Iteration   1: 2.694 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  17.981 ms/op
                 getUser·p0.9999: 20.423 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11876
  mean =      2.694 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6204 
    [ 2.500,  5.000) = 5543 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     17.981 ms/op
     p(99.9900) =     20.423 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 10.758 ±(99.9%) 0.334 ms/op
Iteration   1: 7.215 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   6.922 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.215 ms/op
                 listUser·p0.99:   16.515 ms/op
                 listUser·p0.999:  18.734 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4429
  mean =      7.215 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 254 
    [ 5.000,  7.500) = 2674 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      6.922 ms/op
     p(90.0000) =      9.044 ms/op
     p(95.0000) =     10.215 ms/op
     p(99.0000) =     16.515 ms/op
     p(99.9000) =     18.734 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.556          ops/ms
Client.existUser                       thrpt         10.977          ops/ms
Client.getUser                         thrpt          8.379          ops/ms
Client.listUser                        thrpt          3.621          ops/ms
Client.createUser                       avgt          3.258           ms/op
Client.existUser                        avgt          2.010           ms/op
Client.getUser                          avgt          3.219           ms/op
Client.listUser                         avgt          8.332           ms/op
Client.createUser                     sample  10456   3.059 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.090           ms/op
Client.createUser:createUser·p0.50    sample          2.765           ms/op
Client.createUser:createUser·p0.90    sample          4.002           ms/op
Client.createUser:createUser·p0.95    sample          4.284           ms/op
Client.createUser:createUser·p0.99    sample          5.979           ms/op
Client.createUser:createUser·p0.999   sample         21.907           ms/op
Client.createUser:createUser·p0.9999  sample         23.113           ms/op
Client.createUser:createUser·p1.00    sample         23.134           ms/op
Client.existUser                      sample  16215   1.971 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.574           ms/op
Client.existUser:existUser·p0.50      sample          1.823           ms/op
Client.existUser:existUser·p0.90      sample          2.683           ms/op
Client.existUser:existUser·p0.95      sample          2.916           ms/op
Client.existUser:existUser·p0.99      sample          3.859           ms/op
Client.existUser:existUser·p0.999     sample          5.815           ms/op
Client.existUser:existUser·p0.9999    sample         11.582           ms/op
Client.existUser:existUser·p1.00      sample         12.091           ms/op
Client.getUser                        sample  11876   2.694 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.748           ms/op
Client.getUser:getUser·p0.50          sample          2.478           ms/op
Client.getUser:getUser·p0.90          sample          3.363           ms/op
Client.getUser:getUser·p0.95          sample          3.625           ms/op
Client.getUser:getUser·p0.99          sample          5.292           ms/op
Client.getUser:getUser·p0.999         sample         17.981           ms/op
Client.getUser:getUser·p0.9999        sample         20.423           ms/op
Client.getUser:getUser·p1.00          sample         20.447           ms/op
Client.listUser                       sample   4429   7.215 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          1.524           ms/op
Client.listUser:listUser·p0.50        sample          6.922           ms/op
Client.listUser:listUser·p0.90        sample          9.044           ms/op
Client.listUser:listUser·p0.95        sample         10.215           ms/op
Client.listUser:listUser·p0.99        sample         16.515           ms/op
Client.listUser:listUser·p0.999       sample         18.734           ms/op
Client.listUser:listUser·p0.9999      sample         24.117           ms/op
Client.listUser:listUser·p1.00        sample         24.117           ms/op
