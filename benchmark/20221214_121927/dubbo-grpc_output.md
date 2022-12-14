# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ops/ms
# Warmup Iteration   2: 9.416 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.315 ±(99.9%) 3.412 ops/ms [Average]
  (min, avg, max) = (10.133, 10.315, 10.506), stdev = 0.187
  CI (99.9%): [6.903, 13.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.653 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 11.265 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.927 ±(99.9%) 5.333 ops/ms [Average]
  (min, avg, max) = (10.748, 10.927, 11.265), stdev = 0.292
  CI (99.9%): [5.594, 16.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ops/ms
# Warmup Iteration   2: 10.326 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.607 ±(99.9%) 3.770 ops/ms [Average]
  (min, avg, max) = (10.397, 10.607, 10.810), stdev = 0.207
  CI (99.9%): [6.837, 14.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.295 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.057 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (7.967, 8.057, 8.199), stdev = 0.124
  CI (99.9%): [5.789, 10.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.100, 3.113, 3.141), stdev = 0.024
  CI (99.9%): [2.679, 3.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.003 ms/op
Iteration   1: 2.836 ±(99.9%) 0.003 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.916 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (2.836, 2.886, 2.916), stdev = 0.043
  CI (99.9%): [2.101, 3.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.711 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (2.979, 3.033, 3.078), stdev = 0.050
  CI (99.9%): [2.114, 3.952] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.363 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.034 ms/op
Iteration   1: 3.902 ±(99.9%) 0.018 ms/op
Iteration   2: 3.858 ±(99.9%) 0.066 ms/op
Iteration   3: 3.921 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.858, 3.893, 3.921), stdev = 0.032
  CI (99.9%): [3.305, 4.481] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.714 ms/op
                 createUser·p0.9999: 16.924 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.768 ms/op
                 createUser·p0.9999: 12.673 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.609 ms/op
                 createUser·p0.9999: 14.787 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312471
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 828 
    [ 1.250,  2.500) = 27487 
    [ 2.500,  3.750) = 255628 
    [ 3.750,  5.000) = 27608 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.856 ms/op
     p(99.9900) =     16.380 ms/op
     p(99.9990) =     17.228 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.966 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.268 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 15.357 ms/op
                 existUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326056
  mean =      2.944 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53894 
    [ 2.500,  5.000) = 271366 
    [ 5.000,  7.500) = 468 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.268 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.699 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.299 ms/op
                 getUser·p0.9999: 12.753 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.806 ms/op
                 getUser·p0.9999: 15.059 ms/op
                 getUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313307
  mean =      3.062 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1139 
    [ 1.250,  2.500) = 28045 
    [ 2.500,  3.750) = 258221 
    [ 3.750,  5.000) = 25110 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.857 ms/op
     p(99.9900) =     14.549 ms/op
     p(99.9990) =     15.427 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.686 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.038 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.410 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 22.220 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  16.503 ms/op
                 listUser·p0.9999: 20.261 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242386
  mean =      3.960 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5527 
    [ 2.500,  5.000) = 208376 
    [ 5.000,  7.500) = 27352 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     16.525 ms/op
     p(99.9900) =     21.112 ms/op
     p(99.9990) =     22.727 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.315 ± 3.412  ops/ms
ClientGrpc.existUser                       thrpt       3  10.927 ± 5.333  ops/ms
ClientGrpc.getUser                         thrpt       3  10.607 ± 3.770  ops/ms
ClientGrpc.listUser                        thrpt       3   8.057 ± 2.268  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.434   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.784   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.919   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 0.588   ms/op
ClientGrpc.createUser                     sample  312471   3.070 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.754           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.856           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.380           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.334           ms/op
ClientGrpc.existUser                      sample  326056   2.944 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.268           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.699           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.120           ms/op
ClientGrpc.getUser                        sample  313307   3.062 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.549           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.532           ms/op
ClientGrpc.listUser                       sample  242386   3.960 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.410           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.525           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.112           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
