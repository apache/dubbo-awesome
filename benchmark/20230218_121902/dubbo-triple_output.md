# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.601 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 9.752 ops/ms
Iteration   1: 9.531 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.755 ±(99.9%) 4.970 ops/ms [Average]
  (min, avg, max) = (9.531, 9.755, 10.058), stdev = 0.272
  CI (99.9%): [4.785, 14.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 9.753 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.457 ±(99.9%) 3.748 ops/ms [Average]
  (min, avg, max) = (10.229, 10.457, 10.627), stdev = 0.205
  CI (99.9%): [6.709, 14.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.627 ops/ms
# Warmup Iteration   2: 8.807 ops/ms
# Warmup Iteration   3: 9.301 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 9.990 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.846 ±(99.9%) 2.823 ops/ms [Average]
  (min, avg, max) = (9.682, 9.846, 9.990), stdev = 0.155
  CI (99.9%): [7.023, 12.668] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 7.425 ops/ms
# Warmup Iteration   3: 8.779 ops/ms
Iteration   1: 8.546 ops/ms
Iteration   2: 8.677 ops/ms
Iteration   3: 8.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.648 ±(99.9%) 1.661 ops/ms [Average]
  (min, avg, max) = (8.546, 8.648, 8.721), stdev = 0.091
  CI (99.9%): [6.987, 10.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.201 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.006 ms/op
Iteration   1: 3.227 ±(99.9%) 0.007 ms/op
Iteration   2: 3.259 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.179 ±(99.9%) 2.060 ms/op [Average]
  (min, avg, max) = (3.049, 3.179, 3.259), stdev = 0.113
  CI (99.9%): [1.119, 5.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.543 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.005 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
Iteration   3: 3.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.135 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.114, 3.135, 3.165), stdev = 0.027
  CI (99.9%): [2.645, 3.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.885 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.002 ms/op
Iteration   1: 3.206 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
Iteration   3: 3.075 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.111 ±(99.9%) 1.513 ms/op [Average]
  (min, avg, max) = (3.052, 3.111, 3.206), stdev = 0.083
  CI (99.9%): [1.598, 4.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.370 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.004 ms/op
Iteration   1: 3.768 ±(99.9%) 0.008 ms/op
Iteration   2: 3.726 ±(99.9%) 0.007 ms/op
Iteration   3: 3.730 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.741 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.726, 3.741, 3.768), stdev = 0.023
  CI (99.9%): [3.322, 4.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.878 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  18.650 ms/op
                 createUser·p0.9999: 22.831 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  12.913 ms/op
                 createUser·p0.9999: 27.086 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.173 ms/op
                 createUser·p0.999:  13.809 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305118
  mean =      3.146 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14759 
    [ 2.500,  5.000) = 285169 
    [ 5.000,  7.500) = 4349 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     17.593 ms/op
     p(99.9900) =     26.115 ms/op
     p(99.9990) =     28.375 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.797 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 20.337 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  13.616 ms/op
                 existUser·p0.9999: 22.273 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   4.085 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  8.231 ms/op
                 existUser·p0.9999: 23.786 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303878
  mean =      3.159 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29397 
    [ 2.500,  5.000) = 267478 
    [ 5.000,  7.500) = 6413 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.342 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.285 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  12.529 ms/op
                 getUser·p0.9999: 25.068 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.304 ms/op
                 getUser·p0.99:   5.461 ms/op
                 getUser·p0.999:  8.665 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 21.130 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300491
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12898 
    [ 2.500,  5.000) = 279850 
    [ 5.000,  7.500) = 6818 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     11.870 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.682 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 19.000 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  14.118 ms/op
                 listUser·p0.9999: 16.861 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256554
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 249041 
    [ 5.000,  7.500) = 5309 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 327 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.155 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     18.187 ms/op
     p(99.9990) =     19.788 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.755 ± 4.970  ops/ms
ClientPb.existUser                       thrpt       3  10.457 ± 3.748  ops/ms
ClientPb.getUser                         thrpt       3   9.846 ± 2.823  ops/ms
ClientPb.listUser                        thrpt       3   8.648 ± 1.661  ops/ms
ClientPb.createUser                       avgt       3   3.179 ± 2.060   ms/op
ClientPb.existUser                        avgt       3   3.135 ± 0.490   ms/op
ClientPb.getUser                          avgt       3   3.111 ± 1.513   ms/op
ClientPb.listUser                         avgt       3   3.741 ± 0.419   ms/op
ClientPb.createUser                     sample  305118   3.146 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.049           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.115           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  303878   3.159 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.005           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.116           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.167           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  300491   3.192 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.870           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.429           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.494           ms/op
ClientPb.listUser                       sample  256554   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.155           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.187           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.382           ms/op
