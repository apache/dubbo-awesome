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
# Warmup Iteration   1: 3.453 ops/ms
# Warmup Iteration   2: 6.774 ops/ms
# Warmup Iteration   3: 8.026 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.261 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.353 ±(99.9%) 2.174 ops/ms [Average]
  (min, avg, max) = (8.261, 8.353, 8.487), stdev = 0.119
  CI (99.9%): [6.179, 10.527] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.154 ops/ms
# Warmup Iteration   2: 8.426 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 8.719 ops/ms
Iteration   2: 8.753 ops/ms
Iteration   3: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.803 ±(99.9%) 2.139 ops/ms [Average]
  (min, avg, max) = (8.719, 8.803, 8.937), stdev = 0.117
  CI (99.9%): [6.663, 10.942] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.178 ops/ms
Iteration   1: 8.376 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.436 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (8.376, 8.436, 8.544), stdev = 0.094
  CI (99.9%): [6.719, 10.152] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.449 ops/ms
# Warmup Iteration   2: 6.212 ops/ms
# Warmup Iteration   3: 6.534 ops/ms
Iteration   1: 6.545 ops/ms
Iteration   2: 6.873 ops/ms
Iteration   3: 6.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.706 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (6.545, 6.706, 6.873), stdev = 0.164
  CI (99.9%): [3.716, 9.696] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.008 ms/op
Iteration   1: 3.819 ±(99.9%) 0.003 ms/op
Iteration   2: 3.931 ±(99.9%) 0.003 ms/op
Iteration   3: 3.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.872 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.819, 3.872, 3.931), stdev = 0.056
  CI (99.9%): [2.842, 4.902] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.099 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.002 ms/op
Iteration   1: 3.702 ±(99.9%) 0.003 ms/op
Iteration   2: 3.752 ±(99.9%) 0.003 ms/op
Iteration   3: 3.673 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.709 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.673, 3.709, 3.752), stdev = 0.040
  CI (99.9%): [2.979, 4.439] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.052 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.004 ms/op
Iteration   1: 3.929 ±(99.9%) 0.002 ms/op
Iteration   2: 3.835 ±(99.9%) 0.004 ms/op
Iteration   3: 3.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.879 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.835, 3.879, 3.929), stdev = 0.047
  CI (99.9%): [3.021, 4.736] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.812 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.077 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.947 ±(99.9%) 0.014 ms/op
Iteration   1: 4.804 ±(99.9%) 0.018 ms/op
Iteration   2: 4.857 ±(99.9%) 0.010 ms/op
Iteration   3: 4.899 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.854 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (4.804, 4.854, 4.899), stdev = 0.048
  CI (99.9%): [3.985, 5.722] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.999 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  14.216 ms/op
                 createUser·p0.9999: 16.584 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.743 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 30.147 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256870
  mean =      3.739 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8924 
    [ 2.500,  5.000) = 239450 
    [ 5.000,  7.500) = 7350 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     14.684 ms/op
     p(99.9900) =     28.518 ms/op
     p(99.9990) =     31.668 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.010 ms/op
Iteration   1: 3.677 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 17.452 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 3.566 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 26.510 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.596 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  12.863 ms/op
                 existUser·p0.9999: 22.387 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265660
  mean =      3.612 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13268 
    [ 2.500,  5.000) = 244947 
    [ 5.000,  7.500) = 6182 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     13.359 ms/op
     p(99.9900) =     25.341 ms/op
     p(99.9990) =     26.904 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
Iteration   1: 3.790 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 17.811 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.846 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.453 ms/op
                 getUser·p0.999:  15.149 ms/op
                 getUser·p0.9999: 20.875 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 3.815 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  13.590 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251514
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9439 
    [ 2.500,  5.000) = 230862 
    [ 5.000,  7.500) = 9493 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     20.180 ms/op
     p(99.9990) =     21.216 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 7.266 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.224 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.015 ms/op
Iteration   1: 4.866 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  16.067 ms/op
                 listUser·p0.9999: 17.741 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 4.690 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.315 ms/op
                 listUser·p0.9999: 18.183 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 4.826 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 35.240 ms/op
                 listUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200405
  mean =      4.793 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 148319 
    [ 5.000, 10.000) = 51320 
    [10.000, 15.000) = 427 
    [15.000, 20.000) = 257 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     16.508 ms/op
     p(99.9900) =     33.683 ms/op
     p(99.9990) =     39.976 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.353 ± 2.174  ops/ms
ClientGrpc.existUser                       thrpt       3   8.803 ± 2.139  ops/ms
ClientGrpc.getUser                         thrpt       3   8.436 ± 1.716  ops/ms
ClientGrpc.listUser                        thrpt       3   6.706 ± 2.990  ops/ms
ClientGrpc.createUser                       avgt       3   3.872 ± 1.030   ms/op
ClientGrpc.existUser                        avgt       3   3.709 ± 0.730   ms/op
ClientGrpc.getUser                          avgt       3   3.879 ± 0.857   ms/op
ClientGrpc.listUser                         avgt       3   4.854 ± 0.868   ms/op
ClientGrpc.createUser                     sample  256870   3.739 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.733           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.046           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.518           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.982           ms/op
ClientGrpc.existUser                      sample  265660   3.612 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.013           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.359           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.341           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  251514   3.817 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.800           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.480           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.451           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.180           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  200405   4.793 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.937           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.508           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.683           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.436           ms/op
