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
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 4.103 ops/ms
# Warmup Iteration   3: 7.334 ops/ms
Iteration   1: 7.314 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.894 ±(99.9%) 9.229 ops/ms [Average]
  (min, avg, max) = (7.314, 7.894, 8.243), stdev = 0.506
  CI (99.9%): [≈ 0, 17.124] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 6.578 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.897 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.091 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (7.897, 8.091, 8.276), stdev = 0.190
  CI (99.9%): [4.634, 11.548] (assumes normal distribution)


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
# Warmup Iteration   1: 1.985 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 8.026 ops/ms
Iteration   1: 7.968 ops/ms
Iteration   2: 8.041 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.990 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (7.962, 7.990, 8.041), stdev = 0.044
  CI (99.9%): [7.179, 8.801] (assumes normal distribution)


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
# Warmup Iteration   1: 1.962 ops/ms
# Warmup Iteration   2: 5.280 ops/ms
# Warmup Iteration   3: 6.364 ops/ms
Iteration   1: 6.547 ops/ms
Iteration   2: 6.622 ops/ms
Iteration   3: 6.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.628 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (6.547, 6.628, 6.716), stdev = 0.085
  CI (99.9%): [5.077, 8.180] (assumes normal distribution)


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
# Warmup Iteration   1: 13.673 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.005 ms/op
Iteration   1: 3.925 ±(99.9%) 0.009 ms/op
Iteration   2: 4.127 ±(99.9%) 0.009 ms/op
Iteration   3: 3.980 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.011 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (3.925, 4.011, 4.127), stdev = 0.105
  CI (99.9%): [2.101, 5.920] (assumes normal distribution)


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
# Warmup Iteration   1: 10.920 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.007 ms/op
Iteration   1: 3.920 ±(99.9%) 0.005 ms/op
Iteration   2: 3.982 ±(99.9%) 0.008 ms/op
Iteration   3: 3.885 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.929 ±(99.9%) 0.899 ms/op [Average]
  (min, avg, max) = (3.885, 3.929, 3.982), stdev = 0.049
  CI (99.9%): [3.029, 4.828] (assumes normal distribution)


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
# Warmup Iteration   1: 13.457 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.004 ms/op
Iteration   1: 4.110 ±(99.9%) 0.011 ms/op
Iteration   2: 4.325 ±(99.9%) 0.004 ms/op
Iteration   3: 4.106 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.180 ±(99.9%) 2.288 ms/op [Average]
  (min, avg, max) = (4.106, 4.180, 4.325), stdev = 0.125
  CI (99.9%): [1.892, 6.468] (assumes normal distribution)


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
# Warmup Iteration   1: 14.851 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.965 ±(99.9%) 0.005 ms/op
Iteration   1: 4.967 ±(99.9%) 0.007 ms/op
Iteration   2: 4.814 ±(99.9%) 0.012 ms/op
Iteration   3: 4.697 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.826 ±(99.9%) 2.476 ms/op [Average]
  (min, avg, max) = (4.697, 4.826, 4.967), stdev = 0.136
  CI (99.9%): [2.350, 7.302] (assumes normal distribution)


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
# Warmup Iteration   1: 13.242 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.016 ms/op
Iteration   1: 4.108 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   8.110 ms/op
                 createUser·p0.999:  23.669 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 3.964 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  10.923 ms/op
                 createUser·p0.9999: 32.801 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   3: 3.948 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  29.196 ms/op
                 createUser·p0.9999: 32.568 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239503
  mean =      4.005 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 379 
    [ 2.500,  5.000) = 224918 
    [ 5.000,  7.500) = 11714 
    [ 7.500, 10.000) = 1819 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     31.950 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 12.109 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.013 ms/op
Iteration   1: 3.751 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   2: 3.812 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 36.674 ms/op
                 existUser·p1.00:   37.093 ms/op

Iteration   3: 3.949 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.702 ms/op
                 existUser·p0.999:  27.984 ms/op
                 existUser·p0.9999: 31.192 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250308
  mean =      3.836 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 437 
    [ 2.500,  5.000) = 238368 
    [ 5.000,  7.500) = 9369 
    [ 7.500, 10.000) = 1504 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     22.600 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 13.077 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.014 ms/op
Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  15.155 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  23.138 ms/op
                 getUser·p0.9999: 26.988 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 4.029 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.529 ms/op
                 getUser·p0.999:  23.366 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239890
  mean =      4.001 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 227580 
    [ 5.000,  7.500) = 9346 
    [ 7.500, 10.000) = 1772 
    [10.000, 12.500) = 693 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 127 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     27.388 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.255 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.988 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.018 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  25.345 ms/op
                 listUser·p0.9999: 31.923 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   2: 4.682 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 24.254 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.836 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  17.212 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200938
  mean =      4.776 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 169615 
    [ 5.000,  7.500) = 25745 
    [ 7.500, 10.000) = 4160 
    [10.000, 12.500) = 895 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     29.554 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.894 ± 9.229  ops/ms
ClientPb.existUser                       thrpt       3   8.091 ± 3.457  ops/ms
ClientPb.getUser                         thrpt       3   7.990 ± 0.811  ops/ms
ClientPb.listUser                        thrpt       3   6.628 ± 1.552  ops/ms
ClientPb.createUser                       avgt       3   4.011 ± 1.909   ms/op
ClientPb.existUser                        avgt       3   3.929 ± 0.899   ms/op
ClientPb.getUser                          avgt       3   4.180 ± 2.288   ms/op
ClientPb.listUser                         avgt       3   4.826 ± 2.476   ms/op
ClientPb.createUser                     sample  239503   4.005 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.950           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  250308   3.836 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.600           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.848           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.093           ms/op
ClientPb.getUser                        sample  239890   4.001 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.903           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  200938   4.776 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.886           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.440           ms/op
