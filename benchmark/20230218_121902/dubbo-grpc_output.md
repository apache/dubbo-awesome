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
# Warmup Iteration   1: 4.339 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 10.103 ops/ms
Iteration   1: 10.728 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.646 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (10.557, 10.646, 10.728), stdev = 0.086
  CI (99.9%): [9.079, 12.213] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.817 ops/ms
# Warmup Iteration   2: 10.323 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.738 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (10.638, 10.738, 10.792), stdev = 0.086
  CI (99.9%): [9.160, 12.316] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.590 ops/ms
# Warmup Iteration   2: 10.015 ops/ms
# Warmup Iteration   3: 10.445 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 10.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.420 ±(99.9%) 4.698 ops/ms [Average]
  (min, avg, max) = (10.231, 10.420, 10.713), stdev = 0.258
  CI (99.9%): [5.722, 15.118] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.337 ops/ms
# Warmup Iteration   2: 7.873 ops/ms
# Warmup Iteration   3: 7.763 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.960 ±(99.9%) 0.645 ops/ms [Average]
  (min, avg, max) = (7.919, 7.960, 7.985), stdev = 0.035
  CI (99.9%): [7.315, 8.605] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.001 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 1.547 ms/op [Average]
  (min, avg, max) = (2.961, 3.046, 3.130), stdev = 0.085
  CI (99.9%): [1.499, 4.593] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.003 ms/op
Iteration   1: 2.900 ±(99.9%) 0.003 ms/op
Iteration   2: 2.890 ±(99.9%) 0.002 ms/op
Iteration   3: 2.940 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (2.890, 2.910, 2.940), stdev = 0.027
  CI (99.9%): [2.424, 3.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.029, 3.050, 3.077), stdev = 0.025
  CI (99.9%): [2.597, 3.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.581 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.007 ms/op
Iteration   1: 4.090 ±(99.9%) 0.051 ms/op
Iteration   2: 3.985 ±(99.9%) 0.027 ms/op
Iteration   3: 3.928 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.001 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (3.928, 4.001, 4.090), stdev = 0.082
  CI (99.9%): [2.507, 5.494] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  5.831 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.037 ms/op
                 createUser·p0.9999: 32.039 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.860 ms/op
                 createUser·p0.9999: 20.344 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304874
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21321 
    [ 2.500,  5.000) = 282692 
    [ 5.000,  7.500) = 498 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.340 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.404 ms/op
                 existUser·p0.9999: 12.922 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.593 ms/op
                 existUser·p0.99:   4.140 ms/op
                 existUser·p0.999:  6.766 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 2.963 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.737 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324549
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46705 
    [ 2.500,  5.000) = 276982 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     23.209 ms/op
     p(99.9990) =     26.796 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.038 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.392 ms/op
                 getUser·p0.9999: 13.042 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 3.027 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  6.521 ms/op
                 getUser·p0.9999: 15.324 ms/op
                 getUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315572
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1592 
    [ 1.250,  2.500) = 21804 
    [ 2.500,  3.750) = 274989 
    [ 3.750,  5.000) = 16345 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.303 ms/op
     p(99.9900) =     13.941 ms/op
     p(99.9990) =     15.697 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.013 ms/op
Iteration   1: 4.018 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 15.680 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 21.891 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239046
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2649 
    [ 2.500,  5.000) = 211303 
    [ 5.000,  7.500) = 23999 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     20.784 ms/op
     p(99.9990) =     22.158 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.646 ± 1.567  ops/ms
ClientGrpc.existUser                       thrpt       3  10.738 ± 1.578  ops/ms
ClientGrpc.getUser                         thrpt       3  10.420 ± 4.698  ops/ms
ClientGrpc.listUser                        thrpt       3   7.960 ± 0.645  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 1.547   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 0.486   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.452   ms/op
ClientGrpc.listUser                         avgt       3   4.001 ± 1.493   ms/op
ClientGrpc.createUser                     sample  304874   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.472           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.308           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.392           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.440           ms/op
ClientGrpc.existUser                      sample  324549   2.956 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.456           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.709           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.209           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  315572   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.303           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.876           ms/op
ClientGrpc.listUser                       sample  239046   4.017 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.784           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
