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
# Warmup Iteration   1: 1.075 ops/ms
# Warmup Iteration   2: 2.550 ops/ms
# Warmup Iteration   3: 4.970 ops/ms
Iteration   1: 5.089 ops/ms
Iteration   2: 5.434 ops/ms
Iteration   3: 5.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.425 ±(99.9%) 6.042 ops/ms [Average]
  (min, avg, max) = (5.089, 5.425, 5.751), stdev = 0.331
  CI (99.9%): [≈ 0, 11.467] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.717 ops/ms
# Warmup Iteration   2: 4.996 ops/ms
# Warmup Iteration   3: 6.202 ops/ms
Iteration   1: 6.096 ops/ms
Iteration   2: 5.973 ops/ms
Iteration   3: 6.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.097 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (5.973, 6.097, 6.223), stdev = 0.125
  CI (99.9%): [3.811, 8.384] (assumes normal distribution)


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
# Warmup Iteration   1: 1.496 ops/ms
# Warmup Iteration   2: 4.344 ops/ms
# Warmup Iteration   3: 5.083 ops/ms
Iteration   1: 5.730 ops/ms
Iteration   2: 5.779 ops/ms
Iteration   3: 5.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.782 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (5.730, 5.782, 5.836), stdev = 0.053
  CI (99.9%): [4.812, 6.752] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.557 ops/ms
# Warmup Iteration   2: 3.994 ops/ms
# Warmup Iteration   3: 5.031 ops/ms
Iteration   1: 5.254 ops/ms
Iteration   2: 5.105 ops/ms
Iteration   3: 4.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.110 ±(99.9%) 2.599 ops/ms [Average]
  (min, avg, max) = (4.969, 5.110, 5.254), stdev = 0.142
  CI (99.9%): [2.510, 7.709] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.384 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 7.320 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.010 ms/op
Iteration   1: 5.982 ±(99.9%) 0.011 ms/op
Iteration   2: 5.904 ±(99.9%) 0.013 ms/op
Iteration   3: 5.816 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.901 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (5.816, 5.901, 5.982), stdev = 0.083
  CI (99.9%): [4.387, 7.415] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.041 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.724 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.300 ±(99.9%) 0.008 ms/op
Iteration   1: 5.380 ±(99.9%) 0.012 ms/op
Iteration   2: 5.226 ±(99.9%) 0.010 ms/op
Iteration   3: 5.282 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.296 ±(99.9%) 1.423 ms/op [Average]
  (min, avg, max) = (5.226, 5.296, 5.380), stdev = 0.078
  CI (99.9%): [3.874, 6.719] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 20.412 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.010 ms/op
Iteration   1: 5.888 ±(99.9%) 0.011 ms/op
Iteration   2: 5.553 ±(99.9%) 0.011 ms/op
Iteration   3: 5.730 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.724 ±(99.9%) 3.051 ms/op [Average]
  (min, avg, max) = (5.553, 5.724, 5.888), stdev = 0.167
  CI (99.9%): [2.672, 8.775] (assumes normal distribution)


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
# Warmup Iteration   1: 20.179 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 8.829 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.794 ±(99.9%) 0.016 ms/op
Iteration   1: 6.447 ±(99.9%) 0.015 ms/op
Iteration   2: 6.451 ±(99.9%) 0.011 ms/op
Iteration   3: 6.690 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.529 ±(99.9%) 2.542 ms/op [Average]
  (min, avg, max) = (6.447, 6.529, 6.690), stdev = 0.139
  CI (99.9%): [3.987, 9.071] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.494 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 7.519 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.848 ±(99.9%) 0.029 ms/op
Iteration   1: 5.538 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.111 ms/op
                 createUser·p0.99:   10.879 ms/op
                 createUser·p0.999:  15.117 ms/op
                 createUser·p0.9999: 32.094 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   2: 5.446 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.298 ms/op
                 createUser·p0.99:   11.045 ms/op
                 createUser·p0.999:  26.563 ms/op
                 createUser·p0.9999: 39.929 ms/op
                 createUser·p1.00:   40.632 ms/op

Iteration   3: 5.744 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   2.486 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   7.774 ms/op
                 createUser·p0.95:   9.241 ms/op
                 createUser·p0.99:   14.451 ms/op
                 createUser·p0.999:  29.405 ms/op
                 createUser·p0.9999: 32.596 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172099
  mean =      5.573 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 80246 
    [ 5.000, 10.000) = 87899 
    [10.000, 15.000) = 3224 
    [15.000, 20.000) = 452 
    [20.000, 25.000) = 68 
    [25.000, 30.000) = 121 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     26.834 ms/op
     p(99.9900) =     36.817 ms/op
     p(99.9990) =     40.538 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 16.650 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.626 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.027 ms/op
