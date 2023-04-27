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
# Warmup Iteration   1: 2.384 ops/ms
# Warmup Iteration   2: 5.395 ops/ms
# Warmup Iteration   3: 9.432 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 10.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.835 ±(99.9%) 5.529 ops/ms [Average]
  (min, avg, max) = (9.485, 9.835, 10.019), stdev = 0.303
  CI (99.9%): [4.306, 15.365] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 8.846 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.298 ops/ms
Iteration   2: 10.728 ops/ms
Iteration   3: 10.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.545 ±(99.9%) 4.048 ops/ms [Average]
  (min, avg, max) = (10.298, 10.545, 10.728), stdev = 0.222
  CI (99.9%): [6.497, 14.594] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 9.336 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.371 ±(99.9%) 0.900 ops/ms [Average]
  (min, avg, max) = (10.323, 10.371, 10.422), stdev = 0.049
  CI (99.9%): [9.472, 11.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ops/ms
# Warmup Iteration   2: 7.832 ops/ms
# Warmup Iteration   3: 8.473 ops/ms
Iteration   1: 8.728 ops/ms
Iteration   2: 8.627 ops/ms
Iteration   3: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.761 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (8.627, 8.761, 8.927), stdev = 0.153
  CI (99.9%): [5.978, 11.544] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.445 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.005 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
Iteration   3: 3.202 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.158 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (3.082, 3.158, 3.202), stdev = 0.067
  CI (99.9%): [1.943, 4.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.034 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.017, 3.034, 3.056), stdev = 0.020
  CI (99.9%): [2.676, 3.393] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.101 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.306 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.160 ±(99.9%) 2.561 ms/op [Average]
  (min, avg, max) = (3.026, 3.160, 3.306), stdev = 0.140
  CI (99.9%): [0.600, 5.721] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.612 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.007 ms/op
Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
Iteration   2: 3.661 ±(99.9%) 0.010 ms/op
Iteration   3: 3.776 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (3.661, 3.720, 3.776), stdev = 0.057
  CI (99.9%): [2.672, 4.769] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.010 ms/op
Iteration   1: 3.216 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.046 ms/op
                 createUser·p0.9999: 23.107 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.437 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 24.960 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  10.196 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299933
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14552 
    [ 2.500,  5.000) = 280044 
    [ 5.000,  7.500) = 4432 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.175 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 20.137 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.458 ms/op
                 existUser·p0.999:  13.902 ms/op
                 existUser·p0.9999: 22.828 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  10.634 ms/op
                 existUser·p0.9999: 17.721 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309861
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35455 
    [ 2.500,  5.000) = 270080 
    [ 5.000,  7.500) = 3438 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     21.988 ms/op
     p(99.9990) =     23.164 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.481 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
Iteration   1: 3.315 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  15.606 ms/op
                 getUser·p0.9999: 25.373 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  17.038 ms/op
                 getUser·p0.9999: 22.195 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  14.467 ms/op
                 getUser·p0.9999: 21.853 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294142
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16977 
    [ 2.500,  5.000) = 266941 
    [ 5.000,  7.500) = 8940 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     14.694 ms/op
     p(99.9900) =     22.345 ms/op
     p(99.9990) =     25.823 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.945 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.066 ms/op
                 listUser·p0.999:  14.371 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.652 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.092 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.475 ms/op
                 listUser·p0.9999: 17.719 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.363 ms/op
                 listUser·p0.9999: 16.636 ms/op
                 listUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260680
  mean =      3.678 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 66 
    [ 2.500,  3.750) = 212956 
    [ 3.750,  5.000) = 41396 
    [ 5.000,  6.250) = 2138 
    [ 6.250,  7.500) = 2336 
    [ 7.500,  8.750) = 815 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 195 
    [12.500, 13.750) = 171 
    [13.750, 15.000) = 98 
    [15.000, 16.250) = 78 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     19.361 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.835 ± 5.529  ops/ms
ClientPb.existUser                       thrpt       3  10.545 ± 4.048  ops/ms
ClientPb.getUser                         thrpt       3  10.371 ± 0.900  ops/ms
ClientPb.listUser                        thrpt       3   8.761 ± 2.783  ops/ms
ClientPb.createUser                       avgt       3   3.158 ± 1.216   ms/op
ClientPb.existUser                        avgt       3   3.034 ± 0.358   ms/op
ClientPb.getUser                          avgt       3   3.160 ± 2.561   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 1.048   ms/op
ClientPb.createUser                     sample  299933   3.199 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.014           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.757           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  309861   3.095 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.615           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.988           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  294142   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.626           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.694           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.854           ms/op
ClientPb.listUser                       sample  260680   3.678 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.566           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.361           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.857           ms/op
