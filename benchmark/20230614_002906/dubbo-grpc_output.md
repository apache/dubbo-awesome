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
# Warmup Iteration   1: 3.211 ops/ms
# Warmup Iteration   2: 6.684 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 8.157 ops/ms
Iteration   2: 8.265 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.187 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (8.138, 8.187, 8.265), stdev = 0.069
  CI (99.9%): [6.933, 9.441] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.096 ops/ms
# Warmup Iteration   2: 7.989 ops/ms
# Warmup Iteration   3: 8.687 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.579 ops/ms
Iteration   3: 8.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.633 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (8.579, 8.633, 8.666), stdev = 0.047
  CI (99.9%): [7.768, 9.499] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ops/ms
# Warmup Iteration   2: 7.380 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 8.051 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.115 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (8.024, 8.115, 8.270), stdev = 0.135
  CI (99.9%): [5.656, 10.574] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 6.366 ops/ms
# Warmup Iteration   3: 6.364 ops/ms
Iteration   1: 6.318 ops/ms
Iteration   2: 6.378 ops/ms
Iteration   3: 6.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.377 ±(99.9%) 1.054 ops/ms [Average]
  (min, avg, max) = (6.318, 6.377, 6.434), stdev = 0.058
  CI (99.9%): [5.323, 7.430] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.008 ms/op
Iteration   1: 3.985 ±(99.9%) 0.005 ms/op
Iteration   2: 3.951 ±(99.9%) 0.004 ms/op
Iteration   3: 3.842 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.926 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (3.842, 3.926, 3.985), stdev = 0.075
  CI (99.9%): [2.558, 5.294] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.409 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.005 ms/op
Iteration   1: 3.520 ±(99.9%) 0.003 ms/op
Iteration   2: 3.866 ±(99.9%) 0.005 ms/op
Iteration   3: 3.737 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.708 ±(99.9%) 3.189 ms/op [Average]
  (min, avg, max) = (3.520, 3.708, 3.866), stdev = 0.175
  CI (99.9%): [0.519, 6.897] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.850 ±(99.9%) 0.004 ms/op
Iteration   2: 3.976 ±(99.9%) 0.004 ms/op
Iteration   3: 4.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.985 ±(99.9%) 2.544 ms/op [Average]
  (min, avg, max) = (3.850, 3.985, 4.128), stdev = 0.139
  CI (99.9%): [1.441, 6.528] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.101 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.464 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.013 ms/op
Iteration   1: 5.213 ±(99.9%) 0.018 ms/op
Iteration   2: 5.177 ±(99.9%) 0.017 ms/op
Iteration   3: 4.991 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.127 ±(99.9%) 2.173 ms/op [Average]
  (min, avg, max) = (4.991, 5.127, 5.213), stdev = 0.119
  CI (99.9%): [2.954, 7.300] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.145 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
Iteration   1: 3.953 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  16.012 ms/op
                 createUser·p0.9999: 19.131 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 3.842 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   7.009 ms/op
                 createUser·p0.999:  10.744 ms/op
                 createUser·p0.9999: 23.364 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.812 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.126 ms/op
                 createUser·p0.999:  15.728 ms/op
                 createUser·p0.9999: 36.897 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248146
  mean =      3.868 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10842 
    [ 2.500,  5.000) = 218741 
    [ 5.000,  7.500) = 16175 
    [ 7.500, 10.000) = 1673 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.514 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     37.491 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.099 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.012 ms/op
Iteration   1: 3.684 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 16.383 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 3.725 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 19.923 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 3.566 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 20.293 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262383
  mean =      3.657 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12857 
    [ 2.500,  5.000) = 236478 
    [ 5.000,  7.500) = 11092 
    [ 7.500, 10.000) = 1444 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     11.561 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.541 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
Iteration   1: 3.948 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 16.726 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.555 ms/op
                 getUser·p0.999:  14.006 ms/op
                 getUser·p0.9999: 17.635 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.916 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  11.242 ms/op
                 getUser·p0.9999: 20.212 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241849
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9955 
    [ 2.500,  5.000) = 208428 
    [ 5.000,  7.500) = 21207 
    [ 7.500, 10.000) = 1825 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     12.658 ms/op
     p(99.9900) =     19.003 ms/op
     p(99.9990) =     20.466 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 6.702 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.019 ms/op
Iteration   1: 5.296 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   7.174 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 21.757 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.860 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  19.910 ms/op
                 listUser·p0.9999: 24.365 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 4.876 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  21.307 ms/op
                 listUser·p0.9999: 32.375 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191910
  mean =      5.003 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 616 
    [ 2.500,  5.000) = 122858 
    [ 5.000,  7.500) = 57890 
    [ 7.500, 10.000) = 8484 
    [10.000, 12.500) = 1214 
    [12.500, 15.000) = 393 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     20.450 ms/op
     p(99.9900) =     25.358 ms/op
     p(99.9990) =     33.033 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.187 ± 1.254  ops/ms
ClientGrpc.existUser                       thrpt       3   8.633 ± 0.866  ops/ms
ClientGrpc.getUser                         thrpt       3   8.115 ± 2.459  ops/ms
ClientGrpc.listUser                        thrpt       3   6.377 ± 1.054  ops/ms
ClientGrpc.createUser                       avgt       3   3.926 ± 1.368   ms/op
ClientGrpc.existUser                        avgt       3   3.708 ± 3.189   ms/op
ClientGrpc.getUser                          avgt       3   3.985 ± 2.544   ms/op
ClientGrpc.listUser                         avgt       3   5.127 ± 2.173   ms/op
ClientGrpc.createUser                     sample  248146   3.868 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.514           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.110           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.076           ms/op
ClientGrpc.existUser                      sample  262383   3.657 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.922           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.561           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  241849   3.969 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.658           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  191910   5.003 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.966           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.450           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.358           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.063           ms/op
