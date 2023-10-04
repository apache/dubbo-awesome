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
# Warmup Iteration   1: 2.252 ops/ms
# Warmup Iteration   2: 5.156 ops/ms
# Warmup Iteration   3: 8.876 ops/ms
Iteration   1: 9.664 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.456 ±(99.9%) 5.277 ops/ms [Average]
  (min, avg, max) = (9.126, 9.456, 9.664), stdev = 0.289
  CI (99.9%): [4.179, 14.733] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 9.156 ops/ms
# Warmup Iteration   3: 9.853 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 9.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (9.864, 10.128, 10.305), stdev = 0.232
  CI (99.9%): [5.888, 14.368] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ops/ms
# Warmup Iteration   2: 8.898 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.782 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.795 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (9.718, 9.795, 9.886), stdev = 0.085
  CI (99.9%): [8.249, 11.342] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 7.650 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.333 ops/ms
Iteration   3: 8.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.249 ±(99.9%) 3.233 ops/ms [Average]
  (min, avg, max) = (8.045, 8.249, 8.368), stdev = 0.177
  CI (99.9%): [5.016, 11.482] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.236 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.002 ms/op
Iteration   1: 3.394 ±(99.9%) 0.004 ms/op
Iteration   2: 3.400 ±(99.9%) 0.004 ms/op
Iteration   3: 3.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.330 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.195, 3.330, 3.400), stdev = 0.117
  CI (99.9%): [1.201, 5.458] (assumes normal distribution)


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
# Warmup Iteration   1: 8.472 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.162 ±(99.9%) 0.002 ms/op
Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
Iteration   3: 3.201 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.172 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.152, 3.172, 3.201), stdev = 0.026
  CI (99.9%): [2.703, 3.640] (assumes normal distribution)


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
# Warmup Iteration   1: 7.840 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.003 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.004 ms/op
Iteration   3: 3.245 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.228 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.192, 3.228, 3.246), stdev = 0.031
  CI (99.9%): [2.665, 3.790] (assumes normal distribution)


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
# Warmup Iteration   1: 10.175 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.006 ms/op
Iteration   1: 3.830 ±(99.9%) 0.006 ms/op
Iteration   2: 3.892 ±(99.9%) 0.005 ms/op
Iteration   3: 3.822 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.848 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.822, 3.848, 3.892), stdev = 0.038
  CI (99.9%): [3.149, 4.546] (assumes normal distribution)


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
# Warmup Iteration   1: 9.499 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
Iteration   1: 3.320 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  17.135 ms/op
                 createUser·p0.9999: 20.930 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.184 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  20.563 ms/op
                 createUser·p0.9999: 22.256 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  14.937 ms/op
                 createUser·p0.9999: 21.874 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288122
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11494 
    [ 2.500,  5.000) = 270594 
    [ 5.000,  7.500) = 4951 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 171 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     21.993 ms/op
     p(99.9990) =     22.641 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 7.355 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  14.892 ms/op
                 existUser·p0.9999: 24.721 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  15.352 ms/op
                 existUser·p0.9999: 23.785 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  16.839 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294309
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10894 
    [ 2.500,  5.000) = 278084 
    [ 5.000,  7.500) = 4592 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.348 ms/op
     p(99.9900) =     23.808 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 8.811 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
Iteration   1: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  18.392 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  19.156 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  10.539 ms/op
                 getUser·p0.9999: 21.890 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290919
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6579 
    [ 2.500,  5.000) = 278102 
    [ 5.000,  7.500) = 5320 
    [ 7.500, 10.000) = 384 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 198 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.175 ms/op
     p(99.9000) =     15.780 ms/op
     p(99.9900) =     22.565 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 8.812 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.010 ms/op
Iteration   1: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.637 ms/op
                 listUser·p0.999:  14.772 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.906 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.762 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 15.426 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   3: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.324 ms/op
                 listUser·p0.9999: 16.837 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244756
  mean =      3.919 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 237613 
    [ 5.000,  7.500) = 5476 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.963 ms/op
     p(99.9900) =     18.957 ms/op
     p(99.9990) =     20.760 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.456 ± 5.277  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 4.240  ops/ms
ClientPb.getUser                         thrpt       3   9.795 ± 1.546  ops/ms
ClientPb.listUser                        thrpt       3   8.249 ± 3.233  ops/ms
ClientPb.createUser                       avgt       3   3.330 ± 2.129   ms/op
ClientPb.existUser                        avgt       3   3.172 ± 0.469   ms/op
ClientPb.getUser                          avgt       3   3.228 ± 0.563   ms/op
ClientPb.listUser                         avgt       3   3.848 ± 0.699   ms/op
ClientPb.createUser                     sample  288122   3.330 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.731           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.122           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.101           ms/op
ClientPb.existUser                      sample  294309   3.261 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.096           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.808           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.723           ms/op
ClientPb.getUser                        sample  290919   3.300 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.969           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.175           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.780           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.757           ms/op
ClientPb.listUser                       sample  244756   3.919 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.963           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.957           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
