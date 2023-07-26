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
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 5.179 ops/ms
# Warmup Iteration   3: 8.415 ops/ms
Iteration   1: 8.926 ops/ms
Iteration   2: 8.994 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.050 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (8.926, 9.050, 9.230), stdev = 0.159
  CI (99.9%): [6.144, 11.956] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.945 ops/ms
# Warmup Iteration   2: 8.648 ops/ms
# Warmup Iteration   3: 9.765 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 9.380 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.694 ±(99.9%) 5.580 ops/ms [Average]
  (min, avg, max) = (9.380, 9.694, 9.991), stdev = 0.306
  CI (99.9%): [4.114, 15.273] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.721 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 8.974 ops/ms
Iteration   2: 8.800 ops/ms
Iteration   3: 9.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.992 ±(99.9%) 3.683 ops/ms [Average]
  (min, avg, max) = (8.800, 8.992, 9.203), stdev = 0.202
  CI (99.9%): [5.309, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 2.597 ops/ms
# Warmup Iteration   2: 7.067 ops/ms
# Warmup Iteration   3: 7.401 ops/ms
Iteration   1: 7.752 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.814 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (7.752, 7.814, 7.888), stdev = 0.069
  CI (99.9%): [6.561, 9.068] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.321 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.006 ms/op
Iteration   1: 3.428 ±(99.9%) 0.013 ms/op
Iteration   2: 3.492 ±(99.9%) 0.008 ms/op
Iteration   3: 3.417 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.417, 3.446, 3.492), stdev = 0.041
  CI (99.9%): [2.705, 4.186] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.590 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.268 ±(99.9%) 0.009 ms/op
Iteration   2: 3.360 ±(99.9%) 0.007 ms/op
Iteration   3: 3.337 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.322 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.268, 3.322, 3.360), stdev = 0.048
  CI (99.9%): [2.445, 4.198] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.916 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.006 ms/op
Iteration   1: 3.563 ±(99.9%) 0.004 ms/op
Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
Iteration   3: 3.407 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 1.740 ms/op [Average]
  (min, avg, max) = (3.389, 3.453, 3.563), stdev = 0.095
  CI (99.9%): [1.713, 5.193] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.460 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.832 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.006 ms/op
Iteration   1: 4.136 ±(99.9%) 0.011 ms/op
Iteration   2: 4.228 ±(99.9%) 0.006 ms/op
Iteration   3: 3.976 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.113 ±(99.9%) 2.327 ms/op [Average]
  (min, avg, max) = (3.976, 4.113, 4.228), stdev = 0.128
  CI (99.9%): [1.786, 6.440] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.669 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.016 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  21.176 ms/op
                 createUser·p0.9999: 28.105 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   2: 3.490 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.408 ms/op
                 createUser·p0.999:  22.225 ms/op
                 createUser·p0.9999: 25.800 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  18.905 ms/op
                 createUser·p0.9999: 26.768 ms/op
                 createUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276147
  mean =      3.474 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9151 
    [ 2.500,  5.000) = 262221 
    [ 5.000,  7.500) = 3830 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     20.442 ms/op
     p(99.9900) =     26.850 ms/op
     p(99.9990) =     28.415 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.128 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
Iteration   1: 3.547 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  9.664 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.551 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  23.523 ms/op
                 existUser·p0.9999: 26.443 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  22.757 ms/op
                 existUser·p0.9999: 34.464 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271421
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7184 
    [ 2.500,  5.000) = 253402 
    [ 5.000,  7.500) = 9618 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     14.575 ms/op
     p(99.9900) =     33.222 ms/op
     p(99.9990) =     34.987 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.611 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.012 ms/op
Iteration   1: 3.518 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  10.207 ms/op
                 getUser·p0.9999: 24.799 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  24.192 ms/op
                 getUser·p0.9999: 28.433 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  21.779 ms/op
                 getUser·p0.9999: 27.455 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275212
  mean =      3.487 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6500 
    [ 2.500,  5.000) = 260268 
    [ 5.000,  7.500) = 7306 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     11.023 ms/op
     p(99.9900) =     27.836 ms/op
     p(99.9990) =     29.450 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.177 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.015 ms/op
Iteration   1: 4.205 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 4.168 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 16.564 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 4.166 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.262 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 31.850 ms/op
                 listUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229609
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 219084 
    [ 5.000,  7.500) = 7676 
    [ 7.500, 10.000) = 1928 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.521 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.050 ± 2.906  ops/ms
ClientPb.existUser                       thrpt       3   9.694 ± 5.580  ops/ms
ClientPb.getUser                         thrpt       3   8.992 ± 3.683  ops/ms
ClientPb.listUser                        thrpt       3   7.814 ± 1.253  ops/ms
ClientPb.createUser                       avgt       3   3.446 ± 0.740   ms/op
ClientPb.existUser                        avgt       3   3.322 ± 0.876   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 1.740   ms/op
ClientPb.listUser                         avgt       3   4.113 ± 2.327   ms/op
ClientPb.createUser                     sample  276147   3.474 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.442           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.850           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.967           ms/op
ClientPb.existUser                      sample  271421   3.535 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.575           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  275212   3.487 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.614           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.023           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.836           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  229609   4.179 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.521           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.031           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.982           ms/op
