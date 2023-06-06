# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.069 ops/ms
# Warmup Iteration   2: 5.305 ops/ms
# Warmup Iteration   3: 8.661 ops/ms
Iteration   1: 8.958 ops/ms
Iteration   2: 9.017 ops/ms
Iteration   3: 9.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.074 ±(99.9%) 2.773 ops/ms [Average]
  (min, avg, max) = (8.958, 9.074, 9.246), stdev = 0.152
  CI (99.9%): [6.301, 11.847] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.154 ops/ms
# Warmup Iteration   2: 8.665 ops/ms
# Warmup Iteration   3: 8.660 ops/ms
Iteration   1: 9.609 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.645 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (9.609, 9.645, 9.693), stdev = 0.043
  CI (99.9%): [8.855, 10.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 9.241 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 9.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.224 ±(99.9%) 0.283 ops/ms [Average]
  (min, avg, max) = (9.213, 9.224, 9.242), stdev = 0.016
  CI (99.9%): [8.941, 9.508] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 6.692 ops/ms
# Warmup Iteration   3: 7.962 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.012 ±(99.9%) 1.334 ops/ms [Average]
  (min, avg, max) = (7.941, 8.012, 8.087), stdev = 0.073
  CI (99.9%): [6.677, 9.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.759 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.010 ms/op
Iteration   1: 3.534 ±(99.9%) 0.004 ms/op
Iteration   2: 3.608 ±(99.9%) 0.009 ms/op
Iteration   3: 3.757 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.633 ±(99.9%) 2.069 ms/op [Average]
  (min, avg, max) = (3.534, 3.633, 3.757), stdev = 0.113
  CI (99.9%): [1.564, 5.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.933 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.003 ms/op
Iteration   1: 3.271 ±(99.9%) 0.004 ms/op
Iteration   2: 3.269 ±(99.9%) 0.012 ms/op
Iteration   3: 3.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.269, 3.299, 3.357), stdev = 0.050
  CI (99.9%): [2.380, 4.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.014 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.003 ms/op
Iteration   1: 3.452 ±(99.9%) 0.007 ms/op
Iteration   2: 3.436 ±(99.9%) 0.011 ms/op
Iteration   3: 3.432 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.440 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.432, 3.440, 3.452), stdev = 0.011
  CI (99.9%): [3.248, 3.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.278 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.009 ms/op
Iteration   1: 3.942 ±(99.9%) 0.013 ms/op
Iteration   2: 4.113 ±(99.9%) 0.008 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.023 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.942, 4.023, 4.113), stdev = 0.086
  CI (99.9%): [2.457, 5.589] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.393 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.011 ms/op
Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.432 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  20.185 ms/op
                 createUser·p0.9999: 25.248 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  18.983 ms/op
                 createUser·p0.9999: 25.548 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275072
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8610 
    [ 2.500,  5.000) = 257080 
    [ 5.000,  7.500) = 8004 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     18.938 ms/op
     p(99.9900) =     24.690 ms/op
     p(99.9990) =     26.730 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.666 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
Iteration   1: 3.328 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.835 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 24.851 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  11.699 ms/op
                 existUser·p0.9999: 24.976 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.329 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  20.329 ms/op
                 existUser·p0.9999: 31.372 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291169
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12815 
    [ 2.500,  5.000) = 272190 
    [ 5.000,  7.500) = 5135 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.413 ms/op
     p(99.9900) =     28.955 ms/op
     p(99.9990) =     31.821 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.889 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.012 ms/op
Iteration   1: 3.588 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  20.928 ms/op
                 getUser·p0.9999: 24.546 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.565 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.005 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   5.114 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  22.783 ms/op
                 getUser·p0.9999: 25.691 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  14.354 ms/op
                 getUser·p0.9999: 28.236 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271920
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12688 
    [ 2.500,  5.000) = 249234 
    [ 5.000,  7.500) = 8857 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     27.676 ms/op
     p(99.9990) =     28.455 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.564 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.013 ms/op
Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  22.933 ms/op
                 listUser·p0.9999: 30.487 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.795 ms/op
                 listUser·p0.999:  16.472 ms/op
                 listUser·p0.9999: 19.559 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 4.194 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.180 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233550
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 223848 
    [ 5.000,  7.500) = 7157 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     16.956 ms/op
     p(99.9900) =     28.988 ms/op
     p(99.9990) =     31.304 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.074 ± 2.773  ops/ms
ClientPb.existUser                       thrpt       3   9.645 ± 0.789  ops/ms
ClientPb.getUser                         thrpt       3   9.224 ± 0.283  ops/ms
ClientPb.listUser                        thrpt       3   8.012 ± 1.334  ops/ms
ClientPb.createUser                       avgt       3   3.633 ± 2.069   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.919   ms/op
ClientPb.getUser                          avgt       3   3.440 ± 0.192   ms/op
ClientPb.listUser                         avgt       3   4.023 ± 1.566   ms/op
ClientPb.createUser                     sample  275072   3.489 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.513           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.938           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.690           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.066           ms/op
ClientPb.existUser                      sample  291169   3.295 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.413           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.080           ms/op
ClientPb.getUser                        sample  271920   3.530 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.409           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.676           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  233550   4.108 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.956           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.988           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.752           ms/op
