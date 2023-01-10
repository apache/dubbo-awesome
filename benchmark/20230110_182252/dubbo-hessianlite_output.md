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
# Warmup Iteration   1: 0.451 ops/ms
Iteration   1: 1.193 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.193 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:30
# Fork: 1 of 1
# Warmup Iteration   1: 1.401 ops/ms
Iteration   1: 3.412 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.412 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
Iteration   1: 2.763 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.763 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.570 ops/ms
Iteration   1: 0.821 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.821 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 24.947 ±(99.9%) 0.707 ms/op
Iteration   1: 16.098 ±(99.9%) 0.258 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.098 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 16.616 ±(99.9%) 0.272 ms/op
Iteration   1: 9.235 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.235 ms/op


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
# Warmup Iteration   1: 20.717 ±(99.9%) 0.245 ms/op
Iteration   1: 7.539 ±(99.9%) 0.054 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.539 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 39.675 ±(99.9%) 0.886 ms/op
Iteration   1: 30.113 ±(99.9%) 0.347 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  30.113 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 25.738 ±(99.9%) 1.041 ms/op
Iteration   1: 13.187 ±(99.9%) 0.423 ms/op
                 createUser·p0.00:   3.572 ms/op
                 createUser·p0.50:   10.928 ms/op
                 createUser·p0.90:   23.541 ms/op
                 createUser·p0.95:   25.788 ms/op
                 createUser·p0.99:   37.859 ms/op
                 createUser·p0.999:  38.703 ms/op
                 createUser·p0.9999: 41.222 ms/op
                 createUser·p1.00:   41.222 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2431
  mean =     13.187 ±(99.9%) 0.423 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 97 
    [ 5.000, 10.000) = 464 
    [10.000, 15.000) = 1299 
    [15.000, 20.000) = 156 
    [20.000, 25.000) = 282 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.572 ms/op
     p(50.0000) =     10.928 ms/op
     p(90.0000) =     23.541 ms/op
     p(95.0000) =     25.788 ms/op
     p(99.0000) =     37.859 ms/op
     p(99.9000) =     38.703 ms/op
     p(99.9900) =     41.222 ms/op
     p(99.9990) =     41.222 ms/op
     p(99.9999) =     41.222 ms/op
    p(100.0000) =     41.222 ms/op


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
# Warmup Iteration   1: 13.390 ±(99.9%) 0.423 ms/op
Iteration   1: 7.665 ±(99.9%) 0.136 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   7.389 ms/op
                 existUser·p0.90:   9.028 ms/op
                 existUser·p0.95:   10.750 ms/op
                 existUser·p0.99:   17.039 ms/op
                 existUser·p0.999:  29.256 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4185
  mean =      7.665 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 241 
    [ 5.000,  7.500) = 1939 
    [ 7.500, 10.000) = 1671 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =     10.750 ms/op
     p(99.0000) =     17.039 ms/op
     p(99.9000) =     29.256 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 20.375 ±(99.9%) 0.742 ms/op
Iteration   1: 8.527 ±(99.9%) 0.192 ms/op
                 getUser·p0.00:   3.703 ms/op
                 getUser·p0.50:   7.414 ms/op
                 getUser·p0.90:   12.124 ms/op
                 getUser·p0.95:   15.161 ms/op
                 getUser·p0.99:   26.182 ms/op
                 getUser·p0.999:  31.883 ms/op
                 getUser·p0.9999: 32.113 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3752
  mean =      8.527 ±(99.9%) 0.192 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 36 
    [ 5.000,  7.500) = 1989 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.703 ms/op
     p(50.0000) =      7.414 ms/op
     p(90.0000) =     12.124 ms/op
     p(95.0000) =     15.161 ms/op
     p(99.0000) =     26.182 ms/op
     p(99.9000) =     31.883 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 45.253 ±(99.9%) 1.630 ms/op
