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
# Warmup Iteration   1: 4.297 ops/ms
# Warmup Iteration   2: 8.590 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.064 ±(99.9%) 1.408 ops/ms [Average]
  (min, avg, max) = (9.976, 10.064, 10.120), stdev = 0.077
  CI (99.9%): [8.657, 11.472] (assumes normal distribution)


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
# Warmup Iteration   1: 7.707 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.645 ±(99.9%) 2.955 ops/ms [Average]
  (min, avg, max) = (10.459, 10.645, 10.756), stdev = 0.162
  CI (99.9%): [7.690, 13.600] (assumes normal distribution)


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
# Warmup Iteration   1: 7.968 ops/ms
# Warmup Iteration   2: 9.698 ops/ms
# Warmup Iteration   3: 10.028 ops/ms
Iteration   1: 9.783 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.013 ±(99.9%) 3.806 ops/ms [Average]
  (min, avg, max) = (9.783, 10.013, 10.191), stdev = 0.209
  CI (99.9%): [6.207, 13.819] (assumes normal distribution)


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
# Warmup Iteration   1: 6.149 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 7.927 ops/ms
Iteration   2: 8.138 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.077 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (7.927, 8.077, 8.166), stdev = 0.131
  CI (99.9%): [5.694, 10.459] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.002 ms/op
Iteration   1: 3.164 ±(99.9%) 0.001 ms/op
Iteration   2: 3.100 ±(99.9%) 0.001 ms/op
Iteration   3: 3.175 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.147 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.100, 3.147, 3.175), stdev = 0.041
  CI (99.9%): [2.407, 3.886] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.070 ±(99.9%) 0.899 ms/op [Average]
  (min, avg, max) = (3.031, 3.070, 3.126), stdev = 0.049
  CI (99.9%): [2.172, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
Iteration   3: 3.145 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.107, 3.140, 3.168), stdev = 0.031
  CI (99.9%): [2.578, 3.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.007 ms/op
Iteration   1: 3.948 ±(99.9%) 0.029 ms/op
Iteration   2: 3.871 ±(99.9%) 0.008 ms/op
Iteration   3: 3.850 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.889 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.850, 3.889, 3.948), stdev = 0.052
  CI (99.9%): [2.946, 4.833] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.005 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 11.962 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   2: 3.200 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.897 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.268 ms/op
                 createUser·p0.9999: 16.537 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306421
  mean =      3.133 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 475 
    [ 1.250,  2.500) = 8879 
    [ 2.500,  3.750) = 275445 
    [ 3.750,  5.000) = 19794 
    [ 5.000,  6.250) = 838 
    [ 6.250,  7.500) = 433 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.972 ms/op
     p(99.9900) =     15.073 ms/op
     p(99.9990) =     16.937 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.562 ms/op
                 existUser·p0.9999: 17.706 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.070 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.444 ms/op
                 existUser·p0.9999: 19.923 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314938
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17589 
    [ 2.500,  5.000) = 296183 
    [ 5.000,  7.500) = 860 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.398 ms/op
     p(99.9900) =     19.350 ms/op
     p(99.9990) =     20.082 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
Iteration   1: 3.193 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.786 ms/op
                 getUser·p0.9999: 13.316 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.539 ms/op
                 getUser·p0.9999: 13.396 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.741 ms/op
                 getUser·p0.9999: 16.806 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302833
  mean =      3.171 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 563 
    [ 1.250,  2.500) = 9207 
    [ 2.500,  3.750) = 266488 
    [ 3.750,  5.000) = 24974 
    [ 5.000,  6.250) = 801 
    [ 6.250,  7.500) = 325 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.144 ms/op
     p(99.9900) =     15.947 ms/op
     p(99.9990) =     17.006 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.010 ms/op
Iteration   1: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.328 ms/op
                 listUser·p0.9999: 13.480 ms/op
                 listUser·p1.00:   14.041 ms/op

Iteration   2: 3.978 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.619 ms/op
                 listUser·p0.9999: 18.644 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.961 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 17.692 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242505
  mean =      3.958 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2623 
    [ 2.500,  3.750) = 90298 
    [ 3.750,  5.000) = 135026 
    [ 5.000,  6.250) = 9191 
    [ 6.250,  7.500) = 4271 
    [ 7.500,  8.750) = 408 
    [ 8.750, 10.000) = 157 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 162 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.987 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.064 ± 1.408  ops/ms
ClientGrpc.existUser                       thrpt       3  10.645 ± 2.955  ops/ms
ClientGrpc.getUser                         thrpt       3  10.013 ± 3.806  ops/ms
ClientGrpc.listUser                        thrpt       3   8.077 ± 2.383  ops/ms
ClientGrpc.createUser                       avgt       3   3.147 ± 0.739   ms/op
ClientGrpc.existUser                        avgt       3   3.070 ± 0.899   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.562   ms/op
ClientGrpc.listUser                         avgt       3   3.889 ± 0.943   ms/op
ClientGrpc.createUser                     sample  306421   3.133 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.781           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.972           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.073           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  314938   3.047 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.398           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  302833   3.171 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.464           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.144           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.947           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.531           ms/op
ClientGrpc.listUser                       sample  242505   3.958 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.996           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.219           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.104           ms/op
