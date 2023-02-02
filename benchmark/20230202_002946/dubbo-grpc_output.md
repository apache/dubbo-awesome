# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.440 ops/ms
# Warmup Iteration   2: 9.735 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 9.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.102 ±(99.9%) 3.488 ops/ms [Average]
  (min, avg, max) = (9.978, 10.102, 10.323), stdev = 0.191
  CI (99.9%): [6.614, 13.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ops/ms
# Warmup Iteration   2: 10.297 ops/ms
# Warmup Iteration   3: 10.950 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.584 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (10.472, 10.584, 10.712), stdev = 0.120
  CI (99.9%): [8.386, 12.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.963 ops/ms
# Warmup Iteration   2: 9.765 ops/ms
# Warmup Iteration   3: 10.146 ops/ms
Iteration   1: 10.029 ops/ms
Iteration   2: 9.929 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.014 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (9.929, 10.014, 10.083), stdev = 0.078
  CI (99.9%): [8.592, 11.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 7.613 ops/ms
# Warmup Iteration   3: 7.746 ops/ms
Iteration   1: 7.681 ops/ms
Iteration   2: 7.792 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.811 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (7.681, 7.811, 7.959), stdev = 0.140
  CI (99.9%): [5.257, 10.364] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.004 ms/op
Iteration   2: 3.227 ±(99.9%) 0.002 ms/op
Iteration   3: 3.106 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.144 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.098, 3.144, 3.227), stdev = 0.072
  CI (99.9%): [1.823, 4.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.001 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 3.089 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.053 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (2.974, 3.053, 3.096), stdev = 0.069
  CI (99.9%): [1.802, 4.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.002 ms/op
Iteration   2: 3.253 ±(99.9%) 0.002 ms/op
Iteration   3: 3.149 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.204 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.149, 3.204, 3.253), stdev = 0.052
  CI (99.9%): [2.254, 4.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.040 ms/op
Iteration   1: 4.075 ±(99.9%) 0.012 ms/op
Iteration   2: 4.028 ±(99.9%) 0.023 ms/op
Iteration   3: 4.069 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.057 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (4.028, 4.057, 4.075), stdev = 0.026
  CI (99.9%): [3.589, 4.526] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.006 ms/op
Iteration   1: 3.160 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.049 ms/op
                 createUser·p0.9999: 12.843 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 3.169 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.111 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.085 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 23.360 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303575
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22395 
    [ 2.500,  5.000) = 280134 
    [ 5.000,  7.500) = 643 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.559 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     23.787 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.176 ms/op
                 existUser·p0.9999: 16.791 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  9.915 ms/op
                 existUser·p0.9999: 15.411 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314244
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1484 
    [ 1.250,  2.500) = 41097 
    [ 2.500,  3.750) = 239862 
    [ 3.750,  5.000) = 30598 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 88 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.921 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.225 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.216 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.696 ms/op
                 getUser·p0.9999: 13.028 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.776 ms/op
                 getUser·p0.9999: 18.549 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.204 ms/op
                 getUser·p0.9999: 18.967 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300887
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18610 
    [ 2.500,  5.000) = 281205 
    [ 5.000,  7.500) = 837 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.160 ms/op
     p(99.9900) =     18.740 ms/op
     p(99.9990) =     20.080 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.745 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 15.583 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 4.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 18.198 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 4.090 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.194 ms/op
                 listUser·p0.9999: 28.901 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236733
  mean =      4.056 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1574 
    [ 2.500,  5.000) = 208710 
    [ 5.000,  7.500) = 25101 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.914 ms/op
     p(99.9900) =     25.449 ms/op
     p(99.9990) =     29.160 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.102 ± 3.488  ops/ms
ClientGrpc.existUser                       thrpt       3  10.584 ± 2.198  ops/ms
ClientGrpc.getUser                         thrpt       3  10.014 ± 1.422  ops/ms
ClientGrpc.listUser                        thrpt       3   7.811 ± 2.554  ops/ms
ClientGrpc.createUser                       avgt       3   3.144 ± 1.321   ms/op
ClientGrpc.existUser                        avgt       3   3.053 ± 1.251   ms/op
ClientGrpc.getUser                          avgt       3   3.204 ± 0.950   ms/op
ClientGrpc.listUser                         avgt       3   4.057 ± 0.468   ms/op
ClientGrpc.createUser                     sample  303575   3.163 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.559           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  314244   3.052 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.921           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.974           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  300887   3.192 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.845           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.160           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  236733   4.056 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.722           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.914           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.449           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
