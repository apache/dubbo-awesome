# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.060 ops/ms
# Warmup Iteration   2: 2.457 ops/ms
# Warmup Iteration   3: 5.433 ops/ms
Iteration   1: 5.926 ops/ms
Iteration   2: 6.121 ops/ms
Iteration   3: 6.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.162 ±(99.9%) 4.734 ops/ms [Average]
  (min, avg, max) = (5.926, 6.162, 6.440), stdev = 0.259
  CI (99.9%): [1.428, 10.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 5.136 ops/ms
# Warmup Iteration   3: 6.011 ops/ms
Iteration   1: 6.253 ops/ms
Iteration   2: 6.342 ops/ms
Iteration   3: 6.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.358 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (6.253, 6.358, 6.480), stdev = 0.114
  CI (99.9%): [4.272, 8.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 4.673 ops/ms
# Warmup Iteration   3: 5.857 ops/ms
Iteration   1: 5.941 ops/ms
Iteration   2: 5.629 ops/ms
Iteration   3: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.805 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (5.629, 5.805, 5.941), stdev = 0.160
  CI (99.9%): [2.887, 8.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.496 ops/ms
# Warmup Iteration   2: 4.181 ops/ms
# Warmup Iteration   3: 5.362 ops/ms
Iteration   1: 5.123 ops/ms
Iteration   2: 5.340 ops/ms
Iteration   3: 5.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.265 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (5.123, 5.265, 5.340), stdev = 0.123
  CI (99.9%): [3.022, 7.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.807 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 6.510 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.017 ms/op
Iteration   1: 5.098 ±(99.9%) 0.012 ms/op
Iteration   2: 4.986 ±(99.9%) 0.016 ms/op
Iteration   3: 5.225 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.103 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (4.986, 5.103, 5.225), stdev = 0.119
  CI (99.9%): [2.923, 7.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.037 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.615 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.013 ms/op
Iteration   1: 4.902 ±(99.9%) 0.010 ms/op
Iteration   2: 4.842 ±(99.9%) 0.010 ms/op
Iteration   3: 4.833 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.859 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (4.833, 4.859, 4.902), stdev = 0.038
  CI (99.9%): [4.171, 5.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.602 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.103 ±(99.9%) 0.011 ms/op
Iteration   1: 5.142 ±(99.9%) 0.011 ms/op
Iteration   2: 5.324 ±(99.9%) 0.009 ms/op
Iteration   3: 4.990 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.152 ±(99.9%) 3.046 ms/op [Average]
  (min, avg, max) = (4.990, 5.152, 5.324), stdev = 0.167
  CI (99.9%): [2.106, 8.198] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.330 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 7.504 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.118 ±(99.9%) 0.011 ms/op
Iteration   1: 6.023 ±(99.9%) 0.013 ms/op
Iteration   2: 5.929 ±(99.9%) 0.013 ms/op
Iteration   3: 5.895 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.949 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (5.895, 5.949, 6.023), stdev = 0.066
  CI (99.9%): [4.739, 7.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.032 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.411 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.658 ±(99.9%) 0.025 ms/op
Iteration   1: 5.079 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   4.784 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 31.057 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   2: 4.916 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.529 ms/op
                 createUser·p0.999:  20.870 ms/op
                 createUser·p0.9999: 29.179 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 5.044 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   9.449 ms/op
                 createUser·p0.999:  23.649 ms/op
                 createUser·p0.9999: 26.258 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 191374
  mean =      5.012 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 126665 
    [ 5.000,  7.500) = 58797 
    [ 7.500, 10.000) = 4494 
    [10.000, 12.500) = 892 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     21.549 ms/op
     p(99.9900) =     29.515 ms/op
     p(99.9990) =     34.167 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.525 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.772 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.017 ms/op
Iteration   1: 5.023 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.250 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  19.233 ms/op
                 existUser·p0.9999: 29.444 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 4.863 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   4.547 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  16.998 ms/op
                 existUser·p0.9999: 25.713 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 4.930 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   7.078 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  19.116 ms/op
                 existUser·p0.9999: 26.591 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194261
  mean =      4.938 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 137447 
    [ 5.000,  7.500) = 49564 
    [ 7.500, 10.000) = 5117 
    [10.000, 12.500) = 1322 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =     10.148 ms/op
     p(99.9000) =     18.374 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.992 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.904 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.165 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.021 ms/op
Iteration   1: 5.402 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.636 ms/op
                 getUser·p0.95:   8.319 ms/op
                 getUser·p0.99:   11.913 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 25.955 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 5.365 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   11.730 ms/op
                 getUser·p0.999:  24.556 ms/op
                 getUser·p0.9999: 27.855 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 5.080 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.103 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   9.568 ms/op
                 getUser·p0.999:  25.037 ms/op
                 getUser·p0.9999: 31.087 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181767
  mean =      5.278 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 96842 
    [ 5.000,  7.500) = 75622 
    [ 7.500, 10.000) = 6436 
    [10.000, 12.500) = 1745 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 321 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     23.601 ms/op
     p(99.9900) =     29.680 ms/op
     p(99.9990) =     31.753 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.333 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.851 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.289 ±(99.9%) 0.030 ms/op
Iteration   1: 5.926 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  30.999 ms/op
                 listUser·p0.9999: 36.412 ms/op
                 listUser·p1.00:   37.028 ms/op

Iteration   2: 5.705 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.908 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  27.099 ms/op
                 listUser·p0.9999: 32.846 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   3: 5.928 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   11.642 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 23.367 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164054
  mean =      5.851 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 20616 
    [ 5.000,  7.500) = 133056 
    [ 7.500, 10.000) = 7139 
    [10.000, 12.500) = 2127 
    [12.500, 15.000) = 547 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     25.788 ms/op
     p(99.9900) =     35.205 ms/op
     p(99.9990) =     36.902 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.162 ± 4.734  ops/ms
ClientPb.existUser                       thrpt       3   6.358 ± 2.086  ops/ms
ClientPb.getUser                         thrpt       3   5.805 ± 2.918  ops/ms
ClientPb.listUser                        thrpt       3   5.265 ± 2.243  ops/ms
ClientPb.createUser                       avgt       3   5.103 ± 2.180   ms/op
ClientPb.existUser                        avgt       3   4.859 ± 0.688   ms/op
ClientPb.getUser                          avgt       3   5.152 ± 3.046   ms/op
ClientPb.listUser                         avgt       3   5.949 ± 1.210   ms/op
ClientPb.createUser                     sample  191374   5.012 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.752           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.454           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.549           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.515           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  194261   4.938 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.070           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.148           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.374           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.787           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  181767   5.278 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.411           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.537           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.601           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  164054   5.851 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.232           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.788           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.205           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.028           ms/op
