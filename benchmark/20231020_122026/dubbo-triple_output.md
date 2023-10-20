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
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 3.577 ops/ms
# Warmup Iteration   3: 7.203 ops/ms
Iteration   1: 7.053 ops/ms
Iteration   2: 7.323 ops/ms
Iteration   3: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.321 ±(99.9%) 4.870 ops/ms [Average]
  (min, avg, max) = (7.053, 7.321, 7.587), stdev = 0.267
  CI (99.9%): [2.451, 12.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 6.937 ops/ms
# Warmup Iteration   3: 8.060 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.103 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (8.045, 8.103, 8.183), stdev = 0.072
  CI (99.9%): [6.798, 9.408] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.861 ops/ms
# Warmup Iteration   2: 6.088 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.619 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.648 ±(99.9%) 4.007 ops/ms [Average]
  (min, avg, max) = (7.444, 7.648, 7.880), stdev = 0.220
  CI (99.9%): [3.640, 11.655] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 5.131 ops/ms
# Warmup Iteration   3: 6.526 ops/ms
Iteration   1: 6.244 ops/ms
Iteration   2: 6.340 ops/ms
Iteration   3: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.415 ±(99.9%) 3.982 ops/ms [Average]
  (min, avg, max) = (6.244, 6.415, 6.661), stdev = 0.218
  CI (99.9%): [2.433, 10.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.473 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.006 ms/op
Iteration   1: 4.119 ±(99.9%) 0.004 ms/op
Iteration   2: 4.133 ±(99.9%) 0.009 ms/op
Iteration   3: 4.363 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.205 ±(99.9%) 2.500 ms/op [Average]
  (min, avg, max) = (4.119, 4.205, 4.363), stdev = 0.137
  CI (99.9%): [1.705, 6.705] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.726 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.004 ms/op
Iteration   1: 3.957 ±(99.9%) 0.004 ms/op
Iteration   2: 3.974 ±(99.9%) 0.007 ms/op
Iteration   3: 3.806 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.912 ±(99.9%) 1.687 ms/op [Average]
  (min, avg, max) = (3.806, 3.912, 3.974), stdev = 0.092
  CI (99.9%): [2.225, 5.600] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.323 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.004 ms/op
Iteration   1: 4.316 ±(99.9%) 0.007 ms/op
Iteration   2: 4.109 ±(99.9%) 0.002 ms/op
Iteration   3: 4.220 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.215 ±(99.9%) 1.890 ms/op [Average]
  (min, avg, max) = (4.109, 4.215, 4.316), stdev = 0.104
  CI (99.9%): [2.325, 6.105] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.253 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.007 ms/op
Iteration   1: 4.795 ±(99.9%) 0.009 ms/op
Iteration   2: 4.884 ±(99.9%) 0.007 ms/op
Iteration   3: 4.838 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.839 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (4.795, 4.839, 4.884), stdev = 0.044
  CI (99.9%): [4.029, 5.649] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.657 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.704 ±(99.9%) 0.019 ms/op
Iteration   1: 4.288 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 26.694 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.000 ms/op
                 createUser·p0.999:  14.459 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 4.122 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  27.886 ms/op
                 createUser·p0.9999: 33.858 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231478
  mean =      4.148 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 523 
    [ 2.500,  5.000) = 211852 
    [ 5.000,  7.500) = 16571 
    [ 7.500, 10.000) = 1933 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     24.265 ms/op
     p(99.9900) =     32.449 ms/op
     p(99.9990) =     34.979 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.954 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.899 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.014 ms/op
Iteration   1: 4.121 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  16.450 ms/op
                 existUser·p0.9999: 24.944 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.939 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  25.756 ms/op
                 existUser·p0.9999: 28.380 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 4.144 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  17.662 ms/op
                 existUser·p0.9999: 32.318 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 234350
  mean =      4.095 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194 
    [ 2.500,  5.000) = 214804 
    [ 5.000,  7.500) = 14734 
    [ 7.500, 10.000) = 3580 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     31.068 ms/op
     p(99.9990) =     32.898 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 11.304 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.013 ms/op
Iteration   1: 4.338 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   6.537 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  23.013 ms/op
                 getUser·p0.9999: 25.449 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 4.145 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  24.642 ms/op
                 getUser·p0.9999: 28.904 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  26.592 ms/op
                 getUser·p0.9999: 31.687 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229388
  mean =      4.184 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 212626 
    [ 5.000,  7.500) = 13058 
    [ 7.500, 10.000) = 2790 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     32.517 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.304 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.088 ±(99.9%) 0.017 ms/op
Iteration   1: 4.992 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.615 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  23.559 ms/op
                 listUser·p0.9999: 26.011 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 5.010 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   9.076 ms/op
                 listUser·p0.999:  17.734 ms/op
                 listUser·p0.9999: 23.286 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.817 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194110
  mean =      4.938 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 136505 
    [ 5.000,  7.500) = 52354 
    [ 7.500, 10.000) = 3850 
    [10.000, 12.500) = 736 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     19.461 ms/op
     p(99.9900) =     25.054 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.321 ± 4.870  ops/ms
ClientPb.existUser                       thrpt       3   8.103 ± 1.305  ops/ms
ClientPb.getUser                         thrpt       3   7.648 ± 4.007  ops/ms
ClientPb.listUser                        thrpt       3   6.415 ± 3.982  ops/ms
ClientPb.createUser                       avgt       3   4.205 ± 2.500   ms/op
ClientPb.existUser                        avgt       3   3.912 ± 1.687   ms/op
ClientPb.getUser                          avgt       3   4.215 ± 1.890   ms/op
ClientPb.listUser                         avgt       3   4.839 ± 0.810   ms/op
ClientPb.createUser                     sample  231478   4.148 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.449           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  234350   4.095 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.282           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  229388   4.184 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.565           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670           ms/op
ClientPb.listUser                       sample  194110   4.938 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.615           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.461           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.054           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
