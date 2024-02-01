# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.838 ops/ms
# Warmup Iteration   2: 12.109 ops/ms
# Warmup Iteration   3: 12.562 ops/ms
Iteration   1: 12.554 ops/ms
Iteration   2: 12.592 ops/ms
Iteration   3: 12.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.589 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (12.554, 12.589, 12.620), stdev = 0.033
  CI (99.9%): [11.983, 13.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.078 ops/ms
# Warmup Iteration   2: 12.927 ops/ms
# Warmup Iteration   3: 12.916 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.068 ops/ms
Iteration   3: 12.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.004 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (12.879, 13.004, 13.068), stdev = 0.109
  CI (99.9%): [11.017, 14.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.876 ops/ms
# Warmup Iteration   2: 12.601 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.812 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.800 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (12.739, 12.800, 12.849), stdev = 0.056
  CI (99.9%): [11.777, 13.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.957 ops/ms
# Warmup Iteration   2: 10.330 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.537 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (10.491, 10.537, 10.595), stdev = 0.053
  CI (99.9%): [9.571, 11.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.003 ms/op
Iteration   1: 2.596 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
Iteration   3: 2.533 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (2.533, 2.559, 2.596), stdev = 0.033
  CI (99.9%): [1.961, 3.156] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.447, 2.465, 2.492), stdev = 0.024
  CI (99.9%): [2.027, 2.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.483, 2.490, 2.495), stdev = 0.006
  CI (99.9%): [2.381, 2.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.996, 3.008, 3.021), stdev = 0.013
  CI (99.9%): [2.779, 3.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.649 ms/op
                 createUser·p0.999:  8.925 ms/op
                 createUser·p0.9999: 14.191 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  8.766 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 14.000 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383868
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185397 
    [ 2.500,  5.000) = 197783 
    [ 5.000,  7.500) = 266 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     13.838 ms/op
     p(99.9990) =     15.765 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  7.040 ms/op
                 existUser·p0.9999: 13.914 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  7.048 ms/op
                 existUser·p0.9999: 12.387 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.886 ms/op
                 existUser·p0.9999: 11.561 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388168
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 190553 
    [ 2.500,  3.750) = 193491 
    [ 3.750,  5.000) = 3115 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.797 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.594 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.589 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.073 ms/op
                 getUser·p0.999:  9.256 ms/op
                 getUser·p0.9999: 12.939 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  5.301 ms/op
                 getUser·p0.9999: 12.145 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384098
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 190861 
    [ 2.500,  3.750) = 189297 
    [ 3.750,  5.000) = 3106 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      5.874 ms/op
     p(99.9900) =     13.232 ms/op
     p(99.9990) =     14.145 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
Iteration   1: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.449 ms/op
                 listUser·p0.9999: 10.298 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  8.536 ms/op
                 listUser·p0.9999: 11.645 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.683 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.666 ms/op
                 listUser·p0.9999: 10.047 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323735
  mean =      2.963 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 100366 
    [ 2.500,  3.750) = 186339 
    [ 3.750,  5.000) = 30094 
    [ 5.000,  6.250) = 5624 
    [ 6.250,  7.500) = 602 
    [ 7.500,  8.750) = 286 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     10.889 ms/op
     p(99.9990) =     12.242 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.589 ± 0.606  ops/ms
ClientPb.existUser                       thrpt       3  13.004 ± 1.987  ops/ms
ClientPb.getUser                         thrpt       3  12.800 ± 1.023  ops/ms
ClientPb.listUser                        thrpt       3  10.537 ± 0.966  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.598   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.438   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.109   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.229   ms/op
ClientPb.createUser                     sample  383868   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.017           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.838           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.707           ms/op
ClientPb.existUser                      sample  388168   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.797           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  384098   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.232           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  323735   2.963 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.683           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.569           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.889           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
