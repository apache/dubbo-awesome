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
# Warmup Iteration   1: 1.140 ops/ms
Iteration   1: 3.208 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.208 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ops/ms
Iteration   1: 9.038 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.038 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.493 ops/ms
Iteration   1: 5.696 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.696 ops/ms


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
# Warmup Iteration   1: 0.734 ops/ms
Iteration   1: 1.071 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.071 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 11.412 ±(99.9%) 0.305 ms/op
Iteration   1: 7.083 ±(99.9%) 0.149 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.083 ms/op


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
# Warmup Iteration   1: 7.829 ±(99.9%) 0.127 ms/op
Iteration   1: 3.575 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.575 ms/op


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
# Warmup Iteration   1: 11.539 ±(99.9%) 0.240 ms/op
Iteration   1: 6.069 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.069 ms/op


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
# Warmup Iteration   1: 30.833 ±(99.9%) 0.786 ms/op
Iteration   1: 21.214 ±(99.9%) 0.367 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.214 ms/op


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
# Warmup Iteration   1: 10.518 ±(99.9%) 0.309 ms/op
Iteration   1: 4.325 ±(99.9%) 0.111 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   6.309 ms/op
                 createUser·p0.95:   10.093 ms/op
                 createUser·p0.99:   16.556 ms/op
                 createUser·p0.999:  28.836 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 7348
  mean =      4.325 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 5919 
    [ 5.000,  7.500) = 753 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      6.309 ms/op
     p(95.0000) =     10.093 ms/op
     p(99.0000) =     16.556 ms/op
     p(99.9000) =     28.836 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.409 ±(99.9%) 0.224 ms/op
Iteration   1: 3.408 ±(99.9%) 0.099 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   5.560 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   16.769 ms/op
                 existUser·p0.999:  36.220 ms/op
                 existUser·p0.9999: 40.829 ms/op
                 existUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9522
  mean =      3.408 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8393 
    [ 5.000, 10.000) = 846 
    [10.000, 15.000) = 155 
    [15.000, 20.000) = 96 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      5.560 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     16.769 ms/op
     p(99.9000) =     36.220 ms/op
     p(99.9900) =     40.829 ms/op
     p(99.9990) =     40.829 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 11.161 ±(99.9%) 0.331 ms/op
Iteration   1: 6.470 ±(99.9%) 0.174 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   10.240 ms/op
                 getUser·p0.95:   14.857 ms/op
                 getUser·p0.99:   22.710 ms/op
                 getUser·p0.999:  30.838 ms/op
                 getUser·p0.9999: 36.897 ms/op
                 getUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4941
  mean =      6.470 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 2275 
    [ 5.000,  7.500) = 1493 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =     10.240 ms/op
     p(95.0000) =     14.857 ms/op
     p(99.0000) =     22.710 ms/op
     p(99.9000) =     30.838 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 30.208 ±(99.9%) 1.517 ms/op
Iteration   1: 17.291 ±(99.9%) 0.373 ms/op
                 listUser·p0.00:   5.988 ms/op
                 listUser·p0.50:   16.253 ms/op
                 listUser·p0.90:   23.953 ms/op
                 listUser·p0.95:   26.696 ms/op
                 listUser·p0.99:   30.991 ms/op
                 listUser·p0.999:  42.538 ms/op
                 listUser·p0.9999: 42.926 ms/op
                 listUser·p1.00:   42.926 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1845
  mean =     17.291 ±(99.9%) 0.373 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 70 
    [10.000, 15.000) = 547 
    [15.000, 20.000) = 784 
    [20.000, 25.000) = 309 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      5.988 ms/op
     p(50.0000) =     16.253 ms/op
     p(90.0000) =     23.953 ms/op
     p(95.0000) =     26.696 ms/op
     p(99.0000) =     30.991 ms/op
     p(99.9000) =     42.538 ms/op
     p(99.9900) =     42.926 ms/op
     p(99.9990) =     42.926 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.208          ops/ms
Client.existUser                       thrpt         9.038          ops/ms
Client.getUser                         thrpt         5.696          ops/ms
Client.listUser                        thrpt         1.071          ops/ms
Client.createUser                       avgt         7.083           ms/op
Client.existUser                        avgt         3.575           ms/op
Client.getUser                          avgt         6.069           ms/op
Client.listUser                         avgt        21.214           ms/op
Client.createUser                     sample  7348   4.325 ± 0.111   ms/op
Client.createUser:createUser·p0.00    sample         1.788           ms/op
Client.createUser:createUser·p0.50    sample         3.297           ms/op
Client.createUser:createUser·p0.90    sample         6.309           ms/op
Client.createUser:createUser·p0.95    sample        10.093           ms/op
Client.createUser:createUser·p0.99    sample        16.556           ms/op
Client.createUser:createUser·p0.999   sample        28.836           ms/op
Client.createUser:createUser·p0.9999  sample        29.065           ms/op
Client.createUser:createUser·p1.00    sample        29.065           ms/op
Client.existUser                      sample  9522   3.408 ± 0.099   ms/op
Client.existUser:existUser·p0.00      sample         0.928           ms/op
Client.existUser:existUser·p0.50      sample         2.478           ms/op
Client.existUser:existUser·p0.90      sample         5.560           ms/op
Client.existUser:existUser·p0.95      sample         7.873           ms/op
Client.existUser:existUser·p0.99      sample        16.769           ms/op
Client.existUser:existUser·p0.999     sample        36.220           ms/op
Client.existUser:existUser·p0.9999    sample        40.829           ms/op
Client.existUser:existUser·p1.00      sample        40.829           ms/op
Client.getUser                        sample  4941   6.470 ± 0.174   ms/op
Client.getUser:getUser·p0.00          sample         1.681           ms/op
Client.getUser:getUser·p0.50          sample         5.300           ms/op
Client.getUser:getUser·p0.90          sample        10.240           ms/op
Client.getUser:getUser·p0.95          sample        14.857           ms/op
Client.getUser:getUser·p0.99          sample        22.710           ms/op
Client.getUser:getUser·p0.999         sample        30.838           ms/op
Client.getUser:getUser·p0.9999        sample        36.897           ms/op
Client.getUser:getUser·p1.00          sample        36.897           ms/op
Client.listUser                       sample  1845  17.291 ± 0.373   ms/op
Client.listUser:listUser·p0.00        sample         5.988           ms/op
Client.listUser:listUser·p0.50        sample        16.253           ms/op
Client.listUser:listUser·p0.90        sample        23.953           ms/op
Client.listUser:listUser·p0.95        sample        26.696           ms/op
Client.listUser:listUser·p0.99        sample        30.991           ms/op
Client.listUser:listUser·p0.999       sample        42.538           ms/op
Client.listUser:listUser·p0.9999      sample        42.926           ms/op
Client.listUser:listUser·p1.00        sample        42.926           ms/op
