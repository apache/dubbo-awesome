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
# Warmup Iteration   1: 1.929 ops/ms
# Warmup Iteration   2: 4.114 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.686 ±(99.9%) 7.254 ops/ms [Average]
  (min, avg, max) = (8.351, 8.686, 9.126), stdev = 0.398
  CI (99.9%): [1.432, 15.941] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.833 ops/ms
# Warmup Iteration   2: 8.194 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.507 ops/ms
Iteration   2: 9.692 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.470 ±(99.9%) 4.421 ops/ms [Average]
  (min, avg, max) = (9.212, 9.470, 9.692), stdev = 0.242
  CI (99.9%): [5.050, 13.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 8.140 ops/ms
# Warmup Iteration   3: 9.087 ops/ms
Iteration   1: 8.699 ops/ms
Iteration   2: 9.127 ops/ms
Iteration   3: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.895 ±(99.9%) 3.945 ops/ms [Average]
  (min, avg, max) = (8.699, 8.895, 9.127), stdev = 0.216
  CI (99.9%): [4.950, 12.840] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 6.767 ops/ms
# Warmup Iteration   3: 7.016 ops/ms
Iteration   1: 7.488 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 7.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.682 ±(99.9%) 3.184 ops/ms [Average]
  (min, avg, max) = (7.488, 7.682, 7.826), stdev = 0.175
  CI (99.9%): [4.498, 10.866] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.618 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.012 ms/op
Iteration   1: 3.675 ±(99.9%) 0.007 ms/op
Iteration   2: 3.543 ±(99.9%) 0.009 ms/op
Iteration   3: 3.500 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.573 ±(99.9%) 1.664 ms/op [Average]
  (min, avg, max) = (3.500, 3.573, 3.675), stdev = 0.091
  CI (99.9%): [1.909, 5.237] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.660 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.004 ms/op
Iteration   1: 3.382 ±(99.9%) 0.012 ms/op
Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
Iteration   3: 3.446 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.438 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.382, 3.438, 3.485), stdev = 0.052
  CI (99.9%): [2.489, 4.386] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.122 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.005 ms/op
Iteration   1: 3.667 ±(99.9%) 0.008 ms/op
Iteration   2: 3.560 ±(99.9%) 0.009 ms/op
Iteration   3: 3.452 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.560 ±(99.9%) 1.965 ms/op [Average]
  (min, avg, max) = (3.452, 3.560, 3.667), stdev = 0.108
  CI (99.9%): [1.595, 5.524] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.006 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.494 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.012 ms/op
Iteration   1: 4.252 ±(99.9%) 0.009 ms/op
Iteration   2: 4.420 ±(99.9%) 0.012 ms/op
Iteration   3: 4.316 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.329 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (4.252, 4.329, 4.420), stdev = 0.085
  CI (99.9%): [2.778, 5.880] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.335 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.014 ms/op
Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  11.536 ms/op
                 createUser·p0.9999: 28.384 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   2: 3.731 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  27.111 ms/op
                 createUser·p0.9999: 31.107 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 3.596 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  27.136 ms/op
                 createUser·p0.9999: 30.379 ms/op
                 createUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262452
  mean =      3.655 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2723 
    [ 2.500,  5.000) = 252040 
    [ 5.000,  7.500) = 6519 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 131 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     18.124 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.912 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.775 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.012 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  22.118 ms/op
                 existUser·p0.9999: 26.143 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 30.885 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.648 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  25.183 ms/op
                 existUser·p0.9999: 41.943 ms/op
                 existUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273983
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266535 
    [ 5.000, 10.000) = 7051 
    [10.000, 15.000) = 118 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 88 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     40.018 ms/op
     p(99.9990) =     42.812 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.574 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.013 ms/op
Iteration   1: 3.747 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.365 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  22.401 ms/op
                 getUser·p0.9999: 29.610 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   2: 3.731 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.919 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.720 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  11.665 ms/op
                 getUser·p0.9999: 32.240 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.811 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.233 ms/op
                 getUser·p0.999:  27.731 ms/op
                 getUser·p0.9999: 32.173 ms/op
                 getUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254897
  mean =      3.763 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1557 
    [ 2.500,  5.000) = 243601 
    [ 5.000,  7.500) = 8102 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     21.928 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     33.104 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.334 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.378 ±(99.9%) 0.016 ms/op
Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   4.049 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  24.674 ms/op
                 listUser·p0.9999: 29.863 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 4.203 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  16.430 ms/op
                 listUser·p0.9999: 18.080 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.163 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.827 ms/op
                 listUser·p0.99:   6.253 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 20.717 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229072
  mean =      4.191 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 214336 
    [ 5.000,  7.500) = 12362 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     17.070 ms/op
     p(99.9900) =     28.249 ms/op
     p(99.9990) =     30.712 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.686 ± 7.254  ops/ms
ClientPb.existUser                       thrpt       3   9.470 ± 4.421  ops/ms
ClientPb.getUser                         thrpt       3   8.895 ± 3.945  ops/ms
ClientPb.listUser                        thrpt       3   7.682 ± 3.184  ops/ms
ClientPb.createUser                       avgt       3   3.573 ± 1.664   ms/op
ClientPb.existUser                        avgt       3   3.438 ± 0.948   ms/op
ClientPb.getUser                          avgt       3   3.560 ± 1.965   ms/op
ClientPb.listUser                         avgt       3   4.329 ± 1.551   ms/op
ClientPb.createUser                     sample  262452   3.655 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.124           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.409           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.473           ms/op
ClientPb.existUser                      sample  273983   3.501 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.861           ms/op
ClientPb.getUser                        sample  254897   3.763 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.365           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.928           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.785           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  229072   4.191 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.037           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.070           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
