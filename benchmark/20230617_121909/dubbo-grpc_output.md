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
# Warmup Iteration   1: 4.139 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.411 ±(99.9%) 2.625 ops/ms [Average]
  (min, avg, max) = (10.246, 10.411, 10.511), stdev = 0.144
  CI (99.9%): [7.786, 13.037] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.634 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.806 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 11.009 ops/ms
Iteration   3: 10.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.926 ±(99.9%) 2.002 ops/ms [Average]
  (min, avg, max) = (10.802, 10.926, 11.009), stdev = 0.110
  CI (99.9%): [8.924, 12.929] (assumes normal distribution)


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
# Warmup Iteration   1: 7.388 ops/ms
# Warmup Iteration   2: 9.904 ops/ms
# Warmup Iteration   3: 10.267 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.455 ops/ms
Iteration   3: 10.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.326 ±(99.9%) 2.188 ops/ms [Average]
  (min, avg, max) = (10.218, 10.326, 10.455), stdev = 0.120
  CI (99.9%): [8.138, 12.514] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.752 ops/ms
# Warmup Iteration   2: 7.549 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 7.979 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.999 ±(99.9%) 1.098 ops/ms [Average]
  (min, avg, max) = (7.952, 7.999, 8.067), stdev = 0.060
  CI (99.9%): [6.902, 9.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.004 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.992, 3.030, 3.054), stdev = 0.033
  CI (99.9%): [2.425, 3.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.022 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.004, 3.022, 3.038), stdev = 0.017
  CI (99.9%): [2.717, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.072 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.016, 3.036, 3.072), stdev = 0.031
  CI (99.9%): [2.478, 3.595] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.019 ms/op
Iteration   1: 3.871 ±(99.9%) 0.032 ms/op
Iteration   2: 3.856 ±(99.9%) 0.022 ms/op
Iteration   3: 3.869 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.865 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.856, 3.865, 3.871), stdev = 0.008
  CI (99.9%): [3.721, 4.009] (assumes normal distribution)


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 12.172 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.373 ms/op
                 createUser·p0.9999: 12.636 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.898 ms/op
                 createUser·p0.9999: 17.282 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318865
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1185 
    [ 1.250,  2.500) = 19219 
    [ 2.500,  3.750) = 283220 
    [ 3.750,  5.000) = 13807 
    [ 5.000,  6.250) = 838 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.874 ms/op
     p(99.9900) =     16.390 ms/op
     p(99.9990) =     17.617 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.300 ms/op
                 existUser·p0.9999: 10.978 ms/op
                 existUser·p1.00:   11.403 ms/op

Iteration   2: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.601 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  11.052 ms/op
                 existUser·p0.9999: 25.930 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328634
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38559 
    [ 2.500,  5.000) = 288883 
    [ 5.000,  7.500) = 783 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.209 ms/op
     p(99.9900) =     18.661 ms/op
     p(99.9990) =     26.111 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.567 ms/op
                 getUser·p0.9999: 11.637 ms/op
                 getUser·p1.00:   11.796 ms/op

Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.265 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.486 ms/op
                 getUser·p0.9999: 12.913 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.102 ms/op
                 getUser·p0.9999: 15.737 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322733
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1535 
    [ 1.250,  2.500) = 23861 
    [ 2.500,  3.750) = 284501 
    [ 3.750,  5.000) = 11720 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.265 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.228 ms/op
     p(99.9900) =     14.664 ms/op
     p(99.9990) =     16.266 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.338 ms/op
                 listUser·p0.9999: 18.203 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 3.937 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.688 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.045 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 3.864 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.666 ms/op
                 listUser·p0.9999: 22.395 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246597
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5501 
    [ 2.500,  5.000) = 218019 
    [ 5.000,  7.500) = 21643 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.333 ms/op
     p(99.9900) =     23.430 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.411 ± 2.625  ops/ms
ClientGrpc.existUser                       thrpt       3  10.926 ± 2.002  ops/ms
ClientGrpc.getUser                         thrpt       3  10.326 ± 2.188  ops/ms
ClientGrpc.listUser                        thrpt       3   7.999 ± 1.098  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.606   ms/op
ClientGrpc.existUser                        avgt       3   3.022 ± 0.304   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.559   ms/op
ClientGrpc.listUser                         avgt       3   3.865 ± 0.144   ms/op
ClientGrpc.createUser                     sample  318865   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.623           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.874           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.390           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  328634   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.209           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.149           ms/op
ClientGrpc.getUser                        sample  322733   2.976 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.265           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.228           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.664           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.810           ms/op
ClientGrpc.listUser                       sample  246597   3.894 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.688           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.430           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
