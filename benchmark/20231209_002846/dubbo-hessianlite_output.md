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
# Warmup Iteration   1: 2.306 ops/ms
Iteration   1: 6.167 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.167 ops/ms


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
# Warmup Iteration   1: 6.713 ops/ms
Iteration   1: 12.342 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.342 ops/ms


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
# Warmup Iteration   1: 4.152 ops/ms
Iteration   1: 8.677 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.677 ops/ms


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
# Warmup Iteration   1: 1.974 ops/ms
Iteration   1: 3.669 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.669 ops/ms


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.068 ms/op
Iteration   1: 3.139 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.139 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.049 ms/op
Iteration   1: 1.796 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.796 ms/op


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.053 ms/op
Iteration   1: 3.706 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.706 ms/op


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
# Warmup Iteration   1: 13.329 ±(99.9%) 0.172 ms/op
Iteration   1: 8.473 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.473 ms/op


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
# Warmup Iteration   1: 4.850 ±(99.9%) 0.095 ms/op
Iteration   1: 3.349 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.521 ms/op
                 createUser·p0.99:   6.448 ms/op
                 createUser·p0.999:  12.124 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9541
  mean =      3.349 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 780 
    [ 2.500,  3.750) = 7282 
    [ 3.750,  5.000) = 1181 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.521 ms/op
     p(99.0000) =      6.448 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 2.717 ±(99.9%) 0.065 ms/op
Iteration   1: 2.013 ±(99.9%) 0.110 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.477 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  93.192 ms/op
                 existUser·p0.9999: 93.979 ms/op
                 existUser·p1.00:   93.979 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15871
  mean =      2.013 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 15807 
    [ 10.000,  20.000) = 32 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.477 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.318 ms/op
     p(99.9000) =     93.192 ms/op
     p(99.9900) =     93.979 ms/op
     p(99.9990) =     93.979 ms/op
     p(99.9999) =     93.979 ms/op
    p(100.0000) =     93.979 ms/op


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
# Warmup Iteration   1: 4.850 ±(99.9%) 0.117 ms/op
Iteration   1: 3.012 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.871 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 7.355 ms/op
                 getUser·p1.00:   7.356 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10615
  mean =      3.012 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 60 
    [1.500, 2.000) = 193 
    [2.000, 2.500) = 1867 
    [2.500, 3.000) = 3996 
    [3.000, 3.500) = 2370 
    [3.500, 4.000) = 1207 
    [4.000, 4.500) = 548 
    [4.500, 5.000) = 210 
    [5.000, 5.500) = 108 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 25 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =      7.355 ms/op
     p(99.9990) =      7.356 ms/op
     p(99.9999) =      7.356 ms/op
    p(100.0000) =      7.356 ms/op


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
# Warmup Iteration   1: 13.121 ±(99.9%) 0.522 ms/op
Iteration   1: 8.057 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   2.945 ms/op
                 listUser·p0.50:   7.864 ms/op
                 listUser·p0.90:   10.306 ms/op
                 listUser·p0.95:   11.511 ms/op
                 listUser·p0.99:   15.991 ms/op
                 listUser·p0.999:  26.810 ms/op
                 listUser·p0.9999: 27.623 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4073
  mean =      8.057 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 176 
    [ 5.000,  7.500) = 1516 
    [ 7.500, 10.000) = 1907 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.945 ms/op
     p(50.0000) =      7.864 ms/op
     p(90.0000) =     10.306 ms/op
     p(95.0000) =     11.511 ms/op
     p(99.0000) =     15.991 ms/op
     p(99.9000) =     26.810 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.167          ops/ms
Client.existUser                       thrpt         12.342          ops/ms
Client.getUser                         thrpt          8.677          ops/ms
Client.listUser                        thrpt          3.669          ops/ms
Client.createUser                       avgt          3.139           ms/op
Client.existUser                        avgt          1.796           ms/op
Client.getUser                          avgt          3.706           ms/op
Client.listUser                         avgt          8.473           ms/op
Client.createUser                     sample   9541   3.349 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.337           ms/op
Client.createUser:createUser·p0.50    sample          3.248           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.521           ms/op
Client.createUser:createUser·p0.99    sample          6.448           ms/op
Client.createUser:createUser·p0.999   sample         12.124           ms/op
Client.createUser:createUser·p0.9999  sample         12.190           ms/op
Client.createUser:createUser·p1.00    sample         12.190           ms/op
Client.existUser                      sample  15871   2.013 ± 0.110   ms/op
Client.existUser:existUser·p0.00      sample          0.567           ms/op
Client.existUser:existUser·p0.50      sample          1.747           ms/op
Client.existUser:existUser·p0.90      sample          2.477           ms/op
Client.existUser:existUser·p0.95      sample          2.687           ms/op
Client.existUser:existUser·p0.99      sample          3.318           ms/op
Client.existUser:existUser·p0.999     sample         93.192           ms/op
Client.existUser:existUser·p0.9999    sample         93.979           ms/op
Client.existUser:existUser·p1.00      sample         93.979           ms/op
Client.getUser                        sample  10615   3.012 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.690           ms/op
Client.getUser:getUser·p0.50          sample          2.871           ms/op
Client.getUser:getUser·p0.90          sample          3.928           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          5.136           ms/op
Client.getUser:getUser·p0.999         sample          6.881           ms/op
Client.getUser:getUser·p0.9999        sample          7.355           ms/op
Client.getUser:getUser·p1.00          sample          7.356           ms/op
Client.listUser                       sample   4073   8.057 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          2.945           ms/op
Client.listUser:listUser·p0.50        sample          7.864           ms/op
Client.listUser:listUser·p0.90        sample         10.306           ms/op
Client.listUser:listUser·p0.95        sample         11.511           ms/op
Client.listUser:listUser·p0.99        sample         15.991           ms/op
Client.listUser:listUser·p0.999       sample         26.810           ms/op
Client.listUser:listUser·p0.9999      sample         27.623           ms/op
Client.listUser:listUser·p1.00        sample         27.623           ms/op
