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
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 5.830 ops/ms
# Warmup Iteration   3: 8.589 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.194 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (9.120, 9.194, 9.236), stdev = 0.064
  CI (99.9%): [8.018, 10.371] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 9.682 ops/ms
Iteration   2: 9.873 ops/ms
Iteration   3: 9.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.798 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (9.682, 9.798, 9.873), stdev = 0.102
  CI (99.9%): [7.939, 11.658] (assumes normal distribution)


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
# Warmup Iteration   1: 2.848 ops/ms
# Warmup Iteration   2: 8.720 ops/ms
# Warmup Iteration   3: 9.047 ops/ms
Iteration   1: 9.319 ops/ms
Iteration   2: 9.503 ops/ms
Iteration   3: 9.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.438 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (9.319, 9.438, 9.503), stdev = 0.103
  CI (99.9%): [7.558, 11.319] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 7.337 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 7.825 ops/ms
Iteration   3: 7.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.894 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (7.825, 7.894, 7.984), stdev = 0.082
  CI (99.9%): [6.402, 9.386] (assumes normal distribution)


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
# Warmup Iteration   1: 11.475 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.004 ms/op
Iteration   1: 3.545 ±(99.9%) 0.006 ms/op
Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
Iteration   3: 3.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.489 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (3.426, 3.489, 3.545), stdev = 0.060
  CI (99.9%): [2.396, 4.582] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.555 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.005 ms/op
Iteration   1: 3.346 ±(99.9%) 0.004 ms/op
Iteration   2: 3.320 ±(99.9%) 0.007 ms/op
Iteration   3: 3.338 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.320, 3.335, 3.346), stdev = 0.013
  CI (99.9%): [3.098, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 9.881 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.003 ms/op
Iteration   1: 3.399 ±(99.9%) 0.005 ms/op
Iteration   2: 3.380 ±(99.9%) 0.004 ms/op
Iteration   3: 3.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.400 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.380, 3.400, 3.421), stdev = 0.020
  CI (99.9%): [3.032, 3.768] (assumes normal distribution)


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
# Warmup Iteration   1: 10.026 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.006 ms/op
Iteration   1: 4.007 ±(99.9%) 0.006 ms/op
Iteration   2: 4.017 ±(99.9%) 0.005 ms/op
Iteration   3: 4.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.018 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (4.007, 4.018, 4.031), stdev = 0.012
  CI (99.9%): [3.802, 4.235] (assumes normal distribution)


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
# Warmup Iteration   1: 9.542 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
Iteration   1: 3.497 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  20.418 ms/op
                 createUser·p0.9999: 23.293 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.433 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  21.854 ms/op
                 createUser·p0.9999: 24.690 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.508 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  19.787 ms/op
                 createUser·p0.9999: 25.166 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275630
  mean =      3.479 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4209 
    [ 2.500,  5.000) = 266716 
    [ 5.000,  7.500) = 3783 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     20.132 ms/op
     p(99.9900) =     24.885 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 8.156 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
Iteration   1: 3.294 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  14.422 ms/op
                 existUser·p0.9999: 21.745 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.977 ms/op
                 existUser·p0.999:  14.149 ms/op
                 existUser·p0.9999: 22.168 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  17.877 ms/op
                 existUser·p0.9999: 24.623 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290077
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10405 
    [ 2.500,  5.000) = 274812 
    [ 5.000,  7.500) = 3923 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     14.216 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.205 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.783 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
Iteration   1: 3.460 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  14.215 ms/op
                 getUser·p0.9999: 19.916 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.458 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 22.036 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  18.205 ms/op
                 getUser·p0.9999: 28.171 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275414
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10229 
    [ 2.500,  5.000) = 257944 
    [ 5.000,  7.500) = 6106 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     16.887 ms/op
     p(99.9900) =     27.106 ms/op
     p(99.9990) =     29.049 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 11.087 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
Iteration   1: 4.141 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  19.634 ms/op
                 listUser·p0.9999: 23.831 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.066 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.079 ms/op
                 listUser·p0.9999: 17.241 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.109 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.518 ms/op
                 listUser·p0.999:  13.656 ms/op
                 listUser·p0.9999: 16.981 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233755
  mean =      4.105 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 225037 
    [ 5.000,  7.500) = 6705 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.180 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     24.488 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.194 ± 1.176  ops/ms
ClientPb.existUser                       thrpt       3   9.798 ± 1.859  ops/ms
ClientPb.getUser                         thrpt       3   9.438 ± 1.880  ops/ms
ClientPb.listUser                        thrpt       3   7.894 ± 1.492  ops/ms
ClientPb.createUser                       avgt       3   3.489 ± 1.093   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   3.400 ± 0.368   ms/op
ClientPb.listUser                         avgt       3   4.018 ± 0.216   ms/op
ClientPb.createUser                     sample  275630   3.479 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.132           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.885           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.657           ms/op
ClientPb.existUser                      sample  290077   3.308 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.216           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.788           ms/op
ClientPb.getUser                        sample  275414   3.481 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.081           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.887           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.106           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.688           ms/op
ClientPb.listUser                       sample  233755   4.105 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.223           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.180           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
