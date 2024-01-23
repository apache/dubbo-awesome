# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 9.406 ops/ms
# Warmup Iteration   3: 9.525 ops/ms
Iteration   1: 8.620 ops/ms
Iteration   2: 8.532 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.876 ±(99.9%) 9.518 ops/ms [Average]
  (min, avg, max) = (8.532, 8.876, 9.476), stdev = 0.522
  CI (99.9%): [≈ 0, 18.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.882 ops/ms
# Warmup Iteration   2: 10.246 ops/ms
# Warmup Iteration   3: 10.034 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.010 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (9.787, 10.010, 10.150), stdev = 0.195
  CI (99.9%): [6.448, 13.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ops/ms
# Warmup Iteration   2: 9.486 ops/ms
# Warmup Iteration   3: 8.941 ops/ms
Iteration   1: 8.533 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.476 ±(99.9%) 15.012 ops/ms [Average]
  (min, avg, max) = (8.533, 9.476, 10.045), stdev = 0.823
  CI (99.9%): [≈ 0, 24.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ops/ms
# Warmup Iteration   2: 7.861 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.106 ops/ms
Iteration   3: 7.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.963 ±(99.9%) 4.369 ops/ms [Average]
  (min, avg, max) = (7.687, 7.963, 8.106), stdev = 0.240
  CI (99.9%): [3.594, 12.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.664 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.015 ms/op
Iteration   1: 3.261 ±(99.9%) 0.008 ms/op
Iteration   2: 3.410 ±(99.9%) 0.017 ms/op
Iteration   3: 3.609 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.427 ±(99.9%) 3.182 ms/op [Average]
  (min, avg, max) = (3.261, 3.427, 3.609), stdev = 0.174
  CI (99.9%): [0.244, 6.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.319 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
Iteration   1: 3.214 ±(99.9%) 0.011 ms/op
Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
Iteration   3: 3.061 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.126 ±(99.9%) 1.441 ms/op [Average]
  (min, avg, max) = (3.061, 3.126, 3.214), stdev = 0.079
  CI (99.9%): [1.684, 4.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.012 ms/op
Iteration   1: 3.315 ±(99.9%) 0.011 ms/op
Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
Iteration   3: 3.210 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.261 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.210, 3.261, 3.315), stdev = 0.053
  CI (99.9%): [2.298, 4.223] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.623 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.017 ms/op
Iteration   1: 3.963 ±(99.9%) 0.010 ms/op
Iteration   2: 4.306 ±(99.9%) 0.016 ms/op
Iteration   3: 4.102 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.124 ±(99.9%) 3.151 ms/op [Average]
  (min, avg, max) = (3.963, 4.124, 4.306), stdev = 0.173
  CI (99.9%): [0.973, 7.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.649 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.021 ms/op
Iteration   1: 3.261 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  15.302 ms/op
                 createUser·p0.9999: 22.682 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.304 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   6.055 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  17.662 ms/op
                 createUser·p0.9999: 25.865 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.416 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.372 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   9.045 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 20.632 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288289
  mean =      3.326 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83951 
    [ 2.500,  5.000) = 176191 
    [ 5.000,  7.500) = 20977 
    [ 7.500, 10.000) = 5813 
    [10.000, 12.500) = 914 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     15.965 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.131 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.016 ms/op
Iteration   1: 3.347 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.378 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   6.644 ms/op
                 existUser·p0.99:   9.912 ms/op
                 existUser·p0.999:  18.055 ms/op
                 existUser·p0.9999: 23.706 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.602 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   7.102 ms/op
                 existUser·p0.99:   9.707 ms/op
                 existUser·p0.999:  21.955 ms/op
                 existUser·p0.9999: 25.956 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.542 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.353 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.955 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  14.759 ms/op
                 existUser·p0.9999: 19.429 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274669
  mean =      3.494 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77990 
    [ 2.500,  5.000) = 159346 
    [ 5.000,  7.500) = 27218 
    [ 7.500, 10.000) = 7806 
    [10.000, 12.500) = 1577 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     17.902 ms/op
     p(99.9900) =     25.509 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.141 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.018 ms/op
Iteration   1: 3.511 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   6.758 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  15.825 ms/op
                 getUser·p0.9999: 37.348 ms/op
                 getUser·p1.00:   38.863 ms/op

Iteration   2: 3.436 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  19.721 ms/op
                 getUser·p0.9999: 33.096 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   3: 3.224 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.392 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  15.336 ms/op
                 getUser·p0.9999: 21.796 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283308
  mean =      3.386 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80812 
    [ 2.500,  5.000) = 171715 
    [ 5.000,  7.500) = 22797 
    [ 7.500, 10.000) = 6169 
    [10.000, 12.500) = 1291 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     15.838 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     38.415 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.966 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.022 ms/op
Iteration   1: 4.030 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  18.720 ms/op
                 listUser·p0.9999: 27.920 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   2: 4.578 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.403 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  18.257 ms/op
                 listUser·p0.9999: 25.174 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   3: 4.519 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.407 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  17.902 ms/op
                 listUser·p0.9999: 25.388 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 219959
  mean =      4.361 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22302 
    [ 2.500,  5.000) = 140487 
    [ 5.000,  7.500) = 39808 
    [ 7.500, 10.000) = 12534 
    [10.000, 12.500) = 3390 
    [12.500, 15.000) = 837 
    [15.000, 17.500) = 319 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     18.351 ms/op
     p(99.9900) =     27.330 ms/op
     p(99.9990) =     28.489 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.876 ±  9.518  ops/ms
ClientPb.existUser                       thrpt       3  10.010 ±  3.562  ops/ms
ClientPb.getUser                         thrpt       3   9.476 ± 15.012  ops/ms
ClientPb.listUser                        thrpt       3   7.963 ±  4.369  ops/ms
ClientPb.createUser                       avgt       3   3.427 ±  3.182   ms/op
ClientPb.existUser                        avgt       3   3.126 ±  1.441   ms/op
ClientPb.getUser                          avgt       3   3.261 ±  0.962   ms/op
ClientPb.listUser                         avgt       3   4.124 ±  3.151   ms/op
ClientPb.createUser                     sample  288289   3.326 ±  0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.368            ms/op
ClientPb.createUser:createUser·p0.50    sample           2.966            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.964            ms/op
ClientPb.createUser:createUser·p0.95    sample           6.160            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.847            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.965            ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.969            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.280            ms/op
ClientPb.existUser                      sample  274669   3.494 ±  0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.353            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.579            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.922            ms/op
ClientPb.existUser:existUser·p0.99      sample           9.732            ms/op
ClientPb.existUser:existUser·p0.999     sample          17.902            ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.509            ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197            ms/op
ClientPb.getUser                        sample  283308   3.386 ±  0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.372            ms/op
ClientPb.getUser:getUser·p0.50          sample           2.986            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.153            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.439            ms/op
ClientPb.getUser:getUser·p0.99          sample           9.241            ms/op
ClientPb.getUser:getUser·p0.999         sample          15.838            ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.586            ms/op
ClientPb.getUser:getUser·p1.00          sample          38.863            ms/op
ClientPb.listUser                       sample  219959   4.361 ±  0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.403            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797            ms/op
ClientPb.listUser:listUser·p0.90        sample           6.988            ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454            ms/op
ClientPb.listUser:listUser·p0.99        sample          11.534            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.351            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.330            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.541            ms/op
