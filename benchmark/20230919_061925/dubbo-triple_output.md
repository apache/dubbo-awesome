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
# Warmup Iteration   1: 1.570 ops/ms
# Warmup Iteration   2: 3.413 ops/ms
# Warmup Iteration   3: 6.670 ops/ms
Iteration   1: 7.015 ops/ms
Iteration   2: 7.729 ops/ms
Iteration   3: 7.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.470 ±(99.9%) 7.220 ops/ms [Average]
  (min, avg, max) = (7.015, 7.470, 7.729), stdev = 0.396
  CI (99.9%): [0.250, 14.690] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 6.824 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.071 ±(99.9%) 5.585 ops/ms [Average]
  (min, avg, max) = (7.863, 8.071, 8.422), stdev = 0.306
  CI (99.9%): [2.485, 13.656] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.274 ops/ms
# Warmup Iteration   2: 6.086 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 7.609 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.742 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (7.609, 7.742, 7.831), stdev = 0.117
  CI (99.9%): [5.610, 9.873] (assumes normal distribution)


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
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 4.985 ops/ms
# Warmup Iteration   3: 6.339 ops/ms
Iteration   1: 6.312 ops/ms
Iteration   2: 6.513 ops/ms
Iteration   3: 6.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.439 ±(99.9%) 2.010 ops/ms [Average]
  (min, avg, max) = (6.312, 6.439, 6.513), stdev = 0.110
  CI (99.9%): [4.429, 8.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.675 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.553 ±(99.9%) 0.006 ms/op
Iteration   1: 4.143 ±(99.9%) 0.004 ms/op
Iteration   2: 4.153 ±(99.9%) 0.007 ms/op
Iteration   3: 4.234 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.177 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (4.143, 4.177, 4.234), stdev = 0.050
  CI (99.9%): [3.272, 5.082] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.282 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.009 ms/op
Iteration   1: 3.935 ±(99.9%) 0.004 ms/op
Iteration   2: 4.148 ±(99.9%) 0.008 ms/op
Iteration   3: 4.095 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.059 ±(99.9%) 2.026 ms/op [Average]
  (min, avg, max) = (3.935, 4.059, 4.148), stdev = 0.111
  CI (99.9%): [2.034, 6.085] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.367 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.928 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.004 ms/op
Iteration   1: 4.207 ±(99.9%) 0.004 ms/op
Iteration   2: 4.000 ±(99.9%) 0.005 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.074 ±(99.9%) 2.109 ms/op [Average]
  (min, avg, max) = (4.000, 4.074, 4.207), stdev = 0.116
  CI (99.9%): [1.965, 6.182] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.632 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.810 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.004 ±(99.9%) 0.007 ms/op
Iteration   1: 4.846 ±(99.9%) 0.010 ms/op
Iteration   2: 4.921 ±(99.9%) 0.009 ms/op
Iteration   3: 4.960 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.909 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (4.846, 4.909, 4.960), stdev = 0.058
  CI (99.9%): [3.854, 5.964] (assumes normal distribution)


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
# Warmup Iteration   1: 14.059 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.021 ms/op
Iteration   1: 4.461 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  20.021 ms/op
                 createUser·p0.9999: 26.045 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 4.218 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.933 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  26.450 ms/op
                 createUser·p0.9999: 37.148 ms/op
                 createUser·p1.00:   39.780 ms/op

Iteration   3: 4.259 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  25.061 ms/op
                 createUser·p0.9999: 31.982 ms/op
                 createUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222673
  mean =      4.310 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 195814 
    [ 5.000,  7.500) = 20499 
    [ 7.500, 10.000) = 4030 
    [10.000, 12.500) = 1086 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      9.589 ms/op
     p(99.9000) =     23.975 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     38.985 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 12.396 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.014 ms/op
Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   6.431 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  14.813 ms/op
                 existUser·p0.9999: 24.384 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 4.050 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   8.233 ms/op
                 existUser·p0.999:  19.589 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 4.117 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   7.635 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 29.237 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235118
  mean =      4.082 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 419 
    [ 2.500,  5.000) = 213666 
    [ 5.000,  7.500) = 16760 
    [ 7.500, 10.000) = 3227 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     16.524 ms/op
     p(99.9900) =     27.786 ms/op
     p(99.9990) =     29.543 ms/op
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
# Warmup Iteration   1: 14.337 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.016 ms/op
Iteration   1: 4.175 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   9.257 ms/op
                 getUser·p0.999:  23.915 ms/op
                 getUser·p0.9999: 26.652 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 4.184 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  14.285 ms/op
                 getUser·p0.9999: 28.941 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 4.150 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   8.263 ms/op
                 getUser·p0.999:  13.996 ms/op
                 getUser·p0.9999: 31.228 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230062
  mean =      4.170 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 209846 
    [ 5.000,  7.500) = 16113 
    [ 7.500, 10.000) = 2764 
    [10.000, 12.500) = 816 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     17.459 ms/op
     p(99.9900) =     30.703 ms/op
     p(99.9990) =     31.415 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 13.526 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.218 ±(99.9%) 0.022 ms/op
Iteration   1: 4.933 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   9.900 ms/op
                 listUser·p0.999:  24.223 ms/op
                 listUser·p0.9999: 26.511 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.883 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.627 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  21.156 ms/op
                 listUser·p0.9999: 24.883 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.960 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  17.763 ms/op
                 listUser·p0.9999: 20.615 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194687
  mean =      4.925 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 146451 
    [ 5.000,  7.500) = 41172 
    [ 7.500, 10.000) = 5426 
    [10.000, 12.500) = 721 
    [12.500, 15.000) = 375 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.837 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.470 ± 7.220  ops/ms
ClientPb.existUser                       thrpt       3   8.071 ± 5.585  ops/ms
ClientPb.getUser                         thrpt       3   7.742 ± 2.131  ops/ms
ClientPb.listUser                        thrpt       3   6.439 ± 2.010  ops/ms
ClientPb.createUser                       avgt       3   4.177 ± 0.905   ms/op
ClientPb.existUser                        avgt       3   4.059 ± 2.026   ms/op
ClientPb.getUser                          avgt       3   4.074 ± 2.109   ms/op
ClientPb.listUser                         avgt       3   4.909 ± 1.055   ms/op
ClientPb.createUser                     sample  222673   4.310 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.568           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.589           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.162           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.780           ms/op
ClientPb.existUser                      sample  235118   4.082 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.282           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.524           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.786           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  230062   4.170 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.651           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.459           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.703           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  194687   4.925 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.837           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.201           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
