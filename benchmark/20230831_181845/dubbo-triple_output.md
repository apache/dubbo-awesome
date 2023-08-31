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
# Warmup Iteration   1: 1.745 ops/ms
# Warmup Iteration   2: 4.281 ops/ms
# Warmup Iteration   3: 7.043 ops/ms
Iteration   1: 7.295 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.773 ±(99.9%) 7.567 ops/ms [Average]
  (min, avg, max) = (7.295, 7.773, 8.036), stdev = 0.415
  CI (99.9%): [0.206, 15.340] (assumes normal distribution)


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
# Warmup Iteration   1: 2.182 ops/ms
# Warmup Iteration   2: 6.617 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.244 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (8.194, 8.244, 8.274), stdev = 0.043
  CI (99.9%): [7.451, 9.037] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.366 ops/ms
# Warmup Iteration   2: 6.470 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.589 ops/ms
Iteration   2: 7.743 ops/ms
Iteration   3: 7.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.752 ±(99.9%) 3.038 ops/ms [Average]
  (min, avg, max) = (7.589, 7.752, 7.922), stdev = 0.166
  CI (99.9%): [4.714, 10.789] (assumes normal distribution)


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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 5.753 ops/ms
# Warmup Iteration   3: 6.629 ops/ms
Iteration   1: 6.699 ops/ms
Iteration   2: 6.630 ops/ms
Iteration   3: 6.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.695 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (6.630, 6.695, 6.756), stdev = 0.063
  CI (99.9%): [5.538, 7.852] (assumes normal distribution)


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
# Warmup Iteration   1: 11.995 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.010 ms/op
Iteration   1: 4.070 ±(99.9%) 0.006 ms/op
Iteration   2: 4.021 ±(99.9%) 0.007 ms/op
Iteration   3: 3.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.006 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.927, 4.006, 4.070), stdev = 0.073
  CI (99.9%): [2.677, 5.335] (assumes normal distribution)


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
# Warmup Iteration   1: 11.945 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.005 ms/op
Iteration   1: 4.075 ±(99.9%) 0.007 ms/op
Iteration   2: 3.858 ±(99.9%) 0.003 ms/op
Iteration   3: 3.787 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.907 ±(99.9%) 2.735 ms/op [Average]
  (min, avg, max) = (3.787, 3.907, 4.075), stdev = 0.150
  CI (99.9%): [1.172, 6.641] (assumes normal distribution)


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
# Warmup Iteration   1: 13.160 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.789 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.005 ms/op
Iteration   1: 4.284 ±(99.9%) 0.012 ms/op
Iteration   2: 4.049 ±(99.9%) 0.008 ms/op
Iteration   3: 4.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.117 ±(99.9%) 2.645 ms/op [Average]
  (min, avg, max) = (4.019, 4.117, 4.284), stdev = 0.145
  CI (99.9%): [1.472, 6.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.288 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.790 ±(99.9%) 0.006 ms/op
Iteration   1: 4.743 ±(99.9%) 0.013 ms/op
Iteration   2: 4.752 ±(99.9%) 0.012 ms/op
Iteration   3: 4.689 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.728 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (4.689, 4.728, 4.752), stdev = 0.034
  CI (99.9%): [4.102, 5.353] (assumes normal distribution)


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
# Warmup Iteration   1: 12.312 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.554 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.019 ms/op
Iteration   1: 4.053 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  25.199 ms/op
                 createUser·p0.9999: 27.430 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  17.400 ms/op
                 createUser·p0.9999: 28.805 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   3: 3.932 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.968 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  29.320 ms/op
                 createUser·p0.9999: 38.863 ms/op
                 createUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239495
  mean =      4.006 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 136 
    [ 2.500,  5.000) = 228341 
    [ 5.000,  7.500) = 9120 
    [ 7.500, 10.000) = 1166 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 150 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     25.313 ms/op
     p(99.9900) =     37.621 ms/op
     p(99.9990) =     39.518 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


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
# Warmup Iteration   1: 11.524 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.025 ms/op
                 existUser·p0.999:  18.742 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.986 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.057 ms/op
                 existUser·p0.999:  12.721 ms/op
                 existUser·p0.9999: 34.800 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   3: 4.096 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239701
  mean =      4.003 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177 
    [ 2.500,  5.000) = 225410 
    [ 5.000,  7.500) = 10708 
    [ 7.500, 10.000) = 2320 
    [10.000, 12.500) = 676 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     33.132 ms/op
     p(99.9990) =     35.494 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 11.872 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.015 ms/op
Iteration   1: 4.264 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  22.007 ms/op
                 getUser·p0.9999: 24.854 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  12.881 ms/op
                 getUser·p0.9999: 28.660 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  11.150 ms/op
                 getUser·p0.9999: 36.925 ms/op
                 getUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233058
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 217244 
    [ 5.000,  7.500) = 13147 
    [ 7.500, 10.000) = 1816 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     33.207 ms/op
     p(99.9990) =     37.597 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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
# Warmup Iteration   1: 15.472 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.522 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.887 ±(99.9%) 0.018 ms/op
Iteration   1: 4.812 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  24.888 ms/op
                 listUser·p0.9999: 28.913 ms/op
                 listUser·p1.00:   30.376 ms/op

Iteration   2: 4.797 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  18.148 ms/op
                 listUser·p0.9999: 23.061 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 4.748 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  18.044 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200394
  mean =      4.786 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 169625 
    [ 5.000,  7.500) = 24740 
    [ 7.500, 10.000) = 4456 
    [10.000, 12.500) = 840 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     27.355 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.773 ± 7.567  ops/ms
ClientPb.existUser                       thrpt       3   8.244 ± 0.793  ops/ms
ClientPb.getUser                         thrpt       3   7.752 ± 3.038  ops/ms
ClientPb.listUser                        thrpt       3   6.695 ± 1.157  ops/ms
ClientPb.createUser                       avgt       3   4.006 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   3.907 ± 2.735   ms/op
ClientPb.getUser                          avgt       3   4.117 ± 2.645   ms/op
ClientPb.listUser                         avgt       3   4.728 ± 0.625   ms/op
ClientPb.createUser                     sample  239495   4.006 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.715           ms/op
ClientPb.existUser                      sample  239701   4.003 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.477           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.159           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.433           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  233058   4.117 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.514           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.207           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.749           ms/op
ClientPb.listUser                       sample  200394   4.786 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.095           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.546           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.355           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.376           ms/op
