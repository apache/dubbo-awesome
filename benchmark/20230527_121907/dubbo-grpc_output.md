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
# Warmup Iteration   1: 4.197 ops/ms
# Warmup Iteration   2: 8.910 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.570 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (10.524, 10.570, 10.643), stdev = 0.064
  CI (99.9%): [9.405, 11.736] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.423 ops/ms
# Warmup Iteration   2: 10.816 ops/ms
# Warmup Iteration   3: 11.264 ops/ms
Iteration   1: 11.567 ops/ms
Iteration   2: 11.082 ops/ms
Iteration   3: 11.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.268 ±(99.9%) 4.781 ops/ms [Average]
  (min, avg, max) = (11.082, 11.268, 11.567), stdev = 0.262
  CI (99.9%): [6.487, 16.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.010 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.757 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (10.682, 10.757, 10.798), stdev = 0.065
  CI (99.9%): [9.578, 11.936] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.186 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.128 ±(99.9%) 0.350 ops/ms [Average]
  (min, avg, max) = (8.117, 8.128, 8.151), stdev = 0.019
  CI (99.9%): [7.779, 8.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.293 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
Iteration   2: 2.989 ±(99.9%) 0.001 ms/op
Iteration   3: 2.903 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (2.903, 2.961, 2.991), stdev = 0.050
  CI (99.9%): [2.041, 3.881] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.002 ms/op
Iteration   1: 2.904 ±(99.9%) 0.003 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.879 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.879, 2.906, 2.935), stdev = 0.028
  CI (99.9%): [2.396, 3.416] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.018 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.013, 3.018, 3.024), stdev = 0.006
  CI (99.9%): [2.912, 3.123] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.021 ms/op
Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
Iteration   2: 3.939 ±(99.9%) 0.021 ms/op
Iteration   3: 3.916 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.916, 3.932, 3.940), stdev = 0.013
  CI (99.9%): [3.687, 4.176] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.586 ms/op
                 createUser·p0.9999: 13.424 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  7.242 ms/op
                 createUser·p0.9999: 14.762 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  8.241 ms/op
                 createUser·p0.9999: 28.338 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316511
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24039 
    [ 2.500,  5.000) = 291315 
    [ 5.000,  7.500) = 829 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     30.665 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.005 ms/op
Iteration   1: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  8.332 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.574 ms/op
                 existUser·p0.9999: 16.212 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  6.857 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328240
  mean =      2.925 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 843 
    [ 1.250,  2.500) = 37743 
    [ 2.500,  3.750) = 282256 
    [ 3.750,  5.000) = 6653 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     18.356 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.232 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 23.986 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.596 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.442 ms/op
                 getUser·p0.9999: 23.775 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317267
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18558 
    [ 2.500,  5.000) = 297345 
    [ 5.000,  7.500) = 892 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.646 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     24.079 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.638 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.772 ms/op
                 listUser·p0.9999: 20.508 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.787 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.367 ms/op
                 listUser·p0.9999: 22.818 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.680 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 30.435 ms/op
                 listUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247823
  mean =      3.870 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2945 
    [ 2.500,  5.000) = 225304 
    [ 5.000,  7.500) = 18281 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     29.145 ms/op
     p(99.9990) =     30.721 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.570 ± 1.165  ops/ms
ClientGrpc.existUser                       thrpt       3  11.268 ± 4.781  ops/ms
ClientGrpc.getUser                         thrpt       3  10.757 ± 1.179  ops/ms
ClientGrpc.listUser                        thrpt       3   8.128 ± 0.350  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.920   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   3.018 ± 0.105   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 0.245   ms/op
ClientGrpc.createUser                     sample  316511   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.473           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.545           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.903           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.704           ms/op
ClientGrpc.existUser                      sample  328240   2.925 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.356           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  317267   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.646           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.133           ms/op
ClientGrpc.listUser                       sample  247823   3.870 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.972           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.145           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