Iteration   1: 32.510 ±(99.9%) 1.093 ms/op
                 listUser·p0.00:   10.142 ms/op
                 listUser·p0.50:   27.918 ms/op
                 listUser·p0.90:   46.236 ms/op
                 listUser·p0.95:   58.173 ms/op
                 listUser·p0.99:   67.895 ms/op
                 listUser·p0.999:  77.988 ms/op
                 listUser·p0.9999: 77.988 ms/op
                 listUser·p1.00:   77.988 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 986
  mean =     32.510 ±(99.9%) 1.093 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 15 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 490 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 117 
    [40.000, 45.000) = 76 
    [45.000, 50.000) = 58 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 26 
    [60.000, 65.000) = 15 
    [65.000, 70.000) = 9 
    [70.000, 75.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =     10.142 ms/op
     p(50.0000) =     27.918 ms/op
     p(90.0000) =     46.236 ms/op
     p(95.0000) =     58.173 ms/op
     p(99.0000) =     67.895 ms/op
     p(99.9000) =     77.988 ms/op
     p(99.9900) =     77.988 ms/op
     p(99.9990) =     77.988 ms/op
     p(99.9999) =     77.988 ms/op
    p(100.0000) =     77.988 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.193          ops/ms
Client.existUser                       thrpt         3.412          ops/ms
Client.getUser                         thrpt         2.763          ops/ms
Client.listUser                        thrpt         0.821          ops/ms
Client.createUser                       avgt        16.098           ms/op
Client.existUser                        avgt         9.235           ms/op
Client.getUser                          avgt         7.539           ms/op
Client.listUser                         avgt        30.113           ms/op
Client.createUser                     sample  2431  13.187 ± 0.423   ms/op
Client.createUser:createUser·p0.00    sample         3.572           ms/op
Client.createUser:createUser·p0.50    sample        10.928           ms/op
Client.createUser:createUser·p0.90    sample        23.541           ms/op
Client.createUser:createUser·p0.95    sample        25.788           ms/op
Client.createUser:createUser·p0.99    sample        37.859           ms/op
Client.createUser:createUser·p0.999   sample        38.703           ms/op
Client.createUser:createUser·p0.9999  sample        41.222           ms/op
Client.createUser:createUser·p1.00    sample        41.222           ms/op
Client.existUser                      sample  4185   7.665 ± 0.136   ms/op
Client.existUser:existUser·p0.00      sample         1.296           ms/op
Client.existUser:existUser·p0.50      sample         7.389           ms/op
Client.existUser:existUser·p0.90      sample         9.028           ms/op
Client.existUser:existUser·p0.95      sample        10.750           ms/op
Client.existUser:existUser·p0.99      sample        17.039           ms/op
Client.existUser:existUser·p0.999     sample        29.256           ms/op
Client.existUser:existUser·p0.9999    sample        33.751           ms/op
Client.existUser:existUser·p1.00      sample        33.751           ms/op
Client.getUser                        sample  3752   8.527 ± 0.192   ms/op
Client.getUser:getUser·p0.00          sample         3.703           ms/op
Client.getUser:getUser·p0.50          sample         7.414           ms/op
Client.getUser:getUser·p0.90          sample        12.124           ms/op
Client.getUser:getUser·p0.95          sample        15.161           ms/op
Client.getUser:getUser·p0.99          sample        26.182           ms/op
Client.getUser:getUser·p0.999         sample        31.883           ms/op
Client.getUser:getUser·p0.9999        sample        32.113           ms/op
Client.getUser:getUser·p1.00          sample        32.113           ms/op
Client.listUser                       sample   986  32.510 ± 1.093   ms/op
Client.listUser:listUser·p0.00        sample        10.142           ms/op
Client.listUser:listUser·p0.50        sample        27.918           ms/op
Client.listUser:listUser·p0.90        sample        46.236           ms/op
Client.listUser:listUser·p0.95        sample        58.173           ms/op
Client.listUser:listUser·p0.99        sample        67.895           ms/op
Client.listUser:listUser·p0.999       sample        77.988           ms/op
Client.listUser:listUser·p0.9999      sample        77.988           ms/op
Client.listUser:listUser·p1.00        sample        77.988           ms/op
