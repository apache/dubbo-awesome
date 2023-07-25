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
# Warmup Iteration   1: 1.712 ops/ms
# Warmup Iteration   2: 4.161 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.524 ops/ms
Iteration   2: 9.209 ops/ms
Iteration   3: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.907 ±(99.9%) 6.376 ops/ms [Average]
  (min, avg, max) = (8.524, 8.907, 9.209), stdev = 0.349
  CI (99.9%): [2.531, 15.283] (assumes normal distribution)


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
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 8.399 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.313 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (9.221, 9.313, 9.368), stdev = 0.080
  CI (99.9%): [7.850, 10.777] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 8.470 ops/ms
Iteration   1: 8.995 ops/ms
Iteration   2: 9.062 ops/ms
Iteration   3: 9.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.047 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (8.995, 9.047, 9.083), stdev = 0.046
  CI (99.9%): [8.214, 9.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 7.025 ops/ms
# Warmup Iteration   3: 7.661 ops/ms
Iteration   1: 7.525 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.767 ±(99.9%) 4.298 ops/ms [Average]
  (min, avg, max) = (7.525, 7.767, 7.996), stdev = 0.236
  CI (99.9%): [3.469, 12.065] (assumes normal distribution)


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
# Warmup Iteration   1: 11.543 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.004 ms/op
Iteration   1: 3.509 ±(99.9%) 0.005 ms/op
Iteration   2: 3.574 ±(99.9%) 0.007 ms/op
Iteration   3: 3.509 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.531 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.509, 3.531, 3.574), stdev = 0.037
  CI (99.9%): [2.850, 4.212] (assumes normal distribution)


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
# Warmup Iteration   1: 11.256 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.004 ms/op
Iteration   1: 3.390 ±(99.9%) 0.008 ms/op
Iteration   2: 3.343 ±(99.9%) 0.007 ms/op
Iteration   3: 3.350 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.361 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.343, 3.361, 3.390), stdev = 0.025
  CI (99.9%): [2.903, 3.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.161 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.002 ms/op
Iteration   1: 3.565 ±(99.9%) 0.008 ms/op
Iteration   2: 3.467 ±(99.9%) 0.005 ms/op
Iteration   3: 3.724 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.585 ±(99.9%) 2.361 ms/op [Average]
  (min, avg, max) = (3.467, 3.585, 3.724), stdev = 0.129
  CI (99.9%): [1.224, 5.946] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.525 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.007 ms/op
Iteration   1: 4.044 ±(99.9%) 0.008 ms/op
Iteration   2: 4.145 ±(99.9%) 0.005 ms/op
Iteration   3: 3.979 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.056 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.979, 4.056, 4.145), stdev = 0.083
  CI (99.9%): [2.537, 5.575] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.904 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
Iteration   1: 3.612 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  22.852 ms/op
                 createUser·p0.9999: 26.480 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 31.057 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   3: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  22.667 ms/op
                 createUser·p0.9999: 29.959 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273866
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267275 
    [ 5.000, 10.000) = 5991 
    [10.000, 15.000) = 237 
    [15.000, 20.000) = 68 
    [20.000, 25.000) = 113 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     22.680 ms/op
     p(99.9900) =     30.658 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 9.441 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.011 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  21.325 ms/op
                 existUser·p0.9999: 25.561 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  24.027 ms/op
                 existUser·p0.9999: 30.437 ms/op
                 existUser·p1.00:   32.899 ms/op

Iteration   3: 3.510 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  12.518 ms/op
                 existUser·p0.9999: 29.518 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279592
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2091 
    [ 2.500,  5.000) = 271601 
    [ 5.000,  7.500) = 4587 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     12.875 ms/op
     p(99.9900) =     29.525 ms/op
     p(99.9990) =     31.207 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 9.680 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.015 ms/op
Iteration   1: 3.554 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  22.872 ms/op
                 getUser·p0.9999: 24.772 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   2: 3.447 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  23.829 ms/op
                 getUser·p0.9999: 31.776 ms/op
                 getUser·p1.00:   32.244 ms/op

Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  21.022 ms/op
                 getUser·p0.9999: 31.222 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273850
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4842 
    [ 2.500,  5.000) = 260870 
    [ 5.000,  7.500) = 6446 
    [ 7.500, 10.000) = 1044 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     22.367 ms/op
     p(99.9900) =     30.560 ms/op
     p(99.9990) =     32.088 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.246 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.625 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.014 ms/op
Iteration   1: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  22.606 ms/op
                 listUser·p0.9999: 30.212 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   2: 4.178 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  17.577 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 4.243 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 22.311 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231470
  mean =      4.144 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 221706 
    [ 5.000,  7.500) = 7023 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     29.257 ms/op
     p(99.9990) =     30.940 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.907 ± 6.376  ops/ms
ClientPb.existUser                       thrpt       3   9.313 ± 1.464  ops/ms
ClientPb.getUser                         thrpt       3   9.047 ± 0.833  ops/ms
ClientPb.listUser                        thrpt       3   7.767 ± 4.298  ops/ms
ClientPb.createUser                       avgt       3   3.531 ± 0.681   ms/op
ClientPb.existUser                        avgt       3   3.361 ± 0.458   ms/op
ClientPb.getUser                          avgt       3   3.585 ± 2.361   ms/op
ClientPb.listUser                         avgt       3   4.056 ± 1.519   ms/op
ClientPb.createUser                     sample  273866   3.506 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.680           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.658           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.501           ms/op
ClientPb.existUser                      sample  279592   3.430 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.313           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.525           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899           ms/op
ClientPb.getUser                        sample  273850   3.505 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  231470   4.144 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.280           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.317           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899           ms/op
