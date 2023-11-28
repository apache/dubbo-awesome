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
# Warmup Iteration   1: 2.613 ops/ms
Iteration   1: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.349 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.394 ops/ms
Iteration   1: 15.531 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.531 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
Iteration   1: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.995 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
Iteration   1: 3.962 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.962 ops/ms


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
# Warmup Iteration   1: 4.777 ±(99.9%) 0.072 ms/op
Iteration   1: 3.219 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.038 ms/op
Iteration   1: 1.845 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.845 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.051 ms/op
Iteration   1: 3.050 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.050 ms/op


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
# Warmup Iteration   1: 12.004 ±(99.9%) 0.339 ms/op
Iteration   1: 7.369 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.369 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.099 ms/op
Iteration   1: 2.834 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   4.099 ms/op
                 createUser·p0.99:   8.604 ms/op
                 createUser·p0.999:  17.658 ms/op
                 createUser·p0.9999: 18.705 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11282
  mean =      2.834 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 4549 
    [ 2.500,  3.750) = 6068 
    [ 3.750,  5.000) = 287 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      4.099 ms/op
     p(99.0000) =      8.604 ms/op
     p(99.9000) =     17.658 ms/op
     p(99.9900) =     18.705 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 2.777 ±(99.9%) 0.059 ms/op
Iteration   1: 1.785 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.142 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   4.794 ms/op
                 existUser·p0.999:  19.956 ms/op
                 existUser·p0.9999: 22.437 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18073
  mean =      1.785 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17416 
    [ 2.500,  5.000) = 483 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      4.794 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     22.437 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.095 ms/op
Iteration   1: 3.203 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.948 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10001
  mean =      3.203 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1542 
    [ 2.500,  3.750) = 7003 
    [ 3.750,  5.000) = 1275 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.948 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 12.294 ±(99.9%) 0.421 ms/op
Iteration   1: 7.773 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   7.365 ms/op
                 listUser·p0.90:   10.102 ms/op
                 listUser·p0.95:   11.665 ms/op
                 listUser·p0.99:   17.952 ms/op
                 listUser·p0.999:  22.192 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4123
  mean =      7.773 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 141 
    [ 5.000,  7.500) = 2051 
    [ 7.500, 10.000) = 1491 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      7.365 ms/op
     p(90.0000) =     10.102 ms/op
     p(95.0000) =     11.665 ms/op
     p(99.0000) =     17.952 ms/op
     p(99.9000) =     22.192 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.349          ops/ms
Client.existUser                       thrpt         15.531          ops/ms
Client.getUser                         thrpt          8.995          ops/ms
Client.listUser                        thrpt          3.962          ops/ms
Client.createUser                       avgt          3.219           ms/op
Client.existUser                        avgt          1.845           ms/op
Client.getUser                          avgt          3.050           ms/op
Client.listUser                         avgt          7.369           ms/op
Client.createUser                     sample  11282   2.834 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.044           ms/op
Client.createUser:createUser·p0.50    sample          2.593           ms/op
Client.createUser:createUser·p0.90    sample          3.297           ms/op
Client.createUser:createUser·p0.95    sample          4.099           ms/op
Client.createUser:createUser·p0.99    sample          8.604           ms/op
Client.createUser:createUser·p0.999   sample         17.658           ms/op
Client.createUser:createUser·p0.9999  sample         18.705           ms/op
Client.createUser:createUser·p1.00    sample         18.743           ms/op
Client.existUser                      sample  18073   1.785 ± 0.031   ms/op
Client.existUser:existUser·p0.00      sample          0.599           ms/op
Client.existUser:existUser·p0.50      sample          1.669           ms/op
Client.existUser:existUser·p0.90      sample          2.142           ms/op
Client.existUser:existUser·p0.95      sample          2.347           ms/op
Client.existUser:existUser·p0.99      sample          4.794           ms/op
Client.existUser:existUser·p0.999     sample         19.956           ms/op
Client.existUser:existUser·p0.9999    sample         22.437           ms/op
Client.existUser:existUser·p1.00      sample         22.675           ms/op
Client.getUser                        sample  10001   3.203 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.887           ms/op
Client.getUser:getUser·p0.50          sample          3.109           ms/op
Client.getUser:getUser·p0.90          sample          3.948           ms/op
Client.getUser:getUser·p0.95          sample          4.301           ms/op
Client.getUser:getUser·p0.99          sample          5.841           ms/op
Client.getUser:getUser·p0.999         sample         19.268           ms/op
Client.getUser:getUser·p0.9999        sample         19.825           ms/op
Client.getUser:getUser·p1.00          sample         19.825           ms/op
Client.listUser                       sample   4123   7.773 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          1.638           ms/op
Client.listUser:listUser·p0.50        sample          7.365           ms/op
Client.listUser:listUser·p0.90        sample         10.102           ms/op
Client.listUser:listUser·p0.95        sample         11.665           ms/op
Client.listUser:listUser·p0.99        sample         17.952           ms/op
Client.listUser:listUser·p0.999       sample         22.192           ms/op
Client.listUser:listUser·p0.9999      sample         24.379           ms/op
Client.listUser:listUser·p1.00        sample         24.379           ms/op
