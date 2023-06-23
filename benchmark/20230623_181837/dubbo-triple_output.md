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
# Warmup Iteration   1: 1.895 ops/ms
# Warmup Iteration   2: 5.556 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 9.237 ops/ms
Iteration   2: 9.404 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.270 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (9.169, 9.270, 9.404), stdev = 0.121
  CI (99.9%): [7.066, 11.474] (assumes normal distribution)


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
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 8.448 ops/ms
# Warmup Iteration   3: 8.981 ops/ms
Iteration   1: 9.354 ops/ms
Iteration   2: 9.357 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.419 ±(99.9%) 1.995 ops/ms [Average]
  (min, avg, max) = (9.354, 9.419, 9.545), stdev = 0.109
  CI (99.9%): [7.423, 11.414] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.468 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 8.592 ops/ms
Iteration   1: 9.189 ops/ms
Iteration   2: 9.184 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.258 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (9.184, 9.258, 9.400), stdev = 0.124
  CI (99.9%): [7.003, 11.512] (assumes normal distribution)


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
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 6.859 ops/ms
# Warmup Iteration   3: 7.570 ops/ms
Iteration   1: 7.600 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.782 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (7.600, 7.782, 8.009), stdev = 0.208
  CI (99.9%): [3.983, 11.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.832 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.007 ms/op
Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
Iteration   2: 3.682 ±(99.9%) 0.005 ms/op
Iteration   3: 3.507 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.597 ±(99.9%) 1.594 ms/op [Average]
  (min, avg, max) = (3.507, 3.597, 3.682), stdev = 0.087
  CI (99.9%): [2.003, 5.191] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.331 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.011 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
Iteration   3: 3.390 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.303, 3.338, 3.390), stdev = 0.046
  CI (99.9%): [2.502, 4.174] (assumes normal distribution)


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
# Warmup Iteration   1: 10.123 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.007 ms/op
Iteration   1: 3.495 ±(99.9%) 0.008 ms/op
Iteration   2: 3.450 ±(99.9%) 0.009 ms/op
Iteration   3: 3.524 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.490 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.450, 3.490, 3.524), stdev = 0.037
  CI (99.9%): [2.814, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 11.674 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.009 ms/op
Iteration   1: 4.075 ±(99.9%) 0.008 ms/op
Iteration   2: 4.108 ±(99.9%) 0.011 ms/op
Iteration   3: 4.174 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.119 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (4.075, 4.119, 4.174), stdev = 0.050
  CI (99.9%): [3.202, 5.036] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.643 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.011 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  23.697 ms/op
                 createUser·p0.9999: 28.041 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  24.570 ms/op
                 createUser·p0.9999: 29.160 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 26.958 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274913
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10655 
    [ 2.500,  5.000) = 257762 
    [ 5.000,  7.500) = 5568 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 142 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     18.648 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     30.368 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.665 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  21.299 ms/op
                 existUser·p0.9999: 24.252 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   3: 3.460 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  24.433 ms/op
                 existUser·p0.9999: 29.536 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278346
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4102 
    [ 2.500,  5.000) = 268506 
    [ 5.000,  7.500) = 4623 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 11.551 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.009 ms/op
Iteration   1: 3.537 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.538 ms/op
                 getUser·p0.999:  22.021 ms/op
                 getUser·p0.9999: 24.996 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.470 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  21.888 ms/op
                 getUser·p0.9999: 26.317 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.948 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 28.526 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271801
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3691 
    [ 2.500,  5.000) = 259805 
    [ 5.000,  7.500) = 6773 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     27.278 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 10.671 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.016 ms/op
Iteration   1: 4.179 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.478 ms/op
                 listUser·p0.999:  22.774 ms/op
                 listUser·p0.9999: 27.756 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 4.028 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 20.626 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 3.992 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.138 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235985
  mean =      4.065 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 225711 
    [ 5.000,  7.500) = 8310 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     26.522 ms/op
     p(99.9990) =     28.301 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.270 ± 2.204  ops/ms
ClientPb.existUser                       thrpt       3   9.419 ± 1.995  ops/ms
ClientPb.getUser                         thrpt       3   9.258 ± 2.254  ops/ms
ClientPb.listUser                        thrpt       3   7.782 ± 3.798  ops/ms
ClientPb.createUser                       avgt       3   3.597 ± 1.594   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 0.836   ms/op
ClientPb.getUser                          avgt       3   3.490 ± 0.676   ms/op
ClientPb.listUser                         avgt       3   4.119 ± 0.917   ms/op
ClientPb.createUser                     sample  274913   3.491 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.115           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  278346   3.447 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.344           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.114           ms/op
ClientPb.getUser                        sample  271801   3.530 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.577           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  235985   4.065 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.007           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.522           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
