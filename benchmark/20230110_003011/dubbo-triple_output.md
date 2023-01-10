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
# Warmup Iteration   1: 1.107 ops/ms
# Warmup Iteration   2: 2.566 ops/ms
# Warmup Iteration   3: 5.522 ops/ms
Iteration   1: 5.913 ops/ms
Iteration   2: 5.963 ops/ms
Iteration   3: 5.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.935 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (5.913, 5.935, 5.963), stdev = 0.026
  CI (99.9%): [5.465, 6.404] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.411 ops/ms
# Warmup Iteration   2: 5.199 ops/ms
# Warmup Iteration   3: 6.192 ops/ms
Iteration   1: 6.519 ops/ms
Iteration   2: 6.544 ops/ms
Iteration   3: 6.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.480 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (6.376, 6.480, 6.544), stdev = 0.091
  CI (99.9%): [4.827, 8.133] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 4.534 ops/ms
# Warmup Iteration   3: 6.100 ops/ms
Iteration   1: 5.835 ops/ms
Iteration   2: 5.920 ops/ms
Iteration   3: 6.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.020 ±(99.9%) 4.582 ops/ms [Average]
  (min, avg, max) = (5.835, 6.020, 6.306), stdev = 0.251
  CI (99.9%): [1.438, 10.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.564 ops/ms
# Warmup Iteration   2: 4.230 ops/ms
# Warmup Iteration   3: 5.295 ops/ms
Iteration   1: 5.150 ops/ms
Iteration   2: 5.407 ops/ms
Iteration   3: 5.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.346 ±(99.9%) 3.172 ops/ms [Average]
  (min, avg, max) = (5.150, 5.346, 5.481), stdev = 0.174
  CI (99.9%): [2.173, 8.518] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.028 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.816 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.006 ms/op
Iteration   1: 5.388 ±(99.9%) 0.015 ms/op
Iteration   2: 5.255 ±(99.9%) 0.014 ms/op
Iteration   3: 5.034 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.226 ±(99.9%) 3.261 ms/op [Average]
  (min, avg, max) = (5.034, 5.226, 5.388), stdev = 0.179
  CI (99.9%): [1.965, 8.487] (assumes normal distribution)


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
# Warmup Iteration   1: 16.944 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.933 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.006 ms/op
Iteration   1: 5.054 ±(99.9%) 0.007 ms/op
Iteration   2: 4.981 ±(99.9%) 0.011 ms/op
Iteration   3: 4.898 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.978 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (4.898, 4.978, 5.054), stdev = 0.078
  CI (99.9%): [3.548, 6.408] (assumes normal distribution)


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
# Warmup Iteration   1: 16.790 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.213 ±(99.9%) 0.008 ms/op
Iteration   1: 5.381 ±(99.9%) 0.009 ms/op
Iteration   2: 5.110 ±(99.9%) 0.011 ms/op
Iteration   3: 5.367 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.286 ±(99.9%) 2.788 ms/op [Average]
  (min, avg, max) = (5.110, 5.286, 5.381), stdev = 0.153
  CI (99.9%): [2.498, 8.074] (assumes normal distribution)


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
# Warmup Iteration   1: 19.859 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.186 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.192 ±(99.9%) 0.010 ms/op
Iteration   1: 6.163 ±(99.9%) 0.017 ms/op
Iteration   2: 5.803 ±(99.9%) 0.016 ms/op
Iteration   3: 5.926 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.964 ±(99.9%) 3.338 ms/op [Average]
  (min, avg, max) = (5.803, 5.964, 6.163), stdev = 0.183
  CI (99.9%): [2.626, 9.302] (assumes normal distribution)


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
# Warmup Iteration   1: 17.606 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.883 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.051 ±(99.9%) 0.029 ms/op
Iteration   1: 5.217 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  20.796 ms/op
                 createUser·p0.9999: 23.883 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 5.233 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  23.349 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 5.387 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   11.638 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 29.498 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181858
  mean =      5.278 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 94409 
    [ 5.000,  7.500) = 79305 
    [ 7.500, 10.000) = 5903 
    [10.000, 12.500) = 1415 
    [12.500, 15.000) = 447 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 111 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     27.710 ms/op
     p(99.9990) =     29.864 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 16.739 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.033 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.336 ±(99.9%) 0.022 ms/op
Iteration   1: 4.954 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.347 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  18.392 ms/op
                 existUser·p0.9999: 26.625 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 5.146 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   10.159 ms/op
                 existUser·p0.999:  24.760 ms/op
                 existUser·p0.9999: 30.573 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   3: 5.213 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.791 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  22.315 ms/op
                 existUser·p0.9999: 37.028 ms/op
                 existUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188059
  mean =      5.102 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 121190 
    [ 5.000, 10.000) = 65042 
    [10.000, 15.000) = 1475 
    [15.000, 20.000) = 122 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     23.392 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     39.572 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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
# Warmup Iteration   1: 18.054 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.562 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.284 ±(99.9%) 0.018 ms/op
Iteration   1: 5.380 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   13.009 ms/op
                 getUser·p0.999:  23.381 ms/op
                 getUser·p0.9999: 27.756 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 5.235 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.642 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  25.726 ms/op
                 getUser·p0.9999: 29.772 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 5.148 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 30.041 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182650
  mean =      5.253 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 98888 
    [ 5.000,  7.500) = 74172 
    [ 7.500, 10.000) = 6349 
    [10.000, 12.500) = 1983 
    [12.500, 15.000) = 755 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     23.003 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.950 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 19.513 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 6.973 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.220 ±(99.9%) 0.026 ms/op
Iteration   1: 6.130 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.173 ms/op
                 listUser·p0.999:  26.401 ms/op
                 listUser·p0.9999: 29.667 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 5.977 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.957 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  26.435 ms/op
                 listUser·p0.9999: 30.757 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   3: 6.122 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   12.029 ms/op
                 listUser·p0.999:  25.601 ms/op
                 listUser·p0.9999: 36.358 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157960
  mean =      6.076 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 14113 
    [ 5.000,  7.500) = 130504 
    [ 7.500, 10.000) = 9182 
    [10.000, 12.500) = 2762 
    [12.500, 15.000) = 734 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.445 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     25.955 ms/op
     p(99.9900) =     33.430 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.935 ± 0.470  ops/ms
ClientPb.existUser                       thrpt       3   6.480 ± 1.653  ops/ms
ClientPb.getUser                         thrpt       3   6.020 ± 4.582  ops/ms
ClientPb.listUser                        thrpt       3   5.346 ± 3.172  ops/ms
ClientPb.createUser                       avgt       3   5.226 ± 3.261   ms/op
ClientPb.existUser                        avgt       3   4.978 ± 1.430   ms/op
ClientPb.getUser                          avgt       3   5.286 ± 2.788   ms/op
ClientPb.listUser                         avgt       3   5.964 ± 3.338   ms/op
ClientPb.createUser                     sample  181858   5.278 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.765           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.200           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  188059   5.102 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.431           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.945           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.392           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.419           ms/op
ClientPb.getUser                        sample  182650   5.253 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.403           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.003           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  157960   6.076 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.445           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.955           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.438           ms/op
