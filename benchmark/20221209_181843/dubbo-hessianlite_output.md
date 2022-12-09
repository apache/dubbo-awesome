# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.975 ops/ms
Iteration   1: 2.209 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.209 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.459 ops/ms
Iteration   1: 5.798 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.798 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.731 ops/ms
Iteration   1: 4.403 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.403 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.784 ops/ms
Iteration   1: 1.368 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.368 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 17.753 ±(99.9%) 0.251 ms/op
Iteration   1: 7.326 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.326 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.647 ±(99.9%) 0.099 ms/op
Iteration   1: 4.074 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.919 ±(99.9%) 0.140 ms/op
Iteration   1: 5.277 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.277 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.958 ±(99.9%) 0.665 ms/op
Iteration   1: 18.806 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.806 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.832 ±(99.9%) 0.581 ms/op
Iteration   1: 6.136 ±(99.9%) 0.122 ms/op
                 createUser·p0.00:   1.970 ms/op
                 createUser·p0.50:   6.312 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   10.104 ms/op
                 createUser·p0.99:   20.858 ms/op
                 createUser·p0.999:  24.493 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5272
  mean =      6.136 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 1698 
    [ 5.000,  7.500) = 3095 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      6.312 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =     10.104 ms/op
     p(99.0000) =     20.858 ms/op
     p(99.9000) =     24.493 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.888 ±(99.9%) 0.328 ms/op
Iteration   1: 4.135 ±(99.9%) 0.106 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   7.026 ms/op
                 existUser·p0.95:   10.060 ms/op
                 existUser·p0.99:   14.533 ms/op
                 existUser·p0.999:  27.149 ms/op
                 existUser·p0.9999: 27.525 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7732
  mean =      4.135 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1638 
    [ 2.500,  5.000) = 4879 
    [ 5.000,  7.500) = 553 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      7.026 ms/op
     p(95.0000) =     10.060 ms/op
     p(99.0000) =     14.533 ms/op
     p(99.9000) =     27.149 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.317 ±(99.9%) 0.388 ms/op
Iteration   1: 4.857 ±(99.9%) 0.076 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   12.269 ms/op
                 getUser·p0.999:  24.847 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6718
  mean =      4.857 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 5218 
    [ 5.000,  7.500) = 1322 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =     12.269 ms/op
     p(99.9000) =     24.847 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.670 ±(99.9%) 0.687 ms/op
Iteration   1: 16.786 ±(99.9%) 0.175 ms/op
                 listUser·p0.00:   8.176 ms/op
                 listUser·p0.50:   16.499 ms/op
                 listUser·p0.90:   19.071 ms/op
                 listUser·p0.95:   19.798 ms/op
                 listUser·p0.99:   24.879 ms/op
                 listUser·p0.999:  27.458 ms/op
                 listUser·p0.9999: 28.869 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1915
  mean =     16.786 ±(99.9%) 0.175 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 1010 
    [17.500, 20.000) = 560 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      8.176 ms/op
     p(50.0000) =     16.499 ms/op
     p(90.0000) =     19.071 ms/op
     p(95.0000) =     19.798 ms/op
     p(99.0000) =     24.879 ms/op
     p(99.9000) =     27.458 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.209          ops/ms
Client.existUser                       thrpt         5.798          ops/ms
Client.getUser                         thrpt         4.403          ops/ms
Client.listUser                        thrpt         1.368          ops/ms
Client.createUser                       avgt         7.326           ms/op
Client.existUser                        avgt         4.074           ms/op
Client.getUser                          avgt         5.277           ms/op
Client.listUser                         avgt        18.806           ms/op
Client.createUser                     sample  5272   6.136 ± 0.122   ms/op
Client.createUser:createUser·p0.00    sample         1.970           ms/op
Client.createUser:createUser·p0.50    sample         6.312           ms/op
Client.createUser:createUser·p0.90    sample         7.119           ms/op
Client.createUser:createUser·p0.95    sample        10.104           ms/op
Client.createUser:createUser·p0.99    sample        20.858           ms/op
Client.createUser:createUser·p0.999   sample        24.493           ms/op
Client.createUser:createUser·p0.9999  sample        24.674           ms/op
Client.createUser:createUser·p1.00    sample        24.674           ms/op
Client.existUser                      sample  7732   4.135 ± 0.106   ms/op
Client.existUser:existUser·p0.00      sample         0.729           ms/op
Client.existUser:existUser·p0.50      sample         3.531           ms/op
Client.existUser:existUser·p0.90      sample         7.026           ms/op
Client.existUser:existUser·p0.95      sample        10.060           ms/op
Client.existUser:existUser·p0.99      sample        14.533           ms/op
Client.existUser:existUser·p0.999     sample        27.149           ms/op
Client.existUser:existUser·p0.9999    sample        27.525           ms/op
Client.existUser:existUser·p1.00      sample        27.525           ms/op
Client.getUser                        sample  6718   4.857 ± 0.076   ms/op
Client.getUser:getUser·p0.00          sample         1.565           ms/op
Client.getUser:getUser·p0.50          sample         4.522           ms/op
Client.getUser:getUser·p0.90          sample         5.693           ms/op
Client.getUser:getUser·p0.95          sample         6.332           ms/op
Client.getUser:getUser·p0.99          sample        12.269           ms/op
Client.getUser:getUser·p0.999         sample        24.847           ms/op
Client.getUser:getUser·p0.9999        sample        25.133           ms/op
Client.getUser:getUser·p1.00          sample        25.133           ms/op
Client.listUser                       sample  1915  16.786 ± 0.175   ms/op
Client.listUser:listUser·p0.00        sample         8.176           ms/op
Client.listUser:listUser·p0.50        sample        16.499           ms/op
Client.listUser:listUser·p0.90        sample        19.071           ms/op
Client.listUser:listUser·p0.95        sample        19.798           ms/op
Client.listUser:listUser·p0.99        sample        24.879           ms/op
Client.listUser:listUser·p0.999       sample        27.458           ms/op
Client.listUser:listUser·p0.9999      sample        28.869           ms/op
Client.listUser:listUser·p1.00        sample        28.869           ms/op
