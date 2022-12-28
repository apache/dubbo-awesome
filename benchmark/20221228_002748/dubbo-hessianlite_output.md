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
# Warmup Iteration   1: 0.687 ops/ms
Iteration   1: 1.305 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.305 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 1.385 ops/ms
Iteration   1: 3.122 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.122 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.301 ops/ms
Iteration   1: 2.446 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.446 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.561 ops/ms
Iteration   1: 0.972 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.972 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 27.239 ±(99.9%) 0.683 ms/op
Iteration   1: 15.989 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  15.989 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.939 ±(99.9%) 0.379 ms/op
Iteration   1: 9.282 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.282 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.415 ±(99.9%) 0.383 ms/op
Iteration   1: 7.974 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.974 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 40.708 ±(99.9%) 0.983 ms/op
Iteration   1: 28.118 ±(99.9%) 0.240 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  28.118 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 21.611 ±(99.9%) 0.851 ms/op
Iteration   1: 12.996 ±(99.9%) 0.349 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   13.132 ms/op
                 createUser·p0.90:   18.170 ms/op
                 createUser·p0.95:   23.249 ms/op
                 createUser·p0.99:   35.344 ms/op
                 createUser·p0.999:  37.196 ms/op
                 createUser·p0.9999: 38.470 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2434
  mean =     12.996 ±(99.9%) 0.349 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 204 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 815 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =     13.132 ms/op
     p(90.0000) =     18.170 ms/op
     p(95.0000) =     23.249 ms/op
     p(99.0000) =     35.344 ms/op
     p(99.9000) =     37.196 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     38.470 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.800 ±(99.9%) 0.392 ms/op
Iteration   1: 9.194 ±(99.9%) 0.165 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   8.880 ms/op
                 existUser·p0.90:   11.420 ms/op
                 existUser·p0.95:   13.402 ms/op
                 existUser·p0.99:   24.936 ms/op
                 existUser·p0.999:  26.918 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3533
  mean =      9.194 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 128 
    [ 5.000,  7.500) = 339 
    [ 7.500, 10.000) = 2362 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      8.880 ms/op
     p(90.0000) =     11.420 ms/op
     p(95.0000) =     13.402 ms/op
     p(99.0000) =     24.936 ms/op
     p(99.9000) =     26.918 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 21.072 ±(99.9%) 0.617 ms/op
Iteration   1: 9.432 ±(99.9%) 0.242 ms/op
                 getUser·p0.00:   1.892 ms/op
                 getUser·p0.50:   8.290 ms/op
                 getUser·p0.90:   14.310 ms/op
                 getUser·p0.95:   17.564 ms/op
                 getUser·p0.99:   25.616 ms/op
                 getUser·p0.999:  36.982 ms/op
                 getUser·p0.9999: 38.076 ms/op
                 getUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3425
  mean =      9.432 ±(99.9%) 0.242 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 121 
    [ 5.000,  7.500) = 1120 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      8.290 ms/op
     p(90.0000) =     14.310 ms/op
     p(95.0000) =     17.564 ms/op
     p(99.0000) =     25.616 ms/op
     p(99.9000) =     36.982 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 49.375 ±(99.9%) 2.949 ms/op
Iteration   1: 30.004 ±(99.9%) 0.745 ms/op
                 listUser·p0.00:   13.287 ms/op
                 listUser·p0.50:   28.115 ms/op
                 listUser·p0.90:   38.194 ms/op
                 listUser·p0.95:   46.131 ms/op
                 listUser·p0.99:   57.289 ms/op
                 listUser·p0.999:  63.812 ms/op
                 listUser·p0.9999: 63.898 ms/op
                 listUser·p1.00:   63.898 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1081
  mean =     30.004 ±(99.9%) 0.745 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 114 
    [25.000, 30.000) = 496 
    [30.000, 35.000) = 215 
    [35.000, 40.000) = 113 
    [40.000, 45.000) = 26 
    [45.000, 50.000) = 29 
    [50.000, 55.000) = 13 
    [55.000, 60.000) = 9 
    [60.000, 65.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =     13.287 ms/op
     p(50.0000) =     28.115 ms/op
     p(90.0000) =     38.194 ms/op
     p(95.0000) =     46.131 ms/op
     p(99.0000) =     57.289 ms/op
     p(99.9000) =     63.812 ms/op
     p(99.9900) =     63.898 ms/op
     p(99.9990) =     63.898 ms/op
     p(99.9999) =     63.898 ms/op
    p(100.0000) =     63.898 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.305          ops/ms
Client.existUser                       thrpt         3.122          ops/ms
Client.getUser                         thrpt         2.446          ops/ms
Client.listUser                        thrpt         0.972          ops/ms
Client.createUser                       avgt        15.989           ms/op
Client.existUser                        avgt         9.282           ms/op
Client.getUser                          avgt         7.974           ms/op
Client.listUser                         avgt        28.118           ms/op
Client.createUser                     sample  2434  12.996 ± 0.349   ms/op
Client.createUser:createUser·p0.00    sample         2.343           ms/op
Client.createUser:createUser·p0.50    sample        13.132           ms/op
Client.createUser:createUser·p0.90    sample        18.170           ms/op
Client.createUser:createUser·p0.95    sample        23.249           ms/op
Client.createUser:createUser·p0.99    sample        35.344           ms/op
Client.createUser:createUser·p0.999   sample        37.196           ms/op
Client.createUser:createUser·p0.9999  sample        38.470           ms/op
Client.createUser:createUser·p1.00    sample        38.470           ms/op
Client.existUser                      sample  3533   9.194 ± 0.165   ms/op
Client.existUser:existUser·p0.00      sample         2.245           ms/op
Client.existUser:existUser·p0.50      sample         8.880           ms/op
Client.existUser:existUser·p0.90      sample        11.420           ms/op
Client.existUser:existUser·p0.95      sample        13.402           ms/op
Client.existUser:existUser·p0.99      sample        24.936           ms/op
Client.existUser:existUser·p0.999     sample        26.918           ms/op
Client.existUser:existUser·p0.9999    sample        27.034           ms/op
Client.existUser:existUser·p1.00      sample        27.034           ms/op
Client.getUser                        sample  3425   9.432 ± 0.242   ms/op
Client.getUser:getUser·p0.00          sample         1.892           ms/op
Client.getUser:getUser·p0.50          sample         8.290           ms/op
Client.getUser:getUser·p0.90          sample        14.310           ms/op
Client.getUser:getUser·p0.95          sample        17.564           ms/op
Client.getUser:getUser·p0.99          sample        25.616           ms/op
Client.getUser:getUser·p0.999         sample        36.982           ms/op
Client.getUser:getUser·p0.9999        sample        38.076           ms/op
Client.getUser:getUser·p1.00          sample        38.076           ms/op
Client.listUser                       sample  1081  30.004 ± 0.745   ms/op
Client.listUser:listUser·p0.00        sample        13.287           ms/op
Client.listUser:listUser·p0.50        sample        28.115           ms/op
Client.listUser:listUser·p0.90        sample        38.194           ms/op
Client.listUser:listUser·p0.95        sample        46.131           ms/op
Client.listUser:listUser·p0.99        sample        57.289           ms/op
Client.listUser:listUser·p0.999       sample        63.812           ms/op
Client.listUser:listUser·p0.9999      sample        63.898           ms/op
Client.listUser:listUser·p1.00        sample        63.898           ms/op
