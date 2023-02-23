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
# Warmup Iteration   1: 1.450 ops/ms
Iteration   1: 2.754 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.754 ops/ms


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
# Warmup Iteration   1: 3.449 ops/ms
Iteration   1: 7.682 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.682 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.956 ops/ms
Iteration   1: 6.067 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.067 ops/ms


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
# Warmup Iteration   1: 0.951 ops/ms
Iteration   1: 1.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.549 ops/ms


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
# Warmup Iteration   1: 17.942 ±(99.9%) 0.278 ms/op
Iteration   1: 7.133 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.133 ms/op


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
# Warmup Iteration   1: 8.185 ±(99.9%) 0.097 ms/op
Iteration   1: 4.001 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.001 ms/op


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
# Warmup Iteration   1: 8.793 ±(99.9%) 0.229 ms/op
Iteration   1: 4.959 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.959 ms/op


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
# Warmup Iteration   1: 29.910 ±(99.9%) 0.603 ms/op
Iteration   1: 16.990 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.990 ms/op


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
# Warmup Iteration   1: 10.675 ±(99.9%) 0.312 ms/op
Iteration   1: 5.569 ±(99.9%) 0.090 ms/op
                 createUser·p0.00:   2.023 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   10.273 ms/op
                 createUser·p0.99:   13.500 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5822
  mean =      5.569 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2549 
    [ 5.000,  7.500) = 2770 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =     10.273 ms/op
     p(99.0000) =     13.500 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 6.212 ±(99.9%) 0.200 ms/op
Iteration   1: 3.579 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  25.765 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8939
  mean =      3.579 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1153 
    [ 2.500,  5.000) = 7585 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     25.765 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.299 ms/op
Iteration   1: 4.492 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   6.719 ms/op
                 getUser·p0.99:   17.185 ms/op
                 getUser·p0.999:  19.751 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7255
  mean =      4.492 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 144 
    [ 2.500,  3.750) = 1371 
    [ 3.750,  5.000) = 4554 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      6.719 ms/op
     p(99.0000) =     17.185 ms/op
     p(99.9000) =     19.751 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 25.354 ±(99.9%) 0.924 ms/op
Iteration   1: 16.479 ±(99.9%) 0.243 ms/op
                 listUser·p0.00:   5.947 ms/op
                 listUser·p0.50:   15.811 ms/op
                 listUser·p0.90:   20.061 ms/op
                 listUser·p0.95:   23.291 ms/op
                 listUser·p0.99:   28.689 ms/op
                 listUser·p0.999:  35.072 ms/op
                 listUser·p0.9999: 35.258 ms/op
                 listUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1947
  mean =     16.479 ±(99.9%) 0.243 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 413 
    [15.000, 17.500) = 1107 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.947 ms/op
     p(50.0000) =     15.811 ms/op
     p(90.0000) =     20.061 ms/op
     p(95.0000) =     23.291 ms/op
     p(99.0000) =     28.689 ms/op
     p(99.9000) =     35.072 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.754          ops/ms
Client.existUser                       thrpt         7.682          ops/ms
Client.getUser                         thrpt         6.067          ops/ms
Client.listUser                        thrpt         1.549          ops/ms
Client.createUser                       avgt         7.133           ms/op
Client.existUser                        avgt         4.001           ms/op
Client.getUser                          avgt         4.959           ms/op
Client.listUser                         avgt        16.990           ms/op
Client.createUser                     sample  5822   5.569 ± 0.090   ms/op
Client.createUser:createUser·p0.00    sample         2.023           ms/op
Client.createUser:createUser·p0.50    sample         5.374           ms/op
Client.createUser:createUser·p0.90    sample         7.037           ms/op
Client.createUser:createUser·p0.95    sample        10.273           ms/op
Client.createUser:createUser·p0.99    sample        13.500           ms/op
Client.createUser:createUser·p0.999   sample        20.447           ms/op
Client.createUser:createUser·p0.9999  sample        20.611           ms/op
Client.createUser:createUser·p1.00    sample        20.611           ms/op
Client.existUser                      sample  8939   3.579 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         0.666           ms/op
Client.existUser:existUser·p0.50      sample         3.715           ms/op
Client.existUser:existUser·p0.90      sample         3.985           ms/op
Client.existUser:existUser·p0.95      sample         4.112           ms/op
Client.existUser:existUser·p0.99      sample        10.732           ms/op
Client.existUser:existUser·p0.999     sample        25.765           ms/op
Client.existUser:existUser·p0.9999    sample        33.751           ms/op
Client.existUser:existUser·p1.00      sample        33.751           ms/op
Client.getUser                        sample  7255   4.492 ± 0.072   ms/op
Client.getUser:getUser·p0.00          sample         1.145           ms/op
Client.getUser:getUser·p0.50          sample         4.219           ms/op
Client.getUser:getUser·p0.90          sample         5.382           ms/op
Client.getUser:getUser·p0.95          sample         6.719           ms/op
Client.getUser:getUser·p0.99          sample        17.185           ms/op
Client.getUser:getUser·p0.999         sample        19.751           ms/op
Client.getUser:getUser·p0.9999        sample        19.890           ms/op
Client.getUser:getUser·p1.00          sample        19.890           ms/op
Client.listUser                       sample  1947  16.479 ± 0.243   ms/op
Client.listUser:listUser·p0.00        sample         5.947           ms/op
Client.listUser:listUser·p0.50        sample        15.811           ms/op
Client.listUser:listUser·p0.90        sample        20.061           ms/op
Client.listUser:listUser·p0.95        sample        23.291           ms/op
Client.listUser:listUser·p0.99        sample        28.689           ms/op
Client.listUser:listUser·p0.999       sample        35.072           ms/op
Client.listUser:listUser·p0.9999      sample        35.258           ms/op
Client.listUser:listUser·p1.00        sample        35.258           ms/op
