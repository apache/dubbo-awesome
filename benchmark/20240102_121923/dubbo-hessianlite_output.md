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
# Warmup Iteration   1: 2.197 ops/ms
Iteration   1: 5.945 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.945 ops/ms


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
# Warmup Iteration   1: 6.438 ops/ms
Iteration   1: 11.302 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.302 ops/ms


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
# Warmup Iteration   1: 4.070 ops/ms
Iteration   1: 8.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.020 ops/ms


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
# Warmup Iteration   1: 1.987 ops/ms
Iteration   1: 3.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.566 ops/ms


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.112 ms/op
Iteration   1: 3.037 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.037 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.061 ms/op
Iteration   1: 1.911 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.911 ms/op


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
# Warmup Iteration   1: 5.028 ±(99.9%) 0.059 ms/op
Iteration   1: 3.192 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.192 ms/op


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
# Warmup Iteration   1: 12.494 ±(99.9%) 0.163 ms/op
Iteration   1: 9.346 ±(99.9%) 0.126 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.346 ms/op


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.116 ms/op
Iteration   1: 2.875 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.757 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 11.897 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11197
  mean =      2.875 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1317 
    [ 2.500,  3.750) = 9337 
    [ 3.750,  5.000) = 451 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     11.897 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.102 ms/op
Iteration   1: 1.971 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.304 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 14.522 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16208
  mean =      1.971 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 15091 
    [ 2.500,  3.750) = 925 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.304 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     14.522 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.130 ms/op
Iteration   1: 3.189 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.066 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10019
  mean =      3.189 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 2345 
    [ 2.500,  3.750) = 5575 
    [ 3.750,  5.000) = 1778 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.066 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 13.604 ±(99.9%) 0.443 ms/op
Iteration   1: 7.816 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   7.463 ms/op
                 listUser·p0.90:   10.040 ms/op
                 listUser·p0.95:   11.436 ms/op
                 listUser·p0.99:   18.650 ms/op
                 listUser·p0.999:  32.275 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4191
  mean =      7.816 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 203 
    [ 5.000,  7.500) = 1929 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      7.463 ms/op
     p(90.0000) =     10.040 ms/op
     p(95.0000) =     11.436 ms/op
     p(99.0000) =     18.650 ms/op
     p(99.9000) =     32.275 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.945          ops/ms
Client.existUser                       thrpt         11.302          ops/ms
Client.getUser                         thrpt          8.020          ops/ms
Client.listUser                        thrpt          3.566          ops/ms
Client.createUser                       avgt          3.037           ms/op
Client.existUser                        avgt          1.911           ms/op
Client.getUser                          avgt          3.192           ms/op
Client.listUser                         avgt          9.346           ms/op
Client.createUser                     sample  11197   2.875 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.083           ms/op
Client.createUser:createUser·p0.50    sample          2.757           ms/op
Client.createUser:createUser·p0.90    sample          3.367           ms/op
Client.createUser:createUser·p0.95    sample          3.715           ms/op
Client.createUser:createUser·p0.99    sample          4.735           ms/op
Client.createUser:createUser·p0.999   sample         11.485           ms/op
Client.createUser:createUser·p0.9999  sample         11.897           ms/op
Client.createUser:createUser·p1.00    sample         11.911           ms/op
Client.existUser                      sample  16208   1.971 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.977           ms/op
Client.existUser:existUser·p0.50      sample          1.841           ms/op
Client.existUser:existUser·p0.90      sample          2.421           ms/op
Client.existUser:existUser·p0.95      sample          2.580           ms/op
Client.existUser:existUser·p0.99      sample          3.304           ms/op
Client.existUser:existUser·p0.999     sample         14.434           ms/op
Client.existUser:existUser·p0.9999    sample         14.522           ms/op
Client.existUser:existUser·p1.00      sample         14.533           ms/op
Client.getUser                        sample  10019   3.189 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.717           ms/op
Client.getUser:getUser·p0.50          sample          3.105           ms/op
Client.getUser:getUser·p0.90          sample          4.211           ms/op
Client.getUser:getUser·p0.95          sample          4.645           ms/op
Client.getUser:getUser·p0.99          sample          7.066           ms/op
Client.getUser:getUser·p0.999         sample         14.025           ms/op
Client.getUser:getUser·p0.9999        sample         14.221           ms/op
Client.getUser:getUser·p1.00          sample         14.221           ms/op
Client.listUser                       sample   4191   7.816 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          2.281           ms/op
Client.listUser:listUser·p0.50        sample          7.463           ms/op
Client.listUser:listUser·p0.90        sample         10.040           ms/op
Client.listUser:listUser·p0.95        sample         11.436           ms/op
Client.listUser:listUser·p0.99        sample         18.650           ms/op
Client.listUser:listUser·p0.999       sample         32.275           ms/op
Client.listUser:listUser·p0.9999      sample         33.620           ms/op
Client.listUser:listUser·p1.00        sample         33.620           ms/op
