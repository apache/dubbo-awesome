# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 4.246 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.648 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.025 ±(99.9%) 6.464 ops/ms [Average]
  (min, avg, max) = (7.648, 8.025, 8.351), stdev = 0.354
  CI (99.9%): [1.561, 14.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.283 ops/ms
# Warmup Iteration   2: 6.917 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.328 ops/ms
Iteration   2: 8.566 ops/ms
Iteration   3: 8.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.507 ±(99.9%) 2.884 ops/ms [Average]
  (min, avg, max) = (8.328, 8.507, 8.627), stdev = 0.158
  CI (99.9%): [5.623, 11.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.389 ops/ms
# Warmup Iteration   2: 6.212 ops/ms
# Warmup Iteration   3: 7.463 ops/ms
Iteration   1: 8.250 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.256 ±(99.9%) 3.497 ops/ms [Average]
  (min, avg, max) = (8.067, 8.256, 8.450), stdev = 0.192
  CI (99.9%): [4.759, 11.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.428 ops/ms
# Warmup Iteration   3: 6.555 ops/ms
Iteration   1: 6.592 ops/ms
Iteration   2: 6.672 ops/ms
Iteration   3: 6.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.738 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (6.592, 6.738, 6.949), stdev = 0.187
  CI (99.9%): [3.320, 10.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.411 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.007 ms/op
Iteration   1: 3.913 ±(99.9%) 0.008 ms/op
Iteration   2: 3.984 ±(99.9%) 0.005 ms/op
Iteration   3: 3.954 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.950 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.913, 3.950, 3.984), stdev = 0.036
  CI (99.9%): [3.297, 4.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.997 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.955 ±(99.9%) 0.007 ms/op
Iteration   2: 3.935 ±(99.9%) 0.005 ms/op
Iteration   3: 3.781 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.890 ±(99.9%) 1.739 ms/op [Average]
  (min, avg, max) = (3.781, 3.890, 3.955), stdev = 0.095
  CI (99.9%): [2.151, 5.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.251 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.010 ms/op
Iteration   1: 4.095 ±(99.9%) 0.010 ms/op
Iteration   2: 4.034 ±(99.9%) 0.010 ms/op
Iteration   3: 4.097 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.075 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (4.034, 4.075, 4.097), stdev = 0.036
  CI (99.9%): [3.426, 4.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.749 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.844 ±(99.9%) 0.004 ms/op
Iteration   1: 4.645 ±(99.9%) 0.008 ms/op
Iteration   2: 4.525 ±(99.9%) 0.011 ms/op
Iteration   3: 4.568 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.579 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (4.525, 4.579, 4.645), stdev = 0.061
  CI (99.9%): [3.467, 5.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.511 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 5.048 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.019 ms/op
Iteration   1: 3.919 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  23.095 ms/op
                 createUser·p0.9999: 30.890 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   2: 3.824 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  13.085 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.852 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  25.983 ms/op
                 createUser·p0.9999: 33.993 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248279
  mean =      3.865 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 386 
    [ 2.500,  5.000) = 238004 
    [ 5.000,  7.500) = 8282 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     22.830 ms/op
     p(99.9900) =     32.075 ms/op
     p(99.9990) =     34.443 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.855 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.012 ms/op
Iteration   1: 3.790 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  11.463 ms/op
                 existUser·p0.9999: 31.331 ms/op
                 existUser·p1.00:   32.702 ms/op

Iteration   2: 3.912 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 26.601 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.819 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  28.480 ms/op
                 existUser·p0.9999: 40.717 ms/op
                 existUser·p1.00:   41.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250085
  mean =      3.840 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236392 
    [ 5.000, 10.000) = 12991 
    [10.000, 15.000) = 475 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 110 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     41.418 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.913 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.016 ms/op
Iteration   1: 4.065 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  16.531 ms/op
                 getUser·p0.9999: 25.507 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 4.106 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.966 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  15.404 ms/op
                 getUser·p0.9999: 30.203 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 3.974 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.995 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  27.048 ms/op
                 getUser·p0.9999: 30.735 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237144
  mean =      4.048 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 220893 
    [ 5.000,  7.500) = 12604 
    [ 7.500, 10.000) = 2564 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     31.642 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.134 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.874 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.829 ±(99.9%) 0.020 ms/op
Iteration   1: 4.673 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  25.411 ms/op
                 listUser·p0.9999: 29.380 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   2: 4.866 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  19.832 ms/op
                 listUser·p0.9999: 27.089 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 4.761 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  18.149 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201427
  mean =      4.765 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 160732 
    [ 5.000,  7.500) = 34745 
    [ 7.500, 10.000) = 4324 
    [10.000, 12.500) = 844 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     20.260 ms/op
     p(99.9900) =     27.160 ms/op
     p(99.9990) =     30.886 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.025 ± 6.464  ops/ms
ClientPb.existUser                       thrpt       3   8.507 ± 2.884  ops/ms
ClientPb.getUser                         thrpt       3   8.256 ± 3.497  ops/ms
ClientPb.listUser                        thrpt       3   6.738 ± 3.417  ops/ms
ClientPb.createUser                       avgt       3   3.950 ± 0.654   ms/op
ClientPb.existUser                        avgt       3   3.890 ± 1.739   ms/op
ClientPb.getUser                          avgt       3   4.075 ± 0.649   ms/op
ClientPb.listUser                         avgt       3   4.579 ± 1.113   ms/op
ClientPb.createUser                     sample  248279   3.865 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.792           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.075           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  250085   3.840 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.637           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.387           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.943           ms/op
ClientPb.getUser                        sample  237144   4.048 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.548           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.474           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  201427   4.765 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.260           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.160           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.556           ms/op
