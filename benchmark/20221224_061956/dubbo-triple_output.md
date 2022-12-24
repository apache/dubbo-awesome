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
# Warmup Iteration   1: 1.164 ops/ms
# Warmup Iteration   2: 2.472 ops/ms
# Warmup Iteration   3: 5.311 ops/ms
Iteration   1: 5.654 ops/ms
Iteration   2: 5.759 ops/ms
Iteration   3: 6.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.848 ±(99.9%) 4.582 ops/ms [Average]
  (min, avg, max) = (5.654, 5.848, 6.132), stdev = 0.251
  CI (99.9%): [1.266, 10.431] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.775 ops/ms
# Warmup Iteration   2: 4.822 ops/ms
# Warmup Iteration   3: 5.753 ops/ms
Iteration   1: 5.761 ops/ms
Iteration   2: 5.534 ops/ms
Iteration   3: 5.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.659 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (5.534, 5.659, 5.761), stdev = 0.115
  CI (99.9%): [3.557, 7.761] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.522 ops/ms
# Warmup Iteration   2: 4.233 ops/ms
# Warmup Iteration   3: 5.761 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 5.755 ops/ms
Iteration   3: 5.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.698 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (5.560, 5.698, 5.778), stdev = 0.120
  CI (99.9%): [3.511, 7.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.602 ops/ms
# Warmup Iteration   2: 4.042 ops/ms
# Warmup Iteration   3: 4.763 ops/ms
Iteration   1: 5.156 ops/ms
Iteration   2: 5.285 ops/ms
Iteration   3: 5.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.149 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (5.006, 5.149, 5.285), stdev = 0.140
  CI (99.9%): [2.600, 7.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 17.691 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.013 ms/op
Iteration   1: 5.435 ±(99.9%) 0.010 ms/op
Iteration   2: 5.312 ±(99.9%) 0.010 ms/op
Iteration   3: 5.436 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.394 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (5.312, 5.394, 5.436), stdev = 0.071
  CI (99.9%): [4.095, 6.694] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.880 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.471 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.010 ms/op
Iteration   1: 5.186 ±(99.9%) 0.007 ms/op
Iteration   2: 5.366 ±(99.9%) 0.007 ms/op
Iteration   3: 5.082 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.212 ±(99.9%) 2.622 ms/op [Average]
  (min, avg, max) = (5.082, 5.212, 5.366), stdev = 0.144
  CI (99.9%): [2.590, 7.833] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.946 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.435 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.617 ±(99.9%) 0.006 ms/op
Iteration   1: 5.803 ±(99.9%) 0.011 ms/op
Iteration   2: 5.611 ±(99.9%) 0.006 ms/op
Iteration   3: 5.450 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.622 ±(99.9%) 3.225 ms/op [Average]
  (min, avg, max) = (5.450, 5.622, 5.803), stdev = 0.177
  CI (99.9%): [2.396, 8.847] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.863 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.103 ±(99.9%) 0.017 ms/op
Iteration   1: 6.275 ±(99.9%) 0.016 ms/op
Iteration   2: 6.247 ±(99.9%) 0.013 ms/op
Iteration   3: 6.355 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.292 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (6.247, 6.292, 6.355), stdev = 0.056
  CI (99.9%): [5.272, 7.313] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.578 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.331 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.294 ±(99.9%) 0.029 ms/op
Iteration   1: 5.485 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.882 ms/op
                 createUser·p0.95:   7.733 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  25.570 ms/op
                 createUser·p0.9999: 30.955 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   2: 5.603 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   9.893 ms/op
                 createUser·p0.999:  25.919 ms/op
                 createUser·p0.9999: 29.272 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 5.745 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.307 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  29.557 ms/op
                 createUser·p0.9999: 36.962 ms/op
                 createUser·p1.00:   46.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171027
  mean =      5.609 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64547 
    [ 5.000, 10.000) = 104278 
    [10.000, 15.000) = 1794 
    [15.000, 20.000) = 148 
    [20.000, 25.000) = 36 
    [25.000, 30.000) = 164 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     26.870 ms/op
     p(99.9900) =     35.887 ms/op
     p(99.9990) =     40.229 ms/op
     p(99.9999) =     46.793 ms/op
    p(100.0000) =     46.793 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.734 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.296 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.386 ±(99.9%) 0.020 ms/op
Iteration   1: 5.463 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   7.160 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  15.756 ms/op
                 existUser·p0.9999: 25.400 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 5.179 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.078 ms/op
                 existUser·p0.99:   9.881 ms/op
                 existUser·p0.999:  26.221 ms/op
                 existUser·p0.9999: 31.195 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   3: 5.326 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   7.913 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  27.555 ms/op
                 existUser·p0.9999: 33.225 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180492
  mean =      5.320 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 91756 
    [ 5.000,  7.500) = 78500 
    [ 7.500, 10.000) = 8183 
    [10.000, 12.500) = 1428 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     31.516 ms/op
     p(99.9990) =     34.112 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.433 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.687 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.678 ±(99.9%) 0.025 ms/op
Iteration   1: 5.691 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.997 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   11.993 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 28.911 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   2: 5.628 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.111 ms/op
                 getUser·p0.95:   8.069 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  24.056 ms/op
                 getUser·p0.9999: 27.765 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 5.584 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   7.913 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  24.674 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170340
  mean =      5.634 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 61514 
    [ 5.000,  7.500) = 96262 
    [ 7.500, 10.000) = 9438 
    [10.000, 12.500) = 2034 
    [12.500, 15.000) = 661 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     28.409 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.172 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.325 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.602 ±(99.9%) 0.028 ms/op
Iteration   1: 6.491 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.929 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  28.475 ms/op
                 listUser·p0.9999: 34.542 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 6.308 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  27.304 ms/op
                 listUser·p0.9999: 30.240 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   3: 6.391 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  24.963 ms/op
                 listUser·p0.9999: 31.162 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150005
  mean =      6.396 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 15119 
    [ 5.000,  7.500) = 111951 
    [ 7.500, 10.000) = 17373 
    [10.000, 12.500) = 4135 
    [12.500, 15.000) = 849 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      8.258 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.370 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     33.096 ms/op
     p(99.9990) =     34.701 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.848 ± 4.582  ops/ms
ClientPb.existUser                       thrpt       3   5.659 ± 2.102  ops/ms
ClientPb.getUser                         thrpt       3   5.698 ± 2.187  ops/ms
ClientPb.listUser                        thrpt       3   5.149 ± 2.549  ops/ms
ClientPb.createUser                       avgt       3   5.394 ± 1.299   ms/op
ClientPb.existUser                        avgt       3   5.212 ± 2.622   ms/op
ClientPb.getUser                          avgt       3   5.622 ± 3.225   ms/op
ClientPb.listUser                         avgt       3   6.292 ± 1.020   ms/op
ClientPb.createUser                     sample  171027   5.609 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.914           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.870           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.887           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.793           ms/op
ClientPb.existUser                      sample  180492   5.320 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.516           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  170340   5.634 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.841           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.314           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.409           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  150005   6.396 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.258           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.230           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.096           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
