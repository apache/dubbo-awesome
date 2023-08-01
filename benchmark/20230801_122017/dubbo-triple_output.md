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
# Warmup Iteration   1: 1.296 ops/ms
# Warmup Iteration   2: 2.625 ops/ms
# Warmup Iteration   3: 5.658 ops/ms
Iteration   1: 5.946 ops/ms
Iteration   2: 5.999 ops/ms
Iteration   3: 6.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.099 ±(99.9%) 4.023 ops/ms [Average]
  (min, avg, max) = (5.946, 6.099, 6.352), stdev = 0.220
  CI (99.9%): [2.076, 10.122] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.916 ops/ms
# Warmup Iteration   2: 5.354 ops/ms
# Warmup Iteration   3: 6.204 ops/ms
Iteration   1: 6.827 ops/ms
Iteration   2: 6.507 ops/ms
Iteration   3: 6.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.681 ±(99.9%) 2.955 ops/ms [Average]
  (min, avg, max) = (6.507, 6.681, 6.827), stdev = 0.162
  CI (99.9%): [3.726, 9.635] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.902 ops/ms
# Warmup Iteration   2: 5.503 ops/ms
# Warmup Iteration   3: 6.267 ops/ms
Iteration   1: 6.202 ops/ms
Iteration   2: 6.464 ops/ms
Iteration   3: 6.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.278 ±(99.9%) 2.959 ops/ms [Average]
  (min, avg, max) = (6.168, 6.278, 6.464), stdev = 0.162
  CI (99.9%): [3.319, 9.237] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 4.618 ops/ms
# Warmup Iteration   3: 5.131 ops/ms
Iteration   1: 5.413 ops/ms
Iteration   2: 5.257 ops/ms
Iteration   3: 5.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.324 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (5.257, 5.324, 5.413), stdev = 0.080
  CI (99.9%): [3.863, 6.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.186 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.125 ±(99.9%) 0.013 ms/op
Iteration   1: 5.147 ±(99.9%) 0.008 ms/op
Iteration   2: 5.135 ±(99.9%) 0.011 ms/op
Iteration   3: 5.051 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.111 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (5.051, 5.111, 5.147), stdev = 0.052
  CI (99.9%): [4.163, 6.059] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 13.748 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.012 ms/op
Iteration   1: 4.942 ±(99.9%) 0.004 ms/op
Iteration   2: 5.008 ±(99.9%) 0.008 ms/op
Iteration   3: 5.066 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.005 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.942, 5.005, 5.066), stdev = 0.062
  CI (99.9%): [3.870, 6.140] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 16.840 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.501 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.308 ±(99.9%) 0.009 ms/op
Iteration   1: 5.320 ±(99.9%) 0.007 ms/op
Iteration   2: 5.190 ±(99.9%) 0.006 ms/op
Iteration   3: 5.222 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.244 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (5.190, 5.244, 5.320), stdev = 0.068
  CI (99.9%): [4.011, 6.477] (assumes normal distribution)


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
# Warmup Iteration   1: 17.155 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.714 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.955 ±(99.9%) 0.007 ms/op
Iteration   1: 5.940 ±(99.9%) 0.015 ms/op
Iteration   2: 5.764 ±(99.9%) 0.007 ms/op
Iteration   3: 5.819 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.841 ±(99.9%) 1.639 ms/op [Average]
  (min, avg, max) = (5.764, 5.841, 5.940), stdev = 0.090
  CI (99.9%): [4.202, 7.480] (assumes normal distribution)


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
# Warmup Iteration   1: 16.198 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.459 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.024 ms/op
Iteration   1: 5.300 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   10.239 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 27.600 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 5.262 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.833 ms/op
                 createUser·p0.999:  24.150 ms/op
                 createUser·p0.9999: 27.686 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 5.348 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  27.865 ms/op
                 createUser·p0.9999: 31.229 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180998
  mean =      5.303 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 86391 
    [ 5.000,  7.500) = 84921 
    [ 7.500, 10.000) = 7230 
    [10.000, 12.500) = 1643 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     29.783 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 15.737 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 5.717 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.020 ms/op
Iteration   1: 5.043 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   10.238 ms/op
                 existUser·p0.999:  24.912 ms/op
                 existUser·p0.9999: 28.799 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   2: 4.908 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   6.406 ms/op
                 existUser·p0.99:   9.660 ms/op
                 existUser·p0.999:  23.097 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 4.852 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 31.844 ms/op
                 existUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194499
  mean =      4.933 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 120577 
    [ 5.000,  7.500) = 68267 
    [ 7.500, 10.000) = 3999 
    [10.000, 12.500) = 904 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     30.884 ms/op
     p(99.9990) =     32.105 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 16.732 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.797 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.320 ±(99.9%) 0.021 ms/op
Iteration   1: 5.303 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   11.600 ms/op
                 getUser·p0.999:  23.284 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   2: 5.183 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.134 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  27.372 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 5.225 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.562 ms/op
                 getUser·p0.95:   7.299 ms/op
                 getUser·p0.99:   10.191 ms/op
                 getUser·p0.999:  23.316 ms/op
                 getUser·p0.9999: 29.934 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183132
  mean =      5.236 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 90554 
    [ 5.000,  7.500) = 83809 
    [ 7.500, 10.000) = 6411 
    [10.000, 12.500) = 1678 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     23.326 ms/op
     p(99.9900) =     31.283 ms/op
     p(99.9990) =     34.636 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 17.959 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.163 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.037 ±(99.9%) 0.025 ms/op
Iteration   1: 6.010 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  24.805 ms/op
                 listUser·p0.9999: 27.537 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 5.829 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 33.118 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 6.026 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   12.110 ms/op
                 listUser·p0.999:  20.409 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161226
  mean =      5.953 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 33174 
    [ 5.000,  7.500) = 114837 
    [ 7.500, 10.000) = 9590 
    [10.000, 12.500) = 2403 
    [12.500, 15.000) = 717 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      5.677 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     23.651 ms/op
     p(99.9900) =     31.285 ms/op
     p(99.9990) =     33.747 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.099 ± 4.023  ops/ms
ClientPb.existUser                       thrpt       3   6.681 ± 2.955  ops/ms
ClientPb.getUser                         thrpt       3   6.278 ± 2.959  ops/ms
ClientPb.listUser                        thrpt       3   5.324 ± 1.461  ops/ms
ClientPb.createUser                       avgt       3   5.111 ± 0.948   ms/op
ClientPb.existUser                        avgt       3   5.005 ± 1.135   ms/op
ClientPb.getUser                          avgt       3   5.244 ± 1.233   ms/op
ClientPb.listUser                         avgt       3   5.841 ± 1.639   ms/op
ClientPb.createUser                     sample  180998   5.303 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.073           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.578           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.600           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.719           ms/op
ClientPb.existUser                      sample  194499   4.933 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.634           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.970           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  183132   5.236 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.489           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.535           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.326           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.283           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  161226   5.953 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.636           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.796           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.651           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.948           ms/op