Iteration   1: 5.799 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.453 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   7.881 ms/op
                 existUser·p0.95:   9.355 ms/op
                 existUser·p0.99:   13.746 ms/op
                 existUser·p0.999:  19.916 ms/op
                 existUser·p0.9999: 45.382 ms/op
                 existUser·p1.00:   46.596 ms/op

Iteration   2: 5.748 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.578 ms/op
                 existUser·p0.95:   8.913 ms/op
                 existUser·p0.99:   13.550 ms/op
                 existUser·p0.999:  24.916 ms/op
                 existUser·p0.9999: 32.567 ms/op
                 existUser·p1.00:   33.325 ms/op

Iteration   3: 5.442 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   7.086 ms/op
                 existUser·p0.95:   8.208 ms/op
                 existUser·p0.99:   11.731 ms/op
                 existUser·p0.999:  27.826 ms/op
                 existUser·p0.9999: 30.576 ms/op
                 existUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169634
  mean =      5.658 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 74947 
    [ 5.000, 10.000) = 89577 
    [10.000, 15.000) = 4161 
    [15.000, 20.000) = 741 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     13.238 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     43.912 ms/op
     p(99.9990) =     46.596 ms/op
     p(99.9999) =     46.596 ms/op
    p(100.0000) =     46.596 ms/op


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
# Warmup Iteration   1: 18.461 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 6.958 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.027 ms/op
Iteration   1: 5.806 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   7.856 ms/op
                 getUser·p0.95:   9.355 ms/op
                 getUser·p0.99:   15.057 ms/op
                 getUser·p0.999:  29.515 ms/op
                 getUser·p0.9999: 33.751 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 5.366 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.928 ms/op
                 getUser·p0.999:  22.624 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 5.603 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.851 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.209 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   10.645 ms/op
                 getUser·p0.999:  17.682 ms/op
                 getUser·p0.9999: 35.708 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171780
  mean =      5.586 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 79400 
    [ 5.000,  7.500) = 77019 
    [ 7.500, 10.000) = 11114 
    [10.000, 12.500) = 2333 
    [12.500, 15.000) = 1104 
    [15.000, 17.500) = 266 
    [17.500, 20.000) = 182 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.167 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     12.796 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     33.805 ms/op
     p(99.9990) =     36.194 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 20.724 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 8.010 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.752 ±(99.9%) 0.032 ms/op
Iteration   1: 6.644 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.050 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   10.797 ms/op
                 listUser·p0.99:   15.385 ms/op
                 listUser·p0.999:  27.814 ms/op
                 listUser·p0.9999: 29.727 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 6.834 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.729 ms/op
                 listUser·p0.999:  29.728 ms/op
                 listUser·p0.9999: 37.244 ms/op
                 listUser·p1.00:   37.487 ms/op

Iteration   3: 6.485 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   8.380 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  24.510 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144218
  mean =      6.651 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 6765 
    [ 5.000,  7.500) = 110406 
    [ 7.500, 10.000) = 18819 
    [10.000, 12.500) = 5361 
    [12.500, 15.000) = 1675 
    [15.000, 17.500) = 609 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 123 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      6.054 ms/op
     p(90.0000) =      8.864 ms/op
     p(95.0000) =     10.273 ms/op
     p(99.0000) =     14.451 ms/op
     p(99.9000) =     27.962 ms/op
     p(99.9900) =     35.435 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.425 ± 6.042  ops/ms
ClientPb.existUser                       thrpt       3   6.097 ± 2.286  ops/ms
ClientPb.getUser                         thrpt       3   5.782 ± 0.970  ops/ms
ClientPb.listUser                        thrpt       3   5.110 ± 2.599  ops/ms
ClientPb.createUser                       avgt       3   5.901 ± 1.514   ms/op
ClientPb.existUser                        avgt       3   5.296 ± 1.423   ms/op
ClientPb.getUser                          avgt       3   5.724 ± 3.051   ms/op
ClientPb.listUser                         avgt       3   6.529 ± 2.542   ms/op
ClientPb.createUser                     sample  172099   5.573 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.550           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.255           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  169634   5.658 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.453           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.831           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.238           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.758           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.912           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.596           ms/op
ClientPb.getUser                        sample  171780   5.586 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.079           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.283           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.796           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.805           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.805           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.241           ms/op
ClientPb.listUser                       sample  144218   6.651 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.192           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.054           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.864           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.451           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.487           ms/op
