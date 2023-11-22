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
# Warmup Iteration   1: 2.771 ops/ms
Iteration   1: 6.483 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.483 ops/ms


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
# Warmup Iteration   1: 7.221 ops/ms
Iteration   1: 14.724 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.724 ops/ms


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
# Warmup Iteration   1: 4.796 ops/ms
Iteration   1: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.877 ops/ms


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
# Warmup Iteration   1: 1.983 ops/ms
Iteration   1: 3.692 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.692 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ±(99.9%) 0.070 ms/op
Iteration   1: 2.952 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.952 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.029 ms/op
Iteration   1: 1.852 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.045 ms/op
Iteration   1: 2.646 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.646 ms/op


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
# Warmup Iteration   1: 12.171 ±(99.9%) 0.192 ms/op
Iteration   1: 8.288 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.288 ms/op


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.117 ms/op
Iteration   1: 3.335 ±(99.9%) 0.066 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   13.960 ms/op
                 createUser·p0.999:  26.214 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9592
  mean =      3.335 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1597 
    [ 2.500,  5.000) = 7735 
    [ 5.000,  7.500) = 110 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =     13.960 ms/op
     p(99.9000) =     26.214 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.062 ms/op
Iteration   1: 1.867 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.266 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.080 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 19.801 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17139
  mean =      1.867 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 16157 
    [ 2.500,  3.750) = 573 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.080 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     19.801 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.234 ±(99.9%) 0.106 ms/op
Iteration   1: 2.985 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.152 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10711
  mean =      2.985 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3161 
    [ 2.500,  3.750) = 6466 
    [ 3.750,  5.000) = 954 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.152 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 11.398 ±(99.9%) 0.302 ms/op
Iteration   1: 7.216 ±(99.9%) 0.089 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   6.967 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   13.019 ms/op
                 listUser·p0.999:  18.898 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4430
  mean =      7.216 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 284 
    [ 5.000,  7.500) = 2525 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.617 ms/op
     p(50.0000) =      6.967 ms/op
     p(90.0000) =      9.175 ms/op
     p(95.0000) =      9.994 ms/op
     p(99.0000) =     13.019 ms/op
     p(99.9000) =     18.898 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.483          ops/ms
Client.existUser                       thrpt         14.724          ops/ms
Client.getUser                         thrpt          8.877          ops/ms
Client.listUser                        thrpt          3.692          ops/ms
Client.createUser                       avgt          2.952           ms/op
Client.existUser                        avgt          1.852           ms/op
Client.getUser                          avgt          2.646           ms/op
Client.listUser                         avgt          8.288           ms/op
Client.createUser                     sample   9592   3.335 ± 0.066   ms/op
Client.createUser:createUser·p0.00    sample          1.034           ms/op
Client.createUser:createUser·p0.50    sample          2.998           ms/op
Client.createUser:createUser·p0.90    sample          4.088           ms/op
Client.createUser:createUser·p0.95    sample          4.424           ms/op
Client.createUser:createUser·p0.99    sample         13.960           ms/op
Client.createUser:createUser·p0.999   sample         26.214           ms/op
Client.createUser:createUser·p0.9999  sample         26.608           ms/op
Client.createUser:createUser·p1.00    sample         26.608           ms/op
Client.existUser                      sample  17139   1.867 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.266           ms/op
Client.existUser:existUser·p0.50      sample          1.753           ms/op
Client.existUser:existUser·p0.90      sample          2.241           ms/op
Client.existUser:existUser·p0.95      sample          2.449           ms/op
Client.existUser:existUser·p0.99      sample          3.080           ms/op
Client.existUser:existUser·p0.999     sample         19.562           ms/op
Client.existUser:existUser·p0.9999    sample         19.801           ms/op
Client.existUser:existUser·p1.00      sample         19.825           ms/op
Client.getUser                        sample  10711   2.985 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.178           ms/op
Client.getUser:getUser·p0.50          sample          2.912           ms/op
Client.getUser:getUser·p0.90          sample          3.756           ms/op
Client.getUser:getUser·p0.95          sample          4.080           ms/op
Client.getUser:getUser·p0.99          sample          5.152           ms/op
Client.getUser:getUser·p0.999         sample         12.632           ms/op
Client.getUser:getUser·p0.9999        sample         13.189           ms/op
Client.getUser:getUser·p1.00          sample         13.189           ms/op
Client.listUser                       sample   4430   7.216 ± 0.089   ms/op
Client.listUser:listUser·p0.00        sample          2.617           ms/op
Client.listUser:listUser·p0.50        sample          6.967           ms/op
Client.listUser:listUser·p0.90        sample          9.175           ms/op
Client.listUser:listUser·p0.95        sample          9.994           ms/op
Client.listUser:listUser·p0.99        sample         13.019           ms/op
Client.listUser:listUser·p0.999       sample         18.898           ms/op
Client.listUser:listUser·p0.9999      sample         20.021           ms/op
Client.listUser:listUser·p1.00        sample         20.021           ms/op
