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
# Warmup Iteration   1: 3.191 ops/ms
# Warmup Iteration   2: 6.553 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.375 ops/ms
Iteration   3: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.285 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (8.154, 8.285, 8.375), stdev = 0.116
  CI (99.9%): [6.173, 10.397] (assumes normal distribution)


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
# Warmup Iteration   1: 5.388 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 8.849 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.063 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (8.922, 9.063, 9.140), stdev = 0.123
  CI (99.9%): [6.828, 11.298] (assumes normal distribution)


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
# Warmup Iteration   1: 5.131 ops/ms
# Warmup Iteration   2: 7.739 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 8.412 ops/ms
Iteration   3: 8.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.470 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (8.412, 8.470, 8.580), stdev = 0.095
  CI (99.9%): [6.732, 10.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 6.244 ops/ms
# Warmup Iteration   3: 6.149 ops/ms
Iteration   1: 6.264 ops/ms
Iteration   2: 6.513 ops/ms
Iteration   3: 6.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.371 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (6.264, 6.371, 6.513), stdev = 0.128
  CI (99.9%): [4.037, 8.706] (assumes normal distribution)


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
# Warmup Iteration   1: 5.639 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.008 ms/op
Iteration   1: 3.870 ±(99.9%) 0.005 ms/op
Iteration   2: 3.683 ±(99.9%) 0.004 ms/op
Iteration   3: 3.776 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.776 ±(99.9%) 1.705 ms/op [Average]
  (min, avg, max) = (3.683, 3.776, 3.870), stdev = 0.093
  CI (99.9%): [2.071, 5.481] (assumes normal distribution)


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.004 ms/op
Iteration   1: 3.558 ±(99.9%) 0.003 ms/op
Iteration   2: 3.604 ±(99.9%) 0.003 ms/op
Iteration   3: 3.619 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.594 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.558, 3.594, 3.619), stdev = 0.031
  CI (99.9%): [3.020, 4.167] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.008 ms/op
Iteration   1: 3.851 ±(99.9%) 0.005 ms/op
Iteration   2: 3.661 ±(99.9%) 0.004 ms/op
Iteration   3: 3.748 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.754 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.661, 3.754, 3.851), stdev = 0.095
  CI (99.9%): [2.019, 5.488] (assumes normal distribution)


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
# Warmup Iteration   1: 6.178 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.244 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.014 ms/op
Iteration   1: 5.012 ±(99.9%) 0.013 ms/op
Iteration   2: 5.084 ±(99.9%) 0.015 ms/op
Iteration   3: 5.195 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.097 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (5.012, 5.097, 5.195), stdev = 0.092
  CI (99.9%): [3.415, 6.779] (assumes normal distribution)


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
# Warmup Iteration   1: 5.656 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  12.510 ms/op
                 createUser·p0.9999: 14.829 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 3.772 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 19.252 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  12.349 ms/op
                 createUser·p0.9999: 27.341 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252453
  mean =      3.802 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5928 
    [ 2.500,  5.000) = 234601 
    [ 5.000,  7.500) = 10106 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     25.354 ms/op
     p(99.9990) =     27.751 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 4.977 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 14.655 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.852 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 14.937 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.123 ms/op
                 existUser·p0.9999: 18.448 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272584
  mean =      3.522 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15764 
    [ 2.500,  5.000) = 248867 
    [ 5.000,  7.500) = 6466 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     17.866 ms/op
     p(99.9990) =     20.006 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.326 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  11.734 ms/op
                 getUser·p0.9999: 15.351 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 3.858 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 15.457 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 3.838 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  11.840 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249630
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6879 
    [ 2.500,  5.000) = 230332 
    [ 5.000,  7.500) = 10768 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     17.925 ms/op
     p(99.9990) =     20.185 ms/op
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
# Warmup Iteration   1: 7.255 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.223 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.079 ±(99.9%) 0.017 ms/op
Iteration   1: 5.000 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  16.568 ms/op
                 listUser·p0.9999: 22.099 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 4.929 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 19.514 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 4.912 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  19.755 ms/op
                 listUser·p0.9999: 25.573 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194064
  mean =      4.947 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 477 
    [ 2.500,  5.000) = 131445 
    [ 5.000,  7.500) = 53403 
    [ 7.500, 10.000) = 7298 
    [10.000, 12.500) = 901 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     22.307 ms/op
     p(99.9990) =     26.024 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.285 ± 2.112  ops/ms
ClientGrpc.existUser                       thrpt       3   9.063 ± 2.235  ops/ms
ClientGrpc.getUser                         thrpt       3   8.470 ± 1.739  ops/ms
ClientGrpc.listUser                        thrpt       3   6.371 ± 2.335  ops/ms
ClientGrpc.createUser                       avgt       3   3.776 ± 1.705   ms/op
ClientGrpc.existUser                        avgt       3   3.594 ± 0.574   ms/op
ClientGrpc.getUser                          avgt       3   3.754 ± 1.735   ms/op
ClientGrpc.listUser                         avgt       3   5.097 ± 1.682   ms/op
ClientGrpc.createUser                     sample  252453   3.802 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.865           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  272584   3.522 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.174           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.866           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  249630   3.843 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.672           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.925           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  194064   4.947 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.200           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.307           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
