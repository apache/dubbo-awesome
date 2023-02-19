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
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 5.940 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.531 ops/ms
Iteration   2: 9.351 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.469 ±(99.9%) 1.857 ops/ms [Average]
  (min, avg, max) = (9.351, 9.469, 9.531), stdev = 0.102
  CI (99.9%): [7.612, 11.325] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 8.968 ops/ms
# Warmup Iteration   3: 9.540 ops/ms
Iteration   1: 10.032 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.082 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (10.032, 10.082, 10.147), stdev = 0.059
  CI (99.9%): [9.003, 11.161] (assumes normal distribution)


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
# Warmup Iteration   1: 3.058 ops/ms
# Warmup Iteration   2: 8.601 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.331 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.505 ±(99.9%) 3.703 ops/ms [Average]
  (min, avg, max) = (9.331, 9.505, 9.728), stdev = 0.203
  CI (99.9%): [5.802, 13.208] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.978 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (7.879, 7.978, 8.159), stdev = 0.157
  CI (99.9%): [5.118, 10.838] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.007 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
Iteration   2: 3.378 ±(99.9%) 0.011 ms/op
Iteration   3: 3.494 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (3.378, 3.418, 3.494), stdev = 0.066
  CI (99.9%): [2.223, 4.613] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.003 ms/op
Iteration   1: 3.273 ±(99.9%) 0.005 ms/op
Iteration   2: 3.236 ±(99.9%) 0.011 ms/op
Iteration   3: 3.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (3.236, 3.294, 3.372), stdev = 0.070
  CI (99.9%): [2.012, 4.575] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.482 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.006 ms/op
Iteration   1: 3.405 ±(99.9%) 0.006 ms/op
Iteration   2: 3.311 ±(99.9%) 0.013 ms/op
Iteration   3: 3.438 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.385 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.311, 3.385, 3.438), stdev = 0.066
  CI (99.9%): [2.181, 4.589] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.518 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.008 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
Iteration   2: 4.055 ±(99.9%) 0.010 ms/op
Iteration   3: 3.967 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.880, 3.967, 4.055), stdev = 0.087
  CI (99.9%): [2.375, 5.560] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.916 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.376 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  19.833 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  21.734 ms/op
                 createUser·p0.9999: 24.298 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  14.386 ms/op
                 createUser·p0.9999: 26.854 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284162
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12925 
    [ 2.500,  5.000) = 265506 
    [ 5.000,  7.500) = 4874 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     16.725 ms/op
     p(99.9900) =     25.742 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 7.927 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.008 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.714 ms/op
                 existUser·p0.999:  19.089 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 26.001 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.381 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  20.330 ms/op
                 existUser·p0.9999: 33.081 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285766
  mean =      3.358 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6195 
    [ 2.500,  5.000) = 274229 
    [ 5.000,  7.500) = 4355 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     33.461 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 7.701 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
Iteration   1: 3.478 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  20.808 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  23.101 ms/op
                 getUser·p0.9999: 25.160 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.991 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 25.688 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274510
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13952 
    [ 2.500,  5.000) = 252992 
    [ 5.000,  7.500) = 6611 
    [ 7.500, 10.000) = 575 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     20.216 ms/op
     p(99.9900) =     25.675 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 9.702 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.632 ms/op
                 listUser·p0.9999: 26.839 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.799 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  17.781 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241986
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 231106 
    [ 5.000,  7.500) = 8834 
    [ 7.500, 10.000) = 1119 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     24.760 ms/op
     p(99.9990) =     27.137 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.469 ± 1.857  ops/ms
ClientPb.existUser                       thrpt       3  10.082 ± 1.079  ops/ms
ClientPb.getUser                         thrpt       3   9.505 ± 3.703  ops/ms
ClientPb.listUser                        thrpt       3   7.978 ± 2.860  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 1.195   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 1.281   ms/op
ClientPb.getUser                          avgt       3   3.385 ± 1.204   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 1.593   ms/op
ClientPb.createUser                     sample  284162   3.374 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.725           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.742           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  285766   3.358 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.087           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.588           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  274510   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.555           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.675           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  241986   3.965 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.481           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.351           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
