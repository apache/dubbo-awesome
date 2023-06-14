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
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 8.959 ops/ms
# Warmup Iteration   3: 9.929 ops/ms
Iteration   1: 10.834 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.573 ±(99.9%) 4.467 ops/ms [Average]
  (min, avg, max) = (10.349, 10.573, 10.834), stdev = 0.245
  CI (99.9%): [6.105, 15.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.158 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 11.082 ops/ms
Iteration   1: 11.041 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 11.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.975 ±(99.9%) 4.351 ops/ms [Average]
  (min, avg, max) = (10.710, 10.975, 11.173), stdev = 0.238
  CI (99.9%): [6.624, 15.326] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.425 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.598 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (10.539, 10.598, 10.694), stdev = 0.084
  CI (99.9%): [9.065, 12.130] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.366 ops/ms
# Warmup Iteration   2: 7.674 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 8.325 ops/ms
Iteration   2: 8.414 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.335 ±(99.9%) 1.372 ops/ms [Average]
  (min, avg, max) = (8.265, 8.335, 8.414), stdev = 0.075
  CI (99.9%): [6.962, 9.707] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.001 ms/op
Iteration   1: 2.997 ±(99.9%) 0.001 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.031 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.997, 3.031, 3.071), stdev = 0.038
  CI (99.9%): [2.345, 3.716] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.002 ms/op
Iteration   1: 2.920 ±(99.9%) 0.002 ms/op
Iteration   2: 2.863 ±(99.9%) 0.001 ms/op
Iteration   3: 2.826 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (2.826, 2.870, 2.920), stdev = 0.047
  CI (99.9%): [2.006, 3.734] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.004 ms/op
Iteration   1: 3.028 ±(99.9%) 0.001 ms/op
Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.028, 3.044, 3.058), stdev = 0.015
  CI (99.9%): [2.766, 3.323] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.007 ms/op
Iteration   1: 3.964 ±(99.9%) 0.036 ms/op
Iteration   2: 3.986 ±(99.9%) 0.009 ms/op
Iteration   3: 3.872 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.872, 3.941, 3.986), stdev = 0.061
  CI (99.9%): [2.837, 5.045] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.866 ms/op
                 createUser·p0.9999: 18.835 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.595 ms/op
                 createUser·p0.9999: 16.332 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  8.164 ms/op
                 createUser·p0.9999: 33.306 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317118
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25974 
    [ 2.500,  5.000) = 289560 
    [ 5.000,  7.500) = 1113 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.829 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.127 ms/op
                 existUser·p0.9999: 16.698 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.183 ms/op
                 existUser·p0.999:  6.731 ms/op
                 existUser·p0.9999: 18.355 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 19.175 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325675
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 36972 
    [ 2.500,  3.750) = 279225 
    [ 3.750,  5.000) = 7758 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.342 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     19.513 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.787 ms/op
                 getUser·p0.9999: 12.755 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.303 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.771 ms/op
                 getUser·p0.9999: 14.728 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.742 ms/op
                 getUser·p0.9999: 17.197 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316234
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 413 
    [ 1.250,  2.500) = 18511 
    [ 2.500,  3.750) = 281804 
    [ 3.750,  5.000) = 14018 
    [ 5.000,  6.250) = 938 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     15.659 ms/op
     p(99.9990) =     17.515 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 5.389 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.130 ms/op
                 listUser·p0.999:  14.171 ms/op
                 listUser·p0.9999: 21.860 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 3.964 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.392 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.153 ms/op
                 listUser·p0.9999: 26.174 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.858 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 25.261 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241011
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3078 
    [ 2.500,  5.000) = 210523 
    [ 5.000,  7.500) = 26046 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     25.228 ms/op
     p(99.9990) =     26.430 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.573 ± 4.467  ops/ms
ClientGrpc.existUser                       thrpt       3  10.975 ± 4.351  ops/ms
ClientGrpc.getUser                         thrpt       3  10.598 ± 1.532  ops/ms
ClientGrpc.listUser                        thrpt       3   8.335 ± 1.372  ops/ms
ClientGrpc.createUser                       avgt       3   3.031 ± 0.686   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 0.864   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.278   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 1.104   ms/op
ClientGrpc.createUser                     sample  317118   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.655           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.884           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.620           ms/op
ClientGrpc.existUser                      sample  325675   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.759           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.342           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.809           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  316234   3.034 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.303           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.659           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  241011   3.985 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.392           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.228           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
