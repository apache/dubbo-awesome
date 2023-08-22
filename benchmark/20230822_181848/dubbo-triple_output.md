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
# Warmup Iteration   1: 1.228 ops/ms
# Warmup Iteration   2: 2.975 ops/ms
# Warmup Iteration   3: 6.026 ops/ms
Iteration   1: 6.023 ops/ms
Iteration   2: 6.444 ops/ms
Iteration   3: 6.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.321 ±(99.9%) 4.740 ops/ms [Average]
  (min, avg, max) = (6.023, 6.321, 6.497), stdev = 0.260
  CI (99.9%): [1.582, 11.061] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.702 ops/ms
# Warmup Iteration   2: 5.328 ops/ms
# Warmup Iteration   3: 6.219 ops/ms
Iteration   1: 6.232 ops/ms
Iteration   2: 6.491 ops/ms
Iteration   3: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.313 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (6.217, 6.313, 6.491), stdev = 0.154
  CI (99.9%): [3.510, 9.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 5.181 ops/ms
# Warmup Iteration   3: 6.327 ops/ms
Iteration   1: 6.066 ops/ms
Iteration   2: 6.234 ops/ms
Iteration   3: 6.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.224 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (6.066, 6.224, 6.371), stdev = 0.152
  CI (99.9%): [3.442, 9.006] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 4.374 ops/ms
# Warmup Iteration   3: 5.245 ops/ms
Iteration   1: 5.473 ops/ms
Iteration   2: 5.395 ops/ms
Iteration   3: 5.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.436 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (5.395, 5.436, 5.473), stdev = 0.039
  CI (99.9%): [4.723, 6.149] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.045 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.494 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.597 ±(99.9%) 0.012 ms/op
Iteration   1: 5.253 ±(99.9%) 0.012 ms/op
Iteration   2: 5.131 ±(99.9%) 0.015 ms/op
Iteration   3: 5.192 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.192 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (5.131, 5.192, 5.253), stdev = 0.061
  CI (99.9%): [4.077, 6.307] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.152 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.703 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.925 ±(99.9%) 0.015 ms/op
Iteration   1: 4.860 ±(99.9%) 0.009 ms/op
Iteration   2: 4.960 ±(99.9%) 0.006 ms/op
Iteration   3: 5.030 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.950 ±(99.9%) 1.565 ms/op [Average]
  (min, avg, max) = (4.860, 4.950, 5.030), stdev = 0.086
  CI (99.9%): [3.385, 6.515] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.801 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.008 ms/op
Iteration   1: 5.139 ±(99.9%) 0.009 ms/op
Iteration   2: 5.117 ±(99.9%) 0.009 ms/op
Iteration   3: 5.125 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.127 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (5.117, 5.127, 5.139), stdev = 0.011
  CI (99.9%): [4.929, 5.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.589 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.501 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.782 ±(99.9%) 0.019 ms/op
Iteration   1: 5.986 ±(99.9%) 0.018 ms/op
Iteration   2: 5.869 ±(99.9%) 0.010 ms/op
Iteration   3: 5.885 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.913 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (5.869, 5.913, 5.986), stdev = 0.064
  CI (99.9%): [4.750, 7.077] (assumes normal distribution)


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
# Warmup Iteration   1: 16.438 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.297 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.024 ms/op
Iteration   1: 5.138 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.160 ms/op
                 createUser·p0.99:   10.129 ms/op
                 createUser·p0.999:  22.040 ms/op
                 createUser·p0.9999: 26.207 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   2: 5.129 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  24.782 ms/op
                 createUser·p0.9999: 29.574 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 5.033 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  24.957 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188172
  mean =      5.100 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 120483 
    [ 5.000,  7.500) = 60302 
    [ 7.500, 10.000) = 5573 
    [10.000, 12.500) = 1078 
    [12.500, 15.000) = 393 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.868 ms/op
     p(99.9000) =     22.238 ms/op
     p(99.9900) =     28.243 ms/op
     p(99.9990) =     30.282 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 15.610 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.017 ms/op
Iteration   1: 4.866 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.472 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  19.832 ms/op
                 existUser·p0.9999: 23.916 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 5.046 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  21.555 ms/op
                 existUser·p0.9999: 29.108 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 4.884 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.472 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  14.970 ms/op
                 existUser·p0.9999: 28.243 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194550
  mean =      4.931 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 137884 
    [ 5.000,  7.500) = 50503 
    [ 7.500, 10.000) = 4649 
    [10.000, 12.500) = 1079 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     19.789 ms/op
     p(99.9900) =     28.714 ms/op
     p(99.9990) =     29.590 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.221 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.599 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.019 ms/op
Iteration   1: 5.147 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.388 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  25.841 ms/op
                 getUser·p0.9999: 34.494 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   2: 5.296 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.668 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  23.888 ms/op
                 getUser·p0.9999: 34.926 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 5.180 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  25.108 ms/op
                 getUser·p0.9999: 28.339 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184295
  mean =      5.207 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 102854 
    [ 5.000,  7.500) = 72706 
    [ 7.500, 10.000) = 6631 
    [10.000, 12.500) = 1407 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     24.252 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     35.402 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 19.029 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.776 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.852 ±(99.9%) 0.020 ms/op
Iteration   1: 5.988 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  24.681 ms/op
                 listUser·p0.9999: 28.627 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 5.788 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  26.994 ms/op
                 listUser·p0.9999: 31.683 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   3: 5.938 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.195 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   12.023 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162615
  mean =      5.903 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 17852 
    [ 5.000,  7.500) = 131916 
    [ 7.500, 10.000) = 9768 
    [10.000, 12.500) = 1934 
    [12.500, 15.000) = 552 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     30.564 ms/op
     p(99.9990) =     32.938 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.321 ± 4.740  ops/ms
ClientPb.existUser                       thrpt       3   6.313 ± 2.803  ops/ms
ClientPb.getUser                         thrpt       3   6.224 ± 2.782  ops/ms
ClientPb.listUser                        thrpt       3   5.436 ± 0.713  ops/ms
ClientPb.createUser                       avgt       3   5.192 ± 1.115   ms/op
ClientPb.existUser                        avgt       3   4.950 ± 1.565   ms/op
ClientPb.getUser                          avgt       3   5.127 ± 0.198   ms/op
ClientPb.listUser                         avgt       3   5.913 ± 1.163   ms/op
ClientPb.createUser                     sample  188172   5.100 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.502           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.868           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.243           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  194550   4.931 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.700           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.535           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.789           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.714           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  184295   5.207 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.224           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.406           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.273           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.252           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  162615   5.903 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.044           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.469           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.183           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.564           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
