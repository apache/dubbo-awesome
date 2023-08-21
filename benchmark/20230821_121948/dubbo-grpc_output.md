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
# Warmup Iteration   1: 3.038 ops/ms
# Warmup Iteration   2: 6.907 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.339 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (8.119, 8.339, 8.546), stdev = 0.214
  CI (99.9%): [4.437, 12.242] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ops/ms
# Warmup Iteration   2: 8.461 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 8.712 ops/ms
Iteration   2: 8.944 ops/ms
Iteration   3: 8.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.837 ±(99.9%) 2.133 ops/ms [Average]
  (min, avg, max) = (8.712, 8.837, 8.944), stdev = 0.117
  CI (99.9%): [6.704, 10.971] (assumes normal distribution)


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
# Warmup Iteration   1: 5.207 ops/ms
# Warmup Iteration   2: 7.762 ops/ms
# Warmup Iteration   3: 8.329 ops/ms
Iteration   1: 8.490 ops/ms
Iteration   2: 8.470 ops/ms
Iteration   3: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.495 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (8.470, 8.495, 8.527), stdev = 0.029
  CI (99.9%): [7.967, 9.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ops/ms
# Warmup Iteration   2: 5.995 ops/ms
# Warmup Iteration   3: 6.342 ops/ms
Iteration   1: 6.332 ops/ms
Iteration   2: 6.596 ops/ms
Iteration   3: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.503 ±(99.9%) 2.717 ops/ms [Average]
  (min, avg, max) = (6.332, 6.503, 6.596), stdev = 0.149
  CI (99.9%): [3.787, 9.220] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.536 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
Iteration   1: 3.773 ±(99.9%) 0.004 ms/op
Iteration   2: 3.838 ±(99.9%) 0.003 ms/op
Iteration   3: 3.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.834 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (3.773, 3.834, 3.891), stdev = 0.059
  CI (99.9%): [2.757, 4.911] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.052 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.004 ms/op
Iteration   1: 3.620 ±(99.9%) 0.003 ms/op
Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
Iteration   3: 3.613 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.586 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.526, 3.586, 3.620), stdev = 0.052
  CI (99.9%): [2.629, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.005 ms/op
Iteration   1: 3.781 ±(99.9%) 0.004 ms/op
Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
Iteration   3: 3.776 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.763 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.733, 3.763, 3.781), stdev = 0.026
  CI (99.9%): [3.281, 4.245] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.734 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.269 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.010 ms/op
Iteration   1: 4.844 ±(99.9%) 0.014 ms/op
Iteration   2: 4.826 ±(99.9%) 0.012 ms/op
Iteration   3: 4.839 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.836 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (4.826, 4.836, 4.844), stdev = 0.010
  CI (99.9%): [4.662, 5.010] (assumes normal distribution)


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
Iteration   1: 3.803 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  13.939 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  14.859 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.733 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  11.479 ms/op
                 createUser·p0.9999: 39.781 ms/op
                 createUser·p1.00:   40.894 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255910
  mean =      3.751 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 247511 
    [ 5.000, 10.000) = 8007 
    [10.000, 15.000) = 181 
    [15.000, 20.000) = 135 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     13.669 ms/op
     p(99.9900) =     38.431 ms/op
     p(99.9990) =     40.727 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.099 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.010 ms/op
Iteration   1: 3.568 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 20.874 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.596 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  9.566 ms/op
                 existUser·p0.9999: 21.663 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.566 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.893 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 23.102 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268575
  mean =      3.577 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10392 
    [ 2.500,  5.000) = 252712 
    [ 5.000,  7.500) = 4578 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     22.877 ms/op
     p(99.9990) =     23.253 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 5.463 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.748 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   7.304 ms/op
                 getUser·p0.999:  13.379 ms/op
                 getUser·p0.9999: 17.480 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.752 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  10.793 ms/op
                 getUser·p0.9999: 18.071 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 3.752 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  10.040 ms/op
                 getUser·p0.9999: 18.101 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255906
  mean =      3.751 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7764 
    [ 2.500,  5.000) = 238924 
    [ 5.000,  7.500) = 7537 
    [ 7.500, 10.000) = 1175 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.882 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.270 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.939 ±(99.9%) 0.015 ms/op
Iteration   1: 4.913 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 4.854 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  16.386 ms/op
                 listUser·p0.9999: 19.015 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.921 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 25.444 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195923
  mean =      4.896 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 138210 
    [ 5.000,  7.500) = 50666 
    [ 7.500, 10.000) = 5835 
    [10.000, 12.500) = 583 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     17.339 ms/op
     p(99.9900) =     23.974 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.339 ± 3.903  ops/ms
ClientGrpc.existUser                       thrpt       3   8.837 ± 2.133  ops/ms
ClientGrpc.getUser                         thrpt       3   8.495 ± 0.528  ops/ms
ClientGrpc.listUser                        thrpt       3   6.503 ± 2.717  ops/ms
ClientGrpc.createUser                       avgt       3   3.834 ± 1.077   ms/op
ClientGrpc.existUser                        avgt       3   3.586 ± 0.957   ms/op
ClientGrpc.getUser                          avgt       3   3.763 ± 0.482   ms/op
ClientGrpc.listUser                         avgt       3   4.836 ± 0.174   ms/op
ClientGrpc.createUser                     sample  255910   3.751 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.865           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.669           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.431           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.894           ms/op
ClientGrpc.existUser                      sample  268575   3.577 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.700           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.306           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.877           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.298           ms/op
ClientGrpc.getUser                        sample  255906   3.751 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.496           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.289           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.957           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  195923   4.896 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.540           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.339           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
