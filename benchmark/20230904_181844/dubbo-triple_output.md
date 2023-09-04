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
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 4.245 ops/ms
# Warmup Iteration   3: 8.560 ops/ms
Iteration   1: 8.630 ops/ms
Iteration   2: 9.239 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.012 ±(99.9%) 6.065 ops/ms [Average]
  (min, avg, max) = (8.630, 9.012, 9.239), stdev = 0.332
  CI (99.9%): [2.947, 15.077] (assumes normal distribution)


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
# Warmup Iteration   1: 2.766 ops/ms
# Warmup Iteration   2: 8.281 ops/ms
# Warmup Iteration   3: 9.280 ops/ms
Iteration   1: 9.633 ops/ms
Iteration   2: 9.402 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.603 ±(99.9%) 3.422 ops/ms [Average]
  (min, avg, max) = (9.402, 9.603, 9.774), stdev = 0.188
  CI (99.9%): [6.181, 13.025] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.889 ops/ms
Iteration   1: 9.350 ops/ms
Iteration   2: 9.226 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.269 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (9.226, 9.269, 9.350), stdev = 0.070
  CI (99.9%): [7.990, 10.548] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 6.914 ops/ms
# Warmup Iteration   3: 7.549 ops/ms
Iteration   1: 7.580 ops/ms
Iteration   2: 7.594 ops/ms
Iteration   3: 7.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.598 ±(99.9%) 0.384 ops/ms [Average]
  (min, avg, max) = (7.580, 7.598, 7.621), stdev = 0.021
  CI (99.9%): [7.214, 7.983] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.362 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.007 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
Iteration   2: 3.571 ±(99.9%) 0.005 ms/op
Iteration   3: 3.600 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.540 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.449, 3.540, 3.600), stdev = 0.080
  CI (99.9%): [2.077, 5.003] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.248 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.003 ms/op
Iteration   1: 3.453 ±(99.9%) 0.004 ms/op
Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
Iteration   3: 3.398 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.381 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.294, 3.381, 3.453), stdev = 0.081
  CI (99.9%): [1.907, 4.855] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.560 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.003 ms/op
Iteration   1: 3.658 ±(99.9%) 0.007 ms/op
Iteration   2: 3.557 ±(99.9%) 0.006 ms/op
Iteration   3: 3.639 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.618 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (3.557, 3.618, 3.658), stdev = 0.054
  CI (99.9%): [2.632, 4.603] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.106 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.013 ms/op
Iteration   1: 4.030 ±(99.9%) 0.010 ms/op
Iteration   2: 4.127 ±(99.9%) 0.008 ms/op
Iteration   3: 4.173 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.110 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (4.030, 4.110, 4.173), stdev = 0.073
  CI (99.9%): [2.777, 5.442] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.691 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.014 ms/op
Iteration   1: 3.559 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  21.529 ms/op
                 createUser·p0.9999: 25.953 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.495 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   7.000 ms/op
                 createUser·p0.999:  23.939 ms/op
                 createUser·p0.9999: 30.011 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 3.521 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.327 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  22.780 ms/op
                 createUser·p0.9999: 34.925 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272153
  mean =      3.525 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3578 
    [ 2.500,  5.000) = 259376 
    [ 5.000,  7.500) = 7153 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     22.693 ms/op
     p(99.9900) =     33.709 ms/op
     p(99.9990) =     35.670 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.055 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
Iteration   1: 3.509 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  21.168 ms/op
                 existUser·p0.9999: 25.326 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  14.916 ms/op
                 existUser·p0.9999: 26.695 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.420 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  23.772 ms/op
                 existUser·p0.9999: 32.167 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277985
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7283 
    [ 2.500,  5.000) = 260945 
    [ 5.000,  7.500) = 7922 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     32.644 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 11.857 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.013 ms/op
Iteration   1: 3.655 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.789 ms/op
                 getUser·p0.999:  21.474 ms/op
                 getUser·p0.9999: 25.174 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.650 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  10.279 ms/op
                 getUser·p0.9999: 27.098 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   3: 3.661 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  26.311 ms/op
                 getUser·p0.9999: 30.787 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262478
  mean =      3.656 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3520 
    [ 2.500,  5.000) = 245106 
    [ 5.000,  7.500) = 11562 
    [ 7.500, 10.000) = 1676 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     30.302 ms/op
     p(99.9990) =     32.125 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 11.727 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.015 ms/op
Iteration   1: 4.106 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.811 ms/op
                 listUser·p0.999:  22.805 ms/op
                 listUser·p0.9999: 25.113 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.306 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.606 ms/op
                 listUser·p0.999:  16.705 ms/op
                 listUser·p0.9999: 23.970 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236313
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 226391 
    [ 5.000,  7.500) = 7442 
    [ 7.500, 10.000) = 1543 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     17.095 ms/op
     p(99.9900) =     24.469 ms/op
     p(99.9990) =     26.131 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.012 ± 6.065  ops/ms
ClientPb.existUser                       thrpt       3   9.603 ± 3.422  ops/ms
ClientPb.getUser                         thrpt       3   9.269 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3   7.598 ± 0.384  ops/ms
ClientPb.createUser                       avgt       3   3.540 ± 1.463   ms/op
ClientPb.existUser                        avgt       3   3.381 ± 1.474   ms/op
ClientPb.getUser                          avgt       3   3.618 ± 0.986   ms/op
ClientPb.listUser                         avgt       3   4.110 ± 1.332   ms/op
ClientPb.createUser                     sample  272153   3.525 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.693           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.709           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  277985   3.451 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.040           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  262478   3.656 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.763           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  236313   4.063 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.095           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.469           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
