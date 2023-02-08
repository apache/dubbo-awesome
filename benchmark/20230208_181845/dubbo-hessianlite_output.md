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
# Warmup Iteration   1: 0.661 ops/ms
Iteration   1: 1.407 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.407 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.552 ops/ms
Iteration   1: 3.222 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.222 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.368 ops/ms
Iteration   1: 2.464 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.464 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.587 ops/ms
Iteration   1: 0.809 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.809 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 25.560 ±(99.9%) 0.549 ms/op
Iteration   1: 15.109 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  15.109 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 17.209 ±(99.9%) 0.304 ms/op
Iteration   1: 7.679 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.679 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 22.291 ±(99.9%) 0.474 ms/op
Iteration   1: 8.307 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.307 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 47.869 ±(99.9%) 0.775 ms/op
Iteration   1: 25.824 ±(99.9%) 0.184 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  25.824 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 22.655 ±(99.9%) 0.898 ms/op
Iteration   1: 11.720 ±(99.9%) 0.228 ms/op
                 createUser·p0.00:   3.654 ms/op
                 createUser·p0.50:   11.141 ms/op
                 createUser·p0.90:   15.319 ms/op
                 createUser·p0.95:   19.595 ms/op
                 createUser·p0.99:   26.706 ms/op
                 createUser·p0.999:  30.867 ms/op
                 createUser·p0.9999: 30.867 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2753
  mean =     11.720 ±(99.9%) 0.228 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 71 
    [ 5.000,  7.500) = 158 
    [ 7.500, 10.000) = 286 
    [10.000, 12.500) = 1625 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.654 ms/op
     p(50.0000) =     11.141 ms/op
     p(90.0000) =     15.319 ms/op
     p(95.0000) =     19.595 ms/op
     p(99.0000) =     26.706 ms/op
     p(99.9000) =     30.867 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.702 ±(99.9%) 0.416 ms/op
Iteration   1: 7.928 ±(99.9%) 0.195 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   6.971 ms/op
                 existUser·p0.90:   9.847 ms/op
                 existUser·p0.95:   15.204 ms/op
                 existUser·p0.99:   24.555 ms/op
                 existUser·p0.999:  39.322 ms/op
                 existUser·p0.9999: 39.387 ms/op
                 existUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4064
  mean =      7.928 ±(99.9%) 0.195 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 81 
    [ 5.000,  7.500) = 2599 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      6.971 ms/op
     p(90.0000) =      9.847 ms/op
     p(95.0000) =     15.204 ms/op
     p(99.0000) =     24.555 ms/op
     p(99.9000) =     39.322 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 18.239 ±(99.9%) 0.645 ms/op
Iteration   1: 8.650 ±(99.9%) 0.287 ms/op
                 getUser·p0.00:   2.400 ms/op
                 getUser·p0.50:   6.881 ms/op
                 getUser·p0.90:   12.632 ms/op
                 getUser·p0.95:   18.983 ms/op
                 getUser·p0.99:   31.745 ms/op
                 getUser·p0.999:  46.551 ms/op
                 getUser·p0.9999: 46.793 ms/op
                 getUser·p1.00:   46.793 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3693
  mean =      8.650 ±(99.9%) 0.287 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 134 
    [ 5.000, 10.000) = 2844 
    [10.000, 15.000) = 446 
    [15.000, 20.000) = 114 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      6.881 ms/op
     p(90.0000) =     12.632 ms/op
     p(95.0000) =     18.983 ms/op
     p(99.0000) =     31.745 ms/op
     p(99.9000) =     46.551 ms/op
     p(99.9900) =     46.793 ms/op
     p(99.9990) =     46.793 ms/op
     p(99.9999) =     46.793 ms/op
    p(100.0000) =     46.793 ms/op


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
# Warmup Iteration   1: 50.664 ±(99.9%) 2.600 ms/op
Iteration   1: 32.016 ±(99.9%) 0.913 ms/op
                 listUser·p0.00:   16.597 ms/op
                 listUser·p0.50:   29.229 ms/op
                 listUser·p0.90:   43.385 ms/op
                 listUser·p0.95:   47.759 ms/op
                 listUser·p0.99:   61.594 ms/op
                 listUser·p0.999:  72.604 ms/op
                 listUser·p0.9999: 72.614 ms/op
                 listUser·p1.00:   72.614 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1004
  mean =     32.016 ±(99.9%) 0.913 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 172 
    [25.000, 30.000) = 339 
    [30.000, 35.000) = 136 
    [35.000, 40.000) = 149 
    [40.000, 45.000) = 106 
    [45.000, 50.000) = 48 
    [50.000, 55.000) = 15 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =     16.597 ms/op
     p(50.0000) =     29.229 ms/op
     p(90.0000) =     43.385 ms/op
     p(95.0000) =     47.759 ms/op
     p(99.0000) =     61.594 ms/op
     p(99.9000) =     72.604 ms/op
     p(99.9900) =     72.614 ms/op
     p(99.9990) =     72.614 ms/op
     p(99.9999) =     72.614 ms/op
    p(100.0000) =     72.614 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.407          ops/ms
