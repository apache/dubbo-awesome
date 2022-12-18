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
# Warmup Iteration   1: 0.662 ops/ms
Iteration   1: 1.366 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.366 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 1.480 ops/ms
Iteration   1: 3.603 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.603 ops/ms


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
# Warmup Iteration   1: 1.448 ops/ms
Iteration   1: 2.758 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.758 ops/ms


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
# Warmup Iteration   1: 0.508 ops/ms
Iteration   1: 0.966 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.966 ops/ms


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
# Warmup Iteration   1: 27.684 ±(99.9%) 0.535 ms/op
Iteration   1: 16.437 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.437 ms/op


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
# Warmup Iteration   1: 21.067 ±(99.9%) 0.404 ms/op
Iteration   1: 7.845 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.845 ms/op


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
# Warmup Iteration   1: 21.703 ±(99.9%) 0.324 ms/op
Iteration   1: 8.097 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.097 ms/op


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
# Warmup Iteration   1: 36.607 ±(99.9%) 0.878 ms/op
Iteration   1: 26.207 ±(99.9%) 0.199 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.207 ms/op


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
# Warmup Iteration   1: 19.086 ±(99.9%) 0.545 ms/op
Iteration   1: 12.889 ±(99.9%) 0.302 ms/op
                 createUser·p0.00:   4.809 ms/op
                 createUser·p0.50:   12.370 ms/op
                 createUser·p0.90:   15.712 ms/op
                 createUser·p0.95:   21.755 ms/op
                 createUser·p0.99:   35.979 ms/op
                 createUser·p0.999:  37.224 ms/op
                 createUser·p0.9999: 37.224 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2473
  mean =     12.889 ±(99.9%) 0.302 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 802 
    [12.500, 15.000) = 850 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      4.809 ms/op
     p(50.0000) =     12.370 ms/op
     p(90.0000) =     15.712 ms/op
     p(95.0000) =     21.755 ms/op
     p(99.0000) =     35.979 ms/op
     p(99.9000) =     37.224 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 13.346 ±(99.9%) 0.441 ms/op
Iteration   1: 7.343 ±(99.9%) 0.183 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   6.472 ms/op
                 existUser·p0.90:   9.993 ms/op
                 existUser·p0.95:   12.206 ms/op
                 existUser·p0.99:   20.723 ms/op
                 existUser·p0.999:  43.254 ms/op
                 existUser·p0.9999: 43.319 ms/op
                 existUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4356
  mean =      7.343 ±(99.9%) 0.183 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 616 
    [ 5.000, 10.000) = 3305 
    [10.000, 15.000) = 303 
    [15.000, 20.000) = 86 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      6.472 ms/op
     p(90.0000) =      9.993 ms/op
     p(95.0000) =     12.206 ms/op
     p(99.0000) =     20.723 ms/op
     p(99.9000) =     43.254 ms/op
     p(99.9900) =     43.319 ms/op
     p(99.9990) =     43.319 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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
# Warmup Iteration   1: 17.897 ±(99.9%) 0.433 ms/op
Iteration   1: 8.324 ±(99.9%) 0.224 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   7.217 ms/op
                 getUser·p0.90:   11.469 ms/op
                 getUser·p0.95:   14.516 ms/op
                 getUser·p0.99:   26.765 ms/op
                 getUser·p0.999:  45.753 ms/op
                 getUser·p0.9999: 45.941 ms/op
                 getUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3859
  mean =      8.324 ±(99.9%) 0.224 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 181 
    [ 5.000, 10.000) = 2970 
    [10.000, 15.000) = 529 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      7.217 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     14.516 ms/op
     p(99.0000) =     26.765 ms/op
     p(99.9000) =     45.753 ms/op
     p(99.9900) =     45.941 ms/op
     p(99.9990) =     45.941 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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
