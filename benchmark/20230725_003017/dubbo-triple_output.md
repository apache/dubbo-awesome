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
# Warmup Iteration   1: 1.486 ops/ms
# Warmup Iteration   2: 3.450 ops/ms
# Warmup Iteration   3: 7.268 ops/ms
Iteration   1: 7.245 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.710 ±(99.9%) 7.351 ops/ms [Average]
  (min, avg, max) = (7.245, 7.710, 7.970), stdev = 0.403
  CI (99.9%): [0.359, 15.060] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 6.708 ops/ms
# Warmup Iteration   3: 8.040 ops/ms
Iteration   1: 7.975 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.181 ±(99.9%) 3.825 ops/ms [Average]
  (min, avg, max) = (7.975, 8.181, 8.394), stdev = 0.210
  CI (99.9%): [4.356, 12.006] (assumes normal distribution)


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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 6.471 ops/ms
# Warmup Iteration   3: 7.630 ops/ms
Iteration   1: 8.059 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 7.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.954 ±(99.9%) 3.985 ops/ms [Average]
  (min, avg, max) = (7.703, 7.954, 8.099), stdev = 0.218
  CI (99.9%): [3.969, 11.938] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 5.102 ops/ms
# Warmup Iteration   3: 6.462 ops/ms
Iteration   1: 6.783 ops/ms
Iteration   2: 6.851 ops/ms
Iteration   3: 6.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.720 ±(99.9%) 3.129 ops/ms [Average]
  (min, avg, max) = (6.526, 6.720, 6.851), stdev = 0.172
  CI (99.9%): [3.591, 9.849] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.987 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 5.296 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.010 ms/op
Iteration   1: 4.153 ±(99.9%) 0.006 ms/op
Iteration   2: 4.150 ±(99.9%) 0.011 ms/op
Iteration   3: 3.967 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.090 ±(99.9%) 1.942 ms/op [Average]
  (min, avg, max) = (3.967, 4.090, 4.153), stdev = 0.106
  CI (99.9%): [2.149, 6.032] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.996 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.005 ms/op
Iteration   1: 3.806 ±(99.9%) 0.012 ms/op
Iteration   2: 4.105 ±(99.9%) 0.006 ms/op
Iteration   3: 3.946 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.952 ±(99.9%) 2.729 ms/op [Average]
  (min, avg, max) = (3.806, 3.952, 4.105), stdev = 0.150
  CI (99.9%): [1.223, 6.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.596 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.005 ms/op
Iteration   1: 4.097 ±(99.9%) 0.009 ms/op
Iteration   2: 4.221 ±(99.9%) 0.005 ms/op
Iteration   3: 4.107 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.141 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (4.097, 4.141, 4.221), stdev = 0.069
  CI (99.9%): [2.887, 5.396] (assumes normal distribution)


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
# Warmup Iteration   1: 13.964 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.356 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.009 ms/op
Iteration   1: 4.678 ±(99.9%) 0.019 ms/op
Iteration   2: 4.756 ±(99.9%) 0.013 ms/op
Iteration   3: 4.909 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.781 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (4.678, 4.781, 4.909), stdev = 0.118
  CI (99.9%): [2.630, 6.932] (assumes normal distribution)


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
# Warmup Iteration   1: 13.918 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.626 ±(99.9%) 0.020 ms/op
Iteration   1: 4.132 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.075 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  14.303 ms/op
                 createUser·p0.9999: 27.691 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 3.959 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.890 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  28.463 ms/op
                 createUser·p0.9999: 34.068 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  23.997 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237010
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181 
    [ 2.500,  5.000) = 223480 
    [ 5.000,  7.500) = 11409 
    [ 7.500, 10.000) = 1302 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     23.788 ms/op
     p(99.9900) =     32.483 ms/op
     p(99.9990) =     34.423 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 11.672 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.013 ms/op
Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 24.982 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.847 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  25.224 ms/op
                 existUser·p0.9999: 28.182 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   3: 3.835 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  19.421 ms/op
                 existUser·p0.9999: 30.070 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245180
  mean =      3.914 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185 
    [ 2.500,  5.000) = 235371 
    [ 5.000,  7.500) = 7194 
    [ 7.500, 10.000) = 1832 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     19.360 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     30.710 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 13.243 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.014 ms/op
Iteration   1: 3.950 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.695 ms/op
                 getUser·p0.999:  23.915 ms/op
                 getUser·p0.9999: 30.856 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   2: 3.937 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   7.418 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 32.760 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   3: 4.127 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.331 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  27.250 ms/op
                 getUser·p0.9999: 31.433 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239789
  mean =      4.003 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 226547 
    [ 5.000,  7.500) = 10571 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     23.934 ms/op
     p(99.9900) =     31.720 ms/op
     p(99.9990) =     33.804 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 15.306 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.868 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.021 ms/op
Iteration   1: 4.679 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.548 ms/op
                 listUser·p0.999:  26.062 ms/op
                 listUser·p0.9999: 31.272 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 4.808 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 27.078 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   3: 4.779 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  18.256 ms/op
                 listUser·p0.9999: 23.046 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201602
  mean =      4.755 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 166703 
    [ 5.000,  7.500) = 29998 
    [ 7.500, 10.000) = 3531 
    [10.000, 12.500) = 790 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     20.801 ms/op
     p(99.9900) =     29.650 ms/op
     p(99.9990) =     31.717 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.710 ± 7.351  ops/ms
ClientPb.existUser                       thrpt       3   8.181 ± 3.825  ops/ms
ClientPb.getUser                         thrpt       3   7.954 ± 3.985  ops/ms
ClientPb.listUser                        thrpt       3   6.720 ± 3.129  ops/ms
ClientPb.createUser                       avgt       3   4.090 ± 1.942   ms/op
ClientPb.existUser                        avgt       3   3.952 ± 2.729   ms/op
ClientPb.getUser                          avgt       3   4.141 ± 1.255   ms/op
ClientPb.listUser                         avgt       3   4.781 ± 2.151   ms/op
ClientPb.createUser                     sample  237010   4.049 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.612           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.788           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.537           ms/op
ClientPb.existUser                      sample  245180   3.914 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.360           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.574           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.293           ms/op
ClientPb.getUser                        sample  239789   4.003 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.934           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.720           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  201602   4.755 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.208           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.801           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.650           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.752           ms/op
