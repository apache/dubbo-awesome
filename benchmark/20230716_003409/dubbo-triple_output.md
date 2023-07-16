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
# Warmup Iteration   1: 1.179 ops/ms
# Warmup Iteration   2: 2.439 ops/ms
# Warmup Iteration   3: 5.620 ops/ms
Iteration   1: 5.613 ops/ms
Iteration   2: 5.810 ops/ms
Iteration   3: 5.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.759 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (5.613, 5.759, 5.854), stdev = 0.129
  CI (99.9%): [3.412, 8.106] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.877 ops/ms
# Warmup Iteration   2: 5.073 ops/ms
# Warmup Iteration   3: 6.501 ops/ms
Iteration   1: 6.512 ops/ms
Iteration   2: 6.274 ops/ms
Iteration   3: 6.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.385 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (6.274, 6.385, 6.512), stdev = 0.120
  CI (99.9%): [4.202, 8.568] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.488 ops/ms
# Warmup Iteration   2: 4.593 ops/ms
# Warmup Iteration   3: 5.843 ops/ms
Iteration   1: 6.328 ops/ms
Iteration   2: 6.060 ops/ms
Iteration   3: 6.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.174 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (6.060, 6.174, 6.328), stdev = 0.138
  CI (99.9%): [3.652, 8.696] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 4.460 ops/ms
# Warmup Iteration   3: 5.096 ops/ms
Iteration   1: 5.136 ops/ms
Iteration   2: 5.329 ops/ms
Iteration   3: 5.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.281 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (5.136, 5.281, 5.380), stdev = 0.129
  CI (99.9%): [2.934, 7.629] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.005 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 7.167 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.672 ±(99.9%) 0.009 ms/op
Iteration   1: 5.460 ±(99.9%) 0.010 ms/op
Iteration   2: 5.161 ±(99.9%) 0.018 ms/op
Iteration   3: 5.403 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.341 ±(99.9%) 2.899 ms/op [Average]
  (min, avg, max) = (5.161, 5.341, 5.460), stdev = 0.159
  CI (99.9%): [2.442, 8.240] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.418 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.565 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.088 ±(99.9%) 0.009 ms/op
Iteration   1: 5.124 ±(99.9%) 0.014 ms/op
Iteration   2: 5.027 ±(99.9%) 0.013 ms/op
Iteration   3: 4.859 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.003 ±(99.9%) 2.437 ms/op [Average]
  (min, avg, max) = (4.859, 5.003, 5.124), stdev = 0.134
  CI (99.9%): [2.566, 7.440] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.930 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.011 ms/op
Iteration   1: 5.343 ±(99.9%) 0.017 ms/op
Iteration   2: 5.407 ±(99.9%) 0.010 ms/op
Iteration   3: 5.057 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.269 ±(99.9%) 3.400 ms/op [Average]
  (min, avg, max) = (5.057, 5.269, 5.407), stdev = 0.186
  CI (99.9%): [1.869, 8.669] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.961 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.094 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.419 ±(99.9%) 0.014 ms/op
Iteration   1: 6.181 ±(99.9%) 0.024 ms/op
Iteration   2: 6.300 ±(99.9%) 0.013 ms/op
Iteration   3: 6.112 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.198 ±(99.9%) 1.739 ms/op [Average]
  (min, avg, max) = (6.112, 6.198, 6.300), stdev = 0.095
  CI (99.9%): [4.459, 7.936] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.415 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.934 ±(99.9%) 0.027 ms/op
Iteration   1: 5.235 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  19.235 ms/op
                 createUser·p0.9999: 27.533 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 5.329 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.070 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 34.932 ms/op
                 createUser·p1.00:   36.504 ms/op

Iteration   3: 5.374 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 27.035 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180547
  mean =      5.312 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 82765 
    [ 5.000,  7.500) = 90334 
    [ 7.500, 10.000) = 5495 
    [10.000, 12.500) = 1204 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =     10.085 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     29.963 ms/op
     p(99.9990) =     36.240 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.629 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.377 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.243 ±(99.9%) 0.018 ms/op
Iteration   1: 4.973 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.578 ms/op
                 existUser·p0.99:   9.519 ms/op
                 existUser·p0.999:  20.206 ms/op
                 existUser·p0.9999: 27.544 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   2: 5.101 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  24.529 ms/op
                 existUser·p0.9999: 29.742 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   3: 5.099 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  26.621 ms/op
                 existUser·p0.9999: 32.824 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189807
  mean =      5.057 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 113448 
    [ 5.000,  7.500) = 69906 
    [ 7.500, 10.000) = 4781 
    [10.000, 12.500) = 1037 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     23.743 ms/op
     p(99.9900) =     31.428 ms/op
     p(99.9990) =     35.265 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.993 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 5.808 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.608 ±(99.9%) 0.022 ms/op
Iteration   1: 5.335 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   11.010 ms/op
                 getUser·p0.999:  23.829 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   2: 5.261 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.544 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.201 ms/op
                 getUser·p0.99:   9.585 ms/op
                 getUser·p0.999:  29.054 ms/op
                 getUser·p0.9999: 36.629 ms/op
                 getUser·p1.00:   37.093 ms/op

Iteration   3: 5.394 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.822 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   9.585 ms/op
                 getUser·p0.999:  29.230 ms/op
                 getUser·p0.9999: 33.002 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180055
  mean =      5.329 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 82562 
    [ 5.000,  7.500) = 89326 
    [ 7.500, 10.000) = 6370 
    [10.000, 12.500) = 1203 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     36.988 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.295 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.996 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.512 ±(99.9%) 0.026 ms/op
Iteration   1: 6.041 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.465 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   11.152 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 25.025 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 6.254 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  29.131 ms/op
                 listUser·p0.9999: 32.531 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   3: 6.217 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  24.089 ms/op
                 listUser·p0.9999: 41.278 ms/op
                 listUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155508
  mean =      6.169 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10819 
    [ 5.000, 10.000) = 141669 
    [10.000, 15.000) = 2619 
    [15.000, 20.000) = 85 
    [20.000, 25.000) = 144 
    [25.000, 30.000) = 104 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     25.738 ms/op
     p(99.9900) =     39.017 ms/op
     p(99.9990) =     41.899 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.759 ± 2.347  ops/ms
ClientPb.existUser                       thrpt       3   6.385 ± 2.183  ops/ms
ClientPb.getUser                         thrpt       3   6.174 ± 2.522  ops/ms
ClientPb.listUser                        thrpt       3   5.281 ± 2.348  ops/ms
ClientPb.createUser                       avgt       3   5.341 ± 2.899   ms/op
ClientPb.existUser                        avgt       3   5.003 ± 2.437   ms/op
ClientPb.getUser                          avgt       3   5.269 ± 3.400   ms/op
ClientPb.listUser                         avgt       3   6.198 ± 1.739   ms/op
ClientPb.createUser                     sample  180547   5.312 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.085           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.963           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.504           ms/op
ClientPb.existUser                      sample  189807   5.057 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.753           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.667           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  180055   5.329 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.079           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.717           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  155508   6.169 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.905           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.256           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.738           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.009           ms/op
