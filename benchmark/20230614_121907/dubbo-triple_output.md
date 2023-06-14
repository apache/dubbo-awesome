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
# Warmup Iteration   1: 1.823 ops/ms
# Warmup Iteration   2: 4.613 ops/ms
# Warmup Iteration   3: 8.219 ops/ms
Iteration   1: 8.313 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.466 ±(99.9%) 4.232 ops/ms [Average]
  (min, avg, max) = (8.313, 8.466, 8.733), stdev = 0.232
  CI (99.9%): [4.234, 12.698] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.408 ops/ms
# Warmup Iteration   2: 7.583 ops/ms
# Warmup Iteration   3: 8.338 ops/ms
Iteration   1: 8.415 ops/ms
Iteration   2: 8.792 ops/ms
Iteration   3: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.642 ±(99.9%) 3.647 ops/ms [Average]
  (min, avg, max) = (8.415, 8.642, 8.792), stdev = 0.200
  CI (99.9%): [4.994, 12.289] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 7.383 ops/ms
# Warmup Iteration   3: 8.210 ops/ms
Iteration   1: 8.588 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.679 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (8.569, 8.679, 8.880), stdev = 0.174
  CI (99.9%): [5.500, 11.858] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.398 ops/ms
# Warmup Iteration   3: 7.400 ops/ms
Iteration   1: 7.575 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.849 ±(99.9%) 4.665 ops/ms [Average]
  (min, avg, max) = (7.575, 7.849, 8.082), stdev = 0.256
  CI (99.9%): [3.184, 12.515] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.824 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.007 ms/op
Iteration   1: 3.403 ±(99.9%) 0.005 ms/op
Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
Iteration   3: 3.351 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.351, 3.419, 3.503), stdev = 0.077
  CI (99.9%): [2.016, 4.822] (assumes normal distribution)


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
# Warmup Iteration   1: 8.401 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.002 ms/op
Iteration   1: 3.389 ±(99.9%) 0.006 ms/op
Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
Iteration   3: 3.430 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.466 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (3.389, 3.466, 3.579), stdev = 0.100
  CI (99.9%): [1.646, 5.286] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.464 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.004 ms/op
Iteration   1: 3.603 ±(99.9%) 0.007 ms/op
Iteration   2: 3.422 ±(99.9%) 0.004 ms/op
Iteration   3: 3.554 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.526 ±(99.9%) 1.709 ms/op [Average]
  (min, avg, max) = (3.422, 3.526, 3.603), stdev = 0.094
  CI (99.9%): [1.817, 5.235] (assumes normal distribution)


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
# Warmup Iteration   1: 12.244 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.011 ms/op
Iteration   1: 4.257 ±(99.9%) 0.010 ms/op
Iteration   2: 4.173 ±(99.9%) 0.013 ms/op
Iteration   3: 4.085 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.172 ±(99.9%) 1.569 ms/op [Average]
  (min, avg, max) = (4.085, 4.172, 4.257), stdev = 0.086
  CI (99.9%): [2.603, 5.741] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.296 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.016 ms/op
Iteration   1: 3.587 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  19.527 ms/op
                 createUser·p0.9999: 22.586 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  22.332 ms/op
                 createUser·p0.9999: 29.907 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  23.272 ms/op
                 createUser·p0.9999: 28.963 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273241
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5225 
    [ 2.500,  5.000) = 257680 
    [ 5.000,  7.500) = 9044 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     29.273 ms/op
     p(99.9990) =     30.564 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 7.923 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.008 ms/op
Iteration   1: 3.448 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 23.256 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   6.220 ms/op
                 existUser·p0.999:  21.985 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.701 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 28.934 ms/op
                 existUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 270270
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4104 
    [ 2.500,  5.000) = 259702 
    [ 5.000,  7.500) = 5237 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     15.954 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.239 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 11.944 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.012 ms/op
Iteration   1: 3.616 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  23.874 ms/op
                 getUser·p0.9999: 50.201 ms/op
                 getUser·p1.00:   50.528 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  22.165 ms/op
                 getUser·p0.9999: 24.644 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.601 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 32.418 ms/op
                 getUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271884
  mean =      3.531 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 261331 
    [ 5.000, 10.000) = 10004 
    [10.000, 15.000) = 241 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 188 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 22 
    [50.000, 55.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     20.615 ms/op
     p(99.9900) =     48.026 ms/op
     p(99.9990) =     50.463 ms/op
     p(99.9999) =     50.528 ms/op
    p(100.0000) =     50.528 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.397 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.762 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.015 ms/op
Iteration   1: 4.257 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  21.689 ms/op
                 listUser·p0.9999: 25.165 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.129 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 4.145 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229523
  mean =      4.176 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 221992 
    [ 5.000,  7.500) = 5238 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 309 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     24.315 ms/op
     p(99.9990) =     25.517 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.466 ± 4.232  ops/ms
ClientPb.existUser                       thrpt       3   8.642 ± 3.647  ops/ms
ClientPb.getUser                         thrpt       3   8.679 ± 3.179  ops/ms
ClientPb.listUser                        thrpt       3   7.849 ± 4.665  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 1.403   ms/op
ClientPb.existUser                        avgt       3   3.466 ± 1.820   ms/op
ClientPb.getUser                          avgt       3   3.526 ± 1.709   ms/op
ClientPb.listUser                         avgt       3   4.172 ± 1.569   ms/op
ClientPb.createUser                     sample  273241   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.218           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.273           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.261           ms/op
ClientPb.existUser                      sample  270270   3.550 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.634           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.954           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.262           ms/op
ClientPb.getUser                        sample  271884   3.531 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.615           ms/op
ClientPb.getUser:getUser·p0.9999        sample          48.026           ms/op
ClientPb.getUser:getUser·p1.00          sample          50.528           ms/op
ClientPb.listUser                       sample  229523   4.176 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
