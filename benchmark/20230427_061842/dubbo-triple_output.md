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
# Warmup Iteration   1: 1.026 ops/ms
# Warmup Iteration   2: 2.228 ops/ms
# Warmup Iteration   3: 5.032 ops/ms
Iteration   1: 5.539 ops/ms
Iteration   2: 5.768 ops/ms
Iteration   3: 5.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.621 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (5.539, 5.621, 5.768), stdev = 0.128
  CI (99.9%): [3.289, 7.952] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.767 ops/ms
# Warmup Iteration   2: 5.363 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.230 ops/ms
Iteration   2: 6.373 ops/ms
Iteration   3: 6.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.369 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (6.230, 6.369, 6.504), stdev = 0.137
  CI (99.9%): [3.863, 8.875] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.495 ops/ms
# Warmup Iteration   2: 4.893 ops/ms
# Warmup Iteration   3: 6.119 ops/ms
Iteration   1: 5.964 ops/ms
Iteration   2: 5.975 ops/ms
Iteration   3: 5.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.961 ±(99.9%) 0.307 ops/ms [Average]
  (min, avg, max) = (5.942, 5.961, 5.975), stdev = 0.017
  CI (99.9%): [5.653, 6.268] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.366 ops/ms
# Warmup Iteration   2: 4.207 ops/ms
# Warmup Iteration   3: 4.982 ops/ms
Iteration   1: 5.254 ops/ms
Iteration   2: 5.126 ops/ms
Iteration   3: 5.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.155 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (5.085, 5.155, 5.254), stdev = 0.088
  CI (99.9%): [3.548, 6.762] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 20.517 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.705 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.445 ±(99.9%) 0.014 ms/op
