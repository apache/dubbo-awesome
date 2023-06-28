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
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 6.322 ops/ms
# Warmup Iteration   3: 8.669 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 9.706 ops/ms
Iteration   3: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.739 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (9.634, 9.739, 9.877), stdev = 0.125
  CI (99.9%): [7.467, 12.011] (assumes normal distribution)


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
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 9.358 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.224 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (10.096, 10.224, 10.450), stdev = 0.196
  CI (99.9%): [6.644, 13.805] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ops/ms
# Warmup Iteration   2: 9.144 ops/ms
# Warmup Iteration   3: 9.345 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 10.240 ops/ms
Iteration   3: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.984 ±(99.9%) 4.697 ops/ms [Average]
  (min, avg, max) = (9.725, 9.984, 10.240), stdev = 0.257
  CI (99.9%): [5.287, 14.681] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.480 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.520 ±(99.9%) 0.772 ops/ms [Average]
  (min, avg, max) = (8.480, 8.520, 8.564), stdev = 0.042
  CI (99.9%): [7.748, 9.292] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.281 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.003 ms/op
Iteration   1: 3.258 ±(99.9%) 0.007 ms/op
Iteration   2: 3.122 ±(99.9%) 0.004 ms/op
Iteration   3: 3.262 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 1.458 ms/op [Average]
  (min, avg, max) = (3.122, 3.214, 3.262), stdev = 0.080
  CI (99.9%): [1.756, 4.671] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.115 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.070 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.054, 3.070, 3.090), stdev = 0.019
  CI (99.9%): [2.727, 3.412] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.354 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.004 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
Iteration   3: 3.240 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.266 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.240, 3.266, 3.303), stdev = 0.033
  CI (99.9%): [2.668, 3.865] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.006 ms/op
Iteration   1: 3.736 ±(99.9%) 0.009 ms/op
Iteration   2: 3.696 ±(99.9%) 0.010 ms/op
Iteration   3: 3.684 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.684, 3.705, 3.736), stdev = 0.027
  CI (99.9%): [3.210, 4.201] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  9.981 ms/op
                 createUser·p0.9999: 22.683 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  13.017 ms/op
                 createUser·p0.9999: 21.992 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  15.585 ms/op
                 createUser·p0.9999: 23.735 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293686
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16547 
    [ 2.500,  5.000) = 271199 
    [ 5.000,  7.500) = 4916 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     22.631 ms/op
     p(99.9990) =     24.054 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.185 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 20.853 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  14.942 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.194 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  15.544 ms/op
                 existUser·p0.9999: 33.945 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299175
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29074 
    [ 2.500,  5.000) = 264176 
    [ 5.000,  7.500) = 5072 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     32.738 ms/op
     p(99.9990) =     34.801 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 7.961 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.370 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  17.440 ms/op
                 getUser·p0.9999: 21.054 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  13.640 ms/op
                 getUser·p0.9999: 28.196 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.794 ms/op
                 getUser·p0.9999: 31.069 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295475
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8985 
    [ 2.500,  5.000) = 277726 
    [ 5.000,  7.500) = 7601 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     13.394 ms/op
     p(99.9900) =     28.669 ms/op
     p(99.9990) =     32.411 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 9.338 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.013 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.049 ms/op
                 listUser·p0.999:  15.219 ms/op
                 listUser·p0.9999: 20.919 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.892 ms/op
                 listUser·p0.9999: 16.793 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.120 ms/op
                 listUser·p0.999:  13.453 ms/op
                 listUser·p0.9999: 17.853 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252004
  mean =      3.810 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 242384 
    [ 5.000,  7.500) = 7635 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.302 ms/op
     p(99.9900) =     20.460 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.739 ± 2.272  ops/ms
ClientPb.existUser                       thrpt       3  10.224 ± 3.580  ops/ms
ClientPb.getUser                         thrpt       3   9.984 ± 4.697  ops/ms
ClientPb.listUser                        thrpt       3   8.520 ± 0.772  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 1.458   ms/op
ClientPb.existUser                        avgt       3   3.070 ± 0.342   ms/op
ClientPb.getUser                          avgt       3   3.266 ± 0.599   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 0.495   ms/op
ClientPb.createUser                     sample  293686   3.267 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  299175   3.206 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.686           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  295475   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.394           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.669           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  252004   3.810 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
