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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 5.936 ops/ms
# Warmup Iteration   3: 8.779 ops/ms
Iteration   1: 9.411 ops/ms
Iteration   2: 8.654 ops/ms
Iteration   3: 9.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.164 ±(99.9%) 8.066 ops/ms [Average]
  (min, avg, max) = (8.654, 9.164, 9.428), stdev = 0.442
  CI (99.9%): [1.098, 17.230] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.238 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 10.157 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.042 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (9.971, 10.042, 10.157), stdev = 0.100
  CI (99.9%): [8.211, 11.872] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 9.330 ops/ms
Iteration   1: 9.619 ops/ms
Iteration   2: 9.738 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.651 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (9.597, 9.651, 9.738), stdev = 0.076
  CI (99.9%): [8.261, 11.042] (assumes normal distribution)


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
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 7.327 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 8.064 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 7.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.940 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (7.871, 7.940, 8.064), stdev = 0.107
  CI (99.9%): [5.986, 9.895] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.006 ms/op
Iteration   1: 3.481 ±(99.9%) 0.009 ms/op
Iteration   2: 3.410 ±(99.9%) 0.008 ms/op
Iteration   3: 3.356 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.356, 3.415, 3.481), stdev = 0.063
  CI (99.9%): [2.272, 4.559] (assumes normal distribution)


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
# Warmup Iteration   1: 7.985 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.241 ±(99.9%) 0.006 ms/op
Iteration   2: 3.253 ±(99.9%) 0.006 ms/op
Iteration   3: 3.120 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.205 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.120, 3.205, 3.253), stdev = 0.074
  CI (99.9%): [1.862, 4.548] (assumes normal distribution)


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
# Warmup Iteration   1: 9.428 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.389 ±(99.9%) 0.004 ms/op
Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
Iteration   3: 3.404 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.389, 3.396, 3.404), stdev = 0.008
  CI (99.9%): [3.257, 3.536] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.852 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.007 ms/op
Iteration   1: 3.928 ±(99.9%) 0.007 ms/op
Iteration   2: 4.005 ±(99.9%) 0.008 ms/op
Iteration   3: 3.871 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.935 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.871, 3.935, 4.005), stdev = 0.067
  CI (99.9%): [2.713, 5.156] (assumes normal distribution)


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
# Warmup Iteration   1: 10.915 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.014 ms/op
Iteration   1: 3.576 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  20.183 ms/op
                 createUser·p0.9999: 25.827 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  21.243 ms/op
                 createUser·p0.9999: 24.079 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.759 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.560 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 29.928 ms/op
                 createUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279930
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16380 
    [ 2.500,  5.000) = 258101 
    [ 5.000,  7.500) = 4301 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     26.708 ms/op
     p(99.9990) =     29.989 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 8.592 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.003 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.901 ms/op
                 existUser·p0.999:  13.654 ms/op
                 existUser·p0.9999: 26.139 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.633 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294419
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8834 
    [ 2.500,  5.000) = 281395 
    [ 5.000,  7.500) = 3393 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.088 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     34.345 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 9.123 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.073 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  17.903 ms/op
                 getUser·p0.9999: 20.733 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  20.442 ms/op
                 getUser·p0.9999: 22.950 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.921 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  17.197 ms/op
                 getUser·p0.9999: 26.876 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279434
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11291 
    [ 2.500,  5.000) = 261031 
    [ 5.000,  7.500) = 5998 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     17.507 ms/op
     p(99.9900) =     25.827 ms/op
     p(99.9990) =     28.089 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 10.047 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  21.103 ms/op
                 listUser·p0.9999: 25.066 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.722 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.550 ms/op
                 listUser·p0.9999: 16.256 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238550
  mean =      4.022 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 227679 
    [ 5.000,  7.500) = 8818 
    [ 7.500, 10.000) = 1189 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     23.827 ms/op
     p(99.9990) =     25.599 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.164 ± 8.066  ops/ms
ClientPb.existUser                       thrpt       3  10.042 ± 1.831  ops/ms
ClientPb.getUser                         thrpt       3   9.651 ± 1.390  ops/ms
ClientPb.listUser                        thrpt       3   7.940 ± 1.954  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 1.143   ms/op
ClientPb.existUser                        avgt       3   3.205 ± 1.343   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 0.140   ms/op
ClientPb.listUser                         avgt       3   3.935 ± 1.221   ms/op
ClientPb.createUser                     sample  279930   3.427 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.425           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.708           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  294419   3.259 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.088           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.489           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  279434   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.507           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.827           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  238550   4.022 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.975           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
