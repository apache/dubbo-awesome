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
# Warmup Iteration   1: 2.471 ops/ms
# Warmup Iteration   2: 6.762 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.680 ops/ms
Iteration   2: 9.499 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.683 ±(99.9%) 3.384 ops/ms [Average]
  (min, avg, max) = (9.499, 9.683, 9.870), stdev = 0.186
  CI (99.9%): [6.298, 13.067] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 9.002 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.033 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.080 ±(99.9%) 4.295 ops/ms [Average]
  (min, avg, max) = (9.871, 10.080, 10.335), stdev = 0.235
  CI (99.9%): [5.785, 14.374] (assumes normal distribution)


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
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 8.352 ops/ms
# Warmup Iteration   3: 9.801 ops/ms
Iteration   1: 9.651 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.594 ±(99.9%) 5.044 ops/ms [Average]
  (min, avg, max) = (9.294, 9.594, 9.838), stdev = 0.276
  CI (99.9%): [4.550, 14.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.229 ops/ms
# Warmup Iteration   2: 7.557 ops/ms
# Warmup Iteration   3: 8.291 ops/ms
Iteration   1: 8.319 ops/ms
Iteration   2: 8.399 ops/ms
Iteration   3: 8.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.355 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (8.319, 8.355, 8.399), stdev = 0.041
  CI (99.9%): [7.614, 9.097] (assumes normal distribution)


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
# Warmup Iteration   1: 9.151 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.006 ms/op
Iteration   2: 3.321 ±(99.9%) 0.005 ms/op
Iteration   3: 3.298 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.263 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.171, 3.263, 3.321), stdev = 0.081
  CI (99.9%): [1.793, 4.734] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.004 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 3.313 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.150 ±(99.9%) 2.584 ms/op [Average]
  (min, avg, max) = (3.064, 3.150, 3.313), stdev = 0.142
  CI (99.9%): [0.566, 5.734] (assumes normal distribution)


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
# Warmup Iteration   1: 8.774 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.005 ms/op
Iteration   1: 3.210 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
Iteration   3: 3.302 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.229 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (3.175, 3.229, 3.302), stdev = 0.066
  CI (99.9%): [2.030, 4.428] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.463 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.009 ms/op
Iteration   1: 3.832 ±(99.9%) 0.004 ms/op
Iteration   2: 3.826 ±(99.9%) 0.011 ms/op
Iteration   3: 3.729 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.729, 3.796, 3.832), stdev = 0.058
  CI (99.9%): [2.734, 4.857] (assumes normal distribution)


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
# Warmup Iteration   1: 8.393 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  12.017 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  13.826 ms/op
                 createUser·p0.9999: 30.081 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.982 ms/op
                 createUser·p0.999:  15.408 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289563
  mean =      3.310 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19257 
    [ 2.500,  5.000) = 263927 
    [ 5.000,  7.500) = 5440 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     15.301 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 7.900 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.303 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 23.415 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  13.052 ms/op
                 existUser·p0.9999: 21.095 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307534
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21499 
    [ 2.500,  5.000) = 281266 
    [ 5.000,  7.500) = 4061 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     10.774 ms/op
     p(99.9900) =     22.634 ms/op
     p(99.9990) =     23.754 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.410 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
Iteration   1: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  19.713 ms/op
                 getUser·p0.9999: 22.022 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.183 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 28.672 ms/op
                 getUser·p1.00:   31.523 ms/op

Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  12.355 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300010
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17262 
    [ 2.500,  5.000) = 278222 
    [ 5.000,  7.500) = 3695 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.728 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.683 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.014 ms/op
Iteration   1: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.625 ms/op
                 listUser·p0.9999: 24.165 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.308 ms/op
                 listUser·p0.9999: 15.548 ms/op
                 listUser·p1.00:   15.827 ms/op

Iteration   3: 3.755 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  12.454 ms/op
                 listUser·p0.9999: 14.974 ms/op
                 listUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255414
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 249149 
    [ 5.000,  7.500) = 4538 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     23.313 ms/op
     p(99.9990) =     24.328 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.683 ± 3.384  ops/ms
ClientPb.existUser                       thrpt       3  10.080 ± 4.295  ops/ms
ClientPb.getUser                         thrpt       3   9.594 ± 5.044  ops/ms
ClientPb.listUser                        thrpt       3   8.355 ± 0.742  ops/ms
ClientPb.createUser                       avgt       3   3.263 ± 1.471   ms/op
ClientPb.existUser                        avgt       3   3.150 ± 2.584   ms/op
ClientPb.getUser                          avgt       3   3.229 ± 1.199   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 1.061   ms/op
ClientPb.createUser                     sample  289563   3.310 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.147           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.301           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  307534   3.122 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.139           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.634           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.855           ms/op
ClientPb.getUser                        sample  300010   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.500           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.728           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.492           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  255414   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.313           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
