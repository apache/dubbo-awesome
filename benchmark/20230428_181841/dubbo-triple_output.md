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
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 6.251 ops/ms
# Warmup Iteration   3: 9.100 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 9.532 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.820 ±(99.9%) 5.327 ops/ms [Average]
  (min, avg, max) = (9.532, 9.820, 10.116), stdev = 0.292
  CI (99.9%): [4.492, 15.147] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 10.006 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.137 ±(99.9%) 3.098 ops/ms [Average]
  (min, avg, max) = (9.970, 10.137, 10.309), stdev = 0.170
  CI (99.9%): [7.039, 13.235] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 9.722 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.053 ±(99.9%) 7.086 ops/ms [Average]
  (min, avg, max) = (9.651, 10.053, 10.426), stdev = 0.388
  CI (99.9%): [2.968, 17.139] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.516 ops/ms
Iteration   2: 8.745 ops/ms
Iteration   3: 8.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.663 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (8.516, 8.663, 8.745), stdev = 0.128
  CI (99.9%): [6.334, 10.992] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.004 ms/op
Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.150 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.134, 3.150, 3.174), stdev = 0.021
  CI (99.9%): [2.766, 3.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 1.722 ms/op [Average]
  (min, avg, max) = (3.046, 3.154, 3.222), stdev = 0.094
  CI (99.9%): [1.432, 4.875] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.631 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.116 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.077 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.000, 3.077, 3.116), stdev = 0.067
  CI (99.9%): [1.862, 4.293] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.086 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.005 ms/op
Iteration   1: 3.660 ±(99.9%) 0.008 ms/op
Iteration   2: 3.627 ±(99.9%) 0.007 ms/op
Iteration   3: 3.561 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.616 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.561, 3.616, 3.660), stdev = 0.051
  CI (99.9%): [2.691, 4.541] (assumes normal distribution)


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
# Warmup Iteration   1: 8.718 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
Iteration   1: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  16.996 ms/op
                 createUser·p0.9999: 20.432 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  12.937 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  15.125 ms/op
                 createUser·p0.9999: 18.245 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303948
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15558 
    [ 2.500,  5.000) = 282426 
    [ 5.000,  7.500) = 4692 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     22.368 ms/op
     p(99.9990) =     24.341 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 7.129 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.336 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 19.192 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 22.593 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 319357
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15797 
    [ 2.500,  5.000) = 299519 
    [ 5.000,  7.500) = 3441 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     11.281 ms/op
     p(99.9900) =     21.039 ms/op
     p(99.9990) =     23.711 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 7.705 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.009 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  13.070 ms/op
                 getUser·p0.9999: 18.432 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  12.939 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 20.603 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303422
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18730 
    [ 2.500,  5.000) = 276772 
    [ 5.000,  7.500) = 6855 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     12.510 ms/op
     p(99.9900) =     20.326 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 8.461 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.011 ms/op
Iteration   1: 3.730 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 18.724 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.781 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 14.303 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   3: 3.728 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  11.751 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256069
  mean =      3.746 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 85 
    [ 2.500,  3.750) = 187361 
    [ 3.750,  5.000) = 61113 
    [ 5.000,  6.250) = 2961 
    [ 6.250,  7.500) = 2574 
    [ 7.500,  8.750) = 863 
    [ 8.750, 10.000) = 344 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 241 
    [12.500, 13.750) = 184 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.236 ms/op
     p(99.9900) =     17.406 ms/op
     p(99.9990) =     19.270 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.820 ± 5.327  ops/ms
ClientPb.existUser                       thrpt       3  10.137 ± 3.098  ops/ms
ClientPb.getUser                         thrpt       3  10.053 ± 7.086  ops/ms
ClientPb.listUser                        thrpt       3   8.663 ± 2.329  ops/ms
ClientPb.createUser                       avgt       3   3.150 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 1.722   ms/op
ClientPb.getUser                          avgt       3   3.077 ± 1.215   ms/op
ClientPb.listUser                         avgt       3   3.616 ± 0.925   ms/op
ClientPb.createUser                     sample  303948   3.155 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.368           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.166           ms/op
ClientPb.existUser                      sample  319357   3.003 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.281           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.921           ms/op
ClientPb.getUser                        sample  303422   3.161 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.813           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.510           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.326           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.201           ms/op
ClientPb.listUser                       sample  256069   3.746 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.406           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.595           ms/op
