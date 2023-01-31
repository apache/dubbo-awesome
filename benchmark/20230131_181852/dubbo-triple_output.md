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
# Warmup Iteration   1: 2.557 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 8.995 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 2.866 ops/ms [Average]
  (min, avg, max) = (9.702, 9.797, 9.979), stdev = 0.157
  CI (99.9%): [6.931, 12.663] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ops/ms
# Warmup Iteration   2: 9.418 ops/ms
# Warmup Iteration   3: 10.013 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.488 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.428, 10.488, 10.569), stdev = 0.073
  CI (99.9%): [9.155, 11.821] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.504 ops/ms
# Warmup Iteration   2: 8.401 ops/ms
# Warmup Iteration   3: 9.975 ops/ms
Iteration   1: 9.851 ops/ms
Iteration   2: 9.754 ops/ms
Iteration   3: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.923 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (9.754, 9.923, 10.163), stdev = 0.214
  CI (99.9%): [6.020, 13.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 7.327 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.446 ops/ms
Iteration   2: 8.514 ops/ms
Iteration   3: 8.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.502 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (8.446, 8.502, 8.548), stdev = 0.052
  CI (99.9%): [7.552, 9.453] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.552 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.005 ms/op
Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
Iteration   3: 3.224 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.165, 3.202, 3.224), stdev = 0.032
  CI (99.9%): [2.610, 3.795] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.315 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.005 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.204 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (3.034, 3.102, 3.204), stdev = 0.090
  CI (99.9%): [1.464, 4.740] (assumes normal distribution)


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
# Warmup Iteration   1: 7.410 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.003 ms/op
Iteration   1: 3.205 ±(99.9%) 0.003 ms/op
Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
Iteration   3: 3.105 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.133 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.090, 3.133, 3.205), stdev = 0.063
  CI (99.9%): [1.987, 4.280] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.406 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.005 ms/op
Iteration   1: 3.651 ±(99.9%) 0.009 ms/op
Iteration   2: 3.659 ±(99.9%) 0.007 ms/op
Iteration   3: 3.710 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.673 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.651, 3.673, 3.710), stdev = 0.032
  CI (99.9%): [3.085, 4.262] (assumes normal distribution)


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
# Warmup Iteration   1: 8.009 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  17.707 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  14.701 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  15.871 ms/op
                 createUser·p0.9999: 23.933 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299175
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25353 
    [ 2.500,  5.000) = 266865 
    [ 5.000,  7.500) = 6164 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     16.512 ms/op
     p(99.9900) =     23.014 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 7.672 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 19.724 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  12.379 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 19.666 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309904
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18589 
    [ 2.500,  5.000) = 287797 
    [ 5.000,  7.500) = 2700 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.954 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 7.414 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.010 ms/op
Iteration   1: 3.200 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   6.460 ms/op
                 getUser·p0.999:  17.489 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  10.292 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  9.433 ms/op
                 getUser·p0.9999: 21.397 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299923
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14040 
    [ 2.500,  5.000) = 279244 
    [ 5.000,  7.500) = 5827 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     23.889 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 9.539 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
Iteration   1: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.574 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 20.895 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 18.302 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.720 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.975 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254208
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 245896 
    [ 5.000,  7.500) = 6275 
    [ 7.500, 10.000) = 1206 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     19.212 ms/op
     p(99.9990) =     21.642 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 2.866  ops/ms
ClientPb.existUser                       thrpt       3  10.488 ± 1.333  ops/ms
ClientPb.getUser                         thrpt       3   9.923 ± 3.903  ops/ms
ClientPb.listUser                        thrpt       3   8.502 ± 0.951  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 0.592   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.638   ms/op
ClientPb.getUser                          avgt       3   3.133 ± 1.146   ms/op
ClientPb.listUser                         avgt       3   3.673 ± 0.588   ms/op
ClientPb.createUser                     sample  299175   3.207 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.570           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.014           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  309904   3.095 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.101           ms/op
ClientPb.getUser                        sample  299923   3.202 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.025           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.889           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.592           ms/op
ClientPb.listUser                       sample  254208   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.212           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.791           ms/op
