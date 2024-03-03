# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.842 ops/ms
# Warmup Iteration   2: 12.190 ops/ms
# Warmup Iteration   3: 12.540 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.837 ops/ms
Iteration   3: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.878 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (12.793, 12.878, 13.004), stdev = 0.111
  CI (99.9%): [10.851, 14.905] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.155 ops/ms
# Warmup Iteration   2: 13.116 ops/ms
# Warmup Iteration   3: 13.099 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 13.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.141 ±(99.9%) 1.332 ops/ms [Average]
  (min, avg, max) = (13.058, 13.141, 13.196), stdev = 0.073
  CI (99.9%): [11.810, 14.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.880 ops/ms
# Warmup Iteration   2: 12.688 ops/ms
# Warmup Iteration   3: 12.868 ops/ms
Iteration   1: 12.849 ops/ms
Iteration   2: 12.986 ops/ms
Iteration   3: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.895 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (12.849, 12.895, 12.986), stdev = 0.079
  CI (99.9%): [11.451, 14.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.659 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.703 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (10.614, 10.703, 10.806), stdev = 0.097
  CI (99.9%): [8.942, 12.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.003 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
Iteration   2: 2.459 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.473 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.459, 2.473, 2.480), stdev = 0.012
  CI (99.9%): [2.248, 2.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.003 ms/op
Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
Iteration   3: 2.405 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.407 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.398, 2.407, 2.418), stdev = 0.010
  CI (99.9%): [2.217, 2.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.456, 2.470, 2.477), stdev = 0.011
  CI (99.9%): [2.260, 2.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.981, 2.996, 3.014), stdev = 0.017
  CI (99.9%): [2.690, 3.301] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.299 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  11.157 ms/op
                 createUser·p0.9999: 14.195 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  10.093 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  8.811 ms/op
                 createUser·p0.9999: 10.621 ms/op
                 createUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379022
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 184471 
    [ 2.500,  3.750) = 190739 
    [ 3.750,  5.000) = 2996 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.831 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.930 ms/op
                 existUser·p0.999:  7.329 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.382 ms/op
                 existUser·p0.9999: 13.281 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.060 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395916
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 202489 
    [ 2.500,  3.750) = 189697 
    [ 3.750,  5.000) = 2944 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      6.754 ms/op
     p(99.9900) =     12.917 ms/op
     p(99.9990) =     13.502 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.015 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 13.536 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.683 ms/op
                 getUser·p0.9999: 12.532 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  8.692 ms/op
                 getUser·p0.9999: 10.647 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390978
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 198007 
    [ 2.500,  3.750) = 189007 
    [ 3.750,  5.000) = 3059 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.489 ms/op
     p(99.9900) =     13.040 ms/op
     p(99.9990) =     13.831 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 15.868 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 11.947 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.336 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 10.575 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324420
  mean =      2.956 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 101113 
    [ 2.500,  3.750) = 185678 
    [ 3.750,  5.000) = 30863 
    [ 5.000,  6.250) = 5373 
    [ 6.250,  7.500) = 554 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 317 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.463 ms/op
     p(99.9900) =     13.447 ms/op
     p(99.9990) =     16.393 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.878 ± 2.027  ops/ms
ClientPb.existUser                       thrpt       3  13.141 ± 1.332  ops/ms
ClientPb.getUser                         thrpt       3  12.895 ± 1.444  ops/ms
ClientPb.listUser                        thrpt       3  10.703 ± 1.761  ops/ms
ClientPb.createUser                       avgt       3   2.473 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.407 ± 0.190   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.210   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.306   ms/op
ClientPb.createUser                     sample  379022   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  395916   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.852           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.754           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  390978   2.453 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.778           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.489           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.040           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  324420   2.956 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.737           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.463           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.843           ms/op
