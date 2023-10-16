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
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.146 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 10.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.169 ±(99.9%) 0.369 ops/ms [Average]
  (min, avg, max) = (10.146, 10.169, 10.181), stdev = 0.020
  CI (99.9%): [9.800, 10.538] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.430 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 11.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.796 ±(99.9%) 7.863 ops/ms [Average]
  (min, avg, max) = (10.518, 10.796, 11.293), stdev = 0.431
  CI (99.9%): [2.933, 18.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.487 ops/ms
# Warmup Iteration   2: 9.753 ops/ms
# Warmup Iteration   3: 10.133 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.275 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.275 ±(99.9%) 0.288 ops/ms [Average]
  (min, avg, max) = (10.259, 10.275, 10.290), stdev = 0.016
  CI (99.9%): [9.986, 10.563] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.451 ops/ms
# Warmup Iteration   2: 7.884 ops/ms
# Warmup Iteration   3: 8.298 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.166 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.227 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (8.166, 8.227, 8.259), stdev = 0.053
  CI (99.9%): [7.262, 9.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.005 ms/op
Iteration   3: 3.160 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.085, 3.123, 3.160), stdev = 0.038
  CI (99.9%): [2.434, 3.812] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.003 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.990, 3.003, 3.021), stdev = 0.016
  CI (99.9%): [2.718, 3.289] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.004 ms/op
Iteration   1: 3.138 ±(99.9%) 0.006 ms/op
Iteration   2: 3.132 ±(99.9%) 0.004 ms/op
Iteration   3: 3.092 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.092, 3.121, 3.138), stdev = 0.025
  CI (99.9%): [2.660, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 5.643 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.024 ms/op
Iteration   1: 3.906 ±(99.9%) 0.030 ms/op
Iteration   2: 3.863 ±(99.9%) 0.016 ms/op
Iteration   3: 3.869 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.879 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.863, 3.879, 3.906), stdev = 0.023
  CI (99.9%): [3.452, 4.307] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.452 ms/op
                 createUser·p0.9999: 19.912 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 13.703 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 17.345 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309722
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13419 
    [ 2.500,  5.000) = 294148 
    [ 5.000,  7.500) = 1622 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     10.368 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     20.375 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.615 ms/op
                 existUser·p0.9999: 17.297 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.857 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.667 ms/op
                 existUser·p0.999:  11.142 ms/op
                 existUser·p0.9999: 15.868 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317746
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2180 
    [ 1.250,  2.500) = 27443 
    [ 2.500,  3.750) = 270878 
    [ 3.750,  5.000) = 15205 
    [ 5.000,  6.250) = 1066 
    [ 6.250,  7.500) = 414 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =     10.818 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     17.847 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.006 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.771 ms/op
                 getUser·p0.9999: 18.672 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.149 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.926 ms/op
                 getUser·p0.9999: 18.771 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.163 ms/op
                 getUser·p0.9999: 21.680 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307088
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10951 
    [ 2.500,  5.000) = 294356 
    [ 5.000,  7.500) = 1366 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     21.342 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 5.634 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  16.264 ms/op
                 listUser·p0.9999: 27.591 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.967 ms/op
                 listUser·p0.9999: 17.394 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 18.020 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245581
  mean =      3.910 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2631 
    [ 2.500,  5.000) = 228340 
    [ 5.000,  7.500) = 13397 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     33.266 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.169 ± 0.369  ops/ms
ClientGrpc.existUser                       thrpt       3  10.796 ± 7.863  ops/ms
ClientGrpc.getUser                         thrpt       3  10.275 ± 0.288  ops/ms
ClientGrpc.listUser                        thrpt       3   8.227 ± 0.965  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.689   ms/op
ClientGrpc.existUser                        avgt       3   3.003 ± 0.286   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 0.461   ms/op
ClientGrpc.listUser                         avgt       3   3.879 ± 0.428   ms/op
ClientGrpc.createUser                     sample  309722   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.368           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.203           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.840           ms/op
ClientGrpc.existUser                      sample  317746   3.020 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.626           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.818           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.368           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  307088   3.125 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.566           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.342           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  245581   3.910 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.994           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
