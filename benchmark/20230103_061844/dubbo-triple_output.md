# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.054 ops/ms
# Warmup Iteration   2: 5.507 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 9.330 ops/ms
Iteration   2: 9.323 ops/ms
Iteration   3: 9.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.393 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (9.323, 9.393, 9.527), stdev = 0.116
  CI (99.9%): [7.281, 11.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 8.831 ops/ms
# Warmup Iteration   3: 9.574 ops/ms
Iteration   1: 9.742 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 9.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.728 ±(99.9%) 4.520 ops/ms [Average]
  (min, avg, max) = (9.473, 9.728, 9.968), stdev = 0.248
  CI (99.9%): [5.207, 14.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ops/ms
# Warmup Iteration   2: 8.181 ops/ms
# Warmup Iteration   3: 9.178 ops/ms
Iteration   1: 9.235 ops/ms
Iteration   2: 9.572 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.514 ±(99.9%) 4.647 ops/ms [Average]
  (min, avg, max) = (9.235, 9.514, 9.734), stdev = 0.255
  CI (99.9%): [4.866, 14.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.939 ops/ms
# Warmup Iteration   2: 7.270 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.139 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (8.016, 8.139, 8.243), stdev = 0.114
  CI (99.9%): [6.052, 10.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.203 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.004 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
Iteration   3: 3.350 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.432 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.350, 3.432, 3.507), stdev = 0.079
  CI (99.9%): [1.997, 4.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.005 ms/op
Iteration   1: 3.253 ±(99.9%) 0.003 ms/op
Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
Iteration   3: 3.193 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 4.051 ms/op [Average]
  (min, avg, max) = (3.193, 3.350, 3.604), stdev = 0.222
  CI (99.9%): [≈ 0, 7.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.381 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.007 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.405 ±(99.9%) 0.006 ms/op
Iteration   3: 3.305 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.374 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.305, 3.374, 3.411), stdev = 0.060
  CI (99.9%): [2.285, 4.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.776 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
Iteration   2: 3.796 ±(99.9%) 0.016 ms/op
Iteration   3: 3.866 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.871 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.796, 3.871, 3.950), stdev = 0.077
  CI (99.9%): [2.467, 5.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.684 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  16.439 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  23.469 ms/op
                 createUser·p0.9999: 31.115 ms/op
                 createUser·p1.00:   32.080 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.918 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 23.998 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286419
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11779 
    [ 2.500,  5.000) = 270109 
    [ 5.000,  7.500) = 3572 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     31.451 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.092 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  19.860 ms/op
                 existUser·p0.9999: 25.737 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  18.616 ms/op
                 existUser·p0.9999: 27.509 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.963 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  17.576 ms/op
                 existUser·p0.9999: 25.376 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288032
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2598 
    [ 2.500,  5.000) = 279616 
    [ 5.000,  7.500) = 4842 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     17.559 ms/op
     p(99.9900) =     26.647 ms/op
     p(99.9990) =     28.225 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.076 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
Iteration   1: 3.633 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 23.715 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  23.201 ms/op
                 getUser·p0.9999: 26.169 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272985
  mean =      3.515 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12417 
    [ 2.500,  5.000) = 250982 
    [ 5.000,  7.500) = 8341 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     19.793 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.224 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.867 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.181 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.964 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  15.783 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 3.832 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  15.242 ms/op
                 listUser·p0.9999: 22.042 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242704
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 234358 
    [ 5.000,  7.500) = 6102 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     22.142 ms/op
     p(99.9990) =     23.663 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.393 ± 2.113  ops/ms
ClientPb.existUser                       thrpt       3   9.728 ± 4.520  ops/ms
ClientPb.getUser                         thrpt       3   9.514 ± 4.647  ops/ms
ClientPb.listUser                        thrpt       3   8.139 ± 2.086  ops/ms
ClientPb.createUser                       avgt       3   3.432 ± 1.435   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 4.051   ms/op
ClientPb.getUser                          avgt       3   3.374 ± 1.089   ms/op
ClientPb.listUser                         avgt       3   3.871 ± 1.403   ms/op
ClientPb.createUser                     sample  286419   3.351 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.810           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.065           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  288032   3.330 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.559           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.647           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  272985   3.515 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.793           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  242704   3.955 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.142           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
