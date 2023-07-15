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
# Warmup Iteration   1: 2.207 ops/ms
# Warmup Iteration   2: 4.895 ops/ms
# Warmup Iteration   3: 8.394 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 9.193 ops/ms
Iteration   3: 8.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.071 ±(99.9%) 2.292 ops/ms [Average]
  (min, avg, max) = (8.942, 9.071, 9.193), stdev = 0.126
  CI (99.9%): [6.780, 11.363] (assumes normal distribution)


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
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.049 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 9.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.871 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (9.820, 9.871, 9.934), stdev = 0.058
  CI (99.9%): [8.816, 10.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 8.576 ops/ms
# Warmup Iteration   3: 9.000 ops/ms
Iteration   1: 8.955 ops/ms
Iteration   2: 8.942 ops/ms
Iteration   3: 9.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.016 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (8.942, 9.016, 9.150), stdev = 0.117
  CI (99.9%): [6.886, 11.146] (assumes normal distribution)


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
# Warmup Iteration   1: 2.909 ops/ms
# Warmup Iteration   2: 5.941 ops/ms
# Warmup Iteration   3: 7.953 ops/ms
Iteration   1: 7.797 ops/ms
Iteration   2: 7.813 ops/ms
Iteration   3: 7.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.808 ±(99.9%) 0.167 ops/ms [Average]
  (min, avg, max) = (7.797, 7.808, 7.813), stdev = 0.009
  CI (99.9%): [7.641, 7.974] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.889 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.005 ms/op
Iteration   1: 3.505 ±(99.9%) 0.006 ms/op
Iteration   2: 3.473 ±(99.9%) 0.009 ms/op
Iteration   3: 3.434 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.471 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.434, 3.471, 3.505), stdev = 0.036
  CI (99.9%): [2.823, 4.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.894 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.007 ms/op
Iteration   1: 3.293 ±(99.9%) 0.010 ms/op
Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
Iteration   3: 3.293 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (3.279, 3.288, 3.293), stdev = 0.008
  CI (99.9%): [3.141, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 8.593 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.003 ms/op
Iteration   1: 3.547 ±(99.9%) 0.007 ms/op
Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
Iteration   3: 3.440 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.472 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (3.429, 3.472, 3.547), stdev = 0.065
  CI (99.9%): [2.281, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 11.600 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.006 ms/op
Iteration   1: 4.127 ±(99.9%) 0.006 ms/op
Iteration   2: 4.002 ±(99.9%) 0.009 ms/op
Iteration   3: 3.839 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.989 ±(99.9%) 2.632 ms/op [Average]
  (min, avg, max) = (3.839, 3.989, 4.127), stdev = 0.144
  CI (99.9%): [1.357, 6.621] (assumes normal distribution)


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
# Warmup Iteration   1: 8.888 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.010 ms/op
Iteration   1: 3.337 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  19.535 ms/op
                 createUser·p0.9999: 34.800 ms/op
                 createUser·p1.00:   35.979 ms/op

Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.089 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   36.766 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 30.966 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279229
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9309 
    [ 2.500,  5.000) = 265296 
    [ 5.000,  7.500) = 3578 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     19.500 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.386 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 8.413 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.008 ms/op
Iteration   1: 3.438 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.458 ms/op
                 existUser·p0.999:  20.967 ms/op
                 existUser·p0.9999: 23.868 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.779 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.044 ms/op
                 existUser·p0.9999: 25.853 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  19.359 ms/op
                 existUser·p0.9999: 35.617 ms/op
                 existUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283332
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12709 
    [ 2.500,  5.000) = 264656 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     19.901 ms/op
     p(99.9900) =     34.385 ms/op
     p(99.9990) =     36.067 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 9.453 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
Iteration   1: 3.554 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  13.976 ms/op
                 getUser·p0.9999: 27.395 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.123 ms/op
                 getUser·p0.999:  21.415 ms/op
                 getUser·p0.9999: 28.858 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.434 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277461
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3129 
    [ 2.500,  5.000) = 266900 
    [ 5.000,  7.500) = 6222 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     27.788 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 10.528 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.412 ms/op
                 listUser·p0.999:  19.682 ms/op
                 listUser·p0.9999: 32.113 ms/op
                 listUser·p1.00:   33.194 ms/op

Iteration   2: 3.876 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.308 ms/op
                 listUser·p0.9999: 19.783 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.069 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  14.360 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241308
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 232977 
    [ 5.000,  7.500) = 6019 
    [ 7.500, 10.000) = 1472 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.034 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     33.018 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.071 ± 2.292  ops/ms
ClientPb.existUser                       thrpt       3   9.871 ± 1.055  ops/ms
ClientPb.getUser                         thrpt       3   9.016 ± 2.130  ops/ms
ClientPb.listUser                        thrpt       3   7.808 ± 0.167  ops/ms
ClientPb.createUser                       avgt       3   3.471 ± 0.649   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   3.472 ± 1.191   ms/op
ClientPb.listUser                         avgt       3   3.989 ± 2.632   ms/op
ClientPb.createUser                     sample  279229   3.437 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.500           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  283332   3.387 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.901           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.385           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.224           ms/op
ClientPb.getUser                        sample  277461   3.456 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.999           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.992           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.788           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  241308   3.977 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.034           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.588           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.194           ms/op
