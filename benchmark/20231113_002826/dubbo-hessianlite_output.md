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
# Warmup Iteration   1: 1.149 ops/ms
Iteration   1: 2.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.680 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ops/ms
Iteration   1: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.693 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.169 ops/ms
Iteration   1: 4.242 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.242 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.862 ops/ms
Iteration   1: 1.095 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.095 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 12.802 ±(99.9%) 0.291 ms/op
Iteration   1: 6.938 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.938 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ±(99.9%) 0.165 ms/op
Iteration   1: 3.494 ±(99.9%) 0.124 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.494 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.272 ±(99.9%) 0.301 ms/op
Iteration   1: 8.582 ±(99.9%) 0.140 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.582 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 34.625 ±(99.9%) 1.010 ms/op
Iteration   1: 24.162 ±(99.9%) 0.330 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.162 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.319 ±(99.9%) 0.410 ms/op
Iteration   1: 7.222 ±(99.9%) 0.270 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   5.882 ms/op
                 createUser·p0.90:   13.728 ms/op
                 createUser·p0.95:   15.580 ms/op
                 createUser·p0.99:   23.676 ms/op
                 createUser·p0.999:  52.361 ms/op
                 createUser·p0.9999: 57.737 ms/op
                 createUser·p1.00:   57.737 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4520
  mean =      7.222 ±(99.9%) 0.270 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1818 
    [ 5.000, 10.000) = 1989 
    [10.000, 15.000) = 453 
    [15.000, 20.000) = 173 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =     13.728 ms/op
     p(95.0000) =     15.580 ms/op
     p(99.0000) =     23.676 ms/op
     p(99.9000) =     52.361 ms/op
     p(99.9900) =     57.737 ms/op
     p(99.9990) =     57.737 ms/op
     p(99.9999) =     57.737 ms/op
    p(100.0000) =     57.737 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.437 ±(99.9%) 0.240 ms/op
Iteration   1: 2.920 ±(99.9%) 0.084 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.281 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   6.003 ms/op
                 existUser·p0.99:   15.860 ms/op
                 existUser·p0.999:  35.914 ms/op
                 existUser·p0.9999: 36.616 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10933
  mean =      2.920 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7459 
    [ 2.500,  5.000) = 2748 
    [ 5.000,  7.500) = 313 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      6.003 ms/op
     p(99.0000) =     15.860 ms/op
     p(99.9000) =     35.914 ms/op
     p(99.9900) =     36.616 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 11.873 ±(99.9%) 0.345 ms/op
Iteration   1: 5.523 ±(99.9%) 0.142 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   8.364 ms/op
                 getUser·p0.95:   10.895 ms/op
                 getUser·p0.99:   18.940 ms/op
                 getUser·p0.999:  32.210 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5779
  mean =      5.523 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 3558 
    [ 5.000,  7.500) = 1472 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      8.364 ms/op
     p(95.0000) =     10.895 ms/op
     p(99.0000) =     18.940 ms/op
     p(99.9000) =     32.210 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 34.038 ±(99.9%) 1.421 ms/op
Iteration   1: 23.238 ±(99.9%) 0.602 ms/op
                 listUser·p0.00:   6.619 ms/op
                 listUser·p0.50:   22.544 ms/op
                 listUser·p0.90:   33.292 ms/op
                 listUser·p0.95:   35.517 ms/op
                 listUser·p0.99:   41.824 ms/op
                 listUser·p0.999:  46.293 ms/op
                 listUser·p0.9999: 47.317 ms/op
                 listUser·p1.00:   47.317 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1380
  mean =     23.238 ±(99.9%) 0.602 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 12 
    [10.000, 15.000) = 139 
    [15.000, 20.000) = 290 
    [20.000, 25.000) = 504 
    [25.000, 30.000) = 197 
    [30.000, 35.000) = 157 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      6.619 ms/op
     p(50.0000) =     22.544 ms/op
     p(90.0000) =     33.292 ms/op
     p(95.0000) =     35.517 ms/op
     p(99.0000) =     41.824 ms/op
     p(99.9000) =     46.293 ms/op
     p(99.9900) =     47.317 ms/op
     p(99.9990) =     47.317 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.680          ops/ms
Client.existUser                       thrpt          7.693          ops/ms
Client.getUser                         thrpt          4.242          ops/ms
Client.listUser                        thrpt          1.095          ops/ms
Client.createUser                       avgt          6.938           ms/op
Client.existUser                        avgt          3.494           ms/op
Client.getUser                          avgt          8.582           ms/op
Client.listUser                         avgt         24.162           ms/op
Client.createUser                     sample   4520   7.222 ± 0.270   ms/op
Client.createUser:createUser·p0.00    sample          1.858           ms/op
Client.createUser:createUser·p0.50    sample          5.882           ms/op
Client.createUser:createUser·p0.90    sample         13.728           ms/op
Client.createUser:createUser·p0.95    sample         15.580           ms/op
Client.createUser:createUser·p0.99    sample         23.676           ms/op
Client.createUser:createUser·p0.999   sample         52.361           ms/op
Client.createUser:createUser·p0.9999  sample         57.737           ms/op
Client.createUser:createUser·p1.00    sample         57.737           ms/op
Client.existUser                      sample  10933   2.920 ± 0.084   ms/op
Client.existUser:existUser·p0.00      sample          0.580           ms/op
Client.existUser:existUser·p0.50      sample          2.281           ms/op
Client.existUser:existUser·p0.90      sample          3.719           ms/op
Client.existUser:existUser·p0.95      sample          6.003           ms/op
Client.existUser:existUser·p0.99      sample         15.860           ms/op
Client.existUser:existUser·p0.999     sample         35.914           ms/op
Client.existUser:existUser·p0.9999    sample         36.616           ms/op
Client.existUser:existUser·p1.00      sample         36.635           ms/op
Client.getUser                        sample   5779   5.523 ± 0.142   ms/op
Client.getUser:getUser·p0.00          sample          1.274           ms/op
Client.getUser:getUser·p0.50          sample          4.456           ms/op
Client.getUser:getUser·p0.90          sample          8.364           ms/op
Client.getUser:getUser·p0.95          sample         10.895           ms/op
Client.getUser:getUser·p0.99          sample         18.940           ms/op
Client.getUser:getUser·p0.999         sample         32.210           ms/op
Client.getUser:getUser·p0.9999        sample         34.865           ms/op
Client.getUser:getUser·p1.00          sample         34.865           ms/op
Client.listUser                       sample   1380  23.238 ± 0.602   ms/op
Client.listUser:listUser·p0.00        sample          6.619           ms/op
Client.listUser:listUser·p0.50        sample         22.544           ms/op
Client.listUser:listUser·p0.90        sample         33.292           ms/op
Client.listUser:listUser·p0.95        sample         35.517           ms/op
Client.listUser:listUser·p0.99        sample         41.824           ms/op
Client.listUser:listUser·p0.999       sample         46.293           ms/op
Client.listUser:listUser·p0.9999      sample         47.317           ms/op
Client.listUser:listUser·p1.00        sample         47.317           ms/op
