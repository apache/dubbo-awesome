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
# Warmup Iteration   1: 2.133 ops/ms
# Warmup Iteration   2: 5.413 ops/ms
# Warmup Iteration   3: 8.814 ops/ms
Iteration   1: 8.946 ops/ms
Iteration   2: 9.177 ops/ms
Iteration   3: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.096 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (8.946, 9.096, 9.177), stdev = 0.130
  CI (99.9%): [6.727, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 3.000 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.494 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 10.030 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.944 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (9.794, 9.944, 10.030), stdev = 0.130
  CI (99.9%): [7.578, 12.309] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.952 ops/ms
# Warmup Iteration   2: 8.555 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.013 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.271 ±(99.9%) 4.543 ops/ms [Average]
  (min, avg, max) = (9.013, 9.271, 9.510), stdev = 0.249
  CI (99.9%): [4.728, 13.814] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 7.294 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.168 ±(99.9%) 1.898 ops/ms [Average]
  (min, avg, max) = (8.095, 8.168, 8.287), stdev = 0.104
  CI (99.9%): [6.270, 10.066] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.025 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.005 ms/op
Iteration   1: 3.284 ±(99.9%) 0.006 ms/op
Iteration   2: 3.392 ±(99.9%) 0.004 ms/op
Iteration   3: 3.379 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.352 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.284, 3.352, 3.392), stdev = 0.059
  CI (99.9%): [2.277, 4.427] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.693 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.003 ms/op
Iteration   1: 3.283 ±(99.9%) 0.006 ms/op
Iteration   2: 3.376 ±(99.9%) 0.005 ms/op
Iteration   3: 3.383 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.347 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.283, 3.347, 3.383), stdev = 0.056
  CI (99.9%): [2.324, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 8.104 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.002 ms/op
Iteration   1: 3.416 ±(99.9%) 0.008 ms/op
Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
Iteration   3: 3.334 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.339 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.267, 3.339, 3.416), stdev = 0.075
  CI (99.9%): [1.974, 4.704] (assumes normal distribution)


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
# Warmup Iteration   1: 9.936 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.010 ms/op
Iteration   1: 4.019 ±(99.9%) 0.015 ms/op
Iteration   2: 3.860 ±(99.9%) 0.011 ms/op
Iteration   3: 3.802 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.894 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (3.802, 3.894, 4.019), stdev = 0.112
  CI (99.9%): [1.844, 5.943] (assumes normal distribution)


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
# Warmup Iteration   1: 8.528 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  20.785 ms/op
                 createUser·p0.9999: 23.289 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.566 ms/op
                 createUser·p0.999:  22.846 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.755 ms/op
                 createUser·p0.9999: 25.616 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284977
  mean =      3.367 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11697 
    [ 2.500,  5.000) = 266518 
    [ 5.000,  7.500) = 5596 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 181 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     25.150 ms/op
     p(99.9990) =     25.826 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 9.728 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 23.692 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.220 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  16.414 ms/op
                 existUser·p0.9999: 24.346 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  18.080 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294282
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19547 
    [ 2.500,  5.000) = 270627 
    [ 5.000,  7.500) = 3116 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     24.136 ms/op
     p(99.9990) =     25.464 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.367 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
Iteration   1: 3.470 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  21.871 ms/op
                 getUser·p0.9999: 29.222 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.442 ms/op
                 getUser·p0.999:  21.911 ms/op
                 getUser·p0.9999: 25.578 ms/op
                 getUser·p1.00:   30.704 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281215
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7455 
    [ 2.500,  5.000) = 267657 
    [ 5.000,  7.500) = 5102 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     20.466 ms/op
     p(99.9900) =     26.731 ms/op
     p(99.9990) =     29.891 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 10.752 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.014 ms/op
Iteration   1: 3.970 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  19.972 ms/op
                 listUser·p0.9999: 29.227 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  18.048 ms/op
                 listUser·p0.9999: 21.364 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.795 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 20.196 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240540
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 230985 
    [ 5.000,  7.500) = 7242 
    [ 7.500, 10.000) = 1430 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     31.955 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.096 ± 2.369  ops/ms
ClientPb.existUser                       thrpt       3   9.944 ± 2.365  ops/ms
ClientPb.getUser                         thrpt       3   9.271 ± 4.543  ops/ms
ClientPb.listUser                        thrpt       3   8.168 ± 1.898  ops/ms
ClientPb.createUser                       avgt       3   3.352 ± 1.075   ms/op
ClientPb.existUser                        avgt       3   3.347 ± 1.023   ms/op
ClientPb.getUser                          avgt       3   3.339 ± 1.365   ms/op
ClientPb.listUser                         avgt       3   3.894 ± 2.049   ms/op
ClientPb.createUser                     sample  284977   3.367 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.150           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.919           ms/op
ClientPb.existUser                      sample  294282   3.260 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.781           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.566           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.136           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  281215   3.410 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.731           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  240540   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.227           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.629           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014           ms/op
