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
# Warmup Iteration   1: 2.635 ops/ms
# Warmup Iteration   2: 6.384 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.433 ops/ms
Iteration   2: 9.713 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.672 ±(99.9%) 4.032 ops/ms [Average]
  (min, avg, max) = (9.433, 9.672, 9.869), stdev = 0.221
  CI (99.9%): [5.641, 13.704] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 9.350 ops/ms
# Warmup Iteration   3: 10.176 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.350 ±(99.9%) 4.619 ops/ms [Average]
  (min, avg, max) = (10.073, 10.350, 10.569), stdev = 0.253
  CI (99.9%): [5.731, 14.969] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 9.381 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.076 ±(99.9%) 4.256 ops/ms [Average]
  (min, avg, max) = (9.823, 10.076, 10.283), stdev = 0.233
  CI (99.9%): [5.820, 14.332] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.480 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 8.380 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.603 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.583 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (8.422, 8.583, 8.725), stdev = 0.152
  CI (99.9%): [5.806, 11.360] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.219 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.003 ms/op
Iteration   1: 3.321 ±(99.9%) 0.005 ms/op
Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.225 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.163, 3.225, 3.321), stdev = 0.084
  CI (99.9%): [1.685, 4.766] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.825 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.004 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.056 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.002, 3.056, 3.132), stdev = 0.068
  CI (99.9%): [1.820, 4.292] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.241 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.004 ms/op
Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
Iteration   3: 3.233 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (3.063, 3.188, 3.266), stdev = 0.109
  CI (99.9%): [1.203, 5.172] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.182 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.006 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
Iteration   2: 3.737 ±(99.9%) 0.007 ms/op
Iteration   3: 3.627 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.690 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.627, 3.690, 3.737), stdev = 0.057
  CI (99.9%): [2.657, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 8.079 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 23.775 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  14.883 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 312380
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10899 
    [ 2.500,  5.000) = 297940 
    [ 5.000,  7.500) = 2807 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     14.690 ms/op
     p(99.9900) =     22.791 ms/op
     p(99.9990) =     24.732 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.307 ms/op
                 existUser·p0.9999: 20.131 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.182 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  13.500 ms/op
                 existUser·p0.9999: 22.969 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309230
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23229 
    [ 2.500,  5.000) = 281204 
    [ 5.000,  7.500) = 4054 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     22.055 ms/op
     p(99.9990) =     23.292 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 8.633 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.010 ms/op
Iteration   1: 3.159 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 20.476 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  8.865 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  13.507 ms/op
                 getUser·p0.9999: 21.739 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297842
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18141 
    [ 2.500,  5.000) = 271031 
    [ 5.000,  7.500) = 7748 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     23.279 ms/op
     p(99.9990) =     25.596 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 9.466 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.879 ms/op
                 listUser·p0.9999: 28.587 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 3.776 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.135 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.847 ms/op
                 listUser·p0.9999: 14.132 ms/op
                 listUser·p1.00:   14.172 ms/op

Iteration   3: 3.631 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 14.454 ms/op
                 listUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258582
  mean =      3.708 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 251408 
    [ 5.000,  7.500) = 5354 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.941 ms/op
     p(99.9900) =     24.913 ms/op
     p(99.9990) =     29.171 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.672 ± 4.032  ops/ms
ClientPb.existUser                       thrpt       3  10.350 ± 4.619  ops/ms
ClientPb.getUser                         thrpt       3  10.076 ± 4.256  ops/ms
ClientPb.listUser                        thrpt       3   8.583 ± 2.777  ops/ms
ClientPb.createUser                       avgt       3   3.225 ± 1.540   ms/op
ClientPb.existUser                        avgt       3   3.056 ± 1.236   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 1.984   ms/op
ClientPb.listUser                         avgt       3   3.690 ± 1.033   ms/op
ClientPb.createUser                     sample  312380   3.071 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.812           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.690           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.791           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.297           ms/op
ClientPb.existUser                      sample  309230   3.102 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.039           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.500           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.055           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.364           ms/op
ClientPb.getUser                        sample  297842   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.279           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.854           ms/op
ClientPb.listUser                       sample  258582   3.708 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.679           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.559           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.913           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
