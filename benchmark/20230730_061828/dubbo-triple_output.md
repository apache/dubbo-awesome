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
# Warmup Iteration   1: 2.453 ops/ms
# Warmup Iteration   2: 6.305 ops/ms
# Warmup Iteration   3: 9.311 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 9.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.928 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (9.839, 9.928, 10.000), stdev = 0.082
  CI (99.9%): [8.433, 11.424] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 10.105 ops/ms
Iteration   1: 10.005 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.102 ±(99.9%) 3.382 ops/ms [Average]
  (min, avg, max) = (9.984, 10.102, 10.315), stdev = 0.185
  CI (99.9%): [6.720, 13.484] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 9.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.012 ±(99.9%) 5.198 ops/ms [Average]
  (min, avg, max) = (9.708, 10.012, 10.274), stdev = 0.285
  CI (99.9%): [4.814, 15.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.308 ±(99.9%) 0.755 ops/ms [Average]
  (min, avg, max) = (8.263, 8.308, 8.344), stdev = 0.041
  CI (99.9%): [7.554, 9.063] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.532 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.005 ms/op
Iteration   1: 3.197 ±(99.9%) 0.003 ms/op
Iteration   2: 3.318 ±(99.9%) 0.005 ms/op
Iteration   3: 3.366 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.294 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.197, 3.294, 3.366), stdev = 0.087
  CI (99.9%): [1.703, 4.885] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.400 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.005 ms/op
Iteration   1: 3.230 ±(99.9%) 0.006 ms/op
Iteration   2: 3.125 ±(99.9%) 0.004 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.122 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (3.012, 3.122, 3.230), stdev = 0.109
  CI (99.9%): [1.129, 5.116] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.723 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.006 ms/op
Iteration   1: 3.295 ±(99.9%) 0.005 ms/op
Iteration   2: 3.189 ±(99.9%) 0.006 ms/op
Iteration   3: 3.273 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.252 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.189, 3.252, 3.295), stdev = 0.056
  CI (99.9%): [2.232, 4.272] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.826 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.006 ms/op
Iteration   1: 3.878 ±(99.9%) 0.007 ms/op
Iteration   2: 3.837 ±(99.9%) 0.007 ms/op
Iteration   3: 3.676 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.797 ±(99.9%) 1.953 ms/op [Average]
  (min, avg, max) = (3.676, 3.797, 3.878), stdev = 0.107
  CI (99.9%): [1.844, 5.749] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.126 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  13.685 ms/op
                 createUser·p0.9999: 20.698 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  20.382 ms/op
                 createUser·p0.9999: 22.830 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.257 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.318 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 17.307 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300402
  mean =      3.197 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22108 
    [ 2.500,  5.000) = 272377 
    [ 5.000,  7.500) = 5254 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     14.110 ms/op
     p(99.9900) =     21.462 ms/op
     p(99.9990) =     23.199 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.338 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  10.777 ms/op
                 existUser·p0.9999: 19.064 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  13.577 ms/op
                 existUser·p0.9999: 20.704 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 19.905 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305610
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19715 
    [ 2.500,  5.000) = 279451 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     20.134 ms/op
     p(99.9990) =     21.452 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 7.596 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
Iteration   1: 3.215 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.052 ms/op
                 getUser·p0.999:  19.440 ms/op
                 getUser·p0.9999: 27.755 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  14.336 ms/op
                 getUser·p0.9999: 21.505 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297170
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12315 
    [ 2.500,  5.000) = 277121 
    [ 5.000,  7.500) = 6692 
    [ 7.500, 10.000) = 526 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     27.417 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.013 ms/op
Iteration   1: 3.846 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.725 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 16.260 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   3: 3.691 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  12.277 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255687
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 250014 
    [ 5.000,  7.500) = 4153 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.079 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     20.607 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.928 ± 1.495  ops/ms
ClientPb.existUser                       thrpt       3  10.102 ± 3.382  ops/ms
ClientPb.getUser                         thrpt       3  10.012 ± 5.198  ops/ms
ClientPb.listUser                        thrpt       3   8.308 ± 0.755  ops/ms
ClientPb.createUser                       avgt       3   3.294 ± 1.591   ms/op
ClientPb.existUser                        avgt       3   3.122 ± 1.993   ms/op
ClientPb.getUser                          avgt       3   3.252 ± 1.020   ms/op
ClientPb.listUser                         avgt       3   3.797 ± 1.953   ms/op
ClientPb.createUser                     sample  300402   3.197 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  305610   3.139 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.134           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.627           ms/op
ClientPb.getUser                        sample  297170   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.975           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.417           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  255687   3.753 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.079           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.726           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.677           ms/op
