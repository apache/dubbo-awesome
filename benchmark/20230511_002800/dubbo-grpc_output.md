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
# Warmup Iteration   1: 3.610 ops/ms
# Warmup Iteration   2: 8.735 ops/ms
# Warmup Iteration   3: 10.198 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.521 ±(99.9%) 1.338 ops/ms [Average]
  (min, avg, max) = (10.464, 10.521, 10.604), stdev = 0.073
  CI (99.9%): [9.183, 11.859] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ops/ms
# Warmup Iteration   2: 10.518 ops/ms
# Warmup Iteration   3: 11.148 ops/ms
Iteration   1: 11.077 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.980 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (10.790, 10.980, 11.077), stdev = 0.165
  CI (99.9%): [7.975, 13.985] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.634 ops/ms
# Warmup Iteration   2: 10.058 ops/ms
# Warmup Iteration   3: 10.278 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 0.249 ops/ms [Average]
  (min, avg, max) = (10.563, 10.577, 10.590), stdev = 0.014
  CI (99.9%): [10.328, 10.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.639 ops/ms
# Warmup Iteration   2: 7.716 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 8.053 ops/ms
Iteration   2: 7.964 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.998 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (7.964, 7.998, 8.053), stdev = 0.048
  CI (99.9%): [7.121, 8.874] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.051 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.038, 3.051, 3.063), stdev = 0.012
  CI (99.9%): [2.826, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.004 ms/op
Iteration   1: 2.903 ±(99.9%) 0.005 ms/op
Iteration   2: 2.903 ±(99.9%) 0.004 ms/op
Iteration   3: 2.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.884, 2.897, 2.903), stdev = 0.011
  CI (99.9%): [2.698, 3.096] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.055 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (3.050, 3.055, 3.060), stdev = 0.005
  CI (99.9%): [2.969, 3.140] (assumes normal distribution)


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.019 ms/op
Iteration   1: 3.889 ±(99.9%) 0.008 ms/op
Iteration   2: 3.965 ±(99.9%) 0.017 ms/op
Iteration   3: 3.913 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.889, 3.922, 3.965), stdev = 0.038
  CI (99.9%): [3.222, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 17.418 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.331 ms/op
                 createUser·p0.999:  7.504 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.708 ms/op
                 createUser·p0.9999: 22.923 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314015
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26993 
    [ 2.500,  5.000) = 285230 
    [ 5.000,  7.500) = 1342 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     21.869 ms/op
     p(99.9990) =     23.256 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.449 ms/op
                 existUser·p0.9999: 15.892 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   2: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.753 ms/op
                 existUser·p0.9999: 23.755 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 2.912 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328078
  mean =      2.925 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40885 
    [ 2.500,  5.000) = 285517 
    [ 5.000,  7.500) = 1368 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     24.666 ms/op
     p(99.9990) =     29.005 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.752 ms/op
                 getUser·p0.9999: 23.678 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.071 ms/op
                 getUser·p0.9999: 14.771 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.559 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.470 ms/op
                 getUser·p0.9999: 17.627 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312268
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21852 
    [ 2.500,  5.000) = 288465 
    [ 5.000,  7.500) = 1586 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     22.955 ms/op
     p(99.9990) =     23.884 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 5.146 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.479 ms/op
                 listUser·p0.9999: 17.107 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239729
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3064 
    [ 2.500,  5.000) = 211885 
    [ 5.000,  7.500) = 23181 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     24.681 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.521 ± 1.338  ops/ms
ClientGrpc.existUser                       thrpt       3  10.980 ± 3.005  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 0.249  ops/ms
ClientGrpc.listUser                        thrpt       3   7.998 ± 0.876  ops/ms
ClientGrpc.createUser                       avgt       3   3.051 ± 0.225   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.199   ms/op
ClientGrpc.getUser                          avgt       3   3.055 ± 0.085   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.700   ms/op
ClientGrpc.createUser                     sample  314015   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.869           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  328078   2.925 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.677           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.666           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.164           ms/op
ClientGrpc.getUser                        sample  312268   3.072 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.559           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.955           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  239729   4.009 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.401           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
