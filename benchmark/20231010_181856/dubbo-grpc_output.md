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
# Warmup Iteration   1: 3.060 ops/ms
# Warmup Iteration   2: 6.830 ops/ms
# Warmup Iteration   3: 7.901 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.380 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (8.337, 8.380, 8.434), stdev = 0.049
  CI (99.9%): [7.478, 9.282] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ops/ms
# Warmup Iteration   2: 8.230 ops/ms
# Warmup Iteration   3: 9.061 ops/ms
Iteration   1: 9.108 ops/ms
Iteration   2: 9.304 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.214 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (9.108, 9.214, 9.304), stdev = 0.099
  CI (99.9%): [7.415, 11.013] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.086 ops/ms
# Warmup Iteration   2: 7.950 ops/ms
# Warmup Iteration   3: 8.397 ops/ms
Iteration   1: 8.378 ops/ms
Iteration   2: 8.556 ops/ms
Iteration   3: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.472 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (8.378, 8.472, 8.556), stdev = 0.090
  CI (99.9%): [6.838, 10.107] (assumes normal distribution)


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
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 6.710 ops/ms
Iteration   1: 6.633 ops/ms
Iteration   2: 6.689 ops/ms
Iteration   3: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.690 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (6.633, 6.690, 6.749), stdev = 0.058
  CI (99.9%): [5.628, 7.752] (assumes normal distribution)


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.014 ms/op
Iteration   1: 3.809 ±(99.9%) 0.003 ms/op
Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
Iteration   3: 3.845 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.786 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.703, 3.786, 3.845), stdev = 0.074
  CI (99.9%): [2.442, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 5.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.003 ms/op
Iteration   1: 3.531 ±(99.9%) 0.003 ms/op
Iteration   2: 3.479 ±(99.9%) 0.002 ms/op
Iteration   3: 3.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.493 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.467, 3.493, 3.531), stdev = 0.034
  CI (99.9%): [2.873, 4.113] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.003 ms/op
Iteration   1: 3.842 ±(99.9%) 0.003 ms/op
Iteration   2: 3.699 ±(99.9%) 0.004 ms/op
Iteration   3: 3.660 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.734 ±(99.9%) 1.743 ms/op [Average]
  (min, avg, max) = (3.660, 3.734, 3.842), stdev = 0.096
  CI (99.9%): [1.991, 5.477] (assumes normal distribution)


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
# Warmup Iteration   1: 6.611 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.092 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.814 ±(99.9%) 0.010 ms/op
Iteration   1: 4.789 ±(99.9%) 0.012 ms/op
Iteration   2: 4.772 ±(99.9%) 0.020 ms/op
Iteration   3: 4.794 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.785 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (4.772, 4.785, 4.794), stdev = 0.011
  CI (99.9%): [4.577, 4.992] (assumes normal distribution)


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.012 ms/op
Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.970 ms/op
                 createUser·p0.999:  14.921 ms/op
                 createUser·p0.9999: 18.069 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.761 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  11.041 ms/op
                 createUser·p0.9999: 17.777 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   7.728 ms/op
                 createUser·p0.999:  12.976 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255914
  mean =      3.751 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10566 
    [ 2.500,  5.000) = 232460 
    [ 5.000,  7.500) = 10857 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     20.299 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  9.967 ms/op
                 existUser·p0.9999: 16.014 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 3.545 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  10.007 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 22.749 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265559
  mean =      3.614 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13457 
    [ 2.500,  5.000) = 242134 
    [ 5.000,  7.500) = 8114 
    [ 7.500, 10.000) = 1563 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 5.445 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  13.425 ms/op
                 getUser·p0.9999: 14.762 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 3.721 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  9.925 ms/op
                 getUser·p0.9999: 16.823 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  13.237 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253463
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9176 
    [ 2.500,  5.000) = 231563 
    [ 5.000,  7.500) = 10864 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     11.464 ms/op
     p(99.9900) =     19.617 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 6.162 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.973 ±(99.9%) 0.017 ms/op
Iteration   1: 4.876 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  16.080 ms/op
                 listUser·p0.9999: 18.594 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 4.773 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 19.277 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.813 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  21.449 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199027
  mean =      4.820 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 205 
    [ 2.500,  5.000) = 146747 
    [ 5.000,  7.500) = 46079 
    [ 7.500, 10.000) = 4952 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     25.762 ms/op
     p(99.9990) =     26.641 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.380 ± 0.902  ops/ms
ClientGrpc.existUser                       thrpt       3   9.214 ± 1.799  ops/ms
ClientGrpc.getUser                         thrpt       3   8.472 ± 1.635  ops/ms
ClientGrpc.listUser                        thrpt       3   6.690 ± 1.062  ops/ms
ClientGrpc.createUser                       avgt       3   3.786 ± 1.343   ms/op
ClientGrpc.existUser                        avgt       3   3.493 ± 0.620   ms/op
ClientGrpc.getUser                          avgt       3   3.734 ± 1.743   ms/op
ClientGrpc.listUser                         avgt       3   4.785 ± 0.208   ms/op
ClientGrpc.createUser                     sample  255914   3.751 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.785           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.078           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.990           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  265559   3.614 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.859           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.873           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.125           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.002           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.246           ms/op
ClientGrpc.getUser                        sample  253463   3.789 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.897           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.464           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.617           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  199027   4.820 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.880           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.762           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
