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
# Warmup Iteration   1: 3.915 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 9.842 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.622 ±(99.9%) 4.273 ops/ms [Average]
  (min, avg, max) = (10.469, 10.622, 10.892), stdev = 0.234
  CI (99.9%): [6.349, 14.896] (assumes normal distribution)


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
# Warmup Iteration   1: 7.234 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 11.237 ops/ms
Iteration   1: 10.881 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.896 ±(99.9%) 0.487 ops/ms [Average]
  (min, avg, max) = (10.879, 10.896, 10.926), stdev = 0.027
  CI (99.9%): [10.409, 11.382] (assumes normal distribution)


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
# Warmup Iteration   1: 6.932 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.334 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 1.702 ops/ms [Average]
  (min, avg, max) = (10.449, 10.535, 10.634), stdev = 0.093
  CI (99.9%): [8.832, 12.237] (assumes normal distribution)


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
# Warmup Iteration   1: 5.695 ops/ms
# Warmup Iteration   2: 7.499 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 7.924 ops/ms
Iteration   2: 7.816 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (7.816, 7.927, 8.040), stdev = 0.112
  CI (99.9%): [5.886, 9.967] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (2.981, 3.012, 3.064), stdev = 0.045
  CI (99.9%): [2.191, 3.833] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.002 ms/op
Iteration   1: 2.833 ±(99.9%) 0.005 ms/op
Iteration   2: 2.865 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (2.833, 2.869, 2.907), stdev = 0.037
  CI (99.9%): [2.192, 3.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
Iteration   3: 3.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (3.020, 3.036, 3.056), stdev = 0.018
  CI (99.9%): [2.707, 3.365] (assumes normal distribution)


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.024 ms/op
Iteration   1: 4.051 ±(99.9%) 0.040 ms/op
Iteration   2: 4.013 ±(99.9%) 0.015 ms/op
Iteration   3: 4.019 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.028 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (4.013, 4.028, 4.051), stdev = 0.021
  CI (99.9%): [3.649, 4.407] (assumes normal distribution)


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  7.957 ms/op
                 createUser·p0.9999: 13.023 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.523 ms/op
                 createUser·p0.9999: 14.015 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.434 ms/op
                 createUser·p0.9999: 16.460 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315766
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 18059 
    [ 2.500,  3.750) = 281401 
    [ 3.750,  5.000) = 14466 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 372 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.114 ms/op
     p(99.9900) =     15.867 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  5.685 ms/op
                 existUser·p0.9999: 13.048 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   2: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.449 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  7.772 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  9.891 ms/op
                 existUser·p0.9999: 24.788 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324187
  mean =      2.959 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33005 
    [ 2.500,  5.000) = 290235 
    [ 5.000,  7.500) = 627 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      7.461 ms/op
     p(99.9900) =     21.796 ms/op
     p(99.9990) =     25.125 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 12.930 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.520 ms/op
                 getUser·p0.9999: 15.109 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.202 ms/op
                 getUser·p0.9999: 32.369 ms/op
                 getUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313946
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17854 
    [ 2.500,  5.000) = 294631 
    [ 5.000,  7.500) = 1076 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     31.903 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.011 ms/op
Iteration   1: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.039 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.346 ms/op
                 listUser·p0.9999: 24.611 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.534 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.825 ms/op
                 listUser·p0.9999: 20.365 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241159
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2372 
    [ 2.500,  5.000) = 212018 
    [ 5.000,  7.500) = 25156 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.481 ms/op
     p(99.9900) =     23.975 ms/op
     p(99.9990) =     24.830 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.622 ± 4.273  ops/ms
ClientGrpc.existUser                       thrpt       3  10.896 ± 0.487  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 1.702  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 2.040  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.676   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.329   ms/op
ClientGrpc.listUser                         avgt       3   4.028 ± 0.379   ms/op
ClientGrpc.createUser                     sample  315766   3.042 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.780           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.114           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.867           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.596           ms/op
ClientGrpc.existUser                      sample  324187   2.959 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.449           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.461           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.796           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.264           ms/op
ClientGrpc.getUser                        sample  313946   3.057 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.903           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.604           ms/op
ClientGrpc.listUser                       sample  241159   3.983 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.534           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.975           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
