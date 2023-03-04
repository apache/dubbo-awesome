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
# Warmup Iteration   1: 1.192 ops/ms
# Warmup Iteration   2: 3.264 ops/ms
# Warmup Iteration   3: 5.594 ops/ms
Iteration   1: 5.476 ops/ms
Iteration   2: 6.104 ops/ms
Iteration   3: 5.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.837 ±(99.9%) 5.923 ops/ms [Average]
  (min, avg, max) = (5.476, 5.837, 6.104), stdev = 0.325
  CI (99.9%): [≈ 0, 11.760] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.659 ops/ms
# Warmup Iteration   2: 5.222 ops/ms
# Warmup Iteration   3: 6.200 ops/ms
Iteration   1: 6.427 ops/ms
Iteration   2: 6.483 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.451 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (6.427, 6.451, 6.483), stdev = 0.029
  CI (99.9%): [5.926, 6.977] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.856 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 6.072 ops/ms
Iteration   1: 5.985 ops/ms
Iteration   2: 6.359 ops/ms
Iteration   3: 6.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.154 ±(99.9%) 3.455 ops/ms [Average]
  (min, avg, max) = (5.985, 6.154, 6.359), stdev = 0.189
  CI (99.9%): [2.699, 9.610] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.680 ops/ms
# Warmup Iteration   2: 4.336 ops/ms
# Warmup Iteration   3: 5.593 ops/ms
Iteration   1: 5.290 ops/ms
Iteration   2: 5.237 ops/ms
Iteration   3: 5.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.305 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (5.237, 5.305, 5.389), stdev = 0.077
  CI (99.9%): [3.900, 6.710] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.180 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.169 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.634 ±(99.9%) 0.009 ms/op
Iteration   1: 5.521 ±(99.9%) 0.014 ms/op
Iteration   2: 5.112 ±(99.9%) 0.015 ms/op
Iteration   3: 5.136 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.256 ±(99.9%) 4.183 ms/op [Average]
  (min, avg, max) = (5.112, 5.256, 5.521), stdev = 0.229
  CI (99.9%): [1.073, 9.440] (assumes normal distribution)


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
# Warmup Iteration   1: 14.754 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.565 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.009 ms/op
Iteration   1: 5.110 ±(99.9%) 0.009 ms/op
Iteration   2: 4.928 ±(99.9%) 0.014 ms/op
Iteration   3: 5.094 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.044 ±(99.9%) 1.843 ms/op [Average]
  (min, avg, max) = (4.928, 5.044, 5.110), stdev = 0.101
  CI (99.9%): [3.201, 6.887] (assumes normal distribution)


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
# Warmup Iteration   1: 15.088 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.780 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.011 ms/op
Iteration   1: 5.151 ±(99.9%) 0.009 ms/op
Iteration   2: 5.246 ±(99.9%) 0.013 ms/op
Iteration   3: 5.580 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.326 ±(99.9%) 4.112 ms/op [Average]
  (min, avg, max) = (5.151, 5.326, 5.580), stdev = 0.225
  CI (99.9%): [1.213, 9.438] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.791 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.200 ±(99.9%) 0.020 ms/op
Iteration   1: 6.162 ±(99.9%) 0.008 ms/op
Iteration   2: 6.211 ±(99.9%) 0.011 ms/op
Iteration   3: 6.097 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.157 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (6.097, 6.157, 6.211), stdev = 0.057
  CI (99.9%): [5.118, 7.196] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.348 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.398 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.022 ms/op
Iteration   1: 5.155 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.127 ms/op
                 createUser·p0.99:   10.313 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 25.087 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 5.595 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.898 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.947 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 27.399 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 5.339 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.082 ms/op
                 createUser·p0.999:  25.199 ms/op
                 createUser·p0.9999: 30.147 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178997
  mean =      5.357 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 82097 
    [ 5.000,  7.500) = 87518 
    [ 7.500, 10.000) = 7116 
    [10.000, 12.500) = 1476 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     29.236 ms/op
     p(99.9990) =     30.915 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.310 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.020 ms/op
Iteration   1: 5.417 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.966 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   10.827 ms/op
                 existUser·p0.999:  21.594 ms/op
                 existUser·p0.9999: 26.948 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   2: 5.076 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.930 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  23.791 ms/op
                 existUser·p0.9999: 28.348 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 5.032 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  23.508 ms/op
                 existUser·p0.9999: 28.890 ms/op
                 existUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185600
  mean =      5.169 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 103561 
    [ 5.000,  7.500) = 73302 
    [ 7.500, 10.000) = 6604 
    [10.000, 12.500) = 1430 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     23.213 ms/op
     p(99.9900) =     28.392 ms/op
     p(99.9990) =     29.894 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 15.921 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.681 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.774 ±(99.9%) 0.026 ms/op
Iteration   1: 5.317 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.717 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  21.975 ms/op
                 getUser·p0.9999: 25.483 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 5.429 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   10.325 ms/op
                 getUser·p0.999:  22.712 ms/op
                 getUser·p0.9999: 25.399 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 5.316 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   10.551 ms/op
                 getUser·p0.999:  23.548 ms/op
                 getUser·p0.9999: 30.014 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179245
  mean =      5.353 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 85932 
    [ 5.000,  7.500) = 83052 
    [ 7.500, 10.000) = 8119 
    [10.000, 12.500) = 1319 
    [12.500, 15.000) = 413 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     22.209 ms/op
     p(99.9900) =     28.516 ms/op
     p(99.9990) =     30.785 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 18.416 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.292 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.336 ±(99.9%) 0.024 ms/op
Iteration   1: 6.217 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  25.938 ms/op
                 listUser·p0.9999: 27.815 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 5.970 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.183 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  25.639 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 6.271 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  19.367 ms/op
                 listUser·p0.9999: 24.658 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155981
  mean =      6.150 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 24944 
    [ 5.000,  7.500) = 112620 
    [ 7.500, 10.000) = 15761 
    [10.000, 12.500) = 1810 
    [12.500, 15.000) = 406 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 147 

  Percentiles, ms/op:
      p(0.0000) =      1.962 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     27.604 ms/op
     p(99.9990) =     28.064 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.837 ± 5.923  ops/ms
ClientPb.existUser                       thrpt       3   6.451 ± 0.525  ops/ms
ClientPb.getUser                         thrpt       3   6.154 ± 3.455  ops/ms
ClientPb.listUser                        thrpt       3   5.305 ± 1.405  ops/ms
ClientPb.createUser                       avgt       3   5.256 ± 4.183   ms/op
ClientPb.existUser                        avgt       3   5.044 ± 1.843   ms/op
ClientPb.getUser                          avgt       3   5.326 ± 4.112   ms/op
ClientPb.listUser                         avgt       3   6.157 ± 1.039   ms/op
ClientPb.createUser                     sample  178997   5.357 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.477           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  185600   5.169 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.778           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.406           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.213           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.950           ms/op
ClientPb.getUser                        sample  179245   5.353 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.355           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.209           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.516           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  155981   6.150 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.962           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.076           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.166           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.604           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
