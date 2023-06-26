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
# Warmup Iteration   1: 4.569 ops/ms
# Warmup Iteration   2: 9.311 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 10.467 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.626 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (10.467, 10.626, 10.721), stdev = 0.139
  CI (99.9%): [8.099, 13.153] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.986 ops/ms
# Warmup Iteration   2: 10.649 ops/ms
# Warmup Iteration   3: 10.990 ops/ms
Iteration   1: 11.314 ops/ms
Iteration   2: 11.322 ops/ms
Iteration   3: 11.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.241 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (11.085, 11.241, 11.322), stdev = 0.135
  CI (99.9%): [8.783, 13.698] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.995 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.752 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.977 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.710 ±(99.9%) 4.462 ops/ms [Average]
  (min, avg, max) = (10.497, 10.710, 10.977), stdev = 0.245
  CI (99.9%): [6.247, 15.172] (assumes normal distribution)


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
# Warmup Iteration   1: 6.509 ops/ms
# Warmup Iteration   2: 7.990 ops/ms
# Warmup Iteration   3: 8.087 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.334 ops/ms
Iteration   3: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.274 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (8.196, 8.274, 8.334), stdev = 0.071
  CI (99.9%): [6.984, 9.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
Iteration   1: 2.917 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.964 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (2.917, 2.964, 2.992), stdev = 0.041
  CI (99.9%): [2.224, 3.704] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.002 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.890 ±(99.9%) 0.003 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.874, 2.886, 2.892), stdev = 0.010
  CI (99.9%): [2.710, 3.061] (assumes normal distribution)


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.036, 3.044, 3.054), stdev = 0.009
  CI (99.9%): [2.871, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.019 ms/op
Iteration   1: 3.998 ±(99.9%) 0.007 ms/op
Iteration   2: 3.942 ±(99.9%) 0.017 ms/op
Iteration   3: 3.871 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.937 ±(99.9%) 1.162 ms/op [Average]
  (min, avg, max) = (3.871, 3.937, 3.998), stdev = 0.064
  CI (99.9%): [2.775, 5.099] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.315 ms/op
                 createUser·p0.999:  8.529 ms/op
                 createUser·p0.9999: 12.295 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.831 ms/op
                 createUser·p0.9999: 13.304 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 16.656 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316404
  mean =      3.033 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1624 
    [ 1.250,  2.500) = 21496 
    [ 2.500,  3.750) = 276013 
    [ 3.750,  5.000) = 15949 
    [ 5.000,  6.250) = 596 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 146 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.571 ms/op
     p(99.9900) =     14.309 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.006 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  5.901 ms/op
                 existUser·p0.9999: 11.428 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.263 ms/op
                 existUser·p0.9999: 13.929 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 14.482 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331419
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1365 
    [ 1.250,  2.500) = 43057 
    [ 2.500,  3.750) = 277257 
    [ 3.750,  5.000) = 8731 
    [ 5.000,  6.250) = 522 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.777 ms/op
     p(99.9990) =     15.123 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.051 ms/op
                 getUser·p0.9999: 11.949 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.429 ms/op
                 getUser·p0.9999: 26.921 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319088
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25937 
    [ 2.500,  5.000) = 291900 
    [ 5.000,  7.500) = 992 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.019 ms/op
     p(99.9900) =     26.089 ms/op
     p(99.9990) =     27.218 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.010 ms/op
Iteration   1: 3.869 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  12.262 ms/op
                 listUser·p0.9999: 16.307 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.929 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.453 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 15.527 ms/op
                 listUser·p1.00:   15.794 ms/op

Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.292 ms/op
                 listUser·p0.9999: 16.606 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247978
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 4191 
    [ 2.500,  3.750) = 123534 
    [ 3.750,  5.000) = 99887 
    [ 5.000,  6.250) = 15774 
    [ 6.250,  7.500) = 3499 
    [ 7.500,  8.750) = 549 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     17.925 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.626 ± 2.527  ops/ms
ClientGrpc.existUser                       thrpt       3  11.241 ± 2.457  ops/ms
ClientGrpc.getUser                         thrpt       3  10.710 ± 4.462  ops/ms
ClientGrpc.listUser                        thrpt       3   8.274 ± 1.290  ops/ms
ClientGrpc.createUser                       avgt       3   2.964 ± 0.740   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.176   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.173   ms/op
ClientGrpc.listUser                         avgt       3   3.937 ± 1.162   ms/op
ClientGrpc.createUser                     sample  316404   3.033 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.587           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.571           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.309           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.843           ms/op
ClientGrpc.existUser                      sample  331419   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.749           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.483           ms/op
ClientGrpc.getUser                        sample  319088   3.008 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.019           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.089           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  247978   3.875 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.453           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.337           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.122           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.022           ms/op
