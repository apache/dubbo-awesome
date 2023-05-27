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
# Warmup Iteration   1: 0.965 ops/ms
# Warmup Iteration   2: 2.256 ops/ms
# Warmup Iteration   3: 4.880 ops/ms
Iteration   1: 5.558 ops/ms
Iteration   2: 5.667 ops/ms
Iteration   3: 5.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.695 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (5.558, 5.695, 5.858), stdev = 0.152
  CI (99.9%): [2.920, 8.470] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.617 ops/ms
# Warmup Iteration   2: 4.937 ops/ms
# Warmup Iteration   3: 5.982 ops/ms
Iteration   1: 6.057 ops/ms
Iteration   2: 6.235 ops/ms
Iteration   3: 6.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.186 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (6.057, 6.186, 6.267), stdev = 0.113
  CI (99.9%): [4.122, 8.251] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.851 ops/ms
# Warmup Iteration   3: 5.919 ops/ms
Iteration   1: 5.391 ops/ms
Iteration   2: 5.503 ops/ms
Iteration   3: 5.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.502 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (5.391, 5.502, 5.612), stdev = 0.111
  CI (99.9%): [3.482, 7.522] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.645 ops/ms
# Warmup Iteration   2: 3.569 ops/ms
# Warmup Iteration   3: 4.951 ops/ms
Iteration   1: 4.981 ops/ms
Iteration   2: 5.162 ops/ms
Iteration   3: 5.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.099 ±(99.9%) 1.856 ops/ms [Average]
  (min, avg, max) = (4.981, 5.099, 5.162), stdev = 0.102
  CI (99.9%): [3.243, 6.955] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.934 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.056 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.177 ±(99.9%) 0.011 ms/op
Iteration   1: 5.111 ±(99.9%) 0.014 ms/op
Iteration   2: 5.488 ±(99.9%) 0.009 ms/op
Iteration   3: 5.221 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.273 ±(99.9%) 3.538 ms/op [Average]
  (min, avg, max) = (5.111, 5.273, 5.488), stdev = 0.194
  CI (99.9%): [1.735, 8.811] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.492 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.925 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.721 ±(99.9%) 0.008 ms/op
Iteration   1: 4.939 ±(99.9%) 0.009 ms/op
Iteration   2: 5.437 ±(99.9%) 0.018 ms/op
Iteration   3: 5.339 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.239 ±(99.9%) 4.810 ms/op [Average]
  (min, avg, max) = (4.939, 5.239, 5.437), stdev = 0.264
  CI (99.9%): [0.428, 10.049] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.099 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.991 ±(99.9%) 0.008 ms/op
Iteration   2: 4.849 ±(99.9%) 0.022 ms/op
Iteration   3: 4.813 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.884 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (4.813, 4.884, 4.991), stdev = 0.094
  CI (99.9%): [3.163, 6.606] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.509 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.705 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.012 ms/op
Iteration   1: 6.028 ±(99.9%) 0.012 ms/op
Iteration   2: 5.724 ±(99.9%) 0.019 ms/op
Iteration   3: 5.924 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.892 ±(99.9%) 2.823 ms/op [Average]
  (min, avg, max) = (5.724, 5.892, 6.028), stdev = 0.155
  CI (99.9%): [3.069, 8.715] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.989 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.331 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.812 ±(99.9%) 0.025 ms/op
Iteration   1: 5.201 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.154 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.275 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  22.630 ms/op
                 createUser·p0.9999: 30.717 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   2: 5.245 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  22.875 ms/op
                 createUser·p0.9999: 34.051 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 5.151 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   7.070 ms/op
                 createUser·p0.99:   10.255 ms/op
                 createUser·p0.999:  27.661 ms/op
                 createUser·p0.9999: 35.689 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184550
  mean =      5.199 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 96593 
    [ 5.000,  7.500) = 81548 
    [ 7.500, 10.000) = 4818 
    [10.000, 12.500) = 996 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      6.988 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     23.083 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 14.228 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.741 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.357 ±(99.9%) 0.019 ms/op
Iteration   1: 4.989 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  12.613 ms/op
                 existUser·p0.9999: 25.538 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   2: 5.033 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   6.775 ms/op
                 existUser·p0.99:   9.747 ms/op
                 existUser·p0.999:  18.860 ms/op
                 existUser·p0.9999: 30.878 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 5.205 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.876 ms/op
                 existUser·p0.999:  27.001 ms/op
                 existUser·p0.9999: 36.991 ms/op
                 existUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189115
  mean =      5.074 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 113880 
    [ 5.000,  7.500) = 69064 
    [ 7.500, 10.000) = 4711 
    [10.000, 12.500) = 757 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     18.782 ms/op
     p(99.9900) =     35.270 ms/op
     p(99.9990) =     37.426 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.949 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.555 ±(99.9%) 0.020 ms/op
Iteration   1: 5.700 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   14.860 ms/op
                 getUser·p0.999:  25.350 ms/op
                 getUser·p0.9999: 32.375 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   2: 5.865 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.798 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.373 ms/op
                 getUser·p0.95:   8.110 ms/op
                 getUser·p0.99:   10.572 ms/op
                 getUser·p0.999:  27.113 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   31.818 ms/op

Iteration   3: 5.136 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.201 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   9.463 ms/op
                 getUser·p0.999:  28.215 ms/op
                 getUser·p0.9999: 33.128 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173000
  mean =      5.549 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 66284 
    [ 5.000,  7.500) = 95749 
    [ 7.500, 10.000) = 7869 
    [10.000, 12.500) = 1999 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 371 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     33.900 ms/op
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
# Warmup Iteration   1: 17.705 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.679 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.504 ±(99.9%) 0.028 ms/op
Iteration   1: 6.477 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  25.315 ms/op
                 listUser·p0.9999: 30.411 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 6.263 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  30.867 ms/op
                 listUser·p0.9999: 35.914 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   3: 5.959 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  20.359 ms/op
                 listUser·p0.9999: 23.548 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154258
  mean =      6.226 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 15986 
    [ 5.000,  7.500) = 121080 
    [ 7.500, 10.000) = 13427 
    [10.000, 12.500) = 2558 
    [12.500, 15.000) = 642 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     24.968 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.695 ± 2.775  ops/ms
ClientPb.existUser                       thrpt       3   6.186 ± 2.064  ops/ms
ClientPb.getUser                         thrpt       3   5.502 ± 2.020  ops/ms
ClientPb.listUser                        thrpt       3   5.099 ± 1.856  ops/ms
ClientPb.createUser                       avgt       3   5.273 ± 3.538   ms/op
ClientPb.existUser                        avgt       3   5.239 ± 4.810   ms/op
ClientPb.getUser                          avgt       3   4.884 ± 1.721   ms/op
ClientPb.listUser                         avgt       3   5.892 ± 2.823   ms/op
ClientPb.createUser                     sample  184550   5.199 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.154           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.988           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.814           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.083           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  189115   5.074 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.276           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.782           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.270           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.535           ms/op
ClientPb.getUser                        sample  173000   5.549 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.503           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.840           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.608           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.375           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  154258   6.226 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.731           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.968           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.996           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.110           ms/op
