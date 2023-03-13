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
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 5.631 ops/ms
# Warmup Iteration   3: 8.643 ops/ms
Iteration   1: 9.403 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.365 ±(99.9%) 3.753 ops/ms [Average]
  (min, avg, max) = (9.142, 9.365, 9.549), stdev = 0.206
  CI (99.9%): [5.612, 13.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 9.503 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 9.946 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.894 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (9.820, 9.894, 9.946), stdev = 0.066
  CI (99.9%): [8.691, 11.096] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.876 ops/ms
# Warmup Iteration   2: 8.105 ops/ms
# Warmup Iteration   3: 9.070 ops/ms
Iteration   1: 9.047 ops/ms
Iteration   2: 9.372 ops/ms
Iteration   3: 9.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.400 ±(99.9%) 6.715 ops/ms [Average]
  (min, avg, max) = (9.047, 9.400, 9.781), stdev = 0.368
  CI (99.9%): [2.685, 16.115] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 7.323 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 8.245 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.093 ±(99.9%) 2.468 ops/ms [Average]
  (min, avg, max) = (7.986, 8.093, 8.245), stdev = 0.135
  CI (99.9%): [5.626, 10.561] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.598 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.007 ms/op
Iteration   1: 3.414 ±(99.9%) 0.007 ms/op
Iteration   2: 3.366 ±(99.9%) 0.008 ms/op
Iteration   3: 3.301 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.360 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (3.301, 3.360, 3.414), stdev = 0.057
  CI (99.9%): [2.323, 4.397] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.060 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.005 ms/op
Iteration   1: 3.249 ±(99.9%) 0.008 ms/op
Iteration   2: 3.366 ±(99.9%) 0.007 ms/op
Iteration   3: 3.314 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.310 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.249, 3.310, 3.366), stdev = 0.058
  CI (99.9%): [2.244, 4.375] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.486 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.005 ms/op
Iteration   1: 3.423 ±(99.9%) 0.005 ms/op
Iteration   2: 3.353 ±(99.9%) 0.011 ms/op
Iteration   3: 3.494 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.423 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.353, 3.423, 3.494), stdev = 0.070
  CI (99.9%): [2.144, 4.703] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.693 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
Iteration   2: 4.104 ±(99.9%) 0.008 ms/op
Iteration   3: 3.913 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.025 ±(99.9%) 1.818 ms/op [Average]
  (min, avg, max) = (3.913, 4.025, 4.104), stdev = 0.100
  CI (99.9%): [2.207, 5.843] (assumes normal distribution)


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
# Warmup Iteration   1: 9.762 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.011 ms/op
Iteration   1: 3.454 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  21.457 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  25.073 ms/op
                 createUser·p0.9999: 28.622 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.982 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280627
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4509 
    [ 2.500,  5.000) = 269797 
    [ 5.000,  7.500) = 5291 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 122 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     20.656 ms/op
     p(99.9900) =     27.261 ms/op
     p(99.9990) =     29.209 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 7.336 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.486 ms/op
                 existUser·p0.9999: 23.020 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  21.705 ms/op
                 existUser·p0.9999: 27.642 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  19.913 ms/op
                 existUser·p0.9999: 27.473 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283907
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12244 
    [ 2.500,  5.000) = 263293 
    [ 5.000,  7.500) = 7228 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     11.823 ms/op
     p(99.9900) =     27.290 ms/op
     p(99.9990) =     29.064 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.167 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
Iteration   1: 3.374 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  18.755 ms/op
                 getUser·p0.9999: 21.695 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  22.060 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  17.751 ms/op
                 getUser·p0.9999: 27.162 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281800
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13738 
    [ 2.500,  5.000) = 259010 
    [ 5.000,  7.500) = 8069 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.604 ms/op
     p(99.9990) =     28.085 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 10.720 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.015 ms/op
Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.744 ms/op
                 listUser·p0.99:   7.488 ms/op
                 listUser·p0.999:  18.684 ms/op
                 listUser·p0.9999: 22.611 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.339 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  18.182 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241302
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 232097 
    [ 5.000,  7.500) = 6800 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.333 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.365 ± 3.753  ops/ms
ClientPb.existUser                       thrpt       3   9.894 ± 1.202  ops/ms
ClientPb.getUser                         thrpt       3   9.400 ± 6.715  ops/ms
ClientPb.listUser                        thrpt       3   8.093 ± 2.468  ops/ms
ClientPb.createUser                       avgt       3   3.360 ± 1.037   ms/op
ClientPb.existUser                        avgt       3   3.310 ± 1.066   ms/op
ClientPb.getUser                          avgt       3   3.423 ± 1.279   ms/op
ClientPb.listUser                         avgt       3   4.025 ± 1.818   ms/op
ClientPb.createUser                     sample  280627   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.656           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.261           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.327           ms/op
ClientPb.existUser                      sample  283907   3.384 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.577           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.823           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  281800   3.406 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.604           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  241302   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
