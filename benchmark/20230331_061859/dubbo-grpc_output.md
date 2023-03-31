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
# Warmup Iteration   1: 4.770 ops/ms
# Warmup Iteration   2: 9.574 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.881 ops/ms
Iteration   3: 10.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.827 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (10.665, 10.827, 10.935), stdev = 0.143
  CI (99.9%): [8.221, 13.434] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ops/ms
# Warmup Iteration   2: 10.701 ops/ms
# Warmup Iteration   3: 11.249 ops/ms
Iteration   1: 11.533 ops/ms
Iteration   2: 11.275 ops/ms
Iteration   3: 11.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.340 ±(99.9%) 3.100 ops/ms [Average]
  (min, avg, max) = (11.212, 11.340, 11.533), stdev = 0.170
  CI (99.9%): [8.240, 14.440] (assumes normal distribution)


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
# Warmup Iteration   1: 7.536 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.715 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.901 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (10.849, 10.901, 10.951), stdev = 0.051
  CI (99.9%): [9.976, 11.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ops/ms
# Warmup Iteration   2: 8.119 ops/ms
# Warmup Iteration   3: 8.163 ops/ms
Iteration   1: 8.306 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.307 ±(99.9%) 0.145 ops/ms [Average]
  (min, avg, max) = (8.299, 8.307, 8.315), stdev = 0.008
  CI (99.9%): [8.162, 8.452] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.939 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.929, 2.939, 2.945), stdev = 0.009
  CI (99.9%): [2.773, 3.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.002 ms/op
Iteration   1: 2.889 ±(99.9%) 0.003 ms/op
Iteration   2: 2.827 ±(99.9%) 0.003 ms/op
Iteration   3: 2.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.827, 2.864, 2.889), stdev = 0.033
  CI (99.9%): [2.270, 3.458] (assumes normal distribution)


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.004 ms/op
Iteration   1: 2.995 ±(99.9%) 0.004 ms/op
Iteration   2: 2.987 ±(99.9%) 0.004 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.975, 2.986, 2.995), stdev = 0.010
  CI (99.9%): [2.803, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.041 ms/op
Iteration   1: 3.771 ±(99.9%) 0.012 ms/op
Iteration   2: 3.864 ±(99.9%) 0.015 ms/op
Iteration   3: 3.854 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.830 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.771, 3.830, 3.864), stdev = 0.051
  CI (99.9%): [2.903, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.888 ms/op
                 createUser·p0.9999: 15.438 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.051 ms/op
                 createUser·p0.9999: 15.717 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  13.004 ms/op
                 createUser·p0.9999: 28.232 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325381
  mean =      2.950 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35972 
    [ 2.500,  5.000) = 288213 
    [ 5.000,  7.500) = 791 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.702 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     21.626 ms/op
     p(99.9990) =     28.762 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.838 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 18.017 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.096 ms/op
                 existUser·p0.9999: 13.036 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.477 ms/op
                 existUser·p0.999:  8.384 ms/op
                 existUser·p0.9999: 14.104 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333954
  mean =      2.873 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2580 
    [ 1.250,  2.500) = 40560 
    [ 2.500,  3.750) = 282764 
    [ 3.750,  5.000) = 7076 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.571 ms/op
     p(99.9900) =     14.513 ms/op
     p(99.9990) =     18.110 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 18.549 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 2.933 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.507 ms/op
                 getUser·p0.999:  10.941 ms/op
                 getUser·p0.9999: 22.541 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 2.906 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  5.964 ms/op
                 getUser·p0.9999: 15.040 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328545
  mean =      2.921 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40521 
    [ 2.500,  5.000) = 286614 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.199 ms/op
     p(99.9900) =     19.312 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.010 ms/op
Iteration   1: 3.724 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  12.912 ms/op
                 listUser·p0.9999: 14.687 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 3.832 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.365 ms/op
                 listUser·p0.999:  13.427 ms/op
                 listUser·p0.9999: 15.428 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 20.306 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252447
  mean =      3.801 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3682 
    [ 2.500,  5.000) = 234574 
    [ 5.000,  7.500) = 13229 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     20.782 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.827 ± 2.607  ops/ms
ClientGrpc.existUser                       thrpt       3  11.340 ± 3.100  ops/ms
ClientGrpc.getUser                         thrpt       3  10.901 ± 0.925  ops/ms
ClientGrpc.listUser                        thrpt       3   8.307 ± 0.145  ops/ms
ClientGrpc.createUser                       avgt       3   2.939 ± 0.167   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.594   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.182   ms/op
ClientGrpc.listUser                         avgt       3   3.830 ± 0.927   ms/op
ClientGrpc.createUser                     sample  325381   2.950 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.545           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.184           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.770           ms/op
ClientGrpc.existUser                      sample  333954   2.873 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.587           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.571           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  328545   2.921 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.531           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.925           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.199           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.312           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  252447   3.801 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.112           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.488           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.562           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.037           ms/op
