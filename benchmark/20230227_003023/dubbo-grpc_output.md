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
# Warmup Iteration   1: 3.417 ops/ms
# Warmup Iteration   2: 6.946 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.875 ops/ms
Iteration   2: 7.810 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.913 ±(99.9%) 2.307 ops/ms [Average]
  (min, avg, max) = (7.810, 7.913, 8.055), stdev = 0.126
  CI (99.9%): [5.606, 10.221] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.939 ops/ms
# Warmup Iteration   2: 8.213 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 8.486 ops/ms
Iteration   2: 8.659 ops/ms
Iteration   3: 8.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.537 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (8.465, 8.537, 8.659), stdev = 0.106
  CI (99.9%): [6.597, 10.477] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.104 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.919 ops/ms
Iteration   1: 7.975 ops/ms
Iteration   2: 8.051 ops/ms
Iteration   3: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.980 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (7.915, 7.980, 8.051), stdev = 0.069
  CI (99.9%): [6.728, 9.233] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ops/ms
# Warmup Iteration   2: 6.258 ops/ms
# Warmup Iteration   3: 6.827 ops/ms
Iteration   1: 6.563 ops/ms
Iteration   2: 6.908 ops/ms
Iteration   3: 6.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.767 ±(99.9%) 3.299 ops/ms [Average]
  (min, avg, max) = (6.563, 6.767, 6.908), stdev = 0.181
  CI (99.9%): [3.468, 10.066] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.428 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 3.995 ±(99.9%) 0.003 ms/op
Iteration   2: 4.007 ±(99.9%) 0.002 ms/op
Iteration   3: 3.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.955 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.865, 3.955, 4.007), stdev = 0.079
  CI (99.9%): [2.514, 5.397] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.997 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.003 ms/op
Iteration   1: 3.777 ±(99.9%) 0.003 ms/op
Iteration   2: 3.806 ±(99.9%) 0.002 ms/op
Iteration   3: 3.847 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.810 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.777, 3.810, 3.847), stdev = 0.035
  CI (99.9%): [3.169, 4.451] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.460 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.006 ms/op
Iteration   1: 4.120 ±(99.9%) 0.008 ms/op
Iteration   2: 3.877 ±(99.9%) 0.005 ms/op
Iteration   3: 3.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.957 ±(99.9%) 2.574 ms/op [Average]
  (min, avg, max) = (3.874, 3.957, 4.120), stdev = 0.141
  CI (99.9%): [1.383, 6.531] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.012 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.278 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.802 ±(99.9%) 0.009 ms/op
Iteration   1: 4.835 ±(99.9%) 0.013 ms/op
Iteration   2: 4.932 ±(99.9%) 0.006 ms/op
Iteration   3: 4.847 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.871 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (4.835, 4.871, 4.932), stdev = 0.053
  CI (99.9%): [3.911, 5.832] (assumes normal distribution)


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.014 ms/op
Iteration   1: 3.901 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.058 ms/op
                 createUser·p0.99:   6.294 ms/op
                 createUser·p0.999:  9.832 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  12.037 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 4.014 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  11.925 ms/op
                 createUser·p0.9999: 36.899 ms/op
                 createUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242997
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7880 
    [ 2.500,  5.000) = 217147 
    [ 5.000,  7.500) = 16924 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     36.025 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.010 ms/op
Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.489 ms/op
                 existUser·p0.999:  9.308 ms/op
                 existUser·p0.9999: 15.442 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 3.708 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  8.769 ms/op
                 existUser·p0.9999: 28.246 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.783 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 20.352 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255825
  mean =      3.754 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10990 
    [ 2.500,  5.000) = 234035 
    [ 5.000,  7.500) = 9840 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =      9.787 ms/op
     p(99.9900) =     27.547 ms/op
     p(99.9990) =     28.392 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 5.377 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  14.211 ms/op
                 getUser·p0.9999: 18.973 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.881 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  9.431 ms/op
                 getUser·p0.9999: 21.345 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.333 ms/op
                 getUser·p0.999:  11.808 ms/op
                 getUser·p0.9999: 24.009 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247229
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5333 
    [ 2.500,  5.000) = 226007 
    [ 5.000,  7.500) = 14797 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     10.655 ms/op
     p(99.9900) =     23.733 ms/op
     p(99.9990) =     24.316 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 6.649 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.222 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.015 ms/op
Iteration   1: 4.760 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   7.086 ms/op
                 listUser·p0.99:   8.679 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 22.047 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.759 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  17.227 ms/op
                 listUser·p0.9999: 20.891 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.579 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  18.716 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204319
  mean =      4.698 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 532 
    [ 2.500,  5.000) = 154546 
    [ 5.000,  7.500) = 43306 
    [ 7.500, 10.000) = 5058 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.574 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.913 ± 2.307  ops/ms
ClientGrpc.existUser                       thrpt       3   8.537 ± 1.940  ops/ms
ClientGrpc.getUser                         thrpt       3   7.980 ± 1.252  ops/ms
ClientGrpc.listUser                        thrpt       3   6.767 ± 3.299  ops/ms
ClientGrpc.createUser                       avgt       3   3.955 ± 1.442   ms/op
ClientGrpc.existUser                        avgt       3   3.810 ± 0.641   ms/op
ClientGrpc.getUser                          avgt       3   3.957 ± 2.574   ms/op
ClientGrpc.listUser                         avgt       3   4.871 ± 0.961   ms/op
ClientGrpc.createUser                     sample  242997   3.949 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.025           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.880           ms/op
ClientGrpc.existUser                      sample  255825   3.754 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.013           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.787           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.410           ms/op
ClientGrpc.getUser                        sample  247229   3.882 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.484           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.655           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.733           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.543           ms/op
ClientGrpc.listUser                       sample  204319   4.698 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.826           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.675           ms/op
