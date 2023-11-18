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
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 12.244 ops/ms
# Warmup Iteration   3: 12.338 ops/ms
Iteration   1: 12.546 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.588 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (12.546, 12.588, 12.631), stdev = 0.043
  CI (99.9%): [11.809, 13.368] (assumes normal distribution)


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
# Warmup Iteration   1: 8.467 ops/ms
# Warmup Iteration   2: 13.031 ops/ms
# Warmup Iteration   3: 13.124 ops/ms
Iteration   1: 13.098 ops/ms
Iteration   2: 13.055 ops/ms
Iteration   3: 13.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.147 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (13.055, 13.147, 13.287), stdev = 0.124
  CI (99.9%): [10.889, 15.404] (assumes normal distribution)


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
# Warmup Iteration   1: 7.817 ops/ms
# Warmup Iteration   2: 12.511 ops/ms
# Warmup Iteration   3: 12.719 ops/ms
Iteration   1: 12.963 ops/ms
Iteration   2: 12.909 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.886 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (12.785, 12.886, 12.963), stdev = 0.091
  CI (99.9%): [11.217, 14.554] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.574 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.633 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (10.584, 10.633, 10.693), stdev = 0.056
  CI (99.9%): [9.617, 11.648] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.513, 2.518, 2.524), stdev = 0.005
  CI (99.9%): [2.421, 2.615] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.723 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.445, 2.458, 2.471), stdev = 0.013
  CI (99.9%): [2.215, 2.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.483, 2.503, 2.521), stdev = 0.019
  CI (99.9%): [2.155, 2.850] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.978, 2.985, 2.993), stdev = 0.007
  CI (99.9%): [2.849, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  11.230 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 12.255 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.648 ms/op
                 createUser·p0.9999: 11.064 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381102
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 182629 
    [ 2.500,  3.750) = 193382 
    [ 3.750,  5.000) = 3669 
    [ 5.000,  6.250) = 891 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.729 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  10.904 ms/op
                 existUser·p0.9999: 13.612 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 12.245 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.272 ms/op
                 existUser·p0.9999: 13.021 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397697
  mean =      2.411 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 204528 
    [ 2.500,  3.750) = 189533 
    [ 3.750,  5.000) = 2763 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 136 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.901 ms/op
                 getUser·p0.9999: 14.974 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.554 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  8.621 ms/op
                 getUser·p0.9999: 11.219 ms/op
                 getUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379689
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 186457 
    [ 2.500,  3.750) = 188442 
    [ 3.750,  5.000) = 3624 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      6.428 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     16.446 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.009 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.818 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 12.080 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.835 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320519
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 95791 
    [ 2.500,  3.750) = 184852 
    [ 3.750,  5.000) = 32262 
    [ 5.000,  6.250) = 6215 
    [ 6.250,  7.500) = 642 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.762 ms/op
     p(99.9990) =     13.042 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.588 ± 0.779  ops/ms
ClientPb.existUser                       thrpt       3  13.147 ± 2.258  ops/ms
ClientPb.getUser                         thrpt       3  12.886 ± 1.669  ops/ms
ClientPb.listUser                        thrpt       3  10.633 ± 1.015  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.097   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.243   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.347   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.137   ms/op
ClientPb.createUser                     sample  381102   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.816           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.729           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  397697   2.411 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.850           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.651           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  379689   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.428           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.548           ms/op
ClientPb.listUser                       sample  320519   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.762           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
