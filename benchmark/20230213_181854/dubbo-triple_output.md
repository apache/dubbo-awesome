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
# Warmup Iteration   1: 2.597 ops/ms
# Warmup Iteration   2: 6.689 ops/ms
# Warmup Iteration   3: 9.459 ops/ms
Iteration   1: 9.576 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 9.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.772 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (9.576, 9.772, 9.890), stdev = 0.171
  CI (99.9%): [6.652, 12.893] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 9.190 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.020 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.249 ±(99.9%) 5.057 ops/ms [Average]
  (min, avg, max) = (10.020, 10.249, 10.557), stdev = 0.277
  CI (99.9%): [5.192, 15.306] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ops/ms
# Warmup Iteration   2: 8.774 ops/ms
# Warmup Iteration   3: 10.093 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 9.789 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.929 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (9.789, 9.929, 10.049), stdev = 0.131
  CI (99.9%): [7.539, 12.319] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.713 ops/ms
Iteration   2: 8.543 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.623 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (8.543, 8.623, 8.713), stdev = 0.085
  CI (99.9%): [7.065, 10.182] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.001 ms/op
Iteration   1: 3.129 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
Iteration   3: 3.044 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.078 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (3.044, 3.078, 3.129), stdev = 0.045
  CI (99.9%): [2.255, 3.900] (assumes normal distribution)


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
# Warmup Iteration   1: 6.971 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.004 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.986 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.969, 2.986, 3.004), stdev = 0.018
  CI (99.9%): [2.666, 3.306] (assumes normal distribution)


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
# Warmup Iteration   1: 8.046 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.003 ms/op
Iteration   1: 3.213 ±(99.9%) 0.006 ms/op
Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
Iteration   3: 3.237 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (3.093, 3.181, 3.237), stdev = 0.077
  CI (99.9%): [1.770, 4.592] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.684 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.006 ms/op
Iteration   1: 3.757 ±(99.9%) 0.006 ms/op
Iteration   2: 3.707 ±(99.9%) 0.007 ms/op
Iteration   3: 3.658 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.658, 3.707, 3.757), stdev = 0.050
  CI (99.9%): [2.799, 4.616] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  18.810 ms/op
                 createUser·p0.9999: 25.130 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.215 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.566 ms/op
                 createUser·p0.9999: 23.075 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.555 ms/op
                 createUser·p0.999:  12.324 ms/op
                 createUser·p0.9999: 24.539 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305431
  mean =      3.141 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20050 
    [ 2.500,  5.000) = 280639 
    [ 5.000,  7.500) = 3881 
    [ 7.500, 10.000) = 421 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     24.394 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.427 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.008 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  13.593 ms/op
                 existUser·p0.9999: 20.336 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  15.696 ms/op
                 existUser·p0.9999: 22.274 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.808 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307239
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13731 
    [ 2.500,  5.000) = 288779 
    [ 5.000,  7.500) = 3955 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     10.056 ms/op
     p(99.9900) =     22.029 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 7.695 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.011 ms/op
Iteration   1: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 21.426 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  20.329 ms/op
                 getUser·p0.9999: 25.069 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  10.135 ms/op
                 getUser·p0.9999: 23.781 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295514
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14723 
    [ 2.500,  5.000) = 272258 
    [ 5.000,  7.500) = 7692 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     15.016 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.190 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 8.131 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.460 ms/op
                 listUser·p0.9999: 25.583 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.744 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.346 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.171 ms/op
                 listUser·p0.9999: 15.815 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255114
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 246605 
    [ 5.000,  7.500) = 6585 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     22.560 ms/op
     p(99.9990) =     25.939 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.772 ± 3.120  ops/ms
ClientPb.existUser                       thrpt       3  10.249 ± 5.057  ops/ms
ClientPb.getUser                         thrpt       3   9.929 ± 2.390  ops/ms
ClientPb.listUser                        thrpt       3   8.623 ± 1.559  ops/ms
ClientPb.createUser                       avgt       3   3.078 ± 0.822   ms/op
ClientPb.existUser                        avgt       3   2.986 ± 0.320   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 1.411   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 0.909   ms/op
ClientPb.createUser                     sample  305431   3.141 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.394           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  307239   3.121 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.029           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.642           ms/op
ClientPb.getUser                        sample  295514   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.016           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  255114   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.582           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.560           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
