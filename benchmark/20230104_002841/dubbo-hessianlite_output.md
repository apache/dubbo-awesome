# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.163 ops/ms
Iteration   1: 3.294 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.294 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
Iteration   1: 6.918 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.918 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.728 ops/ms
Iteration   1: 6.100 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.100 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.886 ops/ms
Iteration   1: 1.424 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.424 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 13.900 ±(99.9%) 0.171 ms/op
Iteration   1: 5.866 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.905 ±(99.9%) 0.068 ms/op
Iteration   1: 3.077 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.077 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.243 ±(99.9%) 0.187 ms/op
Iteration   1: 4.367 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.367 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 23.203 ±(99.9%) 0.423 ms/op
Iteration   1: 15.532 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.532 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.936 ±(99.9%) 0.472 ms/op
Iteration   1: 7.008 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   6.554 ms/op
                 createUser·p0.90:   7.270 ms/op
                 createUser·p0.95:   12.370 ms/op
                 createUser·p0.99:   17.793 ms/op
                 createUser·p0.999:  19.411 ms/op
                 createUser·p0.9999: 19.890 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4615
  mean =      7.008 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 37 
    [ 2.500,  3.750) = 44 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 980 
    [ 6.250,  7.500) = 3042 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      7.270 ms/op
     p(95.0000) =     12.370 ms/op
     p(99.0000) =     17.793 ms/op
     p(99.9000) =     19.411 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.810 ±(99.9%) 0.179 ms/op
Iteration   1: 3.418 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.395 ms/op
                 existUser·p0.99:   12.354 ms/op
                 existUser·p0.999:  23.650 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9602
  mean =      3.418 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2183 
    [ 2.500,  5.000) = 7084 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.395 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     23.650 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 7.669 ±(99.9%) 0.266 ms/op
Iteration   1: 4.338 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.251 ms/op
                 getUser·p0.999:  17.410 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7567
  mean =      4.338 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 44 
    [ 2.500,  3.750) = 1680 
    [ 3.750,  5.000) = 4829 
    [ 5.000,  6.250) = 787 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.251 ms/op
     p(99.9000) =     17.410 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.892 ±(99.9%) 1.148 ms/op
Iteration   1: 18.464 ±(99.9%) 0.269 ms/op
                 listUser·p0.00:   6.996 ms/op
                 listUser·p0.50:   17.596 ms/op
                 listUser·p0.90:   22.059 ms/op
                 listUser·p0.95:   23.350 ms/op
                 listUser·p0.99:   28.040 ms/op
                 listUser·p0.999:  34.936 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1727
  mean =     18.464 ±(99.9%) 0.269 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 695 
    [17.500, 20.000) = 378 
    [20.000, 22.500) = 376 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      6.996 ms/op
     p(50.0000) =     17.596 ms/op
     p(90.0000) =     22.059 ms/op
     p(95.0000) =     23.350 ms/op
     p(99.0000) =     28.040 ms/op
     p(99.9000) =     34.936 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.294          ops/ms
Client.existUser                       thrpt         6.918          ops/ms
Client.getUser                         thrpt         6.100          ops/ms
Client.listUser                        thrpt         1.424          ops/ms
Client.createUser                       avgt         5.866           ms/op
Client.existUser                        avgt         3.077           ms/op
Client.getUser                          avgt         4.367           ms/op
Client.listUser                         avgt        15.532           ms/op
Client.createUser                     sample  4615   7.008 ± 0.110   ms/op
Client.createUser:createUser·p0.00    sample         1.483           ms/op
Client.createUser:createUser·p0.50    sample         6.554           ms/op
Client.createUser:createUser·p0.90    sample         7.270           ms/op
Client.createUser:createUser·p0.95    sample        12.370           ms/op
Client.createUser:createUser·p0.99    sample        17.793           ms/op
Client.createUser:createUser·p0.999   sample        19.411           ms/op
Client.createUser:createUser·p0.9999  sample        19.890           ms/op
Client.createUser:createUser·p1.00    sample        19.890           ms/op
Client.existUser                      sample  9602   3.418 ± 0.059   ms/op
Client.existUser:existUser·p0.00      sample         0.412           ms/op
Client.existUser:existUser·p0.50      sample         3.518           ms/op
Client.existUser:existUser·p0.90      sample         3.932           ms/op
Client.existUser:existUser·p0.95      sample         4.395           ms/op
Client.existUser:existUser·p0.99      sample        12.354           ms/op
Client.existUser:existUser·p0.999     sample        23.650           ms/op
Client.existUser:existUser·p0.9999    sample        25.625           ms/op
Client.existUser:existUser·p1.00      sample        25.625           ms/op
Client.getUser                        sample  7567   4.338 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample         1.010           ms/op
Client.getUser:getUser·p0.50          sample         4.276           ms/op
Client.getUser:getUser·p0.90          sample         5.194           ms/op
Client.getUser:getUser·p0.95          sample         5.751           ms/op
Client.getUser:getUser·p0.99          sample         8.251           ms/op
Client.getUser:getUser·p0.999         sample        17.410           ms/op
Client.getUser:getUser·p0.9999        sample        18.907           ms/op
Client.getUser:getUser·p1.00          sample        18.907           ms/op
Client.listUser                       sample  1727  18.464 ± 0.269   ms/op
Client.listUser:listUser·p0.00        sample         6.996           ms/op
Client.listUser:listUser·p0.50        sample        17.596           ms/op
Client.listUser:listUser·p0.90        sample        22.059           ms/op
Client.listUser:listUser·p0.95        sample        23.350           ms/op
Client.listUser:listUser·p0.99        sample        28.040           ms/op
Client.listUser:listUser·p0.999       sample        34.936           ms/op
Client.listUser:listUser·p0.9999      sample        35.127           ms/op
Client.listUser:listUser·p1.00        sample        35.127           ms/op
