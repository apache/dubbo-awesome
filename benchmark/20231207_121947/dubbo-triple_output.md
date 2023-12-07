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
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 12.129 ops/ms
# Warmup Iteration   3: 12.221 ops/ms
Iteration   1: 12.451 ops/ms
Iteration   2: 12.457 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.551 ±(99.9%) 3.061 ops/ms [Average]
  (min, avg, max) = (12.451, 12.551, 12.745), stdev = 0.168
  CI (99.9%): [9.490, 15.612] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.473 ops/ms
# Warmup Iteration   2: 13.245 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.113 ops/ms
Iteration   2: 13.045 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.064 ±(99.9%) 0.777 ops/ms [Average]
  (min, avg, max) = (13.034, 13.064, 13.113), stdev = 0.043
  CI (99.9%): [12.287, 13.840] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.642 ops/ms
# Warmup Iteration   2: 12.274 ops/ms
# Warmup Iteration   3: 12.492 ops/ms
Iteration   1: 12.672 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.751 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (12.672, 12.751, 12.911), stdev = 0.138
  CI (99.9%): [10.234, 15.268] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.946 ops/ms
# Warmup Iteration   2: 10.593 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.640 ±(99.9%) 0.796 ops/ms [Average]
  (min, avg, max) = (10.590, 10.640, 10.672), stdev = 0.044
  CI (99.9%): [9.844, 11.436] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.004 ms/op
Iteration   1: 2.616 ±(99.9%) 0.005 ms/op
Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
Iteration   3: 2.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.596 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.578, 2.596, 2.616), stdev = 0.019
  CI (99.9%): [2.245, 2.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.648 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
Iteration   3: 2.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.429, 2.443, 2.453), stdev = 0.012
  CI (99.9%): [2.219, 2.667] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.460, 2.471, 2.487), stdev = 0.014
  CI (99.9%): [2.217, 2.726] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
Iteration   3: 2.959 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.959 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (2.957, 2.959, 2.962), stdev = 0.003
  CI (99.9%): [2.913, 3.006] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  10.782 ms/op
                 createUser·p0.9999: 13.653 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.085 ms/op
                 createUser·p0.9999: 12.534 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  8.984 ms/op
                 createUser·p0.9999: 12.805 ms/op
                 createUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378060
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 184658 
    [ 2.500,  3.750) = 189061 
    [ 3.750,  5.000) = 3251 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 158 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.076 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.783 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.402 ms/op
                 existUser·p0.9999: 13.777 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  6.499 ms/op
                 existUser·p0.9999: 11.973 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.471 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.742 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392014
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 196287 
    [ 2.500,  3.750) = 191496 
    [ 3.750,  5.000) = 3161 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 15.653 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.659 ms/op
                 getUser·p0.9999: 12.026 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  8.845 ms/op
                 getUser·p0.9999: 12.260 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382496
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 189060 
    [ 2.500,  3.750) = 187075 
    [ 3.750,  5.000) = 5016 
    [ 5.000,  6.250) = 794 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     15.947 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.756 ms/op
                 listUser·p0.9999: 12.574 ms/op
                 listUser·p1.00:   13.255 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.404 ms/op
                 listUser·p0.9999: 12.041 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.492 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316216
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 88990 
    [ 2.500,  3.750) = 186107 
    [ 3.750,  5.000) = 33759 
    [ 5.000,  6.250) = 5896 
    [ 6.250,  7.500) = 692 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 170 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.532 ms/op
     p(99.9900) =     11.977 ms/op
     p(99.9990) =     13.233 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.551 ± 3.061  ops/ms
ClientPb.existUser                       thrpt       3  13.064 ± 0.777  ops/ms
ClientPb.getUser                         thrpt       3  12.751 ± 2.517  ops/ms
ClientPb.listUser                        thrpt       3  10.640 ± 0.796  ops/ms
ClientPb.createUser                       avgt       3   2.596 ± 0.351   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.224   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.255   ms/op
ClientPb.listUser                         avgt       3   2.959 ± 0.047   ms/op
ClientPb.createUser                     sample  378060   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.727           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.076           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.828           ms/op
ClientPb.existUser                      sample  392014   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.552           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.959           ms/op
ClientPb.getUser                        sample  382496   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.874           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.437           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.169           ms/op
ClientPb.listUser                       sample  316216   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.532           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
