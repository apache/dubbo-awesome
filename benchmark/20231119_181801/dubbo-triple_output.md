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
# Warmup Iteration   1: 4.477 ops/ms
# Warmup Iteration   2: 12.303 ops/ms
# Warmup Iteration   3: 12.489 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.743 ±(99.9%) 1.856 ops/ms [Average]
  (min, avg, max) = (12.660, 12.743, 12.857), stdev = 0.102
  CI (99.9%): [10.888, 14.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.544 ops/ms
# Warmup Iteration   2: 13.191 ops/ms
# Warmup Iteration   3: 13.180 ops/ms
Iteration   1: 13.173 ops/ms
Iteration   2: 13.286 ops/ms
Iteration   3: 13.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.184 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (13.093, 13.184, 13.286), stdev = 0.097
  CI (99.9%): [11.416, 14.952] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ops/ms
# Warmup Iteration   2: 12.533 ops/ms
# Warmup Iteration   3: 12.705 ops/ms
Iteration   1: 12.891 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.812 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (12.763, 12.812, 12.891), stdev = 0.069
  CI (99.9%): [11.548, 14.077] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.887 ops/ms
# Warmup Iteration   2: 10.588 ops/ms
# Warmup Iteration   3: 10.566 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.747 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (10.716, 10.747, 10.789), stdev = 0.038
  CI (99.9%): [10.054, 11.439] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.003 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (2.499, 2.530, 2.556), stdev = 0.029
  CI (99.9%): [1.998, 3.062] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.443, 2.450, 2.457), stdev = 0.007
  CI (99.9%): [2.319, 2.582] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.452, 2.474, 2.487), stdev = 0.019
  CI (99.9%): [2.125, 2.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.971, 2.991, 3.006), stdev = 0.018
  CI (99.9%): [2.658, 3.324] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.120 ms/op
                 createUser·p0.9999: 13.751 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  7.482 ms/op
                 createUser·p0.9999: 11.945 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.210 ms/op
                 createUser·p0.9999: 11.127 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386561
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188795 
    [ 2.500,  3.750) = 193120 
    [ 3.750,  5.000) = 3722 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      7.901 ms/op
     p(99.9900) =     13.195 ms/op
     p(99.9990) =     14.109 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.708 ms/op
                 existUser·p0.999:  7.218 ms/op
                 existUser·p0.9999: 13.960 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.331 ms/op
                 existUser·p0.9999: 15.105 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  10.053 ms/op
                 existUser·p0.9999: 12.456 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387432
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 189024 
    [ 2.500,  3.750) = 194084 
    [ 3.750,  5.000) = 3275 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 141 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.081 ms/op
     p(99.9900) =     14.094 ms/op
     p(99.9990) =     15.583 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.841 ms/op
                 getUser·p0.999:  11.186 ms/op
                 getUser·p0.9999: 13.739 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 15.035 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  8.391 ms/op
                 getUser·p0.9999: 24.281 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382911
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190877 
    [ 2.500,  5.000) = 190640 
    [ 5.000,  7.500) = 1010 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      8.406 ms/op
     p(99.9900) =     15.501 ms/op
     p(99.9990) =     24.986 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.236 ms/op
                 listUser·p0.9999: 11.710 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.031 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 12.125 ms/op
                 listUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318033
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 90665 
    [ 2.500,  3.750) = 186946 
    [ 3.750,  5.000) = 32708 
    [ 5.000,  6.250) = 6292 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 381 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.537 ms/op
     p(99.9990) =     13.085 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.743 ± 1.856  ops/ms
ClientPb.existUser                       thrpt       3  13.184 ± 1.768  ops/ms
ClientPb.getUser                         thrpt       3  12.812 ± 1.264  ops/ms
ClientPb.listUser                        thrpt       3  10.747 ± 0.692  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.532   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.132   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.349   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.333   ms/op
ClientPb.createUser                     sample  386561   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.730           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.901           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.195           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  387432   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.094           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.679           ms/op
ClientPb.getUser                        sample  382911   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.501           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.199           ms/op
ClientPb.listUser                       sample  318033   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.865           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.537           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
