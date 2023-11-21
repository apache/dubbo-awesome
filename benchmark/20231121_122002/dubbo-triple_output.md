# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.508 ops/ms
# Warmup Iteration   2: 12.228 ops/ms
# Warmup Iteration   3: 12.582 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.853 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.807 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (12.673, 12.807, 12.896), stdev = 0.118
  CI (99.9%): [10.651, 14.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 13.005 ops/ms
# Warmup Iteration   3: 13.071 ops/ms
Iteration   1: 13.094 ops/ms
Iteration   2: 13.215 ops/ms
Iteration   3: 13.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.191 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (13.094, 13.191, 13.263), stdev = 0.087
  CI (99.9%): [11.600, 14.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.526 ops/ms
# Warmup Iteration   2: 12.513 ops/ms
# Warmup Iteration   3: 12.565 ops/ms
Iteration   1: 12.745 ops/ms
Iteration   2: 12.902 ops/ms
Iteration   3: 12.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.775 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (12.679, 12.775, 12.902), stdev = 0.115
  CI (99.9%): [10.685, 14.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.244 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.587 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.652 ±(99.9%) 1.065 ops/ms [Average]
  (min, avg, max) = (10.587, 10.652, 10.701), stdev = 0.058
  CI (99.9%): [9.587, 11.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.526, 2.534, 2.544), stdev = 0.009
  CI (99.9%): [2.372, 2.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (2.455, 2.478, 2.495), stdev = 0.021
  CI (99.9%): [2.100, 2.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.467, 2.491, 2.506), stdev = 0.021
  CI (99.9%): [2.102, 2.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
Iteration   3: 3.033 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.033, 3.042, 3.057), stdev = 0.013
  CI (99.9%): [2.801, 3.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.718 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.852 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.590 ms/op
                 createUser·p0.999:  9.573 ms/op
                 createUser·p0.9999: 13.688 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.721 ms/op
                 createUser·p0.9999: 11.447 ms/op
                 createUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380394
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183292 
    [ 2.500,  5.000) = 196177 
    [ 5.000,  7.500) = 536 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  5.785 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.853 ms/op
                 existUser·p0.999:  10.849 ms/op
                 existUser·p0.9999: 14.749 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.568 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384047
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 189080 
    [ 2.500,  3.750) = 190485 
    [ 3.750,  5.000) = 3707 
    [ 5.000,  6.250) = 299 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     14.486 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  6.477 ms/op
                 getUser·p0.9999: 14.141 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.789 ms/op
                 getUser·p0.9999: 13.321 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 10.437 ms/op
                 getUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388477
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 195173 
    [ 2.500,  3.750) = 188419 
    [ 3.750,  5.000) = 3959 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      6.571 ms/op
     p(99.9900) =     13.536 ms/op
     p(99.9990) =     14.813 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.886 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.668 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.757 ms/op
                 listUser·p0.9999: 12.294 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.311 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318945
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 94532 
    [ 2.500,  3.750) = 184399 
    [ 3.750,  5.000) = 32104 
    [ 5.000,  6.250) = 6303 
    [ 6.250,  7.500) = 773 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 196 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.749 ms/op
     p(99.9900) =     11.659 ms/op
     p(99.9990) =     12.460 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.807 ± 2.157  ops/ms
ClientPb.existUser                       thrpt       3  13.191 ± 1.591  ops/ms
ClientPb.getUser                         thrpt       3  12.775 ± 2.090  ops/ms
ClientPb.listUser                        thrpt       3  10.652 ± 1.065  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.162   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.378   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.389   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.241   ms/op
ClientPb.createUser                     sample  380394   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.809           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.840           ms/op
ClientPb.existUser                      sample  384047   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.571           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.832           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.486           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.499           ms/op
ClientPb.getUser                        sample  388477   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.590           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.571           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.536           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  318945   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.749           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.659           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
