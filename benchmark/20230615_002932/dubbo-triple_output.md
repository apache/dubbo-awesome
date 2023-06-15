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
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 9.754 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.836 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (9.754, 9.836, 9.928), stdev = 0.087
  CI (99.9%): [8.248, 11.425] (assumes normal distribution)


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
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 9.152 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.065 ops/ms
Iteration   2: 10.232 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.051 ±(99.9%) 3.430 ops/ms [Average]
  (min, avg, max) = (9.856, 10.051, 10.232), stdev = 0.188
  CI (99.9%): [6.620, 13.481] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 9.512 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.025 ops/ms
Iteration   3: 9.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.982 ±(99.9%) 0.786 ops/ms [Average]
  (min, avg, max) = (9.939, 9.982, 10.025), stdev = 0.043
  CI (99.9%): [9.196, 10.768] (assumes normal distribution)


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
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 7.620 ops/ms
# Warmup Iteration   3: 8.566 ops/ms
Iteration   1: 8.488 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.405 ±(99.9%) 3.400 ops/ms [Average]
  (min, avg, max) = (8.192, 8.405, 8.536), stdev = 0.186
  CI (99.9%): [5.005, 11.805] (assumes normal distribution)


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
# Warmup Iteration   1: 7.779 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.284 ±(99.9%) 0.006 ms/op
Iteration   2: 3.205 ±(99.9%) 0.004 ms/op
Iteration   3: 3.184 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.224 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.184, 3.224, 3.284), stdev = 0.053
  CI (99.9%): [2.262, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 7.116 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
Iteration   3: 3.265 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 2.843 ms/op [Average]
  (min, avg, max) = (2.975, 3.087, 3.265), stdev = 0.156
  CI (99.9%): [0.244, 5.930] (assumes normal distribution)


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
# Warmup Iteration   1: 6.960 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.004 ms/op
Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
Iteration   3: 3.269 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.193 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.137, 3.193, 3.269), stdev = 0.068
  CI (99.9%): [1.946, 4.441] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.008 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.005 ms/op
Iteration   1: 3.783 ±(99.9%) 0.009 ms/op
Iteration   2: 3.825 ±(99.9%) 0.009 ms/op
Iteration   3: 3.816 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.808 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.783, 3.808, 3.825), stdev = 0.022
  CI (99.9%): [3.400, 4.216] (assumes normal distribution)


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
# Warmup Iteration   1: 7.540 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 21.357 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.191 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.599 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.898 ms/op
                 createUser·p0.9999: 24.680 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306447
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11486 
    [ 2.500,  5.000) = 291453 
    [ 5.000,  7.500) = 2652 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     15.648 ms/op
     p(99.9900) =     27.614 ms/op
     p(99.9990) =     29.649 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 7.663 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 20.072 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.631 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 22.589 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 33.564 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296355
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25892 
    [ 2.500,  5.000) = 264282 
    [ 5.000,  7.500) = 5617 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      8.988 ms/op
     p(99.9900) =     32.747 ms/op
     p(99.9990) =     34.285 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 8.442 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.010 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  10.336 ms/op
                 getUser·p0.9999: 20.620 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  10.172 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.345 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  18.490 ms/op
                 getUser·p0.9999: 26.884 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294006
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14577 
    [ 2.500,  5.000) = 271890 
    [ 5.000,  7.500) = 6524 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     25.467 ms/op
     p(99.9990) =     27.330 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 9.213 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.012 ms/op
Iteration   1: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.486 ms/op
                 listUser·p0.999:  15.068 ms/op
                 listUser·p0.9999: 18.334 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.675 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   6.375 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256947
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 23 
    [ 2.500,  3.750) = 194852 
    [ 3.750,  5.000) = 55110 
    [ 5.000,  6.250) = 3056 
    [ 6.250,  7.500) = 2134 
    [ 7.500,  8.750) = 663 
    [ 8.750, 10.000) = 405 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 202 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 80 
    [17.500, 18.750) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.648 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.836 ± 1.589  ops/ms
ClientPb.existUser                       thrpt       3  10.051 ± 3.430  ops/ms
ClientPb.getUser                         thrpt       3   9.982 ± 0.786  ops/ms
ClientPb.listUser                        thrpt       3   8.405 ± 3.400  ops/ms
ClientPb.createUser                       avgt       3   3.224 ± 0.962   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 2.843   ms/op
ClientPb.getUser                          avgt       3   3.193 ± 1.248   ms/op
ClientPb.listUser                         avgt       3   3.808 ± 0.408   ms/op
ClientPb.createUser                     sample  306447   3.130 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.614           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  296355   3.238 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.988           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.747           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  294006   3.266 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.467           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  256947   3.735 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.137           ms/op
