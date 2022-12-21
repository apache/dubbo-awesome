# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.285 ops/ms
# Warmup Iteration   2: 2.921 ops/ms
# Warmup Iteration   3: 5.986 ops/ms
Iteration   1: 6.201 ops/ms
Iteration   2: 6.475 ops/ms
Iteration   3: 6.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.369 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (6.201, 6.369, 6.475), stdev = 0.147
  CI (99.9%): [3.685, 9.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 5.815 ops/ms
# Warmup Iteration   3: 6.822 ops/ms
Iteration   1: 6.350 ops/ms
Iteration   2: 6.976 ops/ms
Iteration   3: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.722 ±(99.9%) 6.015 ops/ms [Average]
  (min, avg, max) = (6.350, 6.722, 6.976), stdev = 0.330
  CI (99.9%): [0.707, 12.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 5.343 ops/ms
# Warmup Iteration   3: 6.434 ops/ms
Iteration   1: 6.765 ops/ms
Iteration   2: 6.516 ops/ms
Iteration   3: 6.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.558 ±(99.9%) 3.452 ops/ms [Average]
  (min, avg, max) = (6.394, 6.558, 6.765), stdev = 0.189
  CI (99.9%): [3.106, 10.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.762 ops/ms
# Warmup Iteration   2: 4.733 ops/ms
# Warmup Iteration   3: 5.806 ops/ms
Iteration   1: 5.664 ops/ms
Iteration   2: 5.788 ops/ms
Iteration   3: 5.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.772 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (5.664, 5.772, 5.864), stdev = 0.101
  CI (99.9%): [3.932, 7.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.818 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.009 ms/op
Iteration   1: 4.594 ±(99.9%) 0.009 ms/op
Iteration   2: 4.649 ±(99.9%) 0.016 ms/op
Iteration   3: 4.483 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.575 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (4.483, 4.575, 4.649), stdev = 0.084
  CI (99.9%): [3.036, 6.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.367 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.526 ±(99.9%) 0.008 ms/op
Iteration   1: 4.262 ±(99.9%) 0.014 ms/op
Iteration   2: 4.463 ±(99.9%) 0.008 ms/op
Iteration   3: 4.481 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.402 ±(99.9%) 2.212 ms/op [Average]
  (min, avg, max) = (4.262, 4.402, 4.481), stdev = 0.121
  CI (99.9%): [2.190, 6.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.943 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.361 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.657 ±(99.9%) 0.017 ms/op
Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
Iteration   2: 4.697 ±(99.9%) 0.012 ms/op
Iteration   3: 4.652 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.657 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (4.623, 4.657, 4.697), stdev = 0.037
  CI (99.9%): [3.982, 5.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.158 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.502 ±(99.9%) 0.015 ms/op
Iteration   1: 5.379 ±(99.9%) 0.014 ms/op
Iteration   2: 5.447 ±(99.9%) 0.019 ms/op
Iteration   3: 5.349 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.392 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (5.349, 5.392, 5.447), stdev = 0.051
  CI (99.9%): [4.468, 6.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.330 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.929 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.240 ±(99.9%) 0.021 ms/op
Iteration   1: 4.696 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   8.806 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 27.007 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 4.563 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   8.333 ms/op
                 createUser·p0.999:  14.472 ms/op
                 createUser·p0.9999: 26.772 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   3: 4.741 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 27.926 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 205577
  mean =      4.666 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 161798 
    [ 5.000,  7.500) = 39362 
    [ 7.500, 10.000) = 3038 
    [10.000, 12.500) = 764 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     21.739 ms/op
     p(99.9900) =     27.376 ms/op
     p(99.9990) =     28.630 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.118 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.012 ms/op
Iteration   1: 4.544 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   8.020 ms/op
                 existUser·p0.999:  13.755 ms/op
                 existUser·p0.9999: 25.981 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 4.516 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   6.152 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  20.395 ms/op
                 existUser·p0.9999: 22.900 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 4.556 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  15.775 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 211394
  mean =      4.539 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 175967 
    [ 5.000,  7.500) = 31220 
    [ 7.500, 10.000) = 3105 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     19.648 ms/op
     p(99.9900) =     25.784 ms/op
     p(99.9990) =     27.834 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.034 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.380 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.015 ms/op
Iteration   1: 4.948 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.388 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   11.452 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 24.366 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   2: 4.698 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.629 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  19.331 ms/op
                 getUser·p0.9999: 26.153 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 4.654 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.466 ms/op
                 getUser·p0.999:  15.954 ms/op
                 getUser·p0.9999: 30.450 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 201371
  mean =      4.764 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 156155 
    [ 5.000,  7.500) = 38842 
    [ 7.500, 10.000) = 4429 
    [10.000, 12.500) = 1193 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     19.321 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     31.094 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.011 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.607 ±(99.9%) 0.021 ms/op
Iteration   1: 5.503 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  23.811 ms/op
                 listUser·p0.9999: 27.499 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   2: 5.445 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  24.070 ms/op
                 listUser·p0.9999: 30.293 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   3: 5.384 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 30.050 ms/op
                 listUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 176211
  mean =      5.444 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 61178 
    [ 5.000,  7.500) = 107565 
    [ 7.500, 10.000) = 5556 
    [10.000, 12.500) = 1169 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     22.996 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     31.340 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.369 ± 2.684  ops/ms
ClientPb.existUser                       thrpt       3   6.722 ± 6.015  ops/ms
ClientPb.getUser                         thrpt       3   6.558 ± 3.452  ops/ms
ClientPb.listUser                        thrpt       3   5.772 ± 1.841  ops/ms
ClientPb.createUser                       avgt       3   4.575 ± 1.540   ms/op
ClientPb.existUser                        avgt       3   4.402 ± 2.212   ms/op
ClientPb.getUser                          avgt       3   4.657 ± 0.675   ms/op
ClientPb.listUser                         avgt       3   5.392 ± 0.924   ms/op
ClientPb.createUser                     sample  205577   4.666 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.102           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.733           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.739           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  211394   4.539 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.714           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.439           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.784           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.886           ms/op
ClientPb.getUser                        sample  201371   4.764 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.321           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.901           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  176211   5.444 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.292           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.125           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.996           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.048           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.490           ms/op
