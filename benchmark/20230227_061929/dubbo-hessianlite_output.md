# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.182 ops/ms
Iteration   1: 2.887 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.887 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.407 ops/ms
Iteration   1: 7.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.072 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.121 ops/ms
Iteration   1: 4.556 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.556 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.030 ops/ms
Iteration   1: 1.307 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.307 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.567 ±(99.9%) 0.240 ms/op
Iteration   1: 5.621 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.621 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.305 ±(99.9%) 0.080 ms/op
Iteration   1: 4.145 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.828 ±(99.9%) 0.107 ms/op
Iteration   1: 3.702 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.180 ±(99.9%) 0.561 ms/op
Iteration   1: 14.445 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.445 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.998 ±(99.9%) 0.296 ms/op
Iteration   1: 6.039 ±(99.9%) 0.151 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   6.087 ms/op
                 createUser·p0.90:   6.817 ms/op
                 createUser·p0.95:   11.275 ms/op
                 createUser·p0.99:   18.809 ms/op
                 createUser·p0.999:  34.275 ms/op
                 createUser·p0.9999: 35.979 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5367
  mean =      6.039 ±(99.9%) 0.151 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 608 
    [ 2.500,  5.000) = 566 
    [ 5.000,  7.500) = 3758 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      6.817 ms/op
     p(95.0000) =     11.275 ms/op
     p(99.0000) =     18.809 ms/op
     p(99.9000) =     34.275 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ±(99.9%) 0.161 ms/op
Iteration   1: 3.390 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   11.878 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9433
  mean =      3.390 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1263 
    [ 2.500,  5.000) = 7683 
    [ 5.000,  7.500) = 256 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.161 ±(99.9%) 0.280 ms/op
Iteration   1: 4.379 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   13.222 ms/op
                 getUser·p0.999:  21.027 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7297
  mean =      4.379 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 116 
    [ 2.500,  5.000) = 6223 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     21.027 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.777 ±(99.9%) 0.705 ms/op
Iteration   1: 14.390 ±(99.9%) 0.233 ms/op
                 listUser·p0.00:   5.464 ms/op
                 listUser·p0.50:   14.320 ms/op
                 listUser·p0.90:   18.252 ms/op
                 listUser·p0.95:   19.664 ms/op
                 listUser·p0.99:   23.784 ms/op
                 listUser·p0.999:  27.614 ms/op
                 listUser·p0.9999: 29.426 ms/op
                 listUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2217
  mean =     14.390 ±(99.9%) 0.233 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 620 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 742 
    [17.500, 20.000) = 209 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      5.464 ms/op
     p(50.0000) =     14.320 ms/op
     p(90.0000) =     18.252 ms/op
     p(95.0000) =     19.664 ms/op
     p(99.0000) =     23.784 ms/op
     p(99.9000) =     27.614 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.887          ops/ms
Client.existUser                       thrpt         7.072          ops/ms
Client.getUser                         thrpt         4.556          ops/ms
Client.listUser                        thrpt         1.307          ops/ms
Client.createUser                       avgt         5.621           ms/op
Client.existUser                        avgt         4.145           ms/op
Client.getUser                          avgt         3.702           ms/op
Client.listUser                         avgt        14.445           ms/op
Client.createUser                     sample  5367   6.039 ± 0.151   ms/op
Client.createUser:createUser·p0.00    sample         1.243           ms/op
Client.createUser:createUser·p0.50    sample         6.087           ms/op
Client.createUser:createUser·p0.90    sample         6.817           ms/op
Client.createUser:createUser·p0.95    sample        11.275           ms/op
Client.createUser:createUser·p0.99    sample        18.809           ms/op
Client.createUser:createUser·p0.999   sample        34.275           ms/op
Client.createUser:createUser·p0.9999  sample        35.979           ms/op
Client.createUser:createUser·p1.00    sample        35.979           ms/op
Client.existUser                      sample  9433   3.390 ± 0.051   ms/op
Client.existUser:existUser·p0.00      sample         1.157           ms/op
Client.existUser:existUser·p0.50      sample         3.207           ms/op
Client.existUser:existUser·p0.90      sample         3.822           ms/op
Client.existUser:existUser·p0.95      sample         5.071           ms/op
Client.existUser:existUser·p0.99      sample        11.878           ms/op
Client.existUser:existUser·p0.999     sample        14.598           ms/op
Client.existUser:existUser·p0.9999    sample        24.117           ms/op
Client.existUser:existUser·p1.00      sample        24.117           ms/op
Client.getUser                        sample  7297   4.379 ± 0.062   ms/op
Client.getUser:getUser·p0.00          sample         1.055           ms/op
Client.getUser:getUser·p0.50          sample         4.125           ms/op
Client.getUser:getUser·p0.90          sample         5.063           ms/op
Client.getUser:getUser·p0.95          sample         5.489           ms/op
Client.getUser:getUser·p0.99          sample        13.222           ms/op
Client.getUser:getUser·p0.999         sample        21.027           ms/op
Client.getUser:getUser·p0.9999        sample        21.266           ms/op
Client.getUser:getUser·p1.00          sample        21.266           ms/op
Client.listUser                       sample  2217  14.390 ± 0.233   ms/op
Client.listUser:listUser·p0.00        sample         5.464           ms/op
Client.listUser:listUser·p0.50        sample        14.320           ms/op
Client.listUser:listUser·p0.90        sample        18.252           ms/op
Client.listUser:listUser·p0.95        sample        19.664           ms/op
Client.listUser:listUser·p0.99        sample        23.784           ms/op
Client.listUser:listUser·p0.999       sample        27.614           ms/op
Client.listUser:listUser·p0.9999      sample        29.426           ms/op
Client.listUser:listUser·p1.00        sample        29.426           ms/op
