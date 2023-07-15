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
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 5.213 ops/ms
# Warmup Iteration   3: 8.432 ops/ms
Iteration   1: 8.949 ops/ms
Iteration   2: 8.967 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.038 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (8.949, 9.038, 9.197), stdev = 0.138
  CI (99.9%): [6.519, 11.556] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 7.631 ops/ms
# Warmup Iteration   3: 8.832 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.817 ops/ms
Iteration   3: 9.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.579 ±(99.9%) 4.339 ops/ms [Average]
  (min, avg, max) = (9.342, 9.579, 9.817), stdev = 0.238
  CI (99.9%): [5.240, 13.917] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 8.361 ops/ms
# Warmup Iteration   3: 9.272 ops/ms
Iteration   1: 9.357 ops/ms
Iteration   2: 9.071 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.199 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (9.071, 9.199, 9.357), stdev = 0.146
  CI (99.9%): [6.542, 11.855] (assumes normal distribution)


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
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 6.745 ops/ms
# Warmup Iteration   3: 7.751 ops/ms
Iteration   1: 7.580 ops/ms
Iteration   2: 7.670 ops/ms
Iteration   3: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.738 ±(99.9%) 3.676 ops/ms [Average]
  (min, avg, max) = (7.580, 7.738, 7.965), stdev = 0.202
  CI (99.9%): [4.062, 11.415] (assumes normal distribution)


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
# Warmup Iteration   1: 9.822 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.005 ms/op
Iteration   1: 3.498 ±(99.9%) 0.008 ms/op
Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
Iteration   3: 3.382 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.475 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (3.382, 3.475, 3.546), stdev = 0.085
  CI (99.9%): [1.932, 5.018] (assumes normal distribution)


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
# Warmup Iteration   1: 9.347 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.005 ms/op
Iteration   1: 3.308 ±(99.9%) 0.005 ms/op
Iteration   2: 3.243 ±(99.9%) 0.003 ms/op
Iteration   3: 3.344 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.243, 3.298, 3.344), stdev = 0.051
  CI (99.9%): [2.362, 4.234] (assumes normal distribution)


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
# Warmup Iteration   1: 9.515 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.005 ms/op
Iteration   1: 3.518 ±(99.9%) 0.008 ms/op
Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
Iteration   3: 3.382 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.417 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (3.349, 3.417, 3.518), stdev = 0.090
  CI (99.9%): [1.783, 5.050] (assumes normal distribution)


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
# Warmup Iteration   1: 10.604 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.009 ms/op
Iteration   1: 4.110 ±(99.9%) 0.010 ms/op
Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
Iteration   3: 4.096 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (4.053, 4.086, 4.110), stdev = 0.030
  CI (99.9%): [3.545, 4.627] (assumes normal distribution)


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
# Warmup Iteration   1: 10.883 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.015 ms/op
Iteration   1: 3.458 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  18.255 ms/op
                 createUser·p0.9999: 21.701 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.522 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  15.371 ms/op
                 createUser·p0.9999: 23.317 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  18.330 ms/op
                 createUser·p0.9999: 27.254 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275910
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5522 
    [ 2.500,  5.000) = 261166 
    [ 5.000,  7.500) = 7839 
    [ 7.500, 10.000) = 850 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     17.108 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.694 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 9.099 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.281 ms/op
                 existUser·p0.999:  14.908 ms/op
                 existUser·p0.9999: 25.054 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  22.331 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283523
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8433 
    [ 2.500,  5.000) = 268852 
    [ 5.000,  7.500) = 5356 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.772 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 9.532 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.012 ms/op
Iteration   1: 3.420 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.453 ms/op
                 getUser·p0.999:  21.265 ms/op
                 getUser·p0.9999: 23.909 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.574 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  27.269 ms/op
                 getUser·p0.9999: 35.000 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.495 ms/op
                 getUser·p0.999:  12.419 ms/op
                 getUser·p0.9999: 27.591 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272906
  mean =      3.516 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5384 
    [ 2.500,  5.000) = 257118 
    [ 5.000,  7.500) = 8805 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     34.191 ms/op
     p(99.9990) =     35.895 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 12.053 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.014 ms/op
Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 27.450 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   2: 4.015 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  18.360 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.214 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 23.138 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232054
  mean =      4.135 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 221438 
    [ 5.000,  7.500) = 6980 
    [ 7.500, 10.000) = 2702 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     18.905 ms/op
     p(99.9900) =     25.382 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.038 ± 2.518  ops/ms
ClientPb.existUser                       thrpt       3   9.579 ± 4.339  ops/ms
ClientPb.getUser                         thrpt       3   9.199 ± 2.656  ops/ms
ClientPb.listUser                        thrpt       3   7.738 ± 3.676  ops/ms
ClientPb.createUser                       avgt       3   3.475 ± 1.543   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 0.936   ms/op
ClientPb.getUser                          avgt       3   3.417 ± 1.633   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 0.541   ms/op
ClientPb.createUser                     sample  275910   3.478 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.108           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.148           ms/op
ClientPb.existUser                      sample  283523   3.385 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.805           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.378           ms/op
ClientPb.getUser                        sample  272906   3.516 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.173           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.191           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  232054   4.135 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.905           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.382           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.148           ms/op
