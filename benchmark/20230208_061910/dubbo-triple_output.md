# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
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
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 8.627 ops/ms
Iteration   1: 9.250 ops/ms
Iteration   2: 9.300 ops/ms
Iteration   3: 9.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.216 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (9.098, 9.216, 9.300), stdev = 0.105
  CI (99.9%): [7.300, 11.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.780 ops/ms
# Warmup Iteration   2: 8.494 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.754 ops/ms
Iteration   2: 9.494 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.561 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (9.435, 9.561, 9.754), stdev = 0.170
  CI (99.9%): [6.459, 12.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.910 ops/ms
# Warmup Iteration   2: 7.275 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.016 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.238 ±(99.9%) 4.216 ops/ms [Average]
  (min, avg, max) = (9.016, 9.238, 9.478), stdev = 0.231
  CI (99.9%): [5.022, 13.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.736 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.035 ±(99.9%) 3.630 ops/ms [Average]
  (min, avg, max) = (7.824, 8.035, 8.219), stdev = 0.199
  CI (99.9%): [4.405, 11.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.999 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.011 ms/op
Iteration   1: 3.702 ±(99.9%) 0.006 ms/op
Iteration   2: 3.597 ±(99.9%) 0.005 ms/op
Iteration   3: 3.372 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.557 ±(99.9%) 3.080 ms/op [Average]
  (min, avg, max) = (3.372, 3.557, 3.702), stdev = 0.169
  CI (99.9%): [0.477, 6.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.005 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
Iteration   2: 3.255 ±(99.9%) 0.007 ms/op
Iteration   3: 3.379 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.255, 3.317, 3.379), stdev = 0.062
  CI (99.9%): [2.184, 4.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.237 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.004 ms/op
Iteration   1: 3.542 ±(99.9%) 0.006 ms/op
Iteration   2: 3.451 ±(99.9%) 0.007 ms/op
Iteration   3: 3.420 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.471 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.420, 3.471, 3.542), stdev = 0.064
  CI (99.9%): [2.307, 4.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.357 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.010 ms/op
Iteration   1: 4.204 ±(99.9%) 0.006 ms/op
Iteration   2: 3.924 ±(99.9%) 0.013 ms/op
Iteration   3: 3.990 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.039 ±(99.9%) 2.674 ms/op [Average]
  (min, avg, max) = (3.924, 4.039, 4.204), stdev = 0.147
  CI (99.9%): [1.366, 6.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.057 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.014 ms/op
Iteration   1: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  22.289 ms/op
                 createUser·p0.9999: 26.114 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  22.378 ms/op
                 createUser·p0.9999: 26.404 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.405 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.021 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  20.675 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276608
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9359 
    [ 2.500,  5.000) = 258215 
    [ 5.000,  7.500) = 7948 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     27.777 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.622 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 23.231 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  11.083 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  13.217 ms/op
                 existUser·p0.9999: 40.080 ms/op
                 existUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285275
  mean =      3.363 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 280048 
    [ 5.000, 10.000) = 4829 
    [10.000, 15.000) = 142 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 190 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.234 ms/op
     p(99.9900) =     37.976 ms/op
     p(99.9990) =     40.249 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.144 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.813 ms/op
                 getUser·p0.999:  20.293 ms/op
                 getUser·p0.9999: 23.487 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 3.509 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  20.758 ms/op
                 getUser·p0.9999: 22.999 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.991 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 27.245 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276607
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9234 
    [ 2.500,  5.000) = 259375 
    [ 5.000,  7.500) = 6545 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     12.555 ms/op
     p(99.9900) =     25.345 ms/op
     p(99.9990) =     28.221 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.498 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.015 ms/op
Iteration   1: 4.109 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  20.036 ms/op
                 listUser·p0.9999: 24.826 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.154 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.906 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232884
  mean =      4.123 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 222360 
    [ 5.000,  7.500) = 7759 
    [ 7.500, 10.000) = 1867 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 209 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     23.944 ms/op
     p(99.9990) =     25.975 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.216 ± 1.916  ops/ms
ClientPb.existUser                       thrpt       3   9.561 ± 3.102  ops/ms
ClientPb.getUser                         thrpt       3   9.238 ± 4.216  ops/ms
ClientPb.listUser                        thrpt       3   8.035 ± 3.630  ops/ms
ClientPb.createUser                       avgt       3   3.557 ± 3.080   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 1.133   ms/op
ClientPb.getUser                          avgt       3   3.471 ± 1.164   ms/op
ClientPb.listUser                         avgt       3   4.039 ± 2.674   ms/op
ClientPb.createUser                     sample  276608   3.467 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.397           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.840           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.777           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  285275   3.363 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.763           ms/op
ClientPb.getUser                        sample  276607   3.470 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.555           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.114           ms/op
ClientPb.listUser                       sample  232884   4.123 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.083           ms/op
