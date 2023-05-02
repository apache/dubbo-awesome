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
# Warmup Iteration   1: 2.364 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 9.520 ops/ms
Iteration   2: 9.551 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.642 ±(99.9%) 3.388 ops/ms [Average]
  (min, avg, max) = (9.520, 9.642, 9.856), stdev = 0.186
  CI (99.9%): [6.254, 13.030] (assumes normal distribution)


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
# Warmup Iteration   1: 2.873 ops/ms
# Warmup Iteration   2: 8.426 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 9.845 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 9.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.886 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (9.843, 9.886, 9.970), stdev = 0.073
  CI (99.9%): [8.559, 11.213] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.526 ops/ms
# Warmup Iteration   2: 8.919 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.538 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.456 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (9.193, 9.456, 9.636), stdev = 0.232
  CI (99.9%): [5.215, 13.696] (assumes normal distribution)


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
# Warmup Iteration   1: 2.894 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 8.284 ops/ms
Iteration   2: 7.948 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.077 ±(99.9%) 3.301 ops/ms [Average]
  (min, avg, max) = (7.948, 8.077, 8.284), stdev = 0.181
  CI (99.9%): [4.775, 11.378] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.689 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.007 ms/op
Iteration   1: 3.372 ±(99.9%) 0.015 ms/op
Iteration   2: 3.390 ±(99.9%) 0.007 ms/op
Iteration   3: 3.349 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.349, 3.370, 3.390), stdev = 0.021
  CI (99.9%): [2.996, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 8.651 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.003 ms/op
Iteration   1: 3.258 ±(99.9%) 0.007 ms/op
Iteration   2: 3.275 ±(99.9%) 0.006 ms/op
Iteration   3: 3.246 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (3.246, 3.259, 3.275), stdev = 0.015
  CI (99.9%): [2.995, 3.524] (assumes normal distribution)


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
# Warmup Iteration   1: 7.859 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.007 ms/op
Iteration   1: 3.354 ±(99.9%) 0.007 ms/op
Iteration   2: 3.351 ±(99.9%) 0.008 ms/op
Iteration   3: 3.338 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.348 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (3.338, 3.348, 3.354), stdev = 0.008
  CI (99.9%): [3.194, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 8.960 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.008 ms/op
Iteration   1: 3.844 ±(99.9%) 0.013 ms/op
Iteration   2: 3.908 ±(99.9%) 0.014 ms/op
Iteration   3: 3.877 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.877 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.844, 3.877, 3.908), stdev = 0.032
  CI (99.9%): [3.296, 4.457] (assumes normal distribution)


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
# Warmup Iteration   1: 9.172 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.378 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  19.835 ms/op
                 createUser·p0.9999: 21.809 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  20.909 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.445 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  16.654 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280346
  mean =      3.424 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8394 
    [ 2.500,  5.000) = 265078 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     16.831 ms/op
     p(99.9900) =     26.377 ms/op
     p(99.9990) =     28.056 ms/op
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
# Warmup Iteration   1: 8.496 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.007 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 21.906 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.766 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  14.336 ms/op
                 existUser·p0.9999: 26.611 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  15.351 ms/op
                 existUser·p0.9999: 25.001 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292117
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6026 
    [ 2.500,  5.000) = 280913 
    [ 5.000,  7.500) = 3800 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     15.113 ms/op
     p(99.9900) =     25.093 ms/op
     p(99.9990) =     27.298 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 9.266 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.012 ms/op
Iteration   1: 3.510 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.808 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  14.842 ms/op
                 getUser·p0.9999: 27.347 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 3.478 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.598 ms/op
                 getUser·p0.999:  21.955 ms/op
                 getUser·p0.9999: 25.219 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  18.000 ms/op
                 getUser·p0.9999: 25.278 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278741
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8423 
    [ 2.500,  5.000) = 261260 
    [ 5.000,  7.500) = 7850 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.534 ms/op
     p(99.9000) =     14.924 ms/op
     p(99.9900) =     25.862 ms/op
     p(99.9990) =     27.546 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 10.025 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.014 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  18.825 ms/op
                 listUser·p0.9999: 22.400 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.618 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  16.241 ms/op
                 listUser·p0.9999: 21.996 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.392 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.149 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239494
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 227103 
    [ 5.000,  7.500) = 10255 
    [ 7.500, 10.000) = 1379 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.358 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.642 ± 3.388  ops/ms
ClientPb.existUser                       thrpt       3   9.886 ± 1.327  ops/ms
ClientPb.getUser                         thrpt       3   9.456 ± 4.240  ops/ms
ClientPb.listUser                        thrpt       3   8.077 ± 3.301  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   3.259 ± 0.265   ms/op
ClientPb.getUser                          avgt       3   3.348 ± 0.154   ms/op
ClientPb.listUser                         avgt       3   3.877 ± 0.580   ms/op
ClientPb.createUser                     sample  280346   3.424 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.377           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  292117   3.282 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.113           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.093           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.820           ms/op
ClientPb.getUser                        sample  278741   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.037           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.924           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.862           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  239494   4.006 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.392           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.922           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
