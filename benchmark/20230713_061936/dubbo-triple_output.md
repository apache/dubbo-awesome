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
# Warmup Iteration   1: 2.039 ops/ms
# Warmup Iteration   2: 4.870 ops/ms
# Warmup Iteration   3: 8.523 ops/ms
Iteration   1: 8.766 ops/ms
Iteration   2: 9.058 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.012 ±(99.9%) 4.133 ops/ms [Average]
  (min, avg, max) = (8.766, 9.012, 9.212), stdev = 0.227
  CI (99.9%): [4.879, 13.144] (assumes normal distribution)


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
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 8.397 ops/ms
# Warmup Iteration   3: 9.202 ops/ms
Iteration   1: 9.982 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 9.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.878 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (9.761, 9.878, 9.982), stdev = 0.111
  CI (99.9%): [7.853, 11.903] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.748 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 8.655 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 9.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.050 ±(99.9%) 3.078 ops/ms [Average]
  (min, avg, max) = (8.864, 9.050, 9.194), stdev = 0.169
  CI (99.9%): [5.972, 12.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.579 ops/ms
# Warmup Iteration   2: 6.775 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 7.805 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.887 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (7.784, 7.887, 8.073), stdev = 0.161
  CI (99.9%): [4.950, 10.825] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.544 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.010 ms/op
Iteration   1: 3.458 ±(99.9%) 0.010 ms/op
Iteration   2: 3.488 ±(99.9%) 0.011 ms/op
Iteration   3: 3.429 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.429, 3.459, 3.488), stdev = 0.030
  CI (99.9%): [2.919, 3.998] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.407 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.004 ms/op
Iteration   1: 3.350 ±(99.9%) 0.010 ms/op
Iteration   2: 3.348 ±(99.9%) 0.006 ms/op
Iteration   3: 3.288 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.288, 3.329, 3.350), stdev = 0.035
  CI (99.9%): [2.689, 3.968] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.959 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.005 ms/op
Iteration   1: 3.615 ±(99.9%) 0.008 ms/op
Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
Iteration   3: 3.580 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.558 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.479, 3.558, 3.615), stdev = 0.070
  CI (99.9%): [2.273, 4.843] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.841 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.004 ms/op
Iteration   1: 4.107 ±(99.9%) 0.006 ms/op
Iteration   2: 4.096 ±(99.9%) 0.007 ms/op
Iteration   3: 3.980 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.061 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (3.980, 4.061, 4.107), stdev = 0.071
  CI (99.9%): [2.772, 5.350] (assumes normal distribution)


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
# Warmup Iteration   1: 9.637 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.012 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.190 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 27.780 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  20.972 ms/op
                 createUser·p0.9999: 25.615 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277984
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7074 
    [ 2.500,  5.000) = 265791 
    [ 5.000,  7.500) = 3989 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.933 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.582 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.010 ms/op
Iteration   1: 3.494 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.820 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 24.593 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  13.100 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.017 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  20.748 ms/op
                 existUser·p0.9999: 25.278 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283814
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7925 
    [ 2.500,  5.000) = 269966 
    [ 5.000,  7.500) = 5011 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     13.225 ms/op
     p(99.9900) =     24.813 ms/op
     p(99.9990) =     26.089 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 9.614 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.012 ms/op
Iteration   1: 3.379 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  19.944 ms/op
                 getUser·p0.9999: 23.464 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  21.610 ms/op
                 getUser·p0.9999: 28.555 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  16.311 ms/op
                 getUser·p0.9999: 26.034 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282055
  mean =      3.400 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1427 
    [ 2.500,  5.000) = 274536 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     27.518 ms/op
     p(99.9990) =     28.832 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 12.085 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.013 ms/op
Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  20.844 ms/op
                 listUser·p0.9999: 25.535 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 3.985 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.611 ms/op
                 listUser·p0.999:  14.395 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 4.118 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.191 ms/op
                 listUser·p0.999:  15.538 ms/op
                 listUser·p0.9999: 18.183 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235106
  mean =      4.079 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 225228 
    [ 5.000,  7.500) = 7456 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     17.000 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     25.777 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.012 ± 4.133  ops/ms
ClientPb.existUser                       thrpt       3   9.878 ± 2.025  ops/ms
ClientPb.getUser                         thrpt       3   9.050 ± 3.078  ops/ms
ClientPb.listUser                        thrpt       3   7.887 ± 2.937  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.639   ms/op
ClientPb.getUser                          avgt       3   3.558 ± 1.285   ms/op
ClientPb.listUser                         avgt       3   4.061 ± 1.289   ms/op
ClientPb.createUser                     sample  277984   3.451 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  283814   3.381 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.692           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.149           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.813           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.116           ms/op
ClientPb.getUser                        sample  282055   3.400 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.411           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.518           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  235106   4.079 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.000           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
