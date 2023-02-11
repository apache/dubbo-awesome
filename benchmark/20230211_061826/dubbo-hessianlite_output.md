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
# Warmup Iteration   1: 1.215 ops/ms
Iteration   1: 2.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.761 ops/ms


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
# Warmup Iteration   1: 3.286 ops/ms
Iteration   1: 5.906 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.906 ops/ms


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
# Warmup Iteration   1: 2.545 ops/ms
Iteration   1: 5.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.344 ops/ms


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
# Warmup Iteration   1: 0.876 ops/ms
Iteration   1: 1.467 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.467 ops/ms


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
# Warmup Iteration   1: 13.988 ±(99.9%) 0.253 ms/op
Iteration   1: 5.795 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.795 ms/op


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
# Warmup Iteration   1: 6.723 ±(99.9%) 0.084 ms/op
Iteration   1: 4.211 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.211 ms/op


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
# Warmup Iteration   1: 7.610 ±(99.9%) 0.086 ms/op
Iteration   1: 4.655 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.655 ms/op


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
# Warmup Iteration   1: 28.729 ±(99.9%) 0.375 ms/op
Iteration   1: 15.190 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.190 ms/op


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
# Warmup Iteration   1: 10.268 ±(99.9%) 0.262 ms/op
Iteration   1: 6.062 ±(99.9%) 0.125 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   5.550 ms/op
                 createUser·p0.90:   6.528 ms/op
                 createUser·p0.95:   11.190 ms/op
                 createUser·p0.99:   14.336 ms/op
                 createUser·p0.999:  33.121 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5270
  mean =      6.062 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 408 
    [ 5.000,  7.500) = 4437 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      5.550 ms/op
     p(90.0000) =      6.528 ms/op
     p(95.0000) =     11.190 ms/op
     p(99.0000) =     14.336 ms/op
     p(99.9000) =     33.121 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.182 ms/op
Iteration   1: 3.874 ±(99.9%) 0.068 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   12.648 ms/op
                 existUser·p0.999:  24.657 ms/op
                 existUser·p0.9999: 25.100 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8258
  mean =      3.874 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 597 
    [ 2.500,  5.000) = 7271 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     24.657 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 9.353 ±(99.9%) 0.306 ms/op
Iteration   1: 4.233 ±(99.9%) 0.055 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   11.854 ms/op
                 getUser·p0.999:  15.974 ms/op
                 getUser·p0.9999: 16.007 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7571
  mean =      4.233 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 62 
    [ 2.500,  3.750) = 2894 
    [ 3.750,  5.000) = 3678 
    [ 5.000,  6.250) = 647 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =     11.854 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 25.901 ±(99.9%) 1.034 ms/op
Iteration   1: 16.636 ±(99.9%) 0.307 ms/op
                 listUser·p0.00:   7.127 ms/op
                 listUser·p0.50:   17.596 ms/op
                 listUser·p0.90:   20.873 ms/op
                 listUser·p0.95:   21.950 ms/op
                 listUser·p0.99:   29.234 ms/op
                 listUser·p0.999:  31.898 ms/op
                 listUser·p0.9999: 32.145 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1942
  mean =     16.636 ±(99.9%) 0.307 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 352 
    [17.500, 20.000) = 711 
    [20.000, 22.500) = 214 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.127 ms/op
     p(50.0000) =     17.596 ms/op
     p(90.0000) =     20.873 ms/op
     p(95.0000) =     21.950 ms/op
     p(99.0000) =     29.234 ms/op
     p(99.9000) =     31.898 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.761          ops/ms
Client.existUser                       thrpt         5.906          ops/ms
Client.getUser                         thrpt         5.344          ops/ms
Client.listUser                        thrpt         1.467          ops/ms
Client.createUser                       avgt         5.795           ms/op
Client.existUser                        avgt         4.211           ms/op
Client.getUser                          avgt         4.655           ms/op
Client.listUser                         avgt        15.190           ms/op
Client.createUser                     sample  5270   6.062 ± 0.125   ms/op
Client.createUser:createUser·p0.00    sample         1.118           ms/op
Client.createUser:createUser·p0.50    sample         5.550           ms/op
Client.createUser:createUser·p0.90    sample         6.528           ms/op
Client.createUser:createUser·p0.95    sample        11.190           ms/op
Client.createUser:createUser·p0.99    sample        14.336           ms/op
Client.createUser:createUser·p0.999   sample        33.121           ms/op
Client.createUser:createUser·p0.9999  sample        33.686           ms/op
Client.createUser:createUser·p1.00    sample        33.686           ms/op
Client.existUser                      sample  8258   3.874 ± 0.068   ms/op
Client.existUser:existUser·p0.00      sample         0.768           ms/op
Client.existUser:existUser·p0.50      sample         3.744           ms/op
Client.existUser:existUser·p0.90      sample         4.092           ms/op
Client.existUser:existUser·p0.95      sample         4.801           ms/op
Client.existUser:existUser·p0.99      sample        12.648           ms/op
Client.existUser:existUser·p0.999     sample        24.657           ms/op
Client.existUser:existUser·p0.9999    sample        25.100           ms/op
Client.existUser:existUser·p1.00      sample        25.100           ms/op
Client.getUser                        sample  7571   4.233 ± 0.055   ms/op
Client.getUser:getUser·p0.00          sample         1.858           ms/op
Client.getUser:getUser·p0.50          sample         3.908           ms/op
Client.getUser:getUser·p0.90          sample         5.349           ms/op
Client.getUser:getUser·p0.95          sample         6.021           ms/op
Client.getUser:getUser·p0.99          sample        11.854           ms/op
Client.getUser:getUser·p0.999         sample        15.974           ms/op
Client.getUser:getUser·p0.9999        sample        16.007           ms/op
Client.getUser:getUser·p1.00          sample        16.007           ms/op
Client.listUser                       sample  1942  16.636 ± 0.307   ms/op
Client.listUser:listUser·p0.00        sample         7.127           ms/op
Client.listUser:listUser·p0.50        sample        17.596           ms/op
Client.listUser:listUser·p0.90        sample        20.873           ms/op
Client.listUser:listUser·p0.95        sample        21.950           ms/op
Client.listUser:listUser·p0.99        sample        29.234           ms/op
Client.listUser:listUser·p0.999       sample        31.898           ms/op
Client.listUser:listUser·p0.9999      sample        32.145           ms/op
Client.listUser:listUser·p1.00        sample        32.145           ms/op
