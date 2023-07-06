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
# Warmup Iteration   1: 4.188 ops/ms
# Warmup Iteration   2: 8.695 ops/ms
# Warmup Iteration   3: 9.950 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.401 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (10.361, 10.401, 10.422), stdev = 0.034
  CI (99.9%): [9.774, 11.027] (assumes normal distribution)


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
# Warmup Iteration   1: 7.090 ops/ms
# Warmup Iteration   2: 10.466 ops/ms
# Warmup Iteration   3: 11.035 ops/ms
Iteration   1: 11.053 ops/ms
Iteration   2: 11.142 ops/ms
Iteration   3: 11.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.074 ±(99.9%) 1.110 ops/ms [Average]
  (min, avg, max) = (11.026, 11.074, 11.142), stdev = 0.061
  CI (99.9%): [9.963, 12.184] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.354 ops/ms
# Warmup Iteration   2: 10.090 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.508 ops/ms
Iteration   2: 10.306 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.414 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (10.306, 10.414, 10.508), stdev = 0.102
  CI (99.9%): [8.554, 12.275] (assumes normal distribution)


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
# Warmup Iteration   1: 6.047 ops/ms
# Warmup Iteration   2: 7.514 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 7.828 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.955 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (7.828, 7.955, 8.131), stdev = 0.157
  CI (99.9%): [5.083, 10.828] (assumes normal distribution)


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.010, 3.038, 3.085), stdev = 0.041
  CI (99.9%): [2.290, 3.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.924 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.820 ±(99.9%) 0.002 ms/op
Iteration   1: 2.879 ±(99.9%) 0.002 ms/op
Iteration   2: 2.890 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.879, 2.887, 2.894), stdev = 0.008
  CI (99.9%): [2.747, 3.028] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.012 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.050, 3.071, 3.084), stdev = 0.018
  CI (99.9%): [2.736, 3.406] (assumes normal distribution)


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
# Warmup Iteration   1: 6.052 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.030 ms/op
Iteration   1: 3.981 ±(99.9%) 0.015 ms/op
Iteration   2: 4.032 ±(99.9%) 0.015 ms/op
Iteration   3: 3.945 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.945, 3.986, 4.032), stdev = 0.044
  CI (99.9%): [3.186, 4.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.308 ms/op
                 createUser·p0.9999: 13.083 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.352 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.924 ms/op
                 createUser·p0.9999: 14.656 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.660 ms/op
                 createUser·p0.9999: 17.256 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311418
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 524 
    [ 1.250,  2.500) = 17457 
    [ 2.500,  3.750) = 273941 
    [ 3.750,  5.000) = 17994 
    [ 5.000,  6.250) = 815 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     16.096 ms/op
     p(99.9990) =     17.589 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  6.799 ms/op
                 existUser·p0.9999: 12.749 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.074 ms/op
                 existUser·p0.9999: 15.007 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 16.756 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328295
  mean =      2.924 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 981 
    [ 1.250,  2.500) = 35691 
    [ 2.500,  3.750) = 281881 
    [ 3.750,  5.000) = 8710 
    [ 5.000,  6.250) = 465 
    [ 6.250,  7.500) = 309 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     16.095 ms/op
     p(99.9990) =     16.997 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  7.945 ms/op
                 getUser·p0.9999: 19.892 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  9.995 ms/op
                 getUser·p0.9999: 14.159 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 31.470 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314902
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23753 
    [ 2.500,  5.000) = 288989 
    [ 5.000,  7.500) = 1809 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      7.974 ms/op
     p(99.9900) =     30.262 ms/op
     p(99.9990) =     31.682 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.548 ms/op
                 listUser·p0.9999: 15.768 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.955 ms/op
                 listUser·p0.9999: 18.187 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237911
  mean =      4.032 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1717 
    [ 2.500,  3.750) = 83555 
    [ 3.750,  5.000) = 132316 
    [ 5.000,  6.250) = 13816 
    [ 6.250,  7.500) = 5108 
    [ 7.500,  8.750) = 674 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 75 
    [16.250, 17.500) = 82 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.157 ms/op
     p(99.9900) =     18.043 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.401 ± 0.626  ops/ms
ClientGrpc.existUser                       thrpt       3  11.074 ± 1.110  ops/ms
ClientGrpc.getUser                         thrpt       3  10.414 ± 1.860  ops/ms
ClientGrpc.listUser                        thrpt       3   7.955 ± 2.873  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.748   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.140   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.335   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 0.801   ms/op
ClientGrpc.createUser                     sample  311418   3.083 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.352           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.096           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.727           ms/op
ClientGrpc.existUser                      sample  328295   2.924 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.095           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  314902   3.050 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.707           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.974           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.752           ms/op
ClientGrpc.listUser                       sample  237911   4.032 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.069           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.157           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.043           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.678           ms/op
