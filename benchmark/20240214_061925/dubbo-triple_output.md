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
# Warmup Iteration   1: 4.695 ops/ms
# Warmup Iteration   2: 11.747 ops/ms
# Warmup Iteration   3: 11.869 ops/ms
Iteration   1: 12.191 ops/ms
Iteration   2: 12.317 ops/ms
Iteration   3: 12.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.237 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (12.191, 12.237, 12.317), stdev = 0.070
  CI (99.9%): [10.967, 13.507] (assumes normal distribution)


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
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 13.170 ops/ms
# Warmup Iteration   3: 13.211 ops/ms
Iteration   1: 13.355 ops/ms
Iteration   2: 13.372 ops/ms
Iteration   3: 13.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.305 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (13.187, 13.305, 13.372), stdev = 0.102
  CI (99.9%): [11.438, 15.171] (assumes normal distribution)


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
# Warmup Iteration   1: 7.798 ops/ms
# Warmup Iteration   2: 12.794 ops/ms
# Warmup Iteration   3: 12.779 ops/ms
Iteration   1: 12.958 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.922 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (12.841, 12.922, 12.968), stdev = 0.071
  CI (99.9%): [11.636, 14.209] (assumes normal distribution)


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
# Warmup Iteration   1: 6.675 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.544 ops/ms
Iteration   1: 10.562 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.568 ±(99.9%) 0.358 ops/ms [Average]
  (min, avg, max) = (10.552, 10.568, 10.590), stdev = 0.020
  CI (99.9%): [10.210, 10.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.003 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.490, 2.504, 2.512), stdev = 0.012
  CI (99.9%): [2.285, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.571 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
Iteration   2: 2.458 ±(99.9%) 0.003 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.438, 2.456, 2.473), stdev = 0.017
  CI (99.9%): [2.137, 2.775] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.481, 2.488, 2.492), stdev = 0.006
  CI (99.9%): [2.380, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
Iteration   3: 3.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.003, 3.019, 3.041), stdev = 0.019
  CI (99.9%): [2.668, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  12.088 ms/op
                 createUser·p0.9999: 13.870 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  9.408 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  9.282 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375587
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179504 
    [ 2.500,  5.000) = 195278 
    [ 5.000,  7.500) = 401 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      9.444 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     15.946 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.853 ms/op
                 existUser·p0.9999: 14.335 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  10.593 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  6.891 ms/op
                 existUser·p0.9999: 12.454 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386902
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 192125 
    [ 2.500,  3.750) = 190538 
    [ 3.750,  5.000) = 3117 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      9.766 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     14.920 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  10.556 ms/op
                 getUser·p0.9999: 13.949 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 13.174 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  8.550 ms/op
                 getUser·p0.9999: 10.869 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377467
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183601 
    [ 2.500,  3.750) = 188361 
    [ 3.750,  5.000) = 4381 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     13.586 ms/op
     p(99.9990) =     14.422 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.009 ms/op
Iteration   1: 3.117 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.858 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 3.110 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.214 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.451 ms/op
                 listUser·p0.9999: 10.561 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309485
  mean =      3.099 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 76815 
    [ 2.500,  3.750) = 188078 
    [ 3.750,  5.000) = 36479 
    [ 5.000,  6.250) = 6558 
    [ 6.250,  7.500) = 748 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 270 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.560 ms/op
     p(99.9900) =     11.126 ms/op
     p(99.9990) =     12.253 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.237 ± 1.270  ops/ms
ClientPb.existUser                       thrpt       3  13.305 ± 1.866  ops/ms
ClientPb.getUser                         thrpt       3  12.922 ± 1.286  ops/ms
ClientPb.listUser                        thrpt       3  10.568 ± 0.358  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.319   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.109   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.351   ms/op
ClientPb.createUser                     sample  375587   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.444           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.906           ms/op
ClientPb.existUser                      sample  386902   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.644           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.766           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.959           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.842           ms/op
ClientPb.getUser                        sample  377467   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.586           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.598           ms/op
ClientPb.listUser                       sample  309485   3.099 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.907           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.560           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.126           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.337           ms/op
