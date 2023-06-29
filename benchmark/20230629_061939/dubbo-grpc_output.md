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
# Warmup Iteration   1: 4.034 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.996 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.558 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (10.444, 10.558, 10.632), stdev = 0.100
  CI (99.9%): [8.727, 12.390] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 10.524 ops/ms
# Warmup Iteration   3: 11.064 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.135 ops/ms
Iteration   3: 11.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.187 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (11.054, 11.187, 11.370), stdev = 0.164
  CI (99.9%): [8.189, 14.184] (assumes normal distribution)


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
# Warmup Iteration   1: 7.149 ops/ms
# Warmup Iteration   2: 10.246 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.630 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.549 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (10.408, 10.549, 10.630), stdev = 0.122
  CI (99.9%): [8.314, 12.783] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.001 ops/ms
# Warmup Iteration   2: 7.549 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 7.992 ops/ms
Iteration   2: 7.874 ops/ms
Iteration   3: 7.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.937 ±(99.9%) 1.089 ops/ms [Average]
  (min, avg, max) = (7.874, 7.937, 7.992), stdev = 0.060
  CI (99.9%): [6.848, 9.027] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.041 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.004 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.011, 3.043, 3.076), stdev = 0.032
  CI (99.9%): [2.453, 3.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.004 ms/op
Iteration   1: 2.866 ±(99.9%) 0.002 ms/op
Iteration   2: 2.895 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (2.866, 2.907, 2.961), stdev = 0.049
  CI (99.9%): [2.018, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.981, 3.010, 3.027), stdev = 0.025
  CI (99.9%): [2.550, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.950 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.009 ms/op
Iteration   1: 3.983 ±(99.9%) 0.027 ms/op
Iteration   2: 4.014 ±(99.9%) 0.034 ms/op
Iteration   3: 3.976 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.991 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.976, 3.991, 4.014), stdev = 0.021
  CI (99.9%): [3.617, 4.365] (assumes normal distribution)


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.005 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.133 ms/op
                 createUser·p0.9999: 19.157 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.672 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 16.055 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313866
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20728 
    [ 2.500,  5.000) = 291614 
    [ 5.000,  7.500) = 1086 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.210 ms/op
     p(99.9900) =     21.614 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.005 ms/op
Iteration   1: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.394 ms/op
                 existUser·p0.9999: 12.843 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   2: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.321 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 14.784 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330593
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 957 
    [ 1.250,  2.500) = 37837 
    [ 2.500,  3.750) = 284959 
    [ 3.750,  5.000) = 5883 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     13.843 ms/op
     p(99.9990) =     14.976 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 12.658 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.758 ms/op
                 getUser·p0.9999: 21.177 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 25.094 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320558
  mean =      2.993 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28395 
    [ 2.500,  5.000) = 290679 
    [ 5.000,  7.500) = 1228 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.061 ms/op
     p(99.9900) =     24.344 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 3.977 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 16.052 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.043 ms/op
                 listUser·p0.9999: 17.618 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.290 ms/op
                 listUser·p0.9999: 20.972 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240682
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2569 
    [ 2.500,  5.000) = 216036 
    [ 5.000,  7.500) = 20645 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.559 ms/op
     p(99.9900) =     20.574 ms/op
     p(99.9990) =     22.294 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.558 ± 1.832  ops/ms
ClientGrpc.existUser                       thrpt       3  11.187 ± 2.998  ops/ms
ClientGrpc.getUser                         thrpt       3  10.549 ± 2.234  ops/ms
ClientGrpc.listUser                        thrpt       3   7.937 ± 1.089  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.590   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.889   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   3.991 ± 0.374   ms/op
ClientGrpc.createUser                     sample  313866   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.437           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.210           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.614           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.381           ms/op
ClientGrpc.existUser                      sample  330593   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.843           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.122           ms/op
ClientGrpc.getUser                        sample  320558   2.993 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.686           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.344           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.559           ms/op
ClientGrpc.listUser                       sample  240682   3.985 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.559           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.574           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.577           ms/op