Client.existUser                       thrpt         3.222          ops/ms
Client.getUser                         thrpt         2.464          ops/ms
Client.listUser                        thrpt         0.809          ops/ms
Client.createUser                       avgt        15.109           ms/op
Client.existUser                        avgt         7.679           ms/op
Client.getUser                          avgt         8.307           ms/op
Client.listUser                         avgt        25.824           ms/op
Client.createUser                     sample  2753  11.720 ± 0.228   ms/op
Client.createUser:createUser·p0.00    sample         3.654           ms/op
Client.createUser:createUser·p0.50    sample        11.141           ms/op
Client.createUser:createUser·p0.90    sample        15.319           ms/op
Client.createUser:createUser·p0.95    sample        19.595           ms/op
Client.createUser:createUser·p0.99    sample        26.706           ms/op
Client.createUser:createUser·p0.999   sample        30.867           ms/op
Client.createUser:createUser·p0.9999  sample        30.867           ms/op
Client.createUser:createUser·p1.00    sample        30.867           ms/op
Client.existUser                      sample  4064   7.928 ± 0.195   ms/op
Client.existUser:existUser·p0.00      sample         1.823           ms/op
Client.existUser:existUser·p0.50      sample         6.971           ms/op
Client.existUser:existUser·p0.90      sample         9.847           ms/op
Client.existUser:existUser·p0.95      sample        15.204           ms/op
Client.existUser:existUser·p0.99      sample        24.555           ms/op
Client.existUser:existUser·p0.999     sample        39.322           ms/op
Client.existUser:existUser·p0.9999    sample        39.387           ms/op
Client.existUser:existUser·p1.00      sample        39.387           ms/op
Client.getUser                        sample  3693   8.650 ± 0.287   ms/op
Client.getUser:getUser·p0.00          sample         2.400           ms/op
Client.getUser:getUser·p0.50          sample         6.881           ms/op
Client.getUser:getUser·p0.90          sample        12.632           ms/op
Client.getUser:getUser·p0.95          sample        18.983           ms/op
Client.getUser:getUser·p0.99          sample        31.745           ms/op
Client.getUser:getUser·p0.999         sample        46.551           ms/op
Client.getUser:getUser·p0.9999        sample        46.793           ms/op
Client.getUser:getUser·p1.00          sample        46.793           ms/op
Client.listUser                       sample  1004  32.016 ± 0.913   ms/op
Client.listUser:listUser·p0.00        sample        16.597           ms/op
Client.listUser:listUser·p0.50        sample        29.229           ms/op
Client.listUser:listUser·p0.90        sample        43.385           ms/op
Client.listUser:listUser·p0.95        sample        47.759           ms/op
Client.listUser:listUser·p0.99        sample        61.594           ms/op
Client.listUser:listUser·p0.999       sample        72.604           ms/op
Client.listUser:listUser·p0.9999      sample        72.614           ms/op
Client.listUser:listUser·p1.00        sample        72.614           ms/op
