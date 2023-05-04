# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 5.874 ops/ms
# Warmup Iteration   3: 7.293 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.776 ±(99.9%) 2.007 ops/ms [Average]
  (min, avg, max) = (7.666, 7.776, 7.886), stdev = 0.110
  CI (99.9%): [5.770, 9.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 7.696 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.720 ops/ms
Iteration   2: 8.571 ops/ms
Iteration   3: 8.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.621 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (8.571, 8.621, 8.720), stdev = 0.086
  CI (99.9%): [7.058, 10.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 7.451 ops/ms
Iteration   2: 7.631 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.667 ±(99.9%) 4.318 ops/ms [Average]
  (min, avg, max) = (7.451, 7.667, 7.920), stdev = 0.237
  CI (99.9%): [3.349, 11.986] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ops/ms
# Warmup Iteration   2: 5.657 ops/ms
# Warmup Iteration   3: 6.130 ops/ms
Iteration   1: 6.280 ops/ms
Iteration   2: 6.403 ops/ms
Iteration   3: 6.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.347 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (6.280, 6.347, 6.403), stdev = 0.062
  CI (99.9%): [5.207, 7.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.612 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.015 ms/op
Iteration   1: 4.011 ±(99.9%) 0.003 ms/op
Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
Iteration   3: 3.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.989 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.942, 3.989, 4.014), stdev = 0.041
  CI (99.9%): [3.239, 4.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.603 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.007 ms/op
Iteration   1: 3.666 ±(99.9%) 0.004 ms/op
Iteration   2: 3.833 ±(99.9%) 0.003 ms/op
Iteration   3: 3.762 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.754 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.666, 3.754, 3.833), stdev = 0.083
  CI (99.9%): [2.232, 5.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.911 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.004 ms/op
Iteration   1: 3.905 ±(99.9%) 0.005 ms/op
Iteration   2: 3.810 ±(99.9%) 0.002 ms/op
Iteration   3: 3.767 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.827 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (3.767, 3.827, 3.905), stdev = 0.070
  CI (99.9%): [2.545, 5.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.829 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.017 ms/op
Iteration   1: 5.370 ±(99.9%) 0.009 ms/op
Iteration   2: 5.116 ±(99.9%) 0.011 ms/op
Iteration   3: 5.285 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.257 ±(99.9%) 2.363 ms/op [Average]
  (min, avg, max) = (5.116, 5.257, 5.370), stdev = 0.130
  CI (99.9%): [2.894, 7.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.952 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.016 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  10.161 ms/op
                 createUser·p0.9999: 29.226 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 3.976 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.763 ms/op
                 createUser·p0.999:  22.413 ms/op
                 createUser·p0.9999: 31.718 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   3: 3.944 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  13.136 ms/op
                 createUser·p0.9999: 32.269 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242473
  mean =      3.959 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8605 
    [ 2.500,  5.000) = 213030 
    [ 5.000,  7.500) = 18178 
    [ 7.500, 10.000) = 2094 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 106 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.637 ms/op
     p(99.9000) =     13.370 ms/op
     p(99.9900) =     31.482 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.551 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
Iteration   1: 3.728 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  12.086 ms/op
                 existUser·p0.9999: 15.637 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   2: 3.785 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.710 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   3: 3.703 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  19.628 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256837
  mean =      3.738 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14381 
    [ 2.500,  5.000) = 226006 
    [ 5.000,  7.500) = 14189 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     12.504 ms/op
     p(99.9900) =     21.603 ms/op
     p(99.9990) =     22.427 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 4.098 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  14.270 ms/op
                 getUser·p0.9999: 22.027 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.977 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   5.706 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  11.830 ms/op
                 getUser·p0.9999: 22.038 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235729
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9599 
    [ 2.500,  5.000) = 196507 
    [ 5.000,  7.500) = 27000 
    [ 7.500, 10.000) = 2148 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     11.981 ms/op
     p(99.9900) =     21.805 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.295 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.635 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.019 ms/op
Iteration   1: 5.170 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 29.644 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 4.991 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  19.977 ms/op
                 listUser·p0.9999: 23.907 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 5.121 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  31.311 ms/op
                 listUser·p0.9999: 40.354 ms/op
                 listUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188518
  mean =      5.093 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 116341 
    [ 5.000, 10.000) = 70239 
    [10.000, 15.000) = 1550 
    [15.000, 20.000) = 206 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     39.079 ms/op
     p(99.9990) =     40.713 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.776 ± 2.007  ops/ms
ClientGrpc.existUser                       thrpt       3   8.621 ± 1.563  ops/ms
ClientGrpc.getUser                         thrpt       3   7.667 ± 4.318  ops/ms
ClientGrpc.listUser                        thrpt       3   6.347 ± 1.140  ops/ms
ClientGrpc.createUser                       avgt       3   3.989 ± 0.750   ms/op
ClientGrpc.existUser                        avgt       3   3.754 ± 1.521   ms/op
ClientGrpc.getUser                          avgt       3   3.827 ± 1.282   ms/op
ClientGrpc.listUser                         avgt       3   5.257 ± 2.363   ms/op
ClientGrpc.createUser                     sample  242473   3.959 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.934           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.370           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.482           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.063           ms/op
ClientGrpc.existUser                      sample  256837   3.738 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.603           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.512           ms/op
ClientGrpc.getUser                        sample  235729   4.072 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.981           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.805           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.512           ms/op
ClientGrpc.listUser                       sample  188518   5.093 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.944           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.079           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.829           ms/op
