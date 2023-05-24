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
# Warmup Iteration   1: 2.394 ops/ms
# Warmup Iteration   2: 5.728 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.608 ops/ms
Iteration   3: 9.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.565 ±(99.9%) 2.644 ops/ms [Average]
  (min, avg, max) = (9.404, 9.565, 9.684), stdev = 0.145
  CI (99.9%): [6.921, 12.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.996 ops/ms
# Warmup Iteration   2: 8.767 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.192 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (10.103, 10.192, 10.301), stdev = 0.101
  CI (99.9%): [8.357, 12.027] (assumes normal distribution)


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
# Warmup Iteration   1: 3.498 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.584 ops/ms
Iteration   1: 9.381 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 10.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.734 ±(99.9%) 5.868 ops/ms [Average]
  (min, avg, max) = (9.381, 9.734, 10.011), stdev = 0.322
  CI (99.9%): [3.866, 15.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 7.858 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.347 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (8.308, 8.347, 8.391), stdev = 0.042
  CI (99.9%): [7.584, 9.110] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.003 ms/op
Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
Iteration   3: 3.147 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.186 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.147, 3.186, 3.230), stdev = 0.042
  CI (99.9%): [2.422, 3.950] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.186 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.004 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
Iteration   3: 3.127 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.150 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.127, 3.150, 3.193), stdev = 0.038
  CI (99.9%): [2.462, 3.838] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.004 ms/op
Iteration   1: 3.388 ±(99.9%) 0.004 ms/op
Iteration   2: 3.335 ±(99.9%) 0.005 ms/op
Iteration   3: 3.216 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.313 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (3.216, 3.313, 3.388), stdev = 0.088
  CI (99.9%): [1.708, 4.918] (assumes normal distribution)


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
# Warmup Iteration   1: 9.784 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.008 ms/op
Iteration   1: 3.887 ±(99.9%) 0.006 ms/op
Iteration   2: 3.731 ±(99.9%) 0.012 ms/op
Iteration   3: 3.794 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.804 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (3.731, 3.804, 3.887), stdev = 0.078
  CI (99.9%): [2.373, 5.235] (assumes normal distribution)


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
# Warmup Iteration   1: 8.783 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  12.427 ms/op
                 createUser·p0.9999: 23.284 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.356 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  20.765 ms/op
                 createUser·p0.9999: 24.288 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.945 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.351 ms/op
                 createUser·p0.9999: 22.341 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289404
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18941 
    [ 2.500,  5.000) = 264396 
    [ 5.000,  7.500) = 4993 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     18.304 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 7.979 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 28.643 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.540 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.288 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  14.562 ms/op
                 existUser·p0.9999: 22.522 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298759
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23852 
    [ 2.500,  5.000) = 268520 
    [ 5.000,  7.500) = 5705 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     13.229 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     28.968 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 9.246 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.010 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  10.159 ms/op
                 getUser·p0.9999: 23.791 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.288 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  13.340 ms/op
                 getUser·p0.9999: 24.055 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  19.096 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289916
  mean =      3.310 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14509 
    [ 2.500,  5.000) = 267196 
    [ 5.000,  7.500) = 7145 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.796 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     24.393 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 10.243 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 25.945 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   2: 3.725 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.527 ms/op
                 listUser·p0.999:  14.440 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.804 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 15.352 ms/op
                 listUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252097
  mean =      3.807 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 245141 
    [ 5.000,  7.500) = 5166 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.039 ms/op
     p(99.9900) =     24.686 ms/op
     p(99.9990) =     26.129 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.565 ± 2.644  ops/ms
ClientPb.existUser                       thrpt       3  10.192 ± 1.835  ops/ms
ClientPb.getUser                         thrpt       3   9.734 ± 5.868  ops/ms
ClientPb.listUser                        thrpt       3   8.347 ± 0.763  ops/ms
ClientPb.createUser                       avgt       3   3.186 ± 0.764   ms/op
ClientPb.existUser                        avgt       3   3.150 ± 0.688   ms/op
ClientPb.getUser                          avgt       3   3.313 ± 1.605   ms/op
ClientPb.listUser                         avgt       3   3.804 ± 1.431   ms/op
ClientPb.createUser                     sample  289404   3.316 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.304           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.969           ms/op
ClientPb.existUser                      sample  298759   3.211 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.574           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.229           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.361           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.164           ms/op
ClientPb.getUser                        sample  289916   3.310 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.944           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.543           ms/op
ClientPb.listUser                       sample  252097   3.807 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.280           ms/op
