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
# Warmup Iteration   1: 4.435 ops/ms
# Warmup Iteration   2: 8.932 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.528 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (10.487, 10.528, 10.596), stdev = 0.060
  CI (99.9%): [9.441, 11.615] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 10.820 ops/ms
# Warmup Iteration   3: 11.075 ops/ms
Iteration   1: 11.060 ops/ms
Iteration   2: 11.178 ops/ms
Iteration   3: 11.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.118 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (11.060, 11.118, 11.178), stdev = 0.059
  CI (99.9%): [10.046, 12.190] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ops/ms
# Warmup Iteration   2: 10.394 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.568 ±(99.9%) 0.849 ops/ms [Average]
  (min, avg, max) = (10.529, 10.568, 10.619), stdev = 0.047
  CI (99.9%): [9.719, 11.416] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 7.788 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.318 ops/ms
Iteration   2: 8.271 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.322 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (8.271, 8.322, 8.378), stdev = 0.053
  CI (99.9%): [7.347, 9.297] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.001 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.064, 3.088, 3.130), stdev = 0.036
  CI (99.9%): [2.426, 3.751] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.002 ms/op
Iteration   1: 2.891 ±(99.9%) 0.003 ms/op
Iteration   2: 2.866 ±(99.9%) 0.003 ms/op
Iteration   3: 2.837 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.865 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (2.837, 2.865, 2.891), stdev = 0.027
  CI (99.9%): [2.371, 3.358] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.990, 3.003, 3.013), stdev = 0.012
  CI (99.9%): [2.780, 3.226] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.017 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
Iteration   2: 3.850 ±(99.9%) 0.011 ms/op
Iteration   3: 3.949 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.901 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.850, 3.901, 3.949), stdev = 0.049
  CI (99.9%): [3.000, 4.802] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.806 ms/op
                 createUser·p0.9999: 13.549 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.471 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.186 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.352 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  10.117 ms/op
                 createUser·p0.9999: 26.884 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317305
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20421 
    [ 2.500,  5.000) = 295767 
    [ 5.000,  7.500) = 741 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.093 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.523 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.437 ms/op
                 existUser·p0.9999: 12.112 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 16.171 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 2.914 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.455 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 29.100 ms/op
                 existUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328392
  mean =      2.922 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40690 
    [ 2.500,  5.000) = 286524 
    [ 5.000,  7.500) = 856 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.427 ms/op
     p(99.9900) =     19.016 ms/op
     p(99.9990) =     29.773 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.280 ms/op
                 getUser·p0.9999: 12.147 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.638 ms/op
                 getUser·p0.9999: 13.476 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.723 ms/op
                 getUser·p0.9999: 16.155 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320482
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1831 
    [ 1.250,  2.500) = 25094 
    [ 2.500,  3.750) = 277235 
    [ 3.750,  5.000) = 15008 
    [ 5.000,  6.250) = 675 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.377 ms/op
     p(99.9900) =     15.562 ms/op
     p(99.9990) =     17.287 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.010 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.257 ms/op
                 listUser·p0.9999: 15.002 ms/op
                 listUser·p1.00:   15.270 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  19.707 ms/op
                 listUser·p0.9999: 27.188 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.769 ms/op
                 listUser·p0.9999: 27.738 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248607
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5150 
    [ 2.500,  5.000) = 221975 
    [ 5.000,  7.500) = 20358 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     26.874 ms/op
     p(99.9990) =     28.903 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.528 ± 1.087  ops/ms
ClientGrpc.existUser                       thrpt       3  11.118 ± 1.072  ops/ms
ClientGrpc.getUser                         thrpt       3  10.568 ± 0.849  ops/ms
ClientGrpc.listUser                        thrpt       3   8.322 ± 0.975  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.662   ms/op
ClientGrpc.existUser                        avgt       3   2.865 ± 0.494   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.223   ms/op
ClientGrpc.listUser                         avgt       3   3.901 ± 0.901   ms/op
ClientGrpc.createUser                     sample  317305   3.025 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.352           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.509           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  328392   2.922 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.427           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.016           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.950           ms/op
ClientGrpc.getUser                        sample  320482   2.994 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.539           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.377           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.562           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.629           ms/op
ClientGrpc.listUser                       sample  248607   3.862 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.668           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.221           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.874           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.967           ms/op
