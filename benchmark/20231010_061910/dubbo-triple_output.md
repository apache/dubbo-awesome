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
# Warmup Iteration   1: 1.713 ops/ms
# Warmup Iteration   2: 3.753 ops/ms
# Warmup Iteration   3: 7.114 ops/ms
Iteration   1: 7.515 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.702 ±(99.9%) 3.075 ops/ms [Average]
  (min, avg, max) = (7.515, 7.702, 7.843), stdev = 0.169
  CI (99.9%): [4.627, 10.777] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 7.274 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 8.175 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.255 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (8.162, 8.255, 8.427), stdev = 0.149
  CI (99.9%): [5.532, 10.978] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.996 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 7.538 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.935 ±(99.9%) 3.413 ops/ms [Average]
  (min, avg, max) = (7.765, 7.935, 8.135), stdev = 0.187
  CI (99.9%): [4.522, 11.348] (assumes normal distribution)


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
# Warmup Iteration   1: 2.035 ops/ms
# Warmup Iteration   2: 5.630 ops/ms
# Warmup Iteration   3: 6.520 ops/ms
Iteration   1: 6.479 ops/ms
Iteration   2: 6.561 ops/ms
Iteration   3: 6.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.639 ±(99.9%) 3.828 ops/ms [Average]
  (min, avg, max) = (6.479, 6.639, 6.876), stdev = 0.210
  CI (99.9%): [2.811, 10.466] (assumes normal distribution)


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
# Warmup Iteration   1: 14.943 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.007 ms/op
Iteration   1: 4.127 ±(99.9%) 0.007 ms/op
Iteration   2: 4.181 ±(99.9%) 0.006 ms/op
Iteration   3: 3.983 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.097 ±(99.9%) 1.872 ms/op [Average]
  (min, avg, max) = (3.983, 4.097, 4.181), stdev = 0.103
  CI (99.9%): [2.225, 5.970] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.132 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.003 ms/op
Iteration   1: 3.971 ±(99.9%) 0.007 ms/op
Iteration   2: 4.368 ±(99.9%) 0.007 ms/op
Iteration   3: 4.302 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.214 ±(99.9%) 3.885 ms/op [Average]
  (min, avg, max) = (3.971, 4.214, 4.368), stdev = 0.213
  CI (99.9%): [0.329, 8.099] (assumes normal distribution)


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
# Warmup Iteration   1: 14.501 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.004 ms/op
Iteration   1: 4.188 ±(99.9%) 0.006 ms/op
Iteration   2: 4.082 ±(99.9%) 0.008 ms/op
Iteration   3: 4.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.139 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (4.082, 4.139, 4.188), stdev = 0.053
  CI (99.9%): [3.166, 5.113] (assumes normal distribution)


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
# Warmup Iteration   1: 16.979 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.830 ±(99.9%) 0.008 ms/op
Iteration   1: 4.809 ±(99.9%) 0.007 ms/op
Iteration   2: 4.732 ±(99.9%) 0.009 ms/op
Iteration   3: 4.878 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.807 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (4.732, 4.807, 4.878), stdev = 0.073
  CI (99.9%): [3.476, 6.137] (assumes normal distribution)


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
# Warmup Iteration   1: 13.957 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 4.960 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.020 ms/op
Iteration   1: 4.176 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  24.393 ms/op
                 createUser·p0.9999: 28.891 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 28.016 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 4.172 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.266 ms/op
                 createUser·p0.999:  28.312 ms/op
                 createUser·p0.9999: 31.523 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233601
  mean =      4.107 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 342 
    [ 2.500,  5.000) = 215411 
    [ 5.000,  7.500) = 15064 
    [ 7.500, 10.000) = 1971 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 110 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     24.524 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     31.894 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 13.349 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.161 ms/op
                 existUser·p0.999:  14.142 ms/op
                 existUser·p0.9999: 26.868 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.925 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  24.424 ms/op
                 existUser·p0.9999: 27.722 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.882 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  15.396 ms/op
                 existUser·p0.9999: 30.499 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244265
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 229812 
    [ 5.000,  7.500) = 12170 
    [ 7.500, 10.000) = 1048 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     29.627 ms/op
     p(99.9990) =     31.133 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 13.706 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.018 ms/op
Iteration   1: 4.273 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  22.846 ms/op
                 getUser·p0.9999: 27.968 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 4.065 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.815 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   8.374 ms/op
                 getUser·p0.999:  25.919 ms/op
                 getUser·p0.9999: 30.221 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   3: 4.346 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.381 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   6.857 ms/op
                 getUser·p0.99:   10.203 ms/op
                 getUser·p0.999:  20.658 ms/op
                 getUser·p0.9999: 41.658 ms/op
                 getUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226993
  mean =      4.224 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 204954 
    [ 5.000, 10.000) = 20232 
    [10.000, 15.000) = 1388 
    [15.000, 20.000) = 174 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 46 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     22.908 ms/op
     p(99.9900) =     39.164 ms/op
     p(99.9990) =     42.356 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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
# Warmup Iteration   1: 15.295 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 5.969 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.247 ±(99.9%) 0.019 ms/op
Iteration   1: 5.069 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   10.665 ms/op
                 listUser·p0.999:  25.395 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 5.153 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.930 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  20.079 ms/op
                 listUser·p0.9999: 23.499 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 5.218 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  17.792 ms/op
                 listUser·p0.9999: 20.910 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 186444
  mean =      5.146 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 125931 
    [ 5.000,  7.500) = 49007 
    [ 7.500, 10.000) = 8645 
    [10.000, 12.500) = 1775 
    [12.500, 15.000) = 539 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     20.433 ms/op
     p(99.9900) =     27.045 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.702 ± 3.075  ops/ms
ClientPb.existUser                       thrpt       3   8.255 ± 2.723  ops/ms
ClientPb.getUser                         thrpt       3   7.935 ± 3.413  ops/ms
ClientPb.listUser                        thrpt       3   6.639 ± 3.828  ops/ms
ClientPb.createUser                       avgt       3   4.097 ± 1.872   ms/op
ClientPb.existUser                        avgt       3   4.214 ± 3.885   ms/op
ClientPb.getUser                          avgt       3   4.139 ± 0.974   ms/op
ClientPb.listUser                         avgt       3   4.807 ± 1.331   ms/op
ClientPb.createUser                     sample  233601   4.107 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.524           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.179           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  244265   3.929 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.446           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.127           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.627           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.326           ms/op
ClientPb.getUser                        sample  226993   4.224 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.381           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.290           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.908           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.164           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.598           ms/op
ClientPb.listUser                       sample  186444   5.146 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.922           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.961           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.433           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.045           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
