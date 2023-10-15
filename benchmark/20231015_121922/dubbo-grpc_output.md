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
# Warmup Iteration   1: 3.716 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 9.439 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.089 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (10.038, 10.089, 10.164), stdev = 0.066
  CI (99.9%): [8.877, 11.301] (assumes normal distribution)


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
# Warmup Iteration   1: 6.899 ops/ms
# Warmup Iteration   2: 9.836 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.526 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.571 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (10.496, 10.571, 10.690), stdev = 0.104
  CI (99.9%): [8.670, 12.472] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.521 ops/ms
# Warmup Iteration   2: 9.713 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 10.032 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.013 ±(99.9%) 0.313 ops/ms [Average]
  (min, avg, max) = (10.000, 10.013, 10.032), stdev = 0.017
  CI (99.9%): [9.700, 10.326] (assumes normal distribution)


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
# Warmup Iteration   1: 5.817 ops/ms
# Warmup Iteration   2: 7.543 ops/ms
# Warmup Iteration   3: 7.942 ops/ms
Iteration   1: 8.043 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.045 ±(99.9%) 1.201 ops/ms [Average]
  (min, avg, max) = (7.981, 8.045, 8.112), stdev = 0.066
  CI (99.9%): [6.845, 9.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
Iteration   2: 3.179 ±(99.9%) 0.003 ms/op
Iteration   3: 3.236 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.190 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.154, 3.190, 3.236), stdev = 0.042
  CI (99.9%): [2.421, 3.958] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.009, 3.026, 3.042), stdev = 0.017
  CI (99.9%): [2.723, 3.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.003 ms/op
Iteration   1: 3.258 ±(99.9%) 0.002 ms/op
Iteration   2: 3.183 ±(99.9%) 0.006 ms/op
Iteration   3: 3.168 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.203 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.168, 3.203, 3.258), stdev = 0.048
  CI (99.9%): [2.327, 4.079] (assumes normal distribution)


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.035 ms/op
Iteration   1: 3.977 ±(99.9%) 0.029 ms/op
Iteration   2: 3.871 ±(99.9%) 0.011 ms/op
Iteration   3: 3.939 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.929 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.871, 3.929, 3.977), stdev = 0.054
  CI (99.9%): [2.945, 4.913] (assumes normal distribution)


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.468 ms/op
                 createUser·p0.9999: 17.335 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  9.281 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 20.837 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301578
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8950 
    [ 2.500,  5.000) = 290173 
    [ 5.000,  7.500) = 1834 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     10.689 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     23.525 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.775 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  10.527 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.741 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311786
  mean =      3.076 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13851 
    [ 2.500,  5.000) = 296299 
    [ 5.000,  7.500) = 1250 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     17.650 ms/op
     p(99.9990) =     28.537 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 23.002 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  9.952 ms/op
                 getUser·p0.9999: 23.558 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.224 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  10.637 ms/op
                 getUser·p0.9999: 41.692 ms/op
                 getUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300041
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 297633 
    [ 5.000, 10.000) = 2131 
    [10.000, 15.000) = 113 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 118 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     40.632 ms/op
     p(99.9990) =     42.009 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


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
# Warmup Iteration   1: 6.153 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.498 ms/op
                 listUser·p0.9999: 24.151 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   2: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.796 ms/op
                 listUser·p0.9999: 18.445 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  18.115 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240685
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2527 
    [ 2.500,  5.000) = 221279 
    [ 5.000,  7.500) = 15496 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.178 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.089 ± 1.212  ops/ms
ClientGrpc.existUser                       thrpt       3  10.571 ± 1.901  ops/ms
ClientGrpc.getUser                         thrpt       3  10.013 ± 0.313  ops/ms
ClientGrpc.listUser                        thrpt       3   8.045 ± 1.201  ops/ms
ClientGrpc.createUser                       avgt       3   3.190 ± 0.768   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 0.303   ms/op
ClientGrpc.getUser                          avgt       3   3.203 ± 0.876   ms/op
ClientGrpc.listUser                         avgt       3   3.929 ± 0.984   ms/op
ClientGrpc.createUser                     sample  301578   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.540           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.689           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.497           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.691           ms/op
ClientGrpc.existUser                      sample  311786   3.076 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.650           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.672           ms/op
ClientGrpc.getUser                        sample  300041   3.198 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.782           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          40.632           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          42.402           ms/op
ClientGrpc.listUser                       sample  240685   3.986 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.970           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
