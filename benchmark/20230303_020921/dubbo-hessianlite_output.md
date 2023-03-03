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
# Warmup Iteration   1: 0.736 ops/ms
Iteration   1: 1.456 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.456 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.722 ops/ms
Iteration   1: 3.724 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.724 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.133 ops/ms
Iteration   1: 2.860 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.860 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.619 ops/ms
Iteration   1: 0.875 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.875 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 26.210 ±(99.9%) 0.495 ms/op
Iteration   1: 14.264 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  14.264 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.286 ±(99.9%) 0.582 ms/op
Iteration   1: 8.140 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.140 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.308 ±(99.9%) 0.307 ms/op
Iteration   1: 6.859 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.859 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 42.631 ±(99.9%) 1.322 ms/op
Iteration   1: 26.251 ±(99.9%) 0.168 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.251 ms/op


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
# Warmup Iteration   1: 20.804 ±(99.9%) 0.446 ms/op
Iteration   1: 12.486 ±(99.9%) 0.302 ms/op
                 createUser·p0.00:   4.989 ms/op
                 createUser·p0.50:   11.370 ms/op
                 createUser·p0.90:   17.891 ms/op
                 createUser·p0.95:   22.662 ms/op
                 createUser·p0.99:   31.786 ms/op
                 createUser·p0.999:  38.732 ms/op
                 createUser·p0.9999: 41.812 ms/op
                 createUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2547
  mean =     12.486 ±(99.9%) 0.302 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 494 
    [10.000, 15.000) = 1647 
    [15.000, 20.000) = 226 
    [20.000, 25.000) = 110 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.989 ms/op
     p(50.0000) =     11.370 ms/op
     p(90.0000) =     17.891 ms/op
     p(95.0000) =     22.662 ms/op
     p(99.0000) =     31.786 ms/op
     p(99.9000) =     38.732 ms/op
     p(99.9900) =     41.812 ms/op
     p(99.9990) =     41.812 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


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
# Warmup Iteration   1: 13.276 ±(99.9%) 0.348 ms/op
Iteration   1: 8.023 ±(99.9%) 0.152 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   8.094 ms/op
                 existUser·p0.90:   11.934 ms/op
                 existUser·p0.95:   13.697 ms/op
                 existUser·p0.99:   17.951 ms/op
                 existUser·p0.999:  23.265 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4008
  mean =      8.023 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 675 
    [ 5.000,  7.500) = 722 
    [ 7.500, 10.000) = 2065 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      8.094 ms/op
     p(90.0000) =     11.934 ms/op
     p(95.0000) =     13.697 ms/op
     p(99.0000) =     17.951 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 18.000 ±(99.9%) 0.449 ms/op
Iteration   1: 8.812 ±(99.9%) 0.207 ms/op
                 getUser·p0.00:   4.448 ms/op
                 getUser·p0.50:   7.938 ms/op
                 getUser·p0.90:   11.796 ms/op
                 getUser·p0.95:   15.909 ms/op
                 getUser·p0.99:   30.343 ms/op
                 getUser·p0.999:  35.632 ms/op
                 getUser·p0.9999: 35.979 ms/op
                 getUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3649
  mean =      8.812 ±(99.9%) 0.207 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33 
    [ 5.000,  7.500) = 1306 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      4.448 ms/op
     p(50.0000) =      7.938 ms/op
     p(90.0000) =     11.796 ms/op
     p(95.0000) =     15.909 ms/op
     p(99.0000) =     30.343 ms/op
     p(99.9000) =     35.632 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 34.091 ±(99.9%) 0.901 ms/op
