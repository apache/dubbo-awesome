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
# Warmup Iteration   1: 1.083 ops/ms
# Warmup Iteration   2: 2.602 ops/ms
# Warmup Iteration   3: 5.332 ops/ms
Iteration   1: 6.033 ops/ms
Iteration   2: 5.982 ops/ms
Iteration   3: 5.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.992 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (5.960, 5.992, 6.033), stdev = 0.038
  CI (99.9%): [5.302, 6.681] (assumes normal distribution)


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
# Warmup Iteration   1: 1.691 ops/ms
# Warmup Iteration   2: 4.580 ops/ms
# Warmup Iteration   3: 6.080 ops/ms
Iteration   1: 6.103 ops/ms
Iteration   2: 6.283 ops/ms
Iteration   3: 6.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.173 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (6.103, 6.173, 6.283), stdev = 0.096
  CI (99.9%): [4.420, 7.927] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.441 ops/ms
# Warmup Iteration   2: 4.401 ops/ms
# Warmup Iteration   3: 5.893 ops/ms
Iteration   1: 5.589 ops/ms
Iteration   2: 5.576 ops/ms
Iteration   3: 5.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.695 ±(99.9%) 3.550 ops/ms [Average]
  (min, avg, max) = (5.576, 5.695, 5.919), stdev = 0.195
  CI (99.9%): [2.145, 9.245] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 4.056 ops/ms
# Warmup Iteration   3: 4.984 ops/ms
Iteration   1: 5.165 ops/ms
Iteration   2: 5.010 ops/ms
Iteration   3: 5.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.155 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (5.010, 5.155, 5.290), stdev = 0.140
  CI (99.9%): [2.596, 7.714] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.002 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.556 ±(99.9%) 0.012 ms/op
Iteration   1: 5.404 ±(99.9%) 0.014 ms/op
Iteration   2: 5.486 ±(99.9%) 0.007 ms/op
Iteration   3: 5.465 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.451 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (5.404, 5.451, 5.486), stdev = 0.043
  CI (99.9%): [4.670, 6.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.801 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.735 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.013 ms/op
Iteration   1: 5.221 ±(99.9%) 0.006 ms/op
Iteration   2: 5.035 ±(99.9%) 0.022 ms/op
Iteration   3: 5.174 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.143 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (5.035, 5.143, 5.221), stdev = 0.097
  CI (99.9%): [3.380, 6.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.446 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.217 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.010 ms/op
Iteration   1: 5.294 ±(99.9%) 0.015 ms/op
Iteration   2: 5.380 ±(99.9%) 0.015 ms/op
Iteration   3: 5.152 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.276 ±(99.9%) 2.097 ms/op [Average]
  (min, avg, max) = (5.152, 5.276, 5.380), stdev = 0.115
  CI (99.9%): [3.178, 7.373] (assumes normal distribution)


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
# Warmup Iteration   1: 17.373 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.495 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.173 ±(99.9%) 0.021 ms/op
Iteration   1: 6.795 ±(99.9%) 0.012 ms/op
Iteration   2: 6.104 ±(99.9%) 0.016 ms/op
Iteration   3: 6.239 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.379 ±(99.9%) 6.684 ms/op [Average]
  (min, avg, max) = (6.104, 6.379, 6.795), stdev = 0.366
  CI (99.9%): [≈ 0, 13.063] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.209 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.895 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.694 ±(99.9%) 0.025 ms/op
Iteration   1: 5.407 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.119 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  24.272 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 5.431 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.299 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  24.153 ms/op
                 createUser·p0.9999: 29.361 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 5.009 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.036 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.275 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  25.991 ms/op
                 createUser·p0.9999: 31.064 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182031
  mean =      5.275 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 87084 
    [ 5.000,  7.500) = 89330 
    [ 7.500, 10.000) = 4572 
    [10.000, 12.500) = 655 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.036 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     24.213 ms/op
     p(99.9900) =     30.428 ms/op
     p(99.9990) =     31.666 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.053 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 6.543 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.289 ±(99.9%) 0.017 ms/op
Iteration   1: 5.115 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  24.331 ms/op
                 existUser·p0.9999: 29.778 ms/op
                 existUser·p1.00:   32.473 ms/op

Iteration   2: 5.104 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  25.052 ms/op
                 existUser·p0.9999: 30.424 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 5.120 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  24.860 ms/op
                 existUser·p0.9999: 29.041 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187647
  mean =      5.113 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 106863 
    [ 5.000,  7.500) = 75028 
    [ 7.500, 10.000) = 4628 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     24.622 ms/op
     p(99.9900) =     29.859 ms/op
     p(99.9990) =     32.128 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.935 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 6.979 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.599 ±(99.9%) 0.019 ms/op
Iteration   1: 5.443 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.979 ms/op
                 getUser·p0.99:   12.217 ms/op
                 getUser·p0.999:  24.102 ms/op
                 getUser·p0.9999: 30.212 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   2: 5.203 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   6.726 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  26.400 ms/op
                 getUser·p0.9999: 42.982 ms/op
                 getUser·p1.00:   43.188 ms/op

Iteration   3: 5.461 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.396 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   7.479 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  16.712 ms/op
                 getUser·p0.9999: 30.741 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178794
  mean =      5.366 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78895 
    [ 5.000, 10.000) = 97631 
    [10.000, 15.000) = 1780 
    [15.000, 20.000) = 290 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     10.536 ms/op
     p(99.9000) =     23.700 ms/op
     p(99.9900) =     40.509 ms/op
     p(99.9990) =     43.085 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.424 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 7.953 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.393 ±(99.9%) 0.023 ms/op
Iteration   1: 6.197 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  31.125 ms/op
                 listUser·p0.9999: 35.193 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   2: 6.255 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   11.858 ms/op
                 listUser·p0.999:  27.484 ms/op
                 listUser·p0.9999: 30.467 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   3: 6.384 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.974 ms/op
                 listUser·p0.999:  23.556 ms/op
                 listUser·p0.9999: 28.344 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152928
  mean =      6.278 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 7303 
    [ 5.000,  7.500) = 132053 
    [ 7.500, 10.000) = 10010 
    [10.000, 12.500) = 2371 
    [12.500, 15.000) = 615 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     34.199 ms/op
     p(99.9990) =     35.991 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.992 ± 0.689  ops/ms
ClientPb.existUser                       thrpt       3   6.173 ± 1.753  ops/ms
ClientPb.getUser                         thrpt       3   5.695 ± 3.550  ops/ms
ClientPb.listUser                        thrpt       3   5.155 ± 2.559  ops/ms
ClientPb.createUser                       avgt       3   5.451 ± 0.781   ms/op
ClientPb.existUser                        avgt       3   5.143 ± 1.763   ms/op
ClientPb.getUser                          avgt       3   5.276 ± 2.097   ms/op
ClientPb.listUser                         avgt       3   6.379 ± 6.684   ms/op
ClientPb.createUser                     sample  182031   5.275 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.036           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.021           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.913           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.213           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.428           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.719           ms/op
ClientPb.existUser                      sample  187647   5.113 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.070           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.044           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.622           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.859           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.473           ms/op
ClientPb.getUser                        sample  178794   5.366 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.095           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.389           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.536           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.700           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.188           ms/op
ClientPb.listUser                       sample  152928   6.278 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.698           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.492           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.199           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
