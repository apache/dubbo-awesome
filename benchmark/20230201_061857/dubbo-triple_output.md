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
# Warmup Iteration   1: 1.040 ops/ms
# Warmup Iteration   2: 2.590 ops/ms
# Warmup Iteration   3: 5.468 ops/ms
Iteration   1: 5.894 ops/ms
Iteration   2: 5.961 ops/ms
Iteration   3: 6.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.975 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (5.894, 5.975, 6.071), stdev = 0.089
  CI (99.9%): [4.345, 7.605] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 5.108 ops/ms
# Warmup Iteration   3: 6.159 ops/ms
Iteration   1: 6.456 ops/ms
Iteration   2: 6.441 ops/ms
Iteration   3: 6.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.428 ±(99.9%) 0.669 ops/ms [Average]
  (min, avg, max) = (6.386, 6.428, 6.456), stdev = 0.037
  CI (99.9%): [5.759, 7.097] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.697 ops/ms
# Warmup Iteration   2: 4.880 ops/ms
# Warmup Iteration   3: 6.074 ops/ms
Iteration   1: 6.034 ops/ms
Iteration   2: 6.171 ops/ms
Iteration   3: 6.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.110 ±(99.9%) 1.277 ops/ms [Average]
  (min, avg, max) = (6.034, 6.110, 6.171), stdev = 0.070
  CI (99.9%): [4.833, 7.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 4.400 ops/ms
# Warmup Iteration   3: 5.103 ops/ms
Iteration   1: 5.152 ops/ms
Iteration   2: 5.359 ops/ms
Iteration   3: 5.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.236 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (5.152, 5.236, 5.359), stdev = 0.109
  CI (99.9%): [3.249, 7.223] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.934 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.437 ±(99.9%) 0.017 ms/op
Iteration   1: 5.257 ±(99.9%) 0.009 ms/op
Iteration   2: 5.197 ±(99.9%) 0.018 ms/op
Iteration   3: 5.244 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.233 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (5.197, 5.233, 5.257), stdev = 0.031
  CI (99.9%): [4.659, 5.807] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.041 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.010 ms/op
Iteration   1: 5.124 ±(99.9%) 0.012 ms/op
Iteration   2: 5.087 ±(99.9%) 0.010 ms/op
Iteration   3: 5.013 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.075 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (5.013, 5.075, 5.124), stdev = 0.056
  CI (99.9%): [4.049, 6.101] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.431 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.620 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.310 ±(99.9%) 0.012 ms/op
Iteration   1: 5.423 ±(99.9%) 0.006 ms/op
Iteration   2: 5.102 ±(99.9%) 0.013 ms/op
Iteration   3: 5.176 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.234 ±(99.9%) 3.069 ms/op [Average]
  (min, avg, max) = (5.102, 5.234, 5.423), stdev = 0.168
  CI (99.9%): [2.164, 8.303] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.743 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.092 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.513 ±(99.9%) 0.010 ms/op
Iteration   1: 6.156 ±(99.9%) 0.018 ms/op
Iteration   2: 5.833 ±(99.9%) 0.025 ms/op
Iteration   3: 6.249 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.080 ±(99.9%) 3.989 ms/op [Average]
  (min, avg, max) = (5.833, 6.080, 6.249), stdev = 0.219
  CI (99.9%): [2.090, 10.069] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.607 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.884 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.029 ms/op
Iteration   1: 5.381 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  22.202 ms/op
                 createUser·p0.9999: 27.075 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 5.168 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.356 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  25.240 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 5.398 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   11.866 ms/op
                 createUser·p0.999:  28.228 ms/op
                 createUser·p0.9999: 31.928 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180586
  mean =      5.314 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 93097 
    [ 5.000,  7.500) = 77929 
    [ 7.500, 10.000) = 7610 
    [10.000, 12.500) = 1230 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     30.472 ms/op
     p(99.9990) =     32.293 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.616 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.488 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.229 ±(99.9%) 0.020 ms/op
Iteration   1: 5.441 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   7.438 ms/op
                 existUser·p0.95:   8.602 ms/op
                 existUser·p0.99:   11.902 ms/op
                 existUser·p0.999:  27.196 ms/op
                 existUser·p0.9999: 36.381 ms/op
                 existUser·p1.00:   36.569 ms/op

Iteration   2: 5.251 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.397 ms/op
                 existUser·p0.99:   10.498 ms/op
                 existUser·p0.999:  14.665 ms/op
                 existUser·p0.9999: 28.335 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 5.168 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   11.417 ms/op
                 existUser·p0.999:  27.236 ms/op
                 existUser·p0.9999: 34.525 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181598
  mean =      5.284 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 104427 
    [ 5.000,  7.500) = 64386 
    [ 7.500, 10.000) = 9503 
    [10.000, 12.500) = 2125 
    [12.500, 15.000) = 678 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     19.543 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.368 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.638 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.726 ±(99.9%) 0.023 ms/op
Iteration   1: 5.581 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.337 ms/op
                 getUser·p0.999:  26.566 ms/op
                 getUser·p0.9999: 30.599 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 5.530 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.560 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  16.452 ms/op
                 getUser·p0.9999: 28.627 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 5.377 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.499 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  26.529 ms/op
                 getUser·p0.9999: 29.478 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174545
  mean =      5.495 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 76857 
    [ 5.000,  7.500) = 84916 
    [ 7.500, 10.000) = 9007 
    [10.000, 12.500) = 2527 
    [12.500, 15.000) = 810 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     30.251 ms/op
     p(99.9990) =     33.935 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.644 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 7.661 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.558 ±(99.9%) 0.030 ms/op
Iteration   1: 6.955 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   9.781 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   14.598 ms/op
                 listUser·p0.999:  25.854 ms/op
                 listUser·p0.9999: 29.918 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   2: 7.520 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   6.742 ms/op
                 listUser·p0.90:   10.764 ms/op
                 listUser·p0.95:   12.435 ms/op
                 listUser·p0.99:   17.269 ms/op
                 listUser·p0.999:  31.276 ms/op
                 listUser·p0.9999: 37.961 ms/op
                 listUser·p1.00:   38.732 ms/op

Iteration   3: 6.684 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   14.467 ms/op
                 listUser·p0.999:  25.802 ms/op
                 listUser·p0.9999: 27.081 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136303
  mean =      7.036 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 6842 
    [ 5.000,  7.500) = 92897 
    [ 7.500, 10.000) = 23717 
    [10.000, 12.500) = 8644 
    [12.500, 15.000) = 2451 
    [15.000, 17.500) = 990 
    [17.500, 20.000) = 332 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      6.300 ms/op
     p(90.0000) =      9.847 ms/op
     p(95.0000) =     11.452 ms/op
     p(99.0000) =     15.614 ms/op
     p(99.9000) =     26.663 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     38.565 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.975 ± 1.630  ops/ms
ClientPb.existUser                       thrpt       3   6.428 ± 0.669  ops/ms
ClientPb.getUser                         thrpt       3   6.110 ± 1.277  ops/ms
ClientPb.listUser                        thrpt       3   5.236 ± 1.987  ops/ms
ClientPb.createUser                       avgt       3   5.233 ± 0.574   ms/op
ClientPb.existUser                        avgt       3   5.075 ± 1.026   ms/op
ClientPb.getUser                          avgt       3   5.234 ± 3.069   ms/op
ClientPb.listUser                         avgt       3   6.080 ± 3.989   ms/op
ClientPb.createUser                     sample  180586   5.314 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.477           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.578           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.109           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  181598   5.284 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.467           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.053           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.354           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.543           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.979           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  174545   5.495 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.035           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.298           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.649           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.166           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.251           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  136303   7.036 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.509           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.300           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.847           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.452           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.614           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.732           ms/op