Iteration   1: 25.501 ±(99.9%) 0.557 ms/op
                 listUser·p0.00:   5.997 ms/op
                 listUser·p0.50:   23.675 ms/op
                 listUser·p0.90:   32.932 ms/op
                 listUser·p0.95:   36.504 ms/op
                 listUser·p0.99:   45.415 ms/op
                 listUser·p0.999:  50.823 ms/op
                 listUser·p0.9999: 50.921 ms/op
                 listUser·p1.00:   50.921 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1250
  mean =     25.501 ±(99.9%) 0.557 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 4 
    [10.000, 15.000) = 19 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 626 
    [25.000, 30.000) = 252 
    [30.000, 35.000) = 180 
    [35.000, 40.000) = 62 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 16 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.997 ms/op
     p(50.0000) =     23.675 ms/op
     p(90.0000) =     32.932 ms/op
     p(95.0000) =     36.504 ms/op
     p(99.0000) =     45.415 ms/op
     p(99.9000) =     50.823 ms/op
     p(99.9900) =     50.921 ms/op
     p(99.9990) =     50.921 ms/op
     p(99.9999) =     50.921 ms/op
    p(100.0000) =     50.921 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.456          ops/ms
Client.existUser                       thrpt         3.724          ops/ms
Client.getUser                         thrpt         2.860          ops/ms
Client.listUser                        thrpt         0.875          ops/ms
Client.createUser                       avgt        14.264           ms/op
Client.existUser                        avgt         8.140           ms/op
Client.getUser                          avgt         6.859           ms/op
Client.listUser                         avgt        26.251           ms/op
Client.createUser                     sample  2547  12.486 ± 0.302   ms/op
Client.createUser:createUser·p0.00    sample         4.989           ms/op
Client.createUser:createUser·p0.50    sample        11.370           ms/op
Client.createUser:createUser·p0.90    sample        17.891           ms/op
Client.createUser:createUser·p0.95    sample        22.662           ms/op
Client.createUser:createUser·p0.99    sample        31.786           ms/op
Client.createUser:createUser·p0.999   sample        38.732           ms/op
Client.createUser:createUser·p0.9999  sample        41.812           ms/op
Client.createUser:createUser·p1.00    sample        41.812           ms/op
Client.existUser                      sample  4008   8.023 ± 0.152   ms/op
Client.existUser:existUser·p0.00      sample         2.179           ms/op
Client.existUser:existUser·p0.50      sample         8.094           ms/op
Client.existUser:existUser·p0.90      sample        11.934           ms/op
Client.existUser:existUser·p0.95      sample        13.697           ms/op
Client.existUser:existUser·p0.99      sample        17.951           ms/op
Client.existUser:existUser·p0.999     sample        23.265           ms/op
Client.existUser:existUser·p0.9999    sample        23.527           ms/op
Client.existUser:existUser·p1.00      sample        23.527           ms/op
Client.getUser                        sample  3649   8.812 ± 0.207   ms/op
Client.getUser:getUser·p0.00          sample         4.448           ms/op
Client.getUser:getUser·p0.50          sample         7.938           ms/op
Client.getUser:getUser·p0.90          sample        11.796           ms/op
Client.getUser:getUser·p0.95          sample        15.909           ms/op
Client.getUser:getUser·p0.99          sample        30.343           ms/op
Client.getUser:getUser·p0.999         sample        35.632           ms/op
Client.getUser:getUser·p0.9999        sample        35.979           ms/op
Client.getUser:getUser·p1.00          sample        35.979           ms/op
Client.listUser                       sample  1250  25.501 ± 0.557   ms/op
Client.listUser:listUser·p0.00        sample         5.997           ms/op
Client.listUser:listUser·p0.50        sample        23.675           ms/op
Client.listUser:listUser·p0.90        sample        32.932           ms/op
Client.listUser:listUser·p0.95        sample        36.504           ms/op
Client.listUser:listUser·p0.99        sample        45.415           ms/op
Client.listUser:listUser·p0.999       sample        50.823           ms/op
Client.listUser:listUser·p0.9999      sample        50.921           ms/op
Client.listUser:listUser·p1.00        sample        50.921           ms/op
