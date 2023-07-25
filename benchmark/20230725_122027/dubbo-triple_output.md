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
# Warmup Iteration   1: 1.668 ops/ms
# Warmup Iteration   2: 3.787 ops/ms
# Warmup Iteration   3: 7.308 ops/ms
Iteration   1: 7.321 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.816 ±(99.9%) 8.213 ops/ms [Average]
  (min, avg, max) = (7.321, 7.816, 8.201), stdev = 0.450
  CI (99.9%): [≈ 0, 16.029] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 6.276 ops/ms
# Warmup Iteration   3: 7.741 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.250 ±(99.9%) 1.729 ops/ms [Average]
  (min, avg, max) = (8.184, 8.250, 8.359), stdev = 0.095
  CI (99.9%): [6.522, 9.979] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 6.549 ops/ms
# Warmup Iteration   3: 7.508 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 8.042 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.994 ±(99.9%) 2.727 ops/ms [Average]
  (min, avg, max) = (7.826, 7.994, 8.113), stdev = 0.149
  CI (99.9%): [5.267, 10.721] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 5.640 ops/ms
# Warmup Iteration   3: 6.463 ops/ms
Iteration   1: 7.040 ops/ms
Iteration   2: 6.933 ops/ms
Iteration   3: 6.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.922 ±(99.9%) 2.266 ops/ms [Average]
  (min, avg, max) = (6.792, 6.922, 7.040), stdev = 0.124
  CI (99.9%): [4.656, 9.188] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.586 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.254 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.006 ms/op
Iteration   1: 3.950 ±(99.9%) 0.005 ms/op
Iteration   2: 3.919 ±(99.9%) 0.008 ms/op
Iteration   3: 3.882 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.917 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (3.882, 3.917, 3.950), stdev = 0.034
  CI (99.9%): [3.293, 4.540] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.249 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.004 ms/op
Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
Iteration   2: 3.739 ±(99.9%) 0.005 ms/op
Iteration   3: 3.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.834 ±(99.9%) 1.759 ms/op [Average]
  (min, avg, max) = (3.739, 3.834, 3.932), stdev = 0.096
  CI (99.9%): [2.075, 5.593] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.933 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.007 ms/op
Iteration   1: 4.044 ±(99.9%) 0.009 ms/op
Iteration   2: 3.933 ±(99.9%) 0.008 ms/op
Iteration   3: 3.867 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.948 ±(99.9%) 1.625 ms/op [Average]
  (min, avg, max) = (3.867, 3.948, 4.044), stdev = 0.089
  CI (99.9%): [2.323, 5.573] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.054 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.537 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.058 ±(99.9%) 0.012 ms/op
Iteration   1: 4.756 ±(99.9%) 0.009 ms/op
Iteration   2: 4.768 ±(99.9%) 0.007 ms/op
Iteration   3: 4.742 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.755 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (4.742, 4.755, 4.768), stdev = 0.013
  CI (99.9%): [4.519, 4.992] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.446 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.881 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.017 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 25.263 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.879 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 24.470 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  18.021 ms/op
                 createUser·p0.9999: 28.800 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243879
  mean =      3.936 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 232006 
    [ 5.000,  7.500) = 9988 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     21.401 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     29.092 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.003 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  22.012 ms/op
                 existUser·p0.9999: 31.228 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   2: 3.745 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  12.943 ms/op
                 existUser·p0.9999: 26.656 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.904 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.829 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  26.054 ms/op
                 existUser·p0.9999: 31.287 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251487
  mean =      3.816 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 242421 
    [ 5.000,  7.500) = 7527 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     21.840 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     33.044 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 13.217 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 4.056 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  18.300 ms/op
                 getUser·p0.9999: 42.410 ms/op
                 getUser·p1.00:   43.385 ms/op

Iteration   2: 3.911 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  24.871 ms/op
                 getUser·p0.9999: 30.306 ms/op
                 getUser·p1.00:   30.966 ms/op

Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  21.210 ms/op
                 getUser·p0.9999: 28.967 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242360
  mean =      3.959 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 231383 
    [ 5.000, 10.000) = 10333 
    [10.000, 15.000) = 329 
    [15.000, 20.000) = 70 
    [20.000, 25.000) = 64 
    [25.000, 30.000) = 138 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     21.165 ms/op
     p(99.9900) =     39.372 ms/op
     p(99.9990) =     42.825 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


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
# Warmup Iteration   1: 14.277 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.681 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.017 ms/op
Iteration   1: 4.713 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.408 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 25.572 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 4.900 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   3: 4.541 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203717
  mean =      4.713 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 175217 
    [ 5.000,  7.500) = 24668 
    [ 7.500, 10.000) = 2765 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     20.751 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     30.045 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.816 ± 8.213  ops/ms
ClientPb.existUser                       thrpt       3   8.250 ± 1.729  ops/ms
ClientPb.getUser                         thrpt       3   7.994 ± 2.727  ops/ms
ClientPb.listUser                        thrpt       3   6.922 ± 2.266  ops/ms
ClientPb.createUser                       avgt       3   3.917 ± 0.624   ms/op
ClientPb.existUser                        avgt       3   3.834 ± 1.759   ms/op
ClientPb.getUser                          avgt       3   3.948 ± 1.625   ms/op
ClientPb.listUser                         avgt       3   4.755 ± 0.236   ms/op
ClientPb.createUser                     sample  243879   3.936 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.401           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.392           ms/op
ClientPb.existUser                      sample  251487   3.816 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.518           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.840           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  242360   3.959 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.165           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.372           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.385           ms/op
ClientPb.listUser                       sample  203717   4.713 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.751           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.967           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
