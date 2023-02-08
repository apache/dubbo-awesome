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
# Warmup Iteration   1: 2.096 ops/ms
# Warmup Iteration   2: 5.432 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 9.095 ops/ms
Iteration   2: 9.495 ops/ms
Iteration   3: 9.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.296 ±(99.9%) 3.643 ops/ms [Average]
  (min, avg, max) = (9.095, 9.296, 9.495), stdev = 0.200
  CI (99.9%): [5.653, 12.939] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 9.526 ops/ms
Iteration   1: 9.472 ops/ms
Iteration   2: 9.883 ops/ms
Iteration   3: 9.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.672 ±(99.9%) 3.751 ops/ms [Average]
  (min, avg, max) = (9.472, 9.672, 9.883), stdev = 0.206
  CI (99.9%): [5.921, 13.423] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 7.966 ops/ms
# Warmup Iteration   3: 9.132 ops/ms
Iteration   1: 9.511 ops/ms
Iteration   2: 9.280 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.353 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (9.268, 9.353, 9.511), stdev = 0.137
  CI (99.9%): [6.851, 11.855] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 7.406 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.169 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (8.104, 8.169, 8.234), stdev = 0.065
  CI (99.9%): [6.986, 9.353] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.372 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
Iteration   1: 3.488 ±(99.9%) 0.005 ms/op
Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
Iteration   3: 3.386 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.369, 3.415, 3.488), stdev = 0.064
  CI (99.9%): [2.247, 4.582] (assumes normal distribution)


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
# Warmup Iteration   1: 9.957 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.011 ms/op
Iteration   1: 3.278 ±(99.9%) 0.007 ms/op
Iteration   2: 3.221 ±(99.9%) 0.011 ms/op
Iteration   3: 3.201 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.234 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.201, 3.234, 3.278), stdev = 0.040
  CI (99.9%): [2.505, 3.963] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.725 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.008 ms/op
Iteration   1: 3.448 ±(99.9%) 0.008 ms/op
Iteration   2: 3.461 ±(99.9%) 0.005 ms/op
Iteration   3: 3.524 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.478 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.448, 3.478, 3.524), stdev = 0.041
  CI (99.9%): [2.732, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 11.633 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 3.908 ±(99.9%) 0.007 ms/op
Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
Iteration   3: 3.882 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.895 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.882, 3.895, 3.908), stdev = 0.013
  CI (99.9%): [3.663, 4.126] (assumes normal distribution)


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
# Warmup Iteration   1: 9.311 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  20.286 ms/op
                 createUser·p0.9999: 24.656 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  23.117 ms/op
                 createUser·p0.9999: 25.960 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  17.268 ms/op
                 createUser·p0.9999: 25.482 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282194
  mean =      3.402 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10071 
    [ 2.500,  5.000) = 265453 
    [ 5.000,  7.500) = 5119 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     18.409 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     26.616 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 8.484 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
Iteration   1: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  10.234 ms/op
                 existUser·p0.9999: 30.778 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   2: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  20.349 ms/op
                 existUser·p0.9999: 25.063 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  14.234 ms/op
                 existUser·p0.9999: 25.205 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290974
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4781 
    [ 2.500,  5.000) = 282154 
    [ 5.000,  7.500) = 3114 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     14.777 ms/op
     p(99.9900) =     29.115 ms/op
     p(99.9990) =     31.657 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 10.520 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.012 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.799 ms/op
                 getUser·p0.999:  20.597 ms/op
                 getUser·p0.9999: 28.889 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   2: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  22.638 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  24.557 ms/op
                 getUser·p0.9999: 29.653 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280072
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6766 
    [ 2.500,  5.000) = 265889 
    [ 5.000,  7.500) = 6154 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     30.061 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 11.928 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.014 ms/op
Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   8.144 ms/op
                 listUser·p0.999:  20.457 ms/op
                 listUser·p0.9999: 23.437 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.543 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 16.807 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.880 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.544 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 15.897 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240508
  mean =      3.992 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 232222 
    [ 5.000,  7.500) = 5957 
    [ 7.500, 10.000) = 1454 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     22.707 ms/op
     p(99.9990) =     23.814 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.296 ± 3.643  ops/ms
ClientPb.existUser                       thrpt       3   9.672 ± 3.751  ops/ms
ClientPb.getUser                         thrpt       3   9.353 ± 2.502  ops/ms
ClientPb.listUser                        thrpt       3   8.169 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 1.167   ms/op
ClientPb.existUser                        avgt       3   3.234 ± 0.729   ms/op
ClientPb.getUser                          avgt       3   3.478 ± 0.746   ms/op
ClientPb.listUser                         avgt       3   3.895 ± 0.232   ms/op
ClientPb.createUser                     sample  282194   3.402 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.409           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.494           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.804           ms/op
ClientPb.existUser                      sample  290974   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.337           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.777           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.115           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  280072   3.427 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.808           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.672           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  240508   3.992 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
