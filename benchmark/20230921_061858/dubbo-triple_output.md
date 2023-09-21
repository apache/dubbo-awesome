# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 5.242 ops/ms
# Warmup Iteration   3: 8.232 ops/ms
Iteration   1: 8.831 ops/ms
Iteration   2: 8.934 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.954 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (8.831, 8.954, 9.096), stdev = 0.133
  CI (99.9%): [6.520, 11.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ops/ms
# Warmup Iteration   2: 8.666 ops/ms
# Warmup Iteration   3: 9.288 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.411 ops/ms
Iteration   3: 9.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.390 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (9.348, 9.390, 9.411), stdev = 0.036
  CI (99.9%): [8.736, 10.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 8.116 ops/ms
# Warmup Iteration   3: 8.786 ops/ms
Iteration   1: 8.968 ops/ms
Iteration   2: 8.996 ops/ms
Iteration   3: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.022 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (8.968, 9.022, 9.102), stdev = 0.071
  CI (99.9%): [7.735, 10.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 6.932 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.458 ops/ms
Iteration   2: 7.670 ops/ms
Iteration   3: 7.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.642 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (7.458, 7.642, 7.798), stdev = 0.172
  CI (99.9%): [4.509, 10.775] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.659 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.006 ms/op
Iteration   1: 3.601 ±(99.9%) 0.007 ms/op
Iteration   2: 3.533 ±(99.9%) 0.006 ms/op
Iteration   3: 3.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.553 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.524, 3.553, 3.601), stdev = 0.042
  CI (99.9%): [2.780, 4.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.290 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.348 ±(99.9%) 0.004 ms/op
Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
Iteration   3: 3.349 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (3.348, 3.359, 3.380), stdev = 0.018
  CI (99.9%): [3.030, 3.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.011 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.004 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.573 ±(99.9%) 0.005 ms/op
Iteration   3: 3.542 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.552 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.540, 3.552, 3.573), stdev = 0.019
  CI (99.9%): [3.212, 3.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.503 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.005 ms/op
Iteration   1: 4.195 ±(99.9%) 0.009 ms/op
Iteration   2: 4.236 ±(99.9%) 0.008 ms/op
Iteration   3: 4.039 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.157 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (4.039, 4.157, 4.236), stdev = 0.104
  CI (99.9%): [2.257, 6.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.639 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.015 ms/op
Iteration   1: 3.574 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 40.701 ms/op
                 createUser·p1.00:   42.992 ms/op

Iteration   2: 3.512 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  22.905 ms/op
                 createUser·p0.9999: 30.693 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 3.617 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  24.194 ms/op
                 createUser·p0.9999: 28.751 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268939
  mean =      3.567 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 260812 
    [ 5.000, 10.000) = 7577 
    [10.000, 15.000) = 165 
    [15.000, 20.000) = 69 
    [20.000, 25.000) = 144 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     21.336 ms/op
     p(99.9900) =     38.018 ms/op
     p(99.9990) =     42.926 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.829 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
Iteration   1: 3.482 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  21.926 ms/op
                 existUser·p0.9999: 23.620 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.478 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  23.233 ms/op
                 existUser·p0.9999: 33.096 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   3: 3.463 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  17.782 ms/op
                 existUser·p0.9999: 28.100 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276245
  mean =      3.474 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5857 
    [ 2.500,  5.000) = 259066 
    [ 5.000,  7.500) = 9447 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     21.250 ms/op
     p(99.9900) =     31.511 ms/op
     p(99.9990) =     33.944 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.012 ms/op
Iteration   1: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.972 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 24.314 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.629 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.964 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  24.344 ms/op
                 getUser·p0.9999: 26.613 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.534 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  23.399 ms/op
                 getUser·p0.9999: 28.432 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269928
  mean =      3.555 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4122 
    [ 2.500,  5.000) = 257252 
    [ 5.000,  7.500) = 6553 
    [ 7.500, 10.000) = 1207 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     21.929 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.440 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.449 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.013 ms/op
Iteration   1: 4.240 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  22.137 ms/op
                 listUser·p0.9999: 30.409 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   2: 4.243 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.625 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.202 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 18.396 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226987
  mean =      4.228 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 214851 
    [ 5.000,  7.500) = 7989 
    [ 7.500, 10.000) = 2981 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     25.286 ms/op
     p(99.9990) =     32.038 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.954 ± 2.434  ops/ms
ClientPb.existUser                       thrpt       3   9.390 ± 0.653  ops/ms
ClientPb.getUser                         thrpt       3   9.022 ± 1.287  ops/ms
ClientPb.listUser                        thrpt       3   7.642 ± 3.133  ops/ms
ClientPb.createUser                       avgt       3   3.553 ± 0.772   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 0.329   ms/op
ClientPb.getUser                          avgt       3   3.552 ± 0.340   ms/op
ClientPb.listUser                         avgt       3   4.157 ± 1.900   ms/op
ClientPb.createUser                     sample  268939   3.567 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.229           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.336           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.018           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.992           ms/op
ClientPb.existUser                      sample  276245   3.474 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.250           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.511           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  269928   3.555 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.929           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.165           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  226987   4.228 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.516           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.170           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.286           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.473           ms/op
