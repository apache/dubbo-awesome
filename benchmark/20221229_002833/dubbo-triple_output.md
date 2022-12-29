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
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 4.136 ops/ms
# Warmup Iteration   3: 7.256 ops/ms
Iteration   1: 7.413 ops/ms
Iteration   2: 8.175 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.888 ±(99.9%) 7.561 ops/ms [Average]
  (min, avg, max) = (7.413, 7.888, 8.175), stdev = 0.414
  CI (99.9%): [0.328, 15.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.358 ops/ms
# Warmup Iteration   2: 7.289 ops/ms
# Warmup Iteration   3: 8.164 ops/ms
Iteration   1: 8.377 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.460 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (8.377, 8.460, 8.536), stdev = 0.080
  CI (99.9%): [7.007, 9.914] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 6.161 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 7.883 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.099 ±(99.9%) 4.882 ops/ms [Average]
  (min, avg, max) = (7.883, 8.099, 8.398), stdev = 0.268
  CI (99.9%): [3.216, 12.981] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.214 ops/ms
# Warmup Iteration   2: 5.852 ops/ms
# Warmup Iteration   3: 6.768 ops/ms
Iteration   1: 6.866 ops/ms
Iteration   2: 6.627 ops/ms
Iteration   3: 7.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.836 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (6.627, 6.836, 7.014), stdev = 0.195
  CI (99.9%): [3.274, 10.398] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.989 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.004 ms/op
Iteration   1: 3.826 ±(99.9%) 0.010 ms/op
Iteration   2: 3.778 ±(99.9%) 0.016 ms/op
Iteration   3: 3.830 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.811 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (3.778, 3.811, 3.830), stdev = 0.029
  CI (99.9%): [3.278, 4.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.790 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.004 ms/op
Iteration   1: 3.981 ±(99.9%) 0.004 ms/op
Iteration   2: 3.823 ±(99.9%) 0.011 ms/op
Iteration   3: 3.757 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.853 ±(99.9%) 2.098 ms/op [Average]
  (min, avg, max) = (3.757, 3.853, 3.981), stdev = 0.115
  CI (99.9%): [1.756, 5.951] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.279 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.006 ms/op
Iteration   1: 3.951 ±(99.9%) 0.005 ms/op
Iteration   2: 3.971 ±(99.9%) 0.008 ms/op
Iteration   3: 3.839 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.920 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.839, 3.920, 3.971), stdev = 0.071
  CI (99.9%): [2.621, 5.220] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.818 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.789 ±(99.9%) 0.006 ms/op
Iteration   1: 4.791 ±(99.9%) 0.007 ms/op
Iteration   2: 4.724 ±(99.9%) 0.007 ms/op
Iteration   3: 4.464 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.660 ±(99.9%) 3.146 ms/op [Average]
  (min, avg, max) = (4.464, 4.660, 4.791), stdev = 0.172
  CI (99.9%): [1.513, 7.806] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.178 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.018 ms/op
Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 26.050 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 3.821 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.062 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  24.750 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.963 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  27.927 ms/op
                 createUser·p0.9999: 31.387 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244454
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 328 
    [ 2.500,  5.000) = 234445 
    [ 5.000,  7.500) = 7420 
    [ 7.500, 10.000) = 1372 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     30.547 ms/op
     p(99.9990) =     31.938 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.442 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.014 ms/op
Iteration   1: 3.699 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  23.237 ms/op
                 existUser·p0.9999: 25.833 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 27.826 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.650 ms/op
                 existUser·p0.999:  26.787 ms/op
                 existUser·p0.9999: 29.763 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251310
  mean =      3.817 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 241728 
    [ 5.000,  7.500) = 7394 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     29.155 ms/op
     p(99.9990) =     30.499 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.782 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  16.875 ms/op
                 getUser·p0.9999: 25.756 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 4.025 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  10.150 ms/op
                 getUser·p0.9999: 26.018 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.920 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  26.786 ms/op
                 getUser·p0.9999: 30.867 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241024
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 228654 
    [ 5.000,  7.500) = 9884 
    [ 7.500, 10.000) = 1746 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     16.907 ms/op
     p(99.9900) =     29.717 ms/op
     p(99.9990) =     31.871 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.542 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.346 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.020 ms/op
Iteration   1: 4.711 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.216 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  26.809 ms/op
                 listUser·p0.9999: 33.234 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 4.751 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  19.880 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.547 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205677
  mean =      4.668 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 172511 
    [ 5.000,  7.500) = 27941 
    [ 7.500, 10.000) = 4055 
    [10.000, 12.500) = 539 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     19.966 ms/op
     p(99.9900) =     31.219 ms/op
     p(99.9990) =     33.682 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.888 ± 7.561  ops/ms
ClientPb.existUser                       thrpt       3   8.460 ± 1.453  ops/ms
ClientPb.getUser                         thrpt       3   8.099 ± 4.882  ops/ms
ClientPb.listUser                        thrpt       3   6.836 ± 3.562  ops/ms
ClientPb.createUser                       avgt       3   3.811 ± 0.534   ms/op
ClientPb.existUser                        avgt       3   3.853 ± 2.098   ms/op
ClientPb.getUser                          avgt       3   3.920 ± 1.299   ms/op
ClientPb.listUser                         avgt       3   4.660 ± 3.146   ms/op
ClientPb.createUser                     sample  244454   3.927 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.479           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.547           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.113           ms/op
ClientPb.existUser                      sample  251310   3.817 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.618           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.643           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.155           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  241024   3.980 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.339           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.487           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.907           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.717           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.375           ms/op
ClientPb.listUser                       sample  205677   4.668 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.966           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.219           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
