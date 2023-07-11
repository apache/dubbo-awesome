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
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 5.797 ops/ms
# Warmup Iteration   3: 8.293 ops/ms
Iteration   1: 8.760 ops/ms
Iteration   2: 9.222 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.035 ±(99.9%) 4.433 ops/ms [Average]
  (min, avg, max) = (8.760, 9.035, 9.222), stdev = 0.243
  CI (99.9%): [4.602, 13.467] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 8.968 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.511 ops/ms
Iteration   2: 9.607 ops/ms
Iteration   3: 9.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.444 ±(99.9%) 3.731 ops/ms [Average]
  (min, avg, max) = (9.214, 9.444, 9.607), stdev = 0.205
  CI (99.9%): [5.713, 13.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ops/ms
# Warmup Iteration   2: 8.092 ops/ms
# Warmup Iteration   3: 9.205 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.492 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (9.240, 9.402, 9.492), stdev = 0.140
  CI (99.9%): [6.841, 11.963] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.753 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.478 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.034 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (7.878, 8.034, 8.158), stdev = 0.143
  CI (99.9%): [5.430, 10.638] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.644 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
Iteration   1: 3.384 ±(99.9%) 0.011 ms/op
Iteration   2: 3.437 ±(99.9%) 0.012 ms/op
Iteration   3: 3.372 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.398 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.372, 3.398, 3.437), stdev = 0.035
  CI (99.9%): [2.763, 4.032] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.285 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.004 ms/op
Iteration   1: 3.415 ±(99.9%) 0.002 ms/op
Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
Iteration   3: 3.341 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.341, 3.367, 3.415), stdev = 0.042
  CI (99.9%): [2.608, 4.126] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.622 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.006 ms/op
Iteration   1: 3.457 ±(99.9%) 0.006 ms/op
Iteration   2: 3.398 ±(99.9%) 0.008 ms/op
Iteration   3: 3.510 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.398, 3.455, 3.510), stdev = 0.056
  CI (99.9%): [2.429, 4.482] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.545 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.006 ms/op
Iteration   1: 4.209 ±(99.9%) 0.006 ms/op
Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
Iteration   3: 4.005 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.082 ±(99.9%) 2.033 ms/op [Average]
  (min, avg, max) = (4.005, 4.082, 4.209), stdev = 0.111
  CI (99.9%): [2.049, 6.114] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 11.090 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.015 ms/op
Iteration   1: 3.471 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  16.870 ms/op
                 createUser·p0.9999: 20.859 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.501 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  17.619 ms/op
                 createUser·p0.9999: 24.223 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 23.713 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276970
  mean =      3.464 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5447 
    [ 2.500,  5.000) = 263947 
    [ 5.000,  7.500) = 6355 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     23.701 ms/op
     p(99.9990) =     25.108 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.219 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.010 ms/op
Iteration   1: 3.297 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  9.402 ms/op
                 existUser·p0.9999: 22.914 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.495 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 24.042 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 3.499 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  23.309 ms/op
                 existUser·p0.9999: 31.055 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279988
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7887 
    [ 2.500,  5.000) = 266687 
    [ 5.000,  7.500) = 4485 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.361 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
Iteration   1: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  19.956 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   2: 3.500 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  22.376 ms/op
                 getUser·p0.9999: 25.180 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  19.035 ms/op
                 getUser·p0.9999: 27.382 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279454
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1795 
    [ 2.500,  5.000) = 271257 
    [ 5.000,  7.500) = 5296 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.740 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 11.672 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
Iteration   1: 4.267 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  22.577 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.734 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 22.944 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 3.916 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235523
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 224921 
    [ 5.000,  7.500) = 7659 
    [ 7.500, 10.000) = 1979 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     17.678 ms/op
     p(99.9900) =     24.918 ms/op
     p(99.9990) =     26.945 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.035 ± 4.433  ops/ms
ClientPb.existUser                       thrpt       3   9.444 ± 3.731  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 2.561  ops/ms
ClientPb.listUser                        thrpt       3   8.034 ± 2.604  ops/ms
ClientPb.createUser                       avgt       3   3.398 ± 0.635   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 0.759   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 1.027   ms/op
ClientPb.listUser                         avgt       3   4.082 ± 2.033   ms/op
ClientPb.createUser                     sample  276970   3.464 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.629           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.701           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.231           ms/op
ClientPb.existUser                      sample  279988   3.427 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.753           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.556           ms/op
ClientPb.getUser                        sample  279454   3.435 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.247           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.639           ms/op
ClientPb.listUser                       sample  235523   4.071 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.918           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.329           ms/op
