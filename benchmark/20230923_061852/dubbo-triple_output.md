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
# Warmup Iteration   1: 2.114 ops/ms
# Warmup Iteration   2: 6.227 ops/ms
# Warmup Iteration   3: 8.447 ops/ms
Iteration   1: 9.114 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.236 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (9.114, 9.236, 9.440), stdev = 0.178
  CI (99.9%): [5.995, 12.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.875 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (9.787, 9.875, 10.042), stdev = 0.144
  CI (99.9%): [7.242, 12.509] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.855 ops/ms
# Warmup Iteration   3: 9.297 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 9.139 ops/ms
Iteration   3: 9.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.257 ±(99.9%) 1.992 ops/ms [Average]
  (min, avg, max) = (9.139, 9.257, 9.355), stdev = 0.109
  CI (99.9%): [7.264, 11.249] (assumes normal distribution)


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
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 7.696 ops/ms
Iteration   1: 7.593 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.836 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (7.593, 7.836, 7.988), stdev = 0.213
  CI (99.9%): [3.953, 11.719] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.007 ms/op
Iteration   1: 3.509 ±(99.9%) 0.005 ms/op
Iteration   2: 3.541 ±(99.9%) 0.005 ms/op
Iteration   3: 3.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.512 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.485, 3.512, 3.541), stdev = 0.028
  CI (99.9%): [2.999, 4.024] (assumes normal distribution)


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
# Warmup Iteration   1: 11.177 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.002 ms/op
Iteration   1: 3.334 ±(99.9%) 0.003 ms/op
Iteration   2: 3.308 ±(99.9%) 0.005 ms/op
Iteration   3: 3.342 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.308, 3.328, 3.342), stdev = 0.018
  CI (99.9%): [3.004, 3.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.328 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.003 ms/op
Iteration   1: 3.600 ±(99.9%) 0.004 ms/op
Iteration   2: 3.593 ±(99.9%) 0.002 ms/op
Iteration   3: 3.535 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.576 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.535, 3.576, 3.600), stdev = 0.036
  CI (99.9%): [2.919, 4.233] (assumes normal distribution)


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
# Warmup Iteration   1: 11.629 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.006 ms/op
Iteration   1: 4.275 ±(99.9%) 0.007 ms/op
Iteration   2: 4.274 ±(99.9%) 0.009 ms/op
Iteration   3: 4.105 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.218 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (4.105, 4.218, 4.275), stdev = 0.098
  CI (99.9%): [2.437, 6.000] (assumes normal distribution)


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
# Warmup Iteration   1: 9.569 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.009 ms/op
Iteration   1: 3.578 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  12.382 ms/op
                 createUser·p0.9999: 21.896 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.490 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  20.167 ms/op
                 createUser·p0.9999: 24.199 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  19.061 ms/op
                 createUser·p0.9999: 27.250 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270051
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5206 
    [ 2.500,  5.000) = 258792 
    [ 5.000,  7.500) = 4734 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.529 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.895 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 11.531 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  19.252 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.139 ms/op
                 existUser·p0.999:  14.584 ms/op
                 existUser·p0.9999: 24.702 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281062
  mean =      3.415 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8692 
    [ 2.500,  5.000) = 267640 
    [ 5.000,  7.500) = 3477 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.890 ms/op
     p(99.9900) =     24.736 ms/op
     p(99.9990) =     27.630 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 8.162 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 22.082 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  21.064 ms/op
                 getUser·p0.9999: 24.038 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.194 ms/op
                 getUser·p0.999:  17.944 ms/op
                 getUser·p0.9999: 22.959 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278568
  mean =      3.444 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5834 
    [ 2.500,  5.000) = 265125 
    [ 5.000,  7.500) = 6264 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.556 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     23.303 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 9.770 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.013 ms/op
Iteration   1: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  17.284 ms/op
                 listUser·p0.9999: 22.821 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 4.020 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 19.826 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.121 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.275 ms/op
                 listUser·p0.9999: 16.306 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234800
  mean =      4.086 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 226859 
    [ 5.000,  7.500) = 6314 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.913 ms/op
     p(99.9900) =     21.842 ms/op
     p(99.9990) =     23.274 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.236 ± 3.242  ops/ms
ClientPb.existUser                       thrpt       3   9.875 ± 2.633  ops/ms
ClientPb.getUser                         thrpt       3   9.257 ± 1.992  ops/ms
ClientPb.listUser                        thrpt       3   7.836 ± 3.883  ops/ms
ClientPb.createUser                       avgt       3   3.512 ± 0.512   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 0.324   ms/op
ClientPb.getUser                          avgt       3   3.576 ± 0.657   ms/op
ClientPb.listUser                         avgt       3   4.218 ± 1.782   ms/op
ClientPb.createUser                     sample  270051   3.550 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.529           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.214           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.017           ms/op
ClientPb.existUser                      sample  281062   3.415 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.890           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.736           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.656           ms/op
ClientPb.getUser                        sample  278568   3.444 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.556           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.121           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.362           ms/op
ClientPb.listUser                       sample  234800   4.086 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.941           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.842           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
