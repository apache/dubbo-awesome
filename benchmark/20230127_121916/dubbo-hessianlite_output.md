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
# Warmup Iteration   1: 1.017 ops/ms
Iteration   1: 2.726 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.726 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ops/ms
Iteration   1: 6.741 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.741 ops/ms


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
# Warmup Iteration   1: 2.176 ops/ms
Iteration   1: 4.541 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.541 ops/ms


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
# Warmup Iteration   1: 0.923 ops/ms
Iteration   1: 1.274 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.274 ops/ms


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
# Warmup Iteration   1: 16.913 ±(99.9%) 0.253 ms/op
Iteration   1: 6.957 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.957 ms/op


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.078 ms/op
Iteration   1: 3.218 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.218 ms/op


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
# Warmup Iteration   1: 7.247 ±(99.9%) 0.092 ms/op
Iteration   1: 5.271 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.271 ms/op


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
# Warmup Iteration   1: 26.574 ±(99.9%) 0.673 ms/op
Iteration   1: 16.484 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.484 ms/op


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
# Warmup Iteration   1: 11.058 ±(99.9%) 0.356 ms/op
Iteration   1: 6.541 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   6.447 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   15.128 ms/op
                 createUser·p0.999:  15.548 ms/op
                 createUser·p0.9999: 35.783 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4768
  mean =      6.541 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 58 
    [ 5.000,  7.500) = 4415 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     15.128 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 5.824 ±(99.9%) 0.186 ms/op
Iteration   1: 3.292 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  21.135 ms/op
                 existUser·p0.9999: 21.135 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9719
  mean =      3.292 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2056 
    [ 2.500,  5.000) = 7333 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 9.923 ±(99.9%) 0.342 ms/op
Iteration   1: 4.621 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   9.257 ms/op
                 getUser·p0.999:  18.903 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7055
  mean =      4.621 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 59 
    [ 2.500,  3.750) = 1735 
    [ 3.750,  5.000) = 3565 
    [ 5.000,  6.250) = 1308 
    [ 6.250,  7.500) = 234 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     18.903 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 24.304 ±(99.9%) 0.698 ms/op
Iteration   1: 16.968 ±(99.9%) 0.241 ms/op
                 listUser·p0.00:   7.528 ms/op
                 listUser·p0.50:   16.663 ms/op
                 listUser·p0.90:   17.891 ms/op
                 listUser·p0.95:   23.888 ms/op
                 listUser·p0.99:   33.294 ms/op
                 listUser·p0.999:  40.977 ms/op
                 listUser·p0.9999: 41.157 ms/op
                 listUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1913
  mean =     16.968 ±(99.9%) 0.241 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 10 
    [10.000, 15.000) = 170 
    [15.000, 20.000) = 1632 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      7.528 ms/op
     p(50.0000) =     16.663 ms/op
     p(90.0000) =     17.891 ms/op
     p(95.0000) =     23.888 ms/op
     p(99.0000) =     33.294 ms/op
     p(99.9000) =     40.977 ms/op
     p(99.9900) =     41.157 ms/op
     p(99.9990) =     41.157 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.726          ops/ms
Client.existUser                       thrpt         6.741          ops/ms
Client.getUser                         thrpt         4.541          ops/ms
Client.listUser                        thrpt         1.274          ops/ms
Client.createUser                       avgt         6.957           ms/op
Client.existUser                        avgt         3.218           ms/op
Client.getUser                          avgt         5.271           ms/op
Client.listUser                         avgt        16.484           ms/op
Client.createUser                     sample  4768   6.541 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample         1.229           ms/op
Client.createUser:createUser·p0.50    sample         6.447           ms/op
Client.createUser:createUser·p0.90    sample         7.070           ms/op
Client.createUser:createUser·p0.95    sample         7.455           ms/op
Client.createUser:createUser·p0.99    sample        15.128           ms/op
Client.createUser:createUser·p0.999   sample        15.548           ms/op
Client.createUser:createUser·p0.9999  sample        35.783           ms/op
Client.createUser:createUser·p1.00    sample        35.783           ms/op
Client.existUser                      sample  9719   3.292 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample         0.591           ms/op
Client.existUser:existUser·p0.50      sample         3.195           ms/op
Client.existUser:existUser·p0.90      sample         3.789           ms/op
Client.existUser:existUser·p0.95      sample         4.039           ms/op
Client.existUser:existUser·p0.99      sample         7.586           ms/op
Client.existUser:existUser·p0.999     sample        21.135           ms/op
Client.existUser:existUser·p0.9999    sample        21.135           ms/op
Client.existUser:existUser·p1.00      sample        21.135           ms/op
Client.getUser                        sample  7055   4.621 ± 0.065   ms/op
Client.getUser:getUser·p0.00          sample         1.495           ms/op
Client.getUser:getUser·p0.50          sample         4.604           ms/op
Client.getUser:getUser·p0.90          sample         5.710           ms/op
Client.getUser:getUser·p0.95          sample         6.504           ms/op
Client.getUser:getUser·p0.99          sample         9.257           ms/op
Client.getUser:getUser·p0.999         sample        18.903           ms/op
Client.getUser:getUser·p0.9999        sample        19.235           ms/op
Client.getUser:getUser·p1.00          sample        19.235           ms/op
Client.listUser                       sample  1913  16.968 ± 0.241   ms/op
Client.listUser:listUser·p0.00        sample         7.528           ms/op
Client.listUser:listUser·p0.50        sample        16.663           ms/op
Client.listUser:listUser·p0.90        sample        17.891           ms/op
Client.listUser:listUser·p0.95        sample        23.888           ms/op
Client.listUser:listUser·p0.99        sample        33.294           ms/op
Client.listUser:listUser·p0.999       sample        40.977           ms/op
Client.listUser:listUser·p0.9999      sample        41.157           ms/op
Client.listUser:listUser·p1.00        sample        41.157           ms/op
