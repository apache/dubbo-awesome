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
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 6.970 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 9.611 ops/ms
Iteration   3: 9.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.721 ±(99.9%) 3.841 ops/ms [Average]
  (min, avg, max) = (9.588, 9.721, 9.964), stdev = 0.211
  CI (99.9%): [5.879, 13.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.260 ops/ms
# Warmup Iteration   2: 8.791 ops/ms
# Warmup Iteration   3: 9.882 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 10.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.298 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (10.227, 10.298, 10.372), stdev = 0.072
  CI (99.9%): [8.977, 11.619] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.339 ops/ms
# Warmup Iteration   2: 9.130 ops/ms
# Warmup Iteration   3: 10.079 ops/ms
Iteration   1: 10.031 ops/ms
Iteration   2: 9.914 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.841 ±(99.9%) 4.299 ops/ms [Average]
  (min, avg, max) = (9.578, 9.841, 10.031), stdev = 0.236
  CI (99.9%): [5.542, 14.140] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 7.008 ops/ms
# Warmup Iteration   3: 7.799 ops/ms
Iteration   1: 8.027 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.187 ±(99.9%) 3.449 ops/ms [Average]
  (min, avg, max) = (8.027, 8.187, 8.395), stdev = 0.189
  CI (99.9%): [4.738, 11.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.859 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.003 ms/op
Iteration   1: 3.349 ±(99.9%) 0.004 ms/op
Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
Iteration   3: 3.175 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (3.175, 3.273, 3.349), stdev = 0.089
  CI (99.9%): [1.645, 4.900] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.966 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.005 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
Iteration   2: 3.245 ±(99.9%) 0.005 ms/op
Iteration   3: 3.233 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.191 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.095, 3.191, 3.245), stdev = 0.083
  CI (99.9%): [1.670, 4.712] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.807 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.005 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.292 ±(99.9%) 0.005 ms/op
Iteration   3: 3.104 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.190 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.104, 3.190, 3.292), stdev = 0.095
  CI (99.9%): [1.460, 4.919] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.894 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.008 ms/op
Iteration   1: 3.957 ±(99.9%) 0.003 ms/op
Iteration   2: 3.755 ±(99.9%) 0.007 ms/op
Iteration   3: 3.720 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.811 ±(99.9%) 2.335 ms/op [Average]
  (min, avg, max) = (3.720, 3.811, 3.957), stdev = 0.128
  CI (99.9%): [1.475, 6.146] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.564 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.010 ms/op
Iteration   1: 3.175 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 31.750 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 26.667 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  14.795 ms/op
                 createUser·p0.9999: 19.882 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302077
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20045 
    [ 2.500,  5.000) = 277215 
    [ 5.000,  7.500) = 4058 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.153 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
Iteration   1: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  13.265 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  11.294 ms/op
                 existUser·p0.9999: 23.411 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310207
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11566 
    [ 2.500,  5.000) = 294133 
    [ 5.000,  7.500) = 3740 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     23.557 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 8.444 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
Iteration   1: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  16.582 ms/op
                 getUser·p0.9999: 25.536 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.870 ms/op
                 getUser·p0.9999: 22.835 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.051 ms/op
                 getUser·p0.999:  16.758 ms/op
                 getUser·p0.9999: 21.388 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295599
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18892 
    [ 2.500,  5.000) = 269539 
    [ 5.000,  7.500) = 6263 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     23.782 ms/op
     p(99.9990) =     25.997 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 10.535 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.012 ms/op
Iteration   1: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.661 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 20.694 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.910 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 3.877 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248813
  mean =      3.856 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 240592 
    [ 5.000,  7.500) = 6346 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     19.971 ms/op
     p(99.9990) =     21.039 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.721 ± 3.841  ops/ms
ClientPb.existUser                       thrpt       3  10.298 ± 1.321  ops/ms
ClientPb.getUser                         thrpt       3   9.841 ± 4.299  ops/ms
ClientPb.listUser                        thrpt       3   8.187 ± 3.449  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 1.628   ms/op
ClientPb.existUser                        avgt       3   3.191 ± 1.521   ms/op
ClientPb.getUser                          avgt       3   3.190 ± 1.729   ms/op
ClientPb.listUser                         avgt       3   3.811 ± 2.335   ms/op
ClientPb.createUser                     sample  302077   3.176 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.598           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.933           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.244           ms/op
ClientPb.existUser                      sample  310207   3.093 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.785           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.478           ms/op
ClientPb.getUser                        sample  295599   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.782           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  248813   3.856 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.264           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.971           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.103           ms/op
