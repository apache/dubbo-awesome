# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 5.249 ops/ms
# Warmup Iteration   3: 6.831 ops/ms
Iteration   1: 7.184 ops/ms
Iteration   2: 7.116 ops/ms
Iteration   3: 7.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.198 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (7.116, 7.198, 7.295), stdev = 0.090
  CI (99.9%): [5.553, 8.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ops/ms
# Warmup Iteration   2: 7.204 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.954 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (7.909, 7.954, 8.023), stdev = 0.061
  CI (99.9%): [6.839, 9.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ops/ms
# Warmup Iteration   2: 6.300 ops/ms
# Warmup Iteration   3: 7.266 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 7.305 ops/ms
Iteration   3: 7.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.412 ±(99.9%) 2.951 ops/ms [Average]
  (min, avg, max) = (7.305, 7.412, 7.598), stdev = 0.162
  CI (99.9%): [4.460, 10.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 4.909 ops/ms
# Warmup Iteration   3: 5.518 ops/ms
Iteration   1: 5.673 ops/ms
Iteration   2: 5.540 ops/ms
Iteration   3: 5.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.681 ±(99.9%) 2.651 ops/ms [Average]
  (min, avg, max) = (5.540, 5.681, 5.830), stdev = 0.145
  CI (99.9%): [3.030, 8.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.006 ms/op
Iteration   1: 4.641 ±(99.9%) 0.005 ms/op
Iteration   2: 4.692 ±(99.9%) 0.004 ms/op
Iteration   3: 4.601 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.645 ±(99.9%) 0.834 ms/op [Average]
  (min, avg, max) = (4.601, 4.645, 4.692), stdev = 0.046
  CI (99.9%): [3.811, 5.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.364 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.005 ms/op
Iteration   1: 4.047 ±(99.9%) 0.003 ms/op
Iteration   2: 4.032 ±(99.9%) 0.004 ms/op
Iteration   3: 4.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.047 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (4.032, 4.047, 4.062), stdev = 0.015
  CI (99.9%): [3.768, 4.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.567 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.007 ms/op
Iteration   1: 4.234 ±(99.9%) 0.004 ms/op
Iteration   2: 4.289 ±(99.9%) 0.002 ms/op
Iteration   3: 4.220 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.248 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (4.220, 4.248, 4.289), stdev = 0.037
  CI (99.9%): [3.577, 4.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.549 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.898 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.554 ±(99.9%) 0.019 ms/op
Iteration   1: 5.416 ±(99.9%) 0.035 ms/op
Iteration   2: 5.565 ±(99.9%) 0.020 ms/op
Iteration   3: 5.530 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.504 ±(99.9%) 1.424 ms/op [Average]
  (min, avg, max) = (5.416, 5.504, 5.565), stdev = 0.078
  CI (99.9%): [4.080, 6.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.911 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.012 ms/op
Iteration   1: 4.335 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  13.646 ms/op
                 createUser·p0.9999: 21.151 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 4.225 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   4.162 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  12.424 ms/op
                 createUser·p0.9999: 19.197 ms/op
                 createUser·p1.00:   19.988 ms/op

Iteration   3: 4.382 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 27.158 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222448
  mean =      4.313 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3626 
    [ 2.500,  5.000) = 186794 
    [ 5.000,  7.500) = 30276 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.624 ms/op
     p(99.9900) =     26.665 ms/op
     p(99.9990) =     27.452 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.920 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.010 ms/op
Iteration   1: 4.094 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  12.182 ms/op
                 existUser·p0.9999: 15.757 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.471 ms/op
                 existUser·p0.999:  11.162 ms/op
                 existUser·p0.9999: 27.987 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 18.539 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237935
  mean =      4.034 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10080 
    [ 2.500,  5.000) = 205695 
    [ 5.000,  7.500) = 20602 
    [ 7.500, 10.000) = 1159 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.747 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     27.539 ms/op
     p(99.9990) =     28.535 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.770 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.011 ms/op
Iteration   1: 4.284 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  12.085 ms/op
                 getUser·p0.9999: 19.318 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 4.333 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  12.822 ms/op
                 getUser·p0.9999: 33.444 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 4.297 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  10.870 ms/op
                 getUser·p0.9999: 26.134 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223037
  mean =      4.305 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2474 
    [ 2.500,  5.000) = 188070 
    [ 5.000,  7.500) = 30848 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     12.369 ms/op
     p(99.9900) =     31.001 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.156 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.154 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.699 ±(99.9%) 0.022 ms/op
Iteration   1: 5.630 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  22.392 ms/op
                 listUser·p0.9999: 25.577 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 5.689 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   10.582 ms/op
                 listUser·p0.999:  15.935 ms/op
                 listUser·p0.9999: 21.058 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 5.435 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.913 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  22.009 ms/op
                 listUser·p0.9999: 25.891 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171959
  mean =      5.582 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 56960 
    [ 5.000,  7.500) = 102733 
    [ 7.500, 10.000) = 10042 
    [10.000, 12.500) = 1411 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     26.498 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.198 ± 1.645  ops/ms
ClientGrpc.existUser                       thrpt       3   7.954 ± 1.115  ops/ms
ClientGrpc.getUser                         thrpt       3   7.412 ± 2.951  ops/ms
ClientGrpc.listUser                        thrpt       3   5.681 ± 2.651  ops/ms
ClientGrpc.createUser                       avgt       3   4.645 ± 0.834   ms/op
ClientGrpc.existUser                        avgt       3   4.047 ± 0.279   ms/op
ClientGrpc.getUser                          avgt       3   4.248 ± 0.671   ms/op
ClientGrpc.listUser                         avgt       3   5.504 ± 1.424   ms/op
ClientGrpc.createUser                     sample  222448   4.313 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.842           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.062           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.624           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.665           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  237935   4.034 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.935           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.747           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.539           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.359           ms/op
ClientGrpc.getUser                        sample  223037   4.305 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.028           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.369           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.001           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.620           ms/op
ClientGrpc.listUser                       sample  171959   5.582 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.358           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.611           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.461           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
