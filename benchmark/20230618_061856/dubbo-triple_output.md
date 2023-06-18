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
# Warmup Iteration   1: 2.682 ops/ms
# Warmup Iteration   2: 6.100 ops/ms
# Warmup Iteration   3: 9.495 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 3.506 ops/ms [Average]
  (min, avg, max) = (9.675, 9.897, 10.009), stdev = 0.192
  CI (99.9%): [6.391, 13.402] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.488 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (10.245, 10.488, 10.718), stdev = 0.237
  CI (99.9%): [6.167, 14.810] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.537 ops/ms
# Warmup Iteration   2: 9.155 ops/ms
# Warmup Iteration   3: 9.321 ops/ms
Iteration   1: 9.943 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.016 ±(99.9%) 1.701 ops/ms [Average]
  (min, avg, max) = (9.943, 10.016, 10.121), stdev = 0.093
  CI (99.9%): [8.315, 11.717] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ops/ms
# Warmup Iteration   2: 7.501 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.276 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 8.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.505 ±(99.9%) 4.428 ops/ms [Average]
  (min, avg, max) = (8.276, 8.505, 8.759), stdev = 0.243
  CI (99.9%): [4.077, 12.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.005 ms/op
Iteration   1: 3.195 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.004 ms/op
Iteration   3: 3.413 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.244 ±(99.9%) 2.757 ms/op [Average]
  (min, avg, max) = (3.123, 3.244, 3.413), stdev = 0.151
  CI (99.9%): [0.487, 6.000] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.637 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
Iteration   3: 3.021 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.021, 3.102, 3.183), stdev = 0.081
  CI (99.9%): [1.622, 4.583] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.618 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.005 ms/op
Iteration   2: 3.238 ±(99.9%) 0.005 ms/op
Iteration   3: 3.148 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.138, 3.175, 3.238), stdev = 0.055
  CI (99.9%): [2.175, 4.175] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.693 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.003 ms/op
Iteration   1: 3.701 ±(99.9%) 0.010 ms/op
Iteration   2: 3.664 ±(99.9%) 0.009 ms/op
Iteration   3: 3.615 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.660 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.615, 3.660, 3.701), stdev = 0.043
  CI (99.9%): [2.871, 4.449] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.167 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.009 ms/op
Iteration   1: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 21.064 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 3.186 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   6.190 ms/op
                 createUser·p0.999:  18.670 ms/op
                 createUser·p0.9999: 23.330 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297579
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15424 
    [ 2.500,  5.000) = 275838 
    [ 5.000,  7.500) = 5556 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     24.673 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.297 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.506 ms/op
                 existUser·p0.999:  15.136 ms/op
                 existUser·p0.9999: 22.963 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.973 ms/op
                 existUser·p0.999:  12.832 ms/op
                 existUser·p0.9999: 24.721 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 21.686 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302540
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16951 
    [ 2.500,  5.000) = 279191 
    [ 5.000,  7.500) = 5544 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     23.314 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 7.495 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.010 ms/op
Iteration   1: 3.197 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  14.019 ms/op
                 getUser·p0.9999: 20.545 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.256 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  21.702 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  14.254 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294721
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8495 
    [ 2.500,  5.000) = 278903 
    [ 5.000,  7.500) = 6198 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.256 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     30.152 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.538 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.013 ms/op
Iteration   1: 3.689 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.624 ms/op
                 listUser·p0.999:  18.490 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 16.056 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   3: 3.702 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.247 ms/op
                 listUser·p0.9999: 17.062 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259976
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 253639 
    [ 5.000,  7.500) = 4568 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.980 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 3.506  ops/ms
ClientPb.existUser                       thrpt       3  10.488 ± 4.321  ops/ms
ClientPb.getUser                         thrpt       3  10.016 ± 1.701  ops/ms
ClientPb.listUser                        thrpt       3   8.505 ± 4.428  ops/ms
ClientPb.createUser                       avgt       3   3.244 ± 2.757   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.480   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 1.000   ms/op
ClientPb.listUser                         avgt       3   3.660 ± 0.789   ms/op
ClientPb.createUser                     sample  297579   3.223 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.762           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.771           ms/op
ClientPb.existUser                      sample  302540   3.174 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.494           ms/op
ClientPb.getUser                        sample  294721   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.256           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.254           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.148           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  259976   3.693 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.382           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
