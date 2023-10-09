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
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 9.463 ops/ms
Iteration   1: 9.679 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.912 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (9.679, 9.912, 10.043), stdev = 0.203
  CI (99.9%): [6.214, 13.610] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.857 ops/ms
# Warmup Iteration   2: 9.955 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.587 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.627 ±(99.9%) 0.900 ops/ms [Average]
  (min, avg, max) = (10.587, 10.627, 10.682), stdev = 0.049
  CI (99.9%): [9.727, 11.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 9.993 ops/ms
Iteration   1: 9.959 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.962 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (9.898, 9.962, 10.029), stdev = 0.065
  CI (99.9%): [8.767, 11.156] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ops/ms
# Warmup Iteration   2: 7.654 ops/ms
# Warmup Iteration   3: 7.661 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.987 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.958 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (7.899, 7.958, 7.987), stdev = 0.051
  CI (99.9%): [7.027, 8.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
Iteration   3: 3.159 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.158, 3.163, 3.173), stdev = 0.009
  CI (99.9%): [3.005, 3.321] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.095 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
Iteration   3: 3.140 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.090 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.036, 3.090, 3.140), stdev = 0.052
  CI (99.9%): [2.141, 4.039] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.582 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.004 ms/op
Iteration   3: 3.182 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.163 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.123, 3.163, 3.184), stdev = 0.035
  CI (99.9%): [2.530, 3.796] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.578 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.026 ms/op
Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
Iteration   2: 4.011 ±(99.9%) 0.026 ms/op
Iteration   3: 3.997 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.017 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.997, 4.017, 4.045), stdev = 0.025
  CI (99.9%): [3.567, 4.468] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 14.778 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.797 ms/op
                 createUser·p0.999:  11.592 ms/op
                 createUser·p0.9999: 16.447 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  12.490 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301640
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10190 
    [ 2.500,  5.000) = 289203 
    [ 5.000,  7.500) = 1637 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     11.387 ms/op
     p(99.9900) =     18.601 ms/op
     p(99.9990) =     25.158 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 17.014 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 18.083 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  14.102 ms/op
                 existUser·p0.9999: 20.923 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309868
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19537 
    [ 2.500,  5.000) = 287668 
    [ 5.000,  7.500) = 1988 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     22.505 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.011 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  11.721 ms/op
                 getUser·p0.9999: 19.560 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.090 ms/op
                 getUser·p0.9999: 20.936 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  9.332 ms/op
                 getUser·p0.9999: 24.302 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301821
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11785 
    [ 2.500,  5.000) = 287513 
    [ 5.000,  7.500) = 1894 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.807 ms/op
     p(99.9000) =      9.593 ms/op
     p(99.9900) =     21.910 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.720 ms/op
                 listUser·p0.999:  14.581 ms/op
                 listUser·p0.9999: 16.315 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  16.184 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.987 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  19.417 ms/op
                 listUser·p0.9999: 34.734 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238298
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1700 
    [ 2.500,  5.000) = 218610 
    [ 5.000,  7.500) = 15696 
    [ 7.500, 10.000) = 1524 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     32.282 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.912 ± 3.698  ops/ms
ClientGrpc.existUser                       thrpt       3  10.627 ± 0.900  ops/ms
ClientGrpc.getUser                         thrpt       3   9.962 ± 1.194  ops/ms
ClientGrpc.listUser                        thrpt       3   7.958 ± 0.930  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.158   ms/op
ClientGrpc.existUser                        avgt       3   3.090 ± 0.949   ms/op
ClientGrpc.getUser                          avgt       3   3.163 ± 0.633   ms/op
ClientGrpc.listUser                         avgt       3   4.017 ± 0.451   ms/op
ClientGrpc.createUser                     sample  301640   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.601           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  309868   3.096 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.370           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.101           ms/op
ClientGrpc.getUser                        sample  301821   3.182 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.540           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.807           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.593           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.910           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.609           ms/op
ClientGrpc.listUser                       sample  238298   4.026 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.758           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.282           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
