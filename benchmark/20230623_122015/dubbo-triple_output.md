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
# Warmup Iteration   1: 0.936 ops/ms
# Warmup Iteration   2: 1.895 ops/ms
# Warmup Iteration   3: 4.339 ops/ms
Iteration   1: 5.110 ops/ms
Iteration   2: 5.057 ops/ms
Iteration   3: 5.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.120 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (5.057, 5.120, 5.193), stdev = 0.068
  CI (99.9%): [3.876, 6.364] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.459 ops/ms
# Warmup Iteration   2: 3.999 ops/ms
# Warmup Iteration   3: 5.252 ops/ms
Iteration   1: 5.383 ops/ms
Iteration   2: 5.527 ops/ms
Iteration   3: 5.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.510 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (5.383, 5.510, 5.620), stdev = 0.119
  CI (99.9%): [3.331, 7.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.353 ops/ms
# Warmup Iteration   2: 3.554 ops/ms
# Warmup Iteration   3: 5.080 ops/ms
Iteration   1: 5.264 ops/ms
Iteration   2: 5.081 ops/ms
Iteration   3: 5.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.192 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (5.081, 5.192, 5.264), stdev = 0.097
  CI (99.9%): [3.415, 6.969] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.294 ops/ms
# Warmup Iteration   2: 3.075 ops/ms
# Warmup Iteration   3: 4.402 ops/ms
Iteration   1: 4.408 ops/ms
Iteration   2: 4.472 ops/ms
Iteration   3: 4.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.473 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (4.408, 4.473, 4.538), stdev = 0.065
  CI (99.9%): [3.287, 5.658] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.420 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.446 ±(99.9%) 0.008 ms/op
Iteration   1: 6.258 ±(99.9%) 0.012 ms/op
Iteration   2: 6.314 ±(99.9%) 0.012 ms/op
Iteration   3: 6.021 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.198 ±(99.9%) 2.839 ms/op [Average]
  (min, avg, max) = (6.021, 6.198, 6.314), stdev = 0.156
  CI (99.9%): [3.359, 9.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.508 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 6.710 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.077 ±(99.9%) 0.010 ms/op
Iteration   1: 5.875 ±(99.9%) 0.009 ms/op
Iteration   2: 5.650 ±(99.9%) 0.015 ms/op
Iteration   3: 5.583 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.703 ±(99.9%) 2.791 ms/op [Average]
  (min, avg, max) = (5.583, 5.703, 5.875), stdev = 0.153
  CI (99.9%): [2.912, 8.494] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 22.493 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 7.523 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.265 ±(99.9%) 0.012 ms/op
Iteration   1: 6.264 ±(99.9%) 0.015 ms/op
Iteration   2: 6.129 ±(99.9%) 0.009 ms/op
Iteration   3: 6.193 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.195 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (6.129, 6.195, 6.264), stdev = 0.068
  CI (99.9%): [4.962, 7.429] (assumes normal distribution)


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
# Warmup Iteration   1: 21.799 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 9.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.245 ±(99.9%) 0.018 ms/op
Iteration   1: 7.504 ±(99.9%) 0.014 ms/op
Iteration   2: 6.968 ±(99.9%) 0.018 ms/op
Iteration   3: 7.099 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.191 ±(99.9%) 5.096 ms/op [Average]
  (min, avg, max) = (6.968, 7.191, 7.504), stdev = 0.279
  CI (99.9%): [2.095, 12.287] (assumes normal distribution)


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
# Warmup Iteration   1: 22.073 ±(99.9%) 0.392 ms/op
# Warmup Iteration   2: 8.428 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 6.701 ±(99.9%) 0.034 ms/op
Iteration   1: 6.191 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   5.759 ms/op
                 createUser·p0.90:   7.987 ms/op
                 createUser·p0.95:   9.028 ms/op
                 createUser·p0.99:   12.258 ms/op
                 createUser·p0.999:  27.675 ms/op
                 createUser·p0.9999: 32.757 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   2: 6.278 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.499 ms/op
                 createUser·p0.50:   5.874 ms/op
                 createUser·p0.90:   8.012 ms/op
                 createUser·p0.95:   9.175 ms/op
                 createUser·p0.99:   13.063 ms/op
                 createUser·p0.999:  29.263 ms/op
                 createUser·p0.9999: 37.939 ms/op
                 createUser·p1.00:   40.108 ms/op

Iteration   3: 6.233 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.825 ms/op
                 createUser·p0.90:   7.913 ms/op
                 createUser·p0.95:   9.142 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  22.535 ms/op
                 createUser·p0.9999: 37.478 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 153944
  mean =      6.234 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 20127 
    [ 5.000, 10.000) = 129190 
    [10.000, 15.000) = 3953 
    [15.000, 20.000) = 418 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 49 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 58 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      7.971 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     27.791 ms/op
     p(99.9900) =     37.461 ms/op
     p(99.9990) =     39.507 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 20.276 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 7.841 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.997 ±(99.9%) 0.025 ms/op
Iteration   1: 5.857 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.560 ms/op
                 existUser·p0.50:   5.399 ms/op
                 existUser·p0.90:   7.733 ms/op
                 existUser·p0.95:   8.995 ms/op
                 existUser·p0.99:   11.846 ms/op
                 existUser·p0.999:  27.439 ms/op
                 existUser·p0.9999: 31.034 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   2: 5.816 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.448 ms/op
                 existUser·p0.90:   7.373 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.449 ms/op
                 existUser·p0.999:  16.217 ms/op
                 existUser·p0.9999: 29.311 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 5.980 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   5.595 ms/op
                 existUser·p0.90:   7.700 ms/op
                 existUser·p0.95:   8.782 ms/op
                 existUser·p0.99:   11.493 ms/op
                 existUser·p0.999:  33.715 ms/op
                 existUser·p0.9999: 37.178 ms/op
                 existUser·p1.00:   41.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163211
  mean =      5.883 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 43409 
    [ 5.000, 10.000) = 115771 
    [10.000, 15.000) = 3646 
    [15.000, 20.000) = 225 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     19.776 ms/op
     p(99.9900) =     36.351 ms/op
     p(99.9990) =     39.219 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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
# Warmup Iteration   1: 21.069 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.792 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.422 ±(99.9%) 0.028 ms/op
Iteration   1: 6.248 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.798 ms/op
                 getUser·p0.50:   5.898 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   9.273 ms/op
                 getUser·p0.99:   11.960 ms/op
                 getUser·p0.999:  23.554 ms/op
                 getUser·p0.9999: 27.691 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 6.317 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.945 ms/op
                 getUser·p0.50:   5.825 ms/op
                 getUser·p0.90:   8.372 ms/op
                 getUser·p0.95:   9.896 ms/op
                 getUser·p0.99:   13.713 ms/op
                 getUser·p0.999:  27.472 ms/op
                 getUser·p0.9999: 30.702 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 6.448 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   5.956 ms/op
                 getUser·p0.90:   8.569 ms/op
                 getUser·p0.95:   10.158 ms/op
                 getUser·p0.99:   13.468 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 32.311 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 151380
  mean =      6.336 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 19377 
    [ 5.000,  7.500) = 109117 
    [ 7.500, 10.000) = 16174 
    [10.000, 12.500) = 4713 
    [12.500, 15.000) = 1345 
    [15.000, 17.500) = 375 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.458 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      8.274 ms/op
     p(95.0000) =      9.748 ms/op
     p(99.0000) =     13.156 ms/op
     p(99.9000) =     23.449 ms/op
     p(99.9900) =     31.420 ms/op
     p(99.9990) =     33.190 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 22.953 ±(99.9%) 0.433 ms/op
# Warmup Iteration   2: 10.205 ±(99.9%) 0.093 ms/op
# Warmup Iteration   3: 7.370 ±(99.9%) 0.035 ms/op
Iteration   1: 7.132 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   6.717 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  31.457 ms/op
                 listUser·p0.9999: 37.782 ms/op
                 listUser·p1.00:   40.698 ms/op

Iteration   2: 7.146 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.986 ms/op
                 listUser·p0.50:   6.758 ms/op
                 listUser·p0.90:   8.765 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.861 ms/op
                 listUser·p0.999:  31.440 ms/op
                 listUser·p0.9999: 35.489 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   3: 7.429 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   6.939 ms/op
                 listUser·p0.90:   9.503 ms/op
                 listUser·p0.95:   10.928 ms/op
                 listUser·p0.99:   14.234 ms/op
                 listUser·p0.999:  35.127 ms/op
                 listUser·p0.9999: 37.119 ms/op
                 listUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 132730
  mean =      7.233 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1436 
    [ 5.000, 10.000) = 122844 
    [10.000, 15.000) = 7578 
    [15.000, 20.000) = 576 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 140 
    [35.000, 40.000) = 84 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.347 ms/op
     p(50.0000) =      6.791 ms/op
     p(90.0000) =      9.093 ms/op
     p(95.0000) =     10.469 ms/op
     p(99.0000) =     13.681 ms/op
     p(99.9000) =     32.801 ms/op
     p(99.9900) =     37.093 ms/op
     p(99.9990) =     39.926 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.120 ± 1.244  ops/ms
ClientPb.existUser                       thrpt       3   5.510 ± 2.179  ops/ms
ClientPb.getUser                         thrpt       3   5.192 ± 1.777  ops/ms
ClientPb.listUser                        thrpt       3   4.473 ± 1.185  ops/ms
ClientPb.createUser                       avgt       3   6.198 ± 2.839   ms/op
ClientPb.existUser                        avgt       3   5.703 ± 2.791   ms/op
ClientPb.getUser                          avgt       3   6.195 ± 1.233   ms/op
ClientPb.listUser                         avgt       3   7.191 ± 5.096   ms/op
ClientPb.createUser                     sample  153944   6.234 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.126           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.173           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.791           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.108           ms/op
ClientPb.existUser                      sample  163211   5.883 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.269           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.586           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.765           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.616           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.776           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.351           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.746           ms/op
ClientPb.getUser                        sample  151380   6.336 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.748           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.156           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.449           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  132730   7.233 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.347           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.093           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.469           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.681           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.801           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.698           ms/op
