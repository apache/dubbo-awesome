# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.491 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.773 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.529 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (8.320, 8.529, 8.773), stdev = 0.228
  CI (99.9%): [4.366, 12.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.167 ops/ms
# Warmup Iteration   2: 8.735 ops/ms
# Warmup Iteration   3: 8.690 ops/ms
Iteration   1: 8.991 ops/ms
Iteration   2: 9.080 ops/ms
Iteration   3: 9.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.029 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (8.991, 9.029, 9.080), stdev = 0.046
  CI (99.9%): [8.192, 9.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.429 ops/ms
# Warmup Iteration   2: 8.156 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.533 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (8.487, 8.533, 8.562), stdev = 0.040
  CI (99.9%): [7.797, 9.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.396 ops/ms
# Warmup Iteration   2: 6.208 ops/ms
# Warmup Iteration   3: 6.744 ops/ms
Iteration   1: 6.904 ops/ms
Iteration   2: 6.889 ops/ms
Iteration   3: 6.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.837 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (6.717, 6.837, 6.904), stdev = 0.104
  CI (99.9%): [4.936, 8.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.011 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.002 ms/op
Iteration   1: 3.723 ±(99.9%) 0.004 ms/op
Iteration   2: 3.802 ±(99.9%) 0.004 ms/op
Iteration   3: 3.782 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.769 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.723, 3.769, 3.802), stdev = 0.041
  CI (99.9%): [3.022, 4.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.003 ms/op
Iteration   1: 3.655 ±(99.9%) 0.003 ms/op
Iteration   2: 3.675 ±(99.9%) 0.002 ms/op
Iteration   3: 3.549 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.626 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (3.549, 3.626, 3.675), stdev = 0.068
  CI (99.9%): [2.394, 4.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.571 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.003 ms/op
Iteration   1: 3.700 ±(99.9%) 0.004 ms/op
Iteration   2: 3.772 ±(99.9%) 0.003 ms/op
Iteration   3: 3.616 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.696 ±(99.9%) 1.428 ms/op [Average]
  (min, avg, max) = (3.616, 3.696, 3.772), stdev = 0.078
  CI (99.9%): [2.268, 5.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.541 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.723 ±(99.9%) 0.011 ms/op
Iteration   1: 4.677 ±(99.9%) 0.020 ms/op
Iteration   2: 4.611 ±(99.9%) 0.008 ms/op
Iteration   3: 4.706 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.665 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (4.611, 4.665, 4.706), stdev = 0.049
  CI (99.9%): [3.778, 5.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
Iteration   1: 3.768 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   5.389 ms/op
                 createUser·p0.999:  9.419 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 3.745 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 14.957 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.773 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  16.306 ms/op
                 createUser·p0.9999: 19.483 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255153
  mean =      3.762 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7020 
    [ 2.500,  5.000) = 240156 
    [ 5.000,  7.500) = 7031 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     18.989 ms/op
     p(99.9990) =     21.704 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.008 ms/op
Iteration   1: 3.544 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  10.817 ms/op
                 existUser·p0.9999: 14.892 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 3.625 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  13.757 ms/op
                 existUser·p0.9999: 18.559 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   3: 3.632 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266573
  mean =      3.600 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 368 
    [ 1.250,  2.500) = 13640 
    [ 2.500,  3.750) = 149864 
    [ 3.750,  5.000) = 97009 
    [ 5.000,  6.250) = 4184 
    [ 6.250,  7.500) = 643 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 138 
    [10.000, 11.250) = 188 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     11.525 ms/op
     p(99.9900) =     18.853 ms/op
     p(99.9990) =     19.519 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.235 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.009 ms/op
Iteration   1: 3.723 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 15.765 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.866 ms/op
                 getUser·p0.9999: 15.590 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  11.113 ms/op
                 getUser·p0.9999: 26.422 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256493
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7743 
    [ 2.500,  5.000) = 241471 
    [ 5.000,  7.500) = 6484 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     24.765 ms/op
     p(99.9990) =     27.212 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.372 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.697 ±(99.9%) 0.014 ms/op
Iteration   1: 4.657 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.226 ms/op
                 listUser·p0.999:  15.077 ms/op
                 listUser·p0.9999: 23.564 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 4.748 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  15.957 ms/op
                 listUser·p0.9999: 18.752 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.761 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  23.352 ms/op
                 listUser·p0.9999: 29.551 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203401
  mean =      4.721 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 155369 
    [ 5.000,  7.500) = 43180 
    [ 7.500, 10.000) = 3908 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     28.038 ms/op
     p(99.9990) =     29.947 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.529 ± 4.164  ops/ms
ClientGrpc.existUser                       thrpt       3   9.029 ± 0.838  ops/ms
ClientGrpc.getUser                         thrpt       3   8.533 ± 0.736  ops/ms
ClientGrpc.listUser                        thrpt       3   6.837 ± 1.901  ops/ms
ClientGrpc.createUser                       avgt       3   3.769 ± 0.748   ms/op
ClientGrpc.existUser                        avgt       3   3.626 ± 1.232   ms/op
ClientGrpc.getUser                          avgt       3   3.696 ± 1.428   ms/op
ClientGrpc.listUser                         avgt       3   4.665 ± 0.886   ms/op
ClientGrpc.createUser                     sample  255153   3.762 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.542           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.945           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.989           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.856           ms/op
ClientGrpc.existUser                      sample  266573   3.600 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.525           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.853           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  256493   3.743 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.838           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.765           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  203401   4.721 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.007           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.038           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.081           ms/op