# Warmup Iteration   1: 39.952 ±(99.9%) 1.506 ms/op
Iteration   1: 24.082 ±(99.9%) 0.652 ms/op
                 listUser·p0.00:   4.923 ms/op
                 listUser·p0.50:   23.331 ms/op
                 listUser·p0.90:   32.375 ms/op
                 listUser·p0.95:   36.831 ms/op
                 listUser·p0.99:   50.839 ms/op
                 listUser·p0.999:  55.622 ms/op
                 listUser·p0.9999: 56.754 ms/op
                 listUser·p1.00:   56.754 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1325
  mean =     24.082 ±(99.9%) 0.652 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 31 
    [10.000, 15.000) = 46 
    [15.000, 20.000) = 197 
    [20.000, 25.000) = 685 
    [25.000, 30.000) = 149 
    [30.000, 35.000) = 113 
    [35.000, 40.000) = 57 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      4.923 ms/op
     p(50.0000) =     23.331 ms/op
     p(90.0000) =     32.375 ms/op
     p(95.0000) =     36.831 ms/op
     p(99.0000) =     50.839 ms/op
     p(99.9000) =     55.622 ms/op
     p(99.9900) =     56.754 ms/op
     p(99.9990) =     56.754 ms/op
     p(99.9999) =     56.754 ms/op
    p(100.0000) =     56.754 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.366          ops/ms
Client.existUser                       thrpt         3.603          ops/ms
Client.getUser                         thrpt         2.758          ops/ms
Client.listUser                        thrpt         0.966          ops/ms
Client.createUser                       avgt        16.437           ms/op
Client.existUser                        avgt         7.845           ms/op
Client.getUser                          avgt         8.097           ms/op
Client.listUser                         avgt        26.207           ms/op
Client.createUser                     sample  2473  12.889 ± 0.302   ms/op
Client.createUser:createUser·p0.00    sample         4.809           ms/op
Client.createUser:createUser·p0.50    sample        12.370           ms/op
Client.createUser:createUser·p0.90    sample        15.712           ms/op
Client.createUser:createUser·p0.95    sample        21.755           ms/op
Client.createUser:createUser·p0.99    sample        35.979           ms/op
Client.createUser:createUser·p0.999   sample        37.224           ms/op
Client.createUser:createUser·p0.9999  sample        37.224           ms/op
Client.createUser:createUser·p1.00    sample        37.224           ms/op
Client.existUser                      sample  4356   7.343 ± 0.183   ms/op
Client.existUser:existUser·p0.00      sample         1.907           ms/op
Client.existUser:existUser·p0.50      sample         6.472           ms/op
Client.existUser:existUser·p0.90      sample         9.993           ms/op
Client.existUser:existUser·p0.95      sample        12.206           ms/op
Client.existUser:existUser·p0.99      sample        20.723           ms/op
Client.existUser:existUser·p0.999     sample        43.254           ms/op
Client.existUser:existUser·p0.9999    sample        43.319           ms/op
Client.existUser:existUser·p1.00      sample        43.319           ms/op
Client.getUser                        sample  3859   8.324 ± 0.224   ms/op
Client.getUser:getUser·p0.00          sample         2.523           ms/op
Client.getUser:getUser·p0.50          sample         7.217           ms/op
Client.getUser:getUser·p0.90          sample        11.469           ms/op
Client.getUser:getUser·p0.95          sample        14.516           ms/op
Client.getUser:getUser·p0.99          sample        26.765           ms/op
Client.getUser:getUser·p0.999         sample        45.753           ms/op
Client.getUser:getUser·p0.9999        sample        45.941           ms/op
Client.getUser:getUser·p1.00          sample        45.941           ms/op
Client.listUser                       sample  1325  24.082 ± 0.652   ms/op
Client.listUser:listUser·p0.00        sample         4.923           ms/op
Client.listUser:listUser·p0.50        sample        23.331           ms/op
Client.listUser:listUser·p0.90        sample        32.375           ms/op
Client.listUser:listUser·p0.95        sample        36.831           ms/op
Client.listUser:listUser·p0.99        sample        50.839           ms/op
Client.listUser:listUser·p0.999       sample        55.622           ms/op
Client.listUser:listUser·p0.9999      sample        56.754           ms/op
Client.listUser:listUser·p1.00        sample        56.754           ms/op
