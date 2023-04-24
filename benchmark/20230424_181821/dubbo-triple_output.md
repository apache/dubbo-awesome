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
# Warmup Iteration   1: 2.167 ops/ms
# Warmup Iteration   2: 5.760 ops/ms
# Warmup Iteration   3: 8.497 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.215 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (9.180, 9.215, 9.269), stdev = 0.047
  CI (99.9%): [8.358, 10.073] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 8.887 ops/ms
# Warmup Iteration   3: 9.512 ops/ms
Iteration   1: 9.723 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 9.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (9.683, 9.801, 9.998), stdev = 0.172
  CI (99.9%): [6.668, 12.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 8.581 ops/ms
# Warmup Iteration   3: 8.926 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.545 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (9.431, 9.545, 9.627), stdev = 0.102
  CI (99.9%): [7.684, 11.406] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 2.790 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 7.722 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.042 ±(99.9%) 5.097 ops/ms [Average]
  (min, avg, max) = (7.722, 8.042, 8.239), stdev = 0.279
  CI (99.9%): [2.946, 13.139] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.212 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.004 ms/op
Iteration   1: 3.401 ±(99.9%) 0.005 ms/op
Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
Iteration   3: 3.443 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.401, 3.418, 3.443), stdev = 0.023
  CI (99.9%): [3.004, 3.831] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.604 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.004 ms/op
Iteration   1: 3.219 ±(99.9%) 0.005 ms/op
Iteration   2: 3.303 ±(99.9%) 0.003 ms/op
Iteration   3: 3.248 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.257 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.219, 3.257, 3.303), stdev = 0.043
  CI (99.9%): [2.476, 4.038] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.208 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.008 ms/op
Iteration   1: 3.487 ±(99.9%) 0.006 ms/op
Iteration   2: 3.545 ±(99.9%) 0.006 ms/op
Iteration   3: 3.390 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.474 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (3.390, 3.474, 3.545), stdev = 0.078
  CI (99.9%): [2.043, 4.906] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.270 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.009 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
Iteration   2: 3.955 ±(99.9%) 0.007 ms/op
Iteration   3: 3.929 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.946 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.929, 3.946, 3.955), stdev = 0.015
  CI (99.9%): [3.672, 4.220] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.990 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.010 ms/op
Iteration   1: 3.441 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 37.336 ms/op
                 createUser·p1.00:   38.863 ms/op

Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  16.635 ms/op
                 createUser·p0.9999: 24.042 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.356 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  20.284 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281357
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13272 
    [ 2.500,  5.000) = 261179 
    [ 5.000,  7.500) = 6027 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     19.703 ms/op
     p(99.9900) =     34.398 ms/op
     p(99.9990) =     38.453 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.729 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  18.532 ms/op
                 existUser·p0.9999: 26.063 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 25.926 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  12.381 ms/op
                 existUser·p0.9999: 35.328 ms/op
                 existUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293433
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8806 
    [ 2.500,  5.000) = 279393 
    [ 5.000,  7.500) = 4386 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     17.699 ms/op
     p(99.9900) =     33.991 ms/op
     p(99.9990) =     35.852 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  15.653 ms/op
                 getUser·p0.9999: 25.680 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  19.929 ms/op
                 getUser·p0.9999: 27.703 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284018
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8132 
    [ 2.500,  5.000) = 268700 
    [ 5.000,  7.500) = 6296 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 10.686 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.014 ms/op
Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  20.426 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.452 ms/op
                 listUser·p0.9999: 20.085 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.972 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.876 ms/op
                 listUser·p0.999:  14.952 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239786
  mean =      4.002 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 229760 
    [ 5.000,  7.500) = 7928 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.945 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     25.730 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.215 ± 0.858  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 3.133  ops/ms
ClientPb.getUser                         thrpt       3   9.545 ± 1.861  ops/ms
ClientPb.listUser                        thrpt       3   8.042 ± 5.097  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 0.413   ms/op
ClientPb.existUser                        avgt       3   3.257 ± 0.781   ms/op
ClientPb.getUser                          avgt       3   3.474 ± 1.431   ms/op
ClientPb.listUser                         avgt       3   3.946 ± 0.274   ms/op
ClientPb.createUser                     sample  281357   3.410 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.703           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  293433   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.699           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.991           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.110           ms/op
ClientPb.getUser                        sample  284018   3.379 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.464           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.702           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.770           ms/op
ClientPb.listUser                       sample  239786   4.002 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.925           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.945           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
