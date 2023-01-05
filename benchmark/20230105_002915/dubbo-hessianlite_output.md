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
# Warmup Iteration   1: 0.669 ops/ms
Iteration   1: 1.634 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.634 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
Iteration   1: 5.019 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.019 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.920 ops/ms
Iteration   1: 3.974 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.974 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.668 ops/ms
Iteration   1: 0.857 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.857 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 19.093 ±(99.9%) 0.373 ms/op
Iteration   1: 10.102 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.102 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 11.205 ±(99.9%) 0.166 ms/op
Iteration   1: 6.550 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.550 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.281 ±(99.9%) 0.190 ms/op
Iteration   1: 6.830 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.830 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 33.436 ±(99.9%) 0.623 ms/op
Iteration   1: 20.424 ±(99.9%) 0.126 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.424 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.458 ±(99.9%) 0.417 ms/op
Iteration   1: 7.421 ±(99.9%) 0.149 ms/op
                 createUser·p0.00:   2.658 ms/op
                 createUser·p0.50:   7.062 ms/op
                 createUser·p0.90:   9.273 ms/op
                 createUser·p0.95:   13.206 ms/op
                 createUser·p0.99:   17.957 ms/op
                 createUser·p0.999:  28.148 ms/op
                 createUser·p0.9999: 28.180 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4307
  mean =      7.421 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 434 
    [ 5.000,  7.500) = 2532 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.658 ms/op
     p(50.0000) =      7.062 ms/op
     p(90.0000) =      9.273 ms/op
     p(95.0000) =     13.206 ms/op
     p(99.0000) =     17.957 ms/op
     p(99.9000) =     28.148 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.922 ±(99.9%) 0.438 ms/op
Iteration   1: 5.629 ±(99.9%) 0.178 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   18.993 ms/op
                 existUser·p0.999:  53.839 ms/op
                 existUser·p0.9999: 54.460 ms/op
                 existUser·p1.00:   54.460 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5738
  mean =      5.629 ±(99.9%) 0.178 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2590 
    [ 5.000, 10.000) = 2910 
    [10.000, 15.000) = 125 
    [15.000, 20.000) = 80 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     18.993 ms/op
     p(99.9000) =     53.839 ms/op
     p(99.9900) =     54.460 ms/op
     p(99.9990) =     54.460 ms/op
     p(99.9999) =     54.460 ms/op
    p(100.0000) =     54.460 ms/op


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
# Warmup Iteration   1: 12.460 ±(99.9%) 0.434 ms/op
Iteration   1: 5.699 ±(99.9%) 0.102 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   7.349 ms/op
                 getUser·p0.99:   15.729 ms/op
                 getUser·p0.999:  29.652 ms/op
                 getUser·p0.9999: 36.045 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5618
  mean =      5.699 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 1955 
    [ 5.000,  7.500) = 3422 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.349 ms/op
     p(99.0000) =     15.729 ms/op
     p(99.9000) =     29.652 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 32.379 ±(99.9%) 0.912 ms/op
Iteration   1: 23.968 ±(99.9%) 0.305 ms/op
                 listUser·p0.00:   13.533 ms/op
                 listUser·p0.50:   23.036 ms/op
                 listUser·p0.90:   28.770 ms/op
                 listUser·p0.95:   29.229 ms/op
                 listUser·p0.99:   30.507 ms/op
                 listUser·p0.999:  32.060 ms/op
                 listUser·p0.9999: 32.342 ms/op
                 listUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1330
  mean =     23.968 ±(99.9%) 0.305 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 481 
    [22.500, 25.000) = 295 
    [25.000, 27.500) = 155 
    [27.500, 30.000) = 294 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     13.533 ms/op
     p(50.0000) =     23.036 ms/op
     p(90.0000) =     28.770 ms/op
     p(95.0000) =     29.229 ms/op
     p(99.0000) =     30.507 ms/op
     p(99.9000) =     32.060 ms/op
     p(99.9900) =     32.342 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:01:28

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.634          ops/ms
Client.existUser                       thrpt         5.019          ops/ms
Client.getUser                         thrpt         3.974          ops/ms
Client.listUser                        thrpt         0.857          ops/ms
Client.createUser                       avgt        10.102           ms/op
Client.existUser                        avgt         6.550           ms/op
Client.getUser                          avgt         6.830           ms/op
Client.listUser                         avgt        20.424           ms/op
Client.createUser                     sample  4307   7.421 ± 0.149   ms/op
Client.createUser:createUser·p0.00    sample         2.658           ms/op
Client.createUser:createUser·p0.50    sample         7.062           ms/op
Client.createUser:createUser·p0.90    sample         9.273           ms/op
Client.createUser:createUser·p0.95    sample        13.206           ms/op
Client.createUser:createUser·p0.99    sample        17.957           ms/op
Client.createUser:createUser·p0.999   sample        28.148           ms/op
Client.createUser:createUser·p0.9999  sample        28.180           ms/op
Client.createUser:createUser·p1.00    sample        28.180           ms/op
Client.existUser                      sample  5738   5.629 ± 0.178   ms/op
Client.existUser:existUser·p0.00      sample         1.311           ms/op
Client.existUser:existUser·p0.50      sample         5.071           ms/op
Client.existUser:existUser·p0.90      sample         6.021           ms/op
Client.existUser:existUser·p0.95      sample         7.643           ms/op
Client.existUser:existUser·p0.99      sample        18.993           ms/op
Client.existUser:existUser·p0.999     sample        53.839           ms/op
Client.existUser:existUser·p0.9999    sample        54.460           ms/op
Client.existUser:existUser·p1.00      sample        54.460           ms/op
Client.getUser                        sample  5618   5.699 ± 0.102   ms/op
Client.getUser:getUser·p0.00          sample         1.104           ms/op
Client.getUser:getUser·p0.50          sample         5.456           ms/op
Client.getUser:getUser·p0.90          sample         6.660           ms/op
Client.getUser:getUser·p0.95          sample         7.349           ms/op
Client.getUser:getUser·p0.99          sample        15.729           ms/op
Client.getUser:getUser·p0.999         sample        29.652           ms/op
Client.getUser:getUser·p0.9999        sample        36.045           ms/op
Client.getUser:getUser·p1.00          sample        36.045           ms/op
Client.listUser                       sample  1330  23.968 ± 0.305   ms/op
Client.listUser:listUser·p0.00        sample        13.533           ms/op
Client.listUser:listUser·p0.50        sample        23.036           ms/op
Client.listUser:listUser·p0.90        sample        28.770           ms/op
Client.listUser:listUser·p0.95        sample        29.229           ms/op
Client.listUser:listUser·p0.99        sample        30.507           ms/op
Client.listUser:listUser·p0.999       sample        32.060           ms/op
Client.listUser:listUser·p0.9999      sample        32.342           ms/op
Client.listUser:listUser·p1.00        sample        32.342           ms/op
