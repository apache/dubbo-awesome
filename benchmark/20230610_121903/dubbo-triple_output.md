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
# Warmup Iteration   1: 1.107 ops/ms
# Warmup Iteration   2: 2.504 ops/ms
# Warmup Iteration   3: 5.153 ops/ms
Iteration   1: 5.744 ops/ms
Iteration   2: 5.933 ops/ms
Iteration   3: 6.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.929 ±(99.9%) 3.336 ops/ms [Average]
  (min, avg, max) = (5.744, 5.929, 6.110), stdev = 0.183
  CI (99.9%): [2.593, 9.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.537 ops/ms
# Warmup Iteration   2: 4.561 ops/ms
# Warmup Iteration   3: 5.840 ops/ms
Iteration   1: 6.067 ops/ms
Iteration   2: 6.219 ops/ms
Iteration   3: 6.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.124 ±(99.9%) 1.503 ops/ms [Average]
  (min, avg, max) = (6.067, 6.124, 6.219), stdev = 0.082
  CI (99.9%): [4.621, 7.627] (assumes normal distribution)


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
# Warmup Iteration   1: 1.459 ops/ms
# Warmup Iteration   2: 4.743 ops/ms
# Warmup Iteration   3: 6.136 ops/ms
Iteration   1: 6.294 ops/ms
Iteration   2: 6.096 ops/ms
Iteration   3: 6.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.183 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (6.096, 6.183, 6.294), stdev = 0.101
  CI (99.9%): [4.335, 8.031] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.613 ops/ms
# Warmup Iteration   2: 4.342 ops/ms
# Warmup Iteration   3: 4.687 ops/ms
Iteration   1: 4.995 ops/ms
Iteration   2: 4.975 ops/ms
Iteration   3: 4.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.893 ±(99.9%) 2.922 ops/ms [Average]
  (min, avg, max) = (4.708, 4.893, 4.995), stdev = 0.160
  CI (99.9%): [1.971, 7.815] (assumes normal distribution)


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
# Warmup Iteration   1: 17.409 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.679 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.640 ±(99.9%) 0.011 ms/op
Iteration   1: 5.386 ±(99.9%) 0.021 ms/op
Iteration   2: 5.156 ±(99.9%) 0.018 ms/op
Iteration   3: 5.531 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.357 ±(99.9%) 3.443 ms/op [Average]
  (min, avg, max) = (5.156, 5.357, 5.531), stdev = 0.189
  CI (99.9%): [1.914, 8.801] (assumes normal distribution)


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
# Warmup Iteration   1: 16.301 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.742 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.384 ±(99.9%) 0.011 ms/op
Iteration   1: 5.043 ±(99.9%) 0.019 ms/op
Iteration   2: 4.994 ±(99.9%) 0.009 ms/op
Iteration   3: 4.977 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.005 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (4.977, 5.005, 5.043), stdev = 0.034
  CI (99.9%): [4.377, 5.633] (assumes normal distribution)


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
# Warmup Iteration   1: 18.319 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.883 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.586 ±(99.9%) 0.022 ms/op
Iteration   1: 5.483 ±(99.9%) 0.015 ms/op
Iteration   2: 5.484 ±(99.9%) 0.016 ms/op
Iteration   3: 5.568 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.512 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (5.483, 5.512, 5.568), stdev = 0.048
  CI (99.9%): [4.628, 6.395] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.540 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.475 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.430 ±(99.9%) 0.010 ms/op
Iteration   1: 6.205 ±(99.9%) 0.017 ms/op
Iteration   2: 6.269 ±(99.9%) 0.014 ms/op
Iteration   3: 6.515 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.330 ±(99.9%) 2.983 ms/op [Average]
  (min, avg, max) = (6.205, 6.330, 6.515), stdev = 0.164
  CI (99.9%): [3.347, 9.313] (assumes normal distribution)


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
# Warmup Iteration   1: 17.146 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.809 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.775 ±(99.9%) 0.024 ms/op
Iteration   1: 5.532 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.425 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.528 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  24.812 ms/op
                 createUser·p0.9999: 28.413 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   2: 5.682 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  25.255 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 5.685 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.299 ms/op
                 createUser·p0.99:   9.323 ms/op
                 createUser·p0.999:  29.871 ms/op
                 createUser·p0.9999: 33.019 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170276
  mean =      5.632 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 51832 
    [ 5.000,  7.500) = 108983 
    [ 7.500, 10.000) = 7405 
    [10.000, 12.500) = 1308 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     25.457 ms/op
     p(99.9900) =     32.668 ms/op
     p(99.9990) =     34.458 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 15.688 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.021 ms/op
Iteration   1: 5.315 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   11.076 ms/op
                 existUser·p0.999:  23.784 ms/op
                 existUser·p0.9999: 26.836 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 5.129 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.816 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  13.560 ms/op
                 existUser·p0.9999: 28.674 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 5.140 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.482 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  27.451 ms/op
                 existUser·p0.9999: 31.101 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184702
  mean =      5.193 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 99571 
    [ 5.000,  7.500) = 78072 
    [ 7.500, 10.000) = 5334 
    [10.000, 12.500) = 969 
    [12.500, 15.000) = 430 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.903 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     18.730 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.331 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.559 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.059 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.021 ms/op
Iteration   1: 5.350 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.966 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  27.866 ms/op
                 getUser·p0.9999: 31.819 ms/op
                 getUser·p1.00:   33.489 ms/op

Iteration   2: 5.551 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   7.283 ms/op
                 getUser·p0.95:   8.348 ms/op
                 getUser·p0.99:   11.130 ms/op
                 getUser·p0.999:  24.604 ms/op
                 getUser·p0.9999: 29.244 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 5.355 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.404 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.299 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  26.451 ms/op
                 getUser·p0.9999: 30.641 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177133
  mean =      5.417 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 70161 
    [ 5.000,  7.500) = 96707 
    [ 7.500, 10.000) = 8506 
    [10.000, 12.500) = 1131 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     24.838 ms/op
     p(99.9900) =     31.106 ms/op
     p(99.9990) =     33.084 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 19.083 ±(99.9%) 0.361 ms/op
# Warmup Iteration   2: 8.374 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.433 ±(99.9%) 0.028 ms/op
Iteration   1: 6.265 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.375 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.226 ms/op
                 listUser·p0.999:  27.099 ms/op
                 listUser·p0.9999: 29.204 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   2: 6.353 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.219 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   7.786 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  29.975 ms/op
                 listUser·p0.9999: 37.809 ms/op
                 listUser·p1.00:   40.501 ms/op

Iteration   3: 6.301 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   3.699 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  24.387 ms/op
                 listUser·p0.9999: 29.544 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152086
  mean =      6.306 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4837 
    [ 5.000, 10.000) = 144479 
    [10.000, 15.000) = 2385 
    [15.000, 20.000) = 103 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 166 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.219 ms/op
     p(50.0000) =      6.078 ms/op
     p(90.0000) =      7.258 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     27.296 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     39.545 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.929 ± 3.336  ops/ms
ClientPb.existUser                       thrpt       3   6.124 ± 1.503  ops/ms
ClientPb.getUser                         thrpt       3   6.183 ± 1.848  ops/ms
ClientPb.listUser                        thrpt       3   4.893 ± 2.922  ops/ms
ClientPb.createUser                       avgt       3   5.357 ± 3.443   ms/op
ClientPb.existUser                        avgt       3   5.005 ± 0.628   ms/op
ClientPb.getUser                          avgt       3   5.512 ± 0.883   ms/op
ClientPb.listUser                         avgt       3   6.330 ± 2.983   ms/op
ClientPb.createUser                     sample  170276   5.632 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.457           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.668           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  184702   5.193 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.070           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.310           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  177133   5.417 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.766           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.838           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.106           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.489           ms/op
ClientPb.listUser                       sample  152086   6.306 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.219           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.078           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.010           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.296           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.501           ms/op
