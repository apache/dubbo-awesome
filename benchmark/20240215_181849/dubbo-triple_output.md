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
# Warmup Iteration   1: 5.117 ops/ms
# Warmup Iteration   2: 12.335 ops/ms
# Warmup Iteration   3: 12.468 ops/ms
Iteration   1: 12.641 ops/ms
Iteration   2: 12.876 ops/ms
Iteration   3: 12.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.752 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (12.641, 12.752, 12.876), stdev = 0.118
  CI (99.9%): [10.600, 14.904] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 13.000 ops/ms
# Warmup Iteration   3: 13.093 ops/ms
Iteration   1: 12.950 ops/ms
Iteration   2: 13.120 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.983 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (12.878, 12.983, 13.120), stdev = 0.125
  CI (99.9%): [10.711, 15.254] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.075 ops/ms
# Warmup Iteration   2: 12.786 ops/ms
# Warmup Iteration   3: 12.822 ops/ms
Iteration   1: 12.951 ops/ms
Iteration   2: 12.975 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.951 ±(99.9%) 0.449 ops/ms [Average]
  (min, avg, max) = (12.926, 12.951, 12.975), stdev = 0.025
  CI (99.9%): [12.502, 13.400] (assumes normal distribution)


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
# Warmup Iteration   1: 6.966 ops/ms
# Warmup Iteration   2: 10.627 ops/ms
# Warmup Iteration   3: 10.682 ops/ms
Iteration   1: 10.787 ops/ms
Iteration   2: 10.798 ops/ms
Iteration   3: 10.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.835 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.787, 10.835, 10.919), stdev = 0.073
  CI (99.9%): [9.502, 12.167] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.518, 2.541, 2.572), stdev = 0.028
  CI (99.9%): [2.033, 3.049] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.004 ms/op
Iteration   1: 2.416 ±(99.9%) 0.004 ms/op
Iteration   2: 2.401 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.401, 2.415, 2.427), stdev = 0.013
  CI (99.9%): [2.176, 2.654] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.450, 2.464, 2.479), stdev = 0.014
  CI (99.9%): [2.200, 2.728] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.504 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.977, 2.992, 3.010), stdev = 0.017
  CI (99.9%): [2.682, 3.301] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  5.709 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.744 ms/op
                 createUser·p0.9999: 12.409 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.827 ms/op
                 createUser·p0.999:  8.102 ms/op
                 createUser·p0.9999: 10.853 ms/op
                 createUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386135
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 188442 
    [ 2.500,  3.750) = 194238 
    [ 3.750,  5.000) = 2748 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.402 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.526 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 12.417 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  6.181 ms/op
                 existUser·p0.9999: 12.222 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394957
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 195817 
    [ 2.500,  3.750) = 196143 
    [ 3.750,  5.000) = 2103 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     13.312 ms/op
     p(99.9990) =     13.912 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.796 ms/op
                 getUser·p0.999:  7.977 ms/op
                 getUser·p0.9999: 12.829 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.209 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  5.654 ms/op
                 getUser·p0.9999: 10.224 ms/op
                 getUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387808
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 195341 
    [ 2.500,  3.750) = 187514 
    [ 3.750,  5.000) = 3758 
    [ 5.000,  6.250) = 651 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      7.874 ms/op
     p(99.9900) =     13.069 ms/op
     p(99.9990) =     14.182 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.519 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.155 ms/op
                 listUser·p1.00:   10.945 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 13.591 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.332 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.775 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322259
  mean =      2.976 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 97792 
    [ 2.500,  3.750) = 187933 
    [ 3.750,  5.000) = 29536 
    [ 5.000,  6.250) = 5646 
    [ 6.250,  7.500) = 506 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 348 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.554 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.752 ± 2.152  ops/ms
ClientPb.existUser                       thrpt       3  12.983 ± 2.272  ops/ms
ClientPb.getUser                         thrpt       3  12.951 ± 0.449  ops/ms
ClientPb.listUser                        thrpt       3  10.835 ± 1.333  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.508   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.264   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.309   ms/op
ClientPb.createUser                     sample  386135   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.960           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.779           ms/op
ClientPb.existUser                      sample  394957   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.597           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.503           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.312           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  387808   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.069           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  322259   2.976 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.848           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