Iteration   1: 5.513 ±(99.9%) 0.012 ms/op
Iteration   2: 5.292 ±(99.9%) 0.014 ms/op
Iteration   3: 5.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.392 ±(99.9%) 2.042 ms/op [Average]
  (min, avg, max) = (5.292, 5.392, 5.513), stdev = 0.112
  CI (99.9%): [3.351, 7.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.853 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.205 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.108 ±(99.9%) 0.011 ms/op
Iteration   1: 5.016 ±(99.9%) 0.013 ms/op
Iteration   2: 5.178 ±(99.9%) 0.015 ms/op
Iteration   3: 4.880 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.025 ±(99.9%) 2.722 ms/op [Average]
  (min, avg, max) = (4.880, 5.025, 5.178), stdev = 0.149
  CI (99.9%): [2.302, 7.747] (assumes normal distribution)


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
# Warmup Iteration   1: 16.930 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.428 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.097 ±(99.9%) 0.011 ms/op
Iteration   1: 5.197 ±(99.9%) 0.015 ms/op
Iteration   2: 4.987 ±(99.9%) 0.015 ms/op
Iteration   3: 5.128 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.104 ±(99.9%) 1.953 ms/op [Average]
  (min, avg, max) = (4.987, 5.104, 5.197), stdev = 0.107
  CI (99.9%): [3.151, 7.057] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.207 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 7.448 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.102 ±(99.9%) 0.016 ms/op
Iteration   1: 6.289 ±(99.9%) 0.018 ms/op
Iteration   2: 6.249 ±(99.9%) 0.010 ms/op
Iteration   3: 5.873 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.137 ±(99.9%) 4.189 ms/op [Average]
  (min, avg, max) = (5.873, 6.137, 6.289), stdev = 0.230
  CI (99.9%): [1.948, 10.326] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.895 ±(99.9%) 0.389 ms/op
# Warmup Iteration   2: 7.929 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.862 ±(99.9%) 0.030 ms/op
Iteration   1: 5.533 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.471 ms/op
                 createUser·p0.99:   11.518 ms/op
                 createUser·p0.999:  22.878 ms/op
                 createUser·p0.9999: 29.331 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 5.631 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  27.191 ms/op
                 createUser·p0.9999: 42.947 ms/op
                 createUser·p1.00:   43.123 ms/op

Iteration   3: 5.418 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  26.935 ms/op
                 createUser·p0.9999: 30.281 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173674
  mean =      5.526 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 79275 
    [ 5.000, 10.000) = 90949 
    [10.000, 15.000) = 2923 
    [15.000, 20.000) = 278 
    [20.000, 25.000) = 69 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.424 ms/op
     p(99.9000) =     26.028 ms/op
     p(99.9900) =     41.591 ms/op
     p(99.9990) =     43.074 ms/op
     p(99.9999) =     43.123 ms/op
    p(100.0000) =     43.123 ms/op


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
# Warmup Iteration   1: 18.122 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 5.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.101 ±(99.9%) 0.021 ms/op
Iteration   1: 5.102 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.966 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  22.708 ms/op
                 existUser·p0.9999: 34.651 ms/op
                 existUser·p1.00:   35.979 ms/op

Iteration   2: 5.016 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   9.208 ms/op
                 existUser·p0.999:  13.751 ms/op
                 existUser·p0.9999: 28.988 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 5.137 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.733 ms/op
                 existUser·p0.99:   10.240 ms/op
                 existUser·p0.999:  27.344 ms/op
                 existUser·p0.9999: 32.110 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188542
  mean =      5.085 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 116865 
    [ 5.000,  7.500) = 62643 
    [ 7.500, 10.000) = 7309 
    [10.000, 12.500) = 1114 
    [12.500, 15.000) = 354 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     15.793 ms/op
     p(99.9900) =     33.133 ms/op
     p(99.9990) =     35.457 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 16.644 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.105 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.426 ±(99.9%) 0.022 ms/op
Iteration   1: 5.395 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   14.385 ms/op
                 getUser·p0.999:  24.826 ms/op
                 getUser·p0.9999: 29.147 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   2: 5.916 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   8.700 ms/op
                 getUser·p0.95:   10.158 ms/op
                 getUser·p0.99:   13.238 ms/op
                 getUser·p0.999:  19.494 ms/op
                 getUser·p0.9999: 26.495 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 5.495 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   11.796 ms/op
                 getUser·p0.999:  22.976 ms/op
                 getUser·p0.9999: 28.841 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171722
  mean =      5.593 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 84964 
    [ 5.000,  7.500) = 68099 
    [ 7.500, 10.000) = 12528 
    [10.000, 12.500) = 4031 
    [12.500, 15.000) = 1129 
    [15.000, 17.500) = 551 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     13.042 ms/op
     p(99.9000) =     23.003 ms/op
     p(99.9900) =     28.863 ms/op
     p(99.9990) =     29.953 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 23.291 ±(99.9%) 0.378 ms/op
# Warmup Iteration   2: 7.307 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.363 ±(99.9%) 0.027 ms/op
Iteration   1: 6.344 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  27.477 ms/op
                 listUser·p0.9999: 39.365 ms/op
                 listUser·p1.00:   40.894 ms/op

Iteration   2: 6.134 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  26.673 ms/op
                 listUser·p0.9999: 29.582 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   3: 6.091 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  24.573 ms/op
                 listUser·p0.9999: 28.156 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155236
  mean =      6.188 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11133 
    [ 5.000, 10.000) = 139830 
    [10.000, 15.000) = 3667 
    [15.000, 20.000) = 300 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 195 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     26.280 ms/op
     p(99.9900) =     37.908 ms/op
     p(99.9990) =     40.388 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.621 ± 2.331  ops/ms
ClientPb.existUser                       thrpt       3   6.369 ± 2.506  ops/ms
ClientPb.getUser                         thrpt       3   5.961 ± 0.307  ops/ms
ClientPb.listUser                        thrpt       3   5.155 ± 1.607  ops/ms
ClientPb.createUser                       avgt       3   5.392 ± 2.042   ms/op
ClientPb.existUser                        avgt       3   5.025 ± 2.722   ms/op
ClientPb.getUser                          avgt       3   5.104 ± 1.953   ms/op
ClientPb.listUser                         avgt       3   6.137 ± 4.189   ms/op
ClientPb.createUser                     sample  173674   5.526 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.991           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.405           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.424           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.591           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.123           ms/op
ClientPb.existUser                      sample  188542   5.085 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.406           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.979           ms/op
ClientPb.getUser                        sample  171722   5.593 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.902           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.042           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.003           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.863           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  155236   6.188 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.288           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.280           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.908           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.894           ms/op
