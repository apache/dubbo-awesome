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
# Warmup Iteration   1: 1.237 ops/ms
Iteration   1: 2.367 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.367 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.668 ops/ms
Iteration   1: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.930 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.085 ops/ms
Iteration   1: 6.094 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.094 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.843 ops/ms
Iteration   1: 1.318 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.318 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 17.237 ±(99.9%) 0.245 ms/op
Iteration   1: 5.587 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.587 ms/op


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
# Warmup Iteration   1: 6.955 ±(99.9%) 0.065 ms/op
Iteration   1: 2.954 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.954 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.112 ms/op
Iteration   1: 4.498 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.498 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.137 ±(99.9%) 0.607 ms/op
Iteration   1: 16.044 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.044 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.574 ±(99.9%) 0.284 ms/op
Iteration   1: 6.295 ±(99.9%) 0.167 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   10.977 ms/op
                 createUser·p0.99:   14.538 ms/op
                 createUser·p0.999:  48.562 ms/op
                 createUser·p0.9999: 53.215 ms/op
                 createUser·p1.00:   53.215 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5091
  mean =      6.295 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 103 
    [ 5.000, 10.000) = 4702 
    [10.000, 15.000) = 254 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =     10.977 ms/op
     p(99.0000) =     14.538 ms/op
     p(99.9000) =     48.562 ms/op
     p(99.9900) =     53.215 ms/op
     p(99.9990) =     53.215 ms/op
     p(99.9999) =     53.215 ms/op
    p(100.0000) =     53.215 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.533 ±(99.9%) 0.214 ms/op
Iteration   1: 3.564 ±(99.9%) 0.074 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   5.321 ms/op
                 existUser·p0.99:   15.204 ms/op
                 existUser·p0.999:  21.242 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8968
  mean =      3.564 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 475 
    [ 2.500,  5.000) = 7964 
    [ 5.000,  7.500) = 242 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      5.321 ms/op
     p(99.0000) =     15.204 ms/op
     p(99.9000) =     21.242 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 9.255 ±(99.9%) 0.324 ms/op
Iteration   1: 4.460 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  14.189 ms/op
                 getUser·p0.9999: 14.926 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7340
  mean =      4.460 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 55 
    [ 2.500,  3.750) = 811 
    [ 3.750,  5.000) = 5326 
    [ 5.000,  6.250) = 964 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     14.926 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 23.327 ±(99.9%) 0.819 ms/op
Iteration   1: 17.712 ±(99.9%) 0.216 ms/op
                 listUser·p0.00:   7.094 ms/op
                 listUser·p0.50:   18.252 ms/op
                 listUser·p0.90:   20.021 ms/op
                 listUser·p0.95:   20.939 ms/op
                 listUser·p0.99:   25.822 ms/op
                 listUser·p0.999:  28.589 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1798
  mean =     17.712 ±(99.9%) 0.216 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 1058 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      7.094 ms/op
     p(50.0000) =     18.252 ms/op
     p(90.0000) =     20.021 ms/op
     p(95.0000) =     20.939 ms/op
     p(99.0000) =     25.822 ms/op
     p(99.9000) =     28.589 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.367          ops/ms
Client.existUser                       thrpt         6.930          ops/ms
Client.getUser                         thrpt         6.094          ops/ms
Client.listUser                        thrpt         1.318          ops/ms
Client.createUser                       avgt         5.587           ms/op
Client.existUser                        avgt         2.954           ms/op
Client.getUser                          avgt         4.498           ms/op
Client.listUser                         avgt        16.044           ms/op
Client.createUser                     sample  5091   6.295 ± 0.167   ms/op
Client.createUser:createUser·p0.00    sample         1.894           ms/op
Client.createUser:createUser·p0.50    sample         5.628           ms/op
Client.createUser:createUser·p0.90    sample         6.717           ms/op
Client.createUser:createUser·p0.95    sample        10.977           ms/op
Client.createUser:createUser·p0.99    sample        14.538           ms/op
Client.createUser:createUser·p0.999   sample        48.562           ms/op
Client.createUser:createUser·p0.9999  sample        53.215           ms/op
Client.createUser:createUser·p1.00    sample        53.215           ms/op
Client.existUser                      sample  8968   3.564 ± 0.074   ms/op
Client.existUser:existUser·p0.00      sample         0.653           ms/op
Client.existUser:existUser·p0.50      sample         3.101           ms/op
Client.existUser:existUser·p0.90      sample         4.227           ms/op
Client.existUser:existUser·p0.95      sample         5.321           ms/op
Client.existUser:existUser·p0.99      sample        15.204           ms/op
Client.existUser:existUser·p0.999     sample        21.242           ms/op
Client.existUser:existUser·p0.9999    sample        24.969           ms/op
Client.existUser:existUser·p1.00      sample        24.969           ms/op
Client.getUser                        sample  7340   4.460 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample         2.097           ms/op
Client.getUser:getUser·p0.50          sample         4.284           ms/op
Client.getUser:getUser·p0.90          sample         5.341           ms/op
Client.getUser:getUser·p0.95          sample         5.685           ms/op
Client.getUser:getUser·p0.99          sample         8.290           ms/op
Client.getUser:getUser·p0.999         sample        14.189           ms/op
Client.getUser:getUser·p0.9999        sample        14.926           ms/op
Client.getUser:getUser·p1.00          sample        14.926           ms/op
Client.listUser                       sample  1798  17.712 ± 0.216   ms/op
Client.listUser:listUser·p0.00        sample         7.094           ms/op
Client.listUser:listUser·p0.50        sample        18.252           ms/op
Client.listUser:listUser·p0.90        sample        20.021           ms/op
Client.listUser:listUser·p0.95        sample        20.939           ms/op
Client.listUser:listUser·p0.99        sample        25.822           ms/op
Client.listUser:listUser·p0.999       sample        28.589           ms/op
Client.listUser:listUser·p0.9999      sample        29.950           ms/op
Client.listUser:listUser·p1.00        sample        29.950           ms/op
