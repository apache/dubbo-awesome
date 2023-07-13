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
# Warmup Iteration   1: 1.788 ops/ms
# Warmup Iteration   2: 4.368 ops/ms
# Warmup Iteration   3: 7.463 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 9.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.670 ±(99.9%) 11.299 ops/ms [Average]
  (min, avg, max) = (7.982, 8.670, 9.183), stdev = 0.619
  CI (99.9%): [≈ 0, 19.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ops/ms
# Warmup Iteration   2: 8.715 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.899 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (9.826, 9.899, 9.947), stdev = 0.064
  CI (99.9%): [8.723, 11.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 8.407 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 9.186 ops/ms
Iteration   2: 9.468 ops/ms
Iteration   3: 9.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.373 ±(99.9%) 2.954 ops/ms [Average]
  (min, avg, max) = (9.186, 9.373, 9.468), stdev = 0.162
  CI (99.9%): [6.419, 12.327] (assumes normal distribution)


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
# Warmup Iteration   1: 2.863 ops/ms
# Warmup Iteration   2: 7.323 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.013 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (7.902, 8.013, 8.100), stdev = 0.101
  CI (99.9%): [6.164, 9.862] (assumes normal distribution)


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
# Warmup Iteration   1: 9.004 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.008 ms/op
Iteration   1: 3.497 ±(99.9%) 0.005 ms/op
Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
Iteration   3: 3.343 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.438 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (3.343, 3.438, 3.497), stdev = 0.083
  CI (99.9%): [1.932, 4.943] (assumes normal distribution)


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
# Warmup Iteration   1: 8.395 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
Iteration   3: 3.291 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.241, 3.259, 3.291), stdev = 0.028
  CI (99.9%): [2.756, 3.763] (assumes normal distribution)


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
# Warmup Iteration   1: 9.678 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.003 ms/op
Iteration   1: 3.330 ±(99.9%) 0.007 ms/op
Iteration   2: 3.386 ±(99.9%) 0.007 ms/op
Iteration   3: 3.486 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.401 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.330, 3.401, 3.486), stdev = 0.079
  CI (99.9%): [1.956, 4.846] (assumes normal distribution)


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
# Warmup Iteration   1: 11.086 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.010 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
Iteration   2: 3.962 ±(99.9%) 0.012 ms/op
Iteration   3: 3.922 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.957 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.922, 3.957, 3.988), stdev = 0.033
  CI (99.9%): [3.356, 4.558] (assumes normal distribution)


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
# Warmup Iteration   1: 9.233 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.600 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  21.791 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  19.578 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275304
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5379 
    [ 2.500,  5.000) = 261777 
    [ 5.000,  7.500) = 7363 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     26.971 ms/op
     p(99.9990) =     31.531 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 7.353 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.305 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.029 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.706 ms/op
                 existUser·p0.9999: 23.876 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 24.635 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 3.307 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.307 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.460 ms/op
                 existUser·p0.999:  16.448 ms/op
                 existUser·p0.9999: 33.926 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289466
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15926 
    [ 2.500,  5.000) = 268915 
    [ 5.000,  7.500) = 3760 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     15.927 ms/op
     p(99.9900) =     32.646 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 9.836 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.011 ms/op
Iteration   1: 3.579 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 22.350 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.932 ms/op
                 getUser·p0.999:  21.792 ms/op
                 getUser·p0.9999: 25.212 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  20.219 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273321
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9005 
    [ 2.500,  5.000) = 256186 
    [ 5.000,  7.500) = 6627 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     24.882 ms/op
     p(99.9990) =     26.158 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 10.214 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.012 ms/op
Iteration   1: 4.232 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  19.086 ms/op
                 listUser·p0.9999: 23.622 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.939 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.595 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236957
  mean =      4.047 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 227789 
    [ 5.000,  7.500) = 6583 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.819 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.670 ± 11.299  ops/ms
ClientPb.existUser                       thrpt       3   9.899 ±  1.177  ops/ms
ClientPb.getUser                         thrpt       3   9.373 ±  2.954  ops/ms
ClientPb.listUser                        thrpt       3   8.013 ±  1.849  ops/ms
ClientPb.createUser                       avgt       3   3.438 ±  1.506   ms/op
ClientPb.existUser                        avgt       3   3.259 ±  0.504   ms/op
ClientPb.getUser                          avgt       3   3.401 ±  1.445   ms/op
ClientPb.listUser                         avgt       3   3.957 ±  0.601   ms/op
ClientPb.createUser                     sample  275304   3.490 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.153            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464            ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.971            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588            ms/op
ClientPb.existUser                      sample  289466   3.313 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.307            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.927            ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.646            ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406            ms/op
ClientPb.getUser                        sample  273321   3.509 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.709            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988            ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.882            ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182            ms/op
ClientPb.listUser                       sample  236957   4.047 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.676            ms/op
ClientPb.listUser:listUser·p0.999       sample          15.270            ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101            ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888            ms/op
