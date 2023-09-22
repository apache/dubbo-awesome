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
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 5.801 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 9.022 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 9.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.547 ±(99.9%) 8.588 ops/ms [Average]
  (min, avg, max) = (9.022, 9.547, 9.931), stdev = 0.471
  CI (99.9%): [0.959, 18.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ops/ms
# Warmup Iteration   2: 9.050 ops/ms
# Warmup Iteration   3: 10.002 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.118 ±(99.9%) 1.484 ops/ms [Average]
  (min, avg, max) = (10.025, 10.118, 10.179), stdev = 0.081
  CI (99.9%): [8.634, 11.601] (assumes normal distribution)


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
# Warmup Iteration   1: 3.543 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 9.564 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.714 ±(99.9%) 2.449 ops/ms [Average]
  (min, avg, max) = (9.564, 9.714, 9.823), stdev = 0.134
  CI (99.9%): [7.266, 12.163] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.438 ops/ms
# Warmup Iteration   2: 7.729 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 8.108 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.104 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (8.012, 8.104, 8.192), stdev = 0.090
  CI (99.9%): [6.464, 9.744] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.390 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.004 ms/op
Iteration   1: 3.248 ±(99.9%) 0.003 ms/op
Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
Iteration   3: 3.294 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.259 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.236, 3.259, 3.294), stdev = 0.030
  CI (99.9%): [2.704, 3.815] (assumes normal distribution)


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
# Warmup Iteration   1: 7.017 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.002 ms/op
Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.064, 3.131, 3.187), stdev = 0.062
  CI (99.9%): [1.998, 4.263] (assumes normal distribution)


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
# Warmup Iteration   1: 8.053 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.003 ms/op
Iteration   1: 3.213 ±(99.9%) 0.005 ms/op
Iteration   2: 3.220 ±(99.9%) 0.003 ms/op
Iteration   3: 3.169 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.169, 3.201, 3.220), stdev = 0.028
  CI (99.9%): [2.693, 3.708] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.165 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.006 ms/op
Iteration   1: 3.856 ±(99.9%) 0.005 ms/op
Iteration   2: 3.846 ±(99.9%) 0.004 ms/op
Iteration   3: 3.798 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.833 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.798, 3.833, 3.856), stdev = 0.031
  CI (99.9%): [3.266, 4.400] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.206 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.008 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  18.381 ms/op
                 createUser·p0.9999: 22.445 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.275 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 25.239 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  14.699 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293675
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10252 
    [ 2.500,  5.000) = 278863 
    [ 5.000,  7.500) = 3462 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.850 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.349 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  17.592 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  16.335 ms/op
                 existUser·p0.9999: 22.459 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 21.952 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297646
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9463 
    [ 2.500,  5.000) = 283875 
    [ 5.000,  7.500) = 3437 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.346 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     21.962 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 8.181 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  16.509 ms/op
                 getUser·p0.9999: 18.827 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  14.618 ms/op
                 getUser·p0.9999: 20.815 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.252 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 22.287 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290409
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10960 
    [ 2.500,  5.000) = 272239 
    [ 5.000,  7.500) = 6020 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.568 ms/op
     p(99.9900) =     20.802 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 10.455 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.867 ms/op
                 listUser·p0.9999: 22.921 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 3.853 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.256 ms/op
                 listUser·p0.9999: 14.336 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.876 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 16.331 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247997
  mean =      3.868 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 240867 
    [ 5.000,  7.500) = 5383 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 416 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     21.601 ms/op
     p(99.9990) =     23.809 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.547 ± 8.588  ops/ms
ClientPb.existUser                       thrpt       3  10.118 ± 1.484  ops/ms
ClientPb.getUser                         thrpt       3   9.714 ± 2.449  ops/ms
ClientPb.listUser                        thrpt       3   8.104 ± 1.640  ops/ms
ClientPb.createUser                       avgt       3   3.259 ± 0.555   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 1.133   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 0.507   ms/op
ClientPb.listUser                         avgt       3   3.833 ± 0.567   ms/op
ClientPb.createUser                     sample  293675   3.268 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.367           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.314           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  297646   3.223 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.346           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.287           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.560           ms/op
ClientPb.getUser                        sample  290409   3.305 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.802           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.200           ms/op
ClientPb.listUser                       sample  247997   3.868 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.601           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
