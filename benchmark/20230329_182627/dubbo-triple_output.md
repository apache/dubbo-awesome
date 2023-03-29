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
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 6.407 ops/ms
# Warmup Iteration   3: 9.464 ops/ms
Iteration   1: 9.662 ops/ms
Iteration   2: 9.591 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.813 ±(99.9%) 5.935 ops/ms [Average]
  (min, avg, max) = (9.591, 9.813, 10.187), stdev = 0.325
  CI (99.9%): [3.878, 15.748] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ops/ms
# Warmup Iteration   2: 9.311 ops/ms
# Warmup Iteration   3: 10.175 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.468 ±(99.9%) 6.254 ops/ms [Average]
  (min, avg, max) = (10.125, 10.468, 10.810), stdev = 0.343
  CI (99.9%): [4.215, 16.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ops/ms
# Warmup Iteration   2: 9.361 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 9.697 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 9.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.716 ±(99.9%) 0.386 ops/ms [Average]
  (min, avg, max) = (9.697, 9.716, 9.739), stdev = 0.021
  CI (99.9%): [9.331, 10.102] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.187 ops/ms
# Warmup Iteration   2: 7.939 ops/ms
# Warmup Iteration   3: 8.364 ops/ms
Iteration   1: 8.605 ops/ms
Iteration   2: 8.574 ops/ms
Iteration   3: 8.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.632 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (8.574, 8.632, 8.716), stdev = 0.074
  CI (99.9%): [7.275, 9.988] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.095 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.078, 3.095, 3.128), stdev = 0.029
  CI (99.9%): [2.574, 3.615] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.005 ms/op
Iteration   1: 3.203 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
Iteration   3: 2.965 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 2.224 ms/op [Average]
  (min, avg, max) = (2.965, 3.069, 3.203), stdev = 0.122
  CI (99.9%): [0.844, 5.293] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.174 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.002 ms/op
Iteration   1: 3.333 ±(99.9%) 0.006 ms/op
Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 2.649 ms/op [Average]
  (min, avg, max) = (3.046, 3.201, 3.333), stdev = 0.145
  CI (99.9%): [0.552, 5.850] (assumes normal distribution)


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
# Warmup Iteration   1: 9.209 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.009 ms/op
Iteration   1: 3.602 ±(99.9%) 0.013 ms/op
Iteration   2: 3.655 ±(99.9%) 0.011 ms/op
Iteration   3: 3.763 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.673 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.602, 3.673, 3.763), stdev = 0.082
  CI (99.9%): [2.175, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 7.531 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.379 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 22.157 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.369 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.672 ms/op
                 createUser·p0.999:  19.463 ms/op
                 createUser·p0.9999: 23.806 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  12.255 ms/op
                 createUser·p0.9999: 18.442 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299176
  mean =      3.209 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17850 
    [ 2.500,  5.000) = 277205 
    [ 5.000,  7.500) = 3496 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.236 ms/op
     p(99.9900) =     22.908 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 6.990 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
Iteration   1: 3.158 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.429 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.917 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  18.547 ms/op
                 existUser·p0.9999: 21.878 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.266 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 24.723 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299913
  mean =      3.201 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18977 
    [ 2.500,  5.000) = 269554 
    [ 5.000,  7.500) = 10174 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     15.411 ms/op
     p(99.9900) =     23.692 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 8.635 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.011 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  12.681 ms/op
                 getUser·p0.9999: 22.908 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  20.509 ms/op
                 getUser·p0.9999: 23.940 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  12.674 ms/op
                 getUser·p0.9999: 20.095 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298032
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16712 
    [ 2.500,  5.000) = 274017 
    [ 5.000,  7.500) = 6591 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     15.842 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.017 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 8.714 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.011 ms/op
Iteration   1: 3.659 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.377 ms/op
                 listUser·p0.9999: 17.678 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.351 ms/op
                 listUser·p0.99:   7.396 ms/op
                 listUser·p0.999:  10.994 ms/op
                 listUser·p0.9999: 15.230 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 3.678 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.338 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258639
  mean =      3.708 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 251736 
    [ 5.000,  7.500) = 4856 
    [ 7.500, 10.000) = 1370 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.375 ms/op
     p(99.9900) =     21.275 ms/op
     p(99.9990) =     22.225 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.813 ± 5.935  ops/ms
ClientPb.existUser                       thrpt       3  10.468 ± 6.254  ops/ms
ClientPb.getUser                         thrpt       3   9.716 ± 0.386  ops/ms
ClientPb.listUser                        thrpt       3   8.632 ± 1.356  ops/ms
ClientPb.createUser                       avgt       3   3.095 ± 0.521   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 2.224   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 2.649   ms/op
ClientPb.listUser                         avgt       3   3.673 ± 1.499   ms/op
ClientPb.createUser                     sample  299176   3.209 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.236           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.908           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.216           ms/op
ClientPb.existUser                      sample  299913   3.201 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.411           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.362           ms/op
ClientPb.getUser                        sample  298032   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  258639   3.708 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.580           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.375           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.275           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.774           ms/op
