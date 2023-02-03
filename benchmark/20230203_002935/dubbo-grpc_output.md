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
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 6.566 ops/ms
# Warmup Iteration   3: 7.794 ops/ms
Iteration   1: 8.111 ops/ms
Iteration   2: 8.232 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.124 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (8.029, 8.124, 8.232), stdev = 0.102
  CI (99.9%): [6.257, 9.991] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ops/ms
# Warmup Iteration   2: 7.898 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.808 ops/ms
Iteration   3: 8.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.665 ±(99.9%) 4.278 ops/ms [Average]
  (min, avg, max) = (8.394, 8.665, 8.808), stdev = 0.234
  CI (99.9%): [4.387, 12.942] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.512 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.351 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (8.246, 8.351, 8.512), stdev = 0.141
  CI (99.9%): [5.771, 10.930] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ops/ms
# Warmup Iteration   2: 6.181 ops/ms
# Warmup Iteration   3: 6.401 ops/ms
Iteration   1: 6.436 ops/ms
Iteration   2: 6.853 ops/ms
Iteration   3: 6.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.641 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (6.436, 6.641, 6.853), stdev = 0.209
  CI (99.9%): [2.831, 10.451] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.008 ms/op
Iteration   1: 3.752 ±(99.9%) 0.004 ms/op
Iteration   2: 3.831 ±(99.9%) 0.003 ms/op
Iteration   3: 3.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.822 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.752, 3.822, 3.882), stdev = 0.066
  CI (99.9%): [2.625, 5.018] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.960 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.003 ms/op
Iteration   1: 3.738 ±(99.9%) 0.002 ms/op
Iteration   2: 3.796 ±(99.9%) 0.004 ms/op
Iteration   3: 3.903 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.813 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (3.738, 3.813, 3.903), stdev = 0.084
  CI (99.9%): [2.288, 5.337] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.235 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.003 ms/op
Iteration   1: 3.931 ±(99.9%) 0.003 ms/op
Iteration   2: 3.949 ±(99.9%) 0.003 ms/op
Iteration   3: 3.902 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.928 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.902, 3.928, 3.949), stdev = 0.024
  CI (99.9%): [3.492, 4.363] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.269 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.176 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.023 ms/op
Iteration   1: 4.772 ±(99.9%) 0.011 ms/op
Iteration   2: 4.753 ±(99.9%) 0.011 ms/op
Iteration   3: 4.660 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.728 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (4.660, 4.728, 4.772), stdev = 0.060
  CI (99.9%): [3.630, 5.827] (assumes normal distribution)


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.010 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  12.665 ms/op
                 createUser·p0.9999: 23.567 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  12.665 ms/op
                 createUser·p0.9999: 19.455 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 19.125 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250909
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6022 
    [ 2.500,  5.000) = 233175 
    [ 5.000,  7.500) = 10421 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     13.734 ms/op
     p(99.9900) =     22.804 ms/op
     p(99.9990) =     24.101 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.009 ms/op
Iteration   1: 3.639 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  8.669 ms/op
                 existUser·p0.9999: 16.497 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  9.813 ms/op
                 existUser·p0.9999: 33.171 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.654 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  11.115 ms/op
                 existUser·p0.9999: 27.500 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259026
  mean =      3.707 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11277 
    [ 2.500,  5.000) = 238002 
    [ 5.000,  7.500) = 8793 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.970 ms/op
     p(99.9000) =      9.911 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     33.470 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 5.671 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.009 ms/op
Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  11.033 ms/op
                 getUser·p0.9999: 14.776 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.842 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  10.891 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.830 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  8.914 ms/op
                 getUser·p0.9999: 32.699 ms/op
                 getUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248477
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5463 
    [ 2.500,  5.000) = 230353 
    [ 5.000,  7.500) = 11734 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     10.134 ms/op
     p(99.9900) =     31.104 ms/op
     p(99.9990) =     33.097 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 6.405 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.016 ms/op
Iteration   1: 4.845 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 20.801 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 4.765 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.154 ms/op
                 listUser·p0.9999: 23.350 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 4.807 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  18.494 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199781
  mean =      4.806 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 143442 
    [ 5.000,  7.500) = 50117 
    [ 7.500, 10.000) = 4889 
    [10.000, 12.500) = 474 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     16.883 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.124 ± 1.867  ops/ms
ClientGrpc.existUser                       thrpt       3   8.665 ± 4.278  ops/ms
ClientGrpc.getUser                         thrpt       3   8.351 ± 2.580  ops/ms
ClientGrpc.listUser                        thrpt       3   6.641 ± 3.810  ops/ms
ClientGrpc.createUser                       avgt       3   3.822 ± 1.196   ms/op
ClientGrpc.existUser                        avgt       3   3.813 ± 1.524   ms/op
ClientGrpc.getUser                          avgt       3   3.928 ± 0.435   ms/op
ClientGrpc.listUser                         avgt       3   4.728 ± 1.098   ms/op
ClientGrpc.createUser                     sample  250909   3.825 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.778           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.734           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.804           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.183           ms/op
ClientGrpc.existUser                      sample  259026   3.707 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.859           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.970           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.911           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.654           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.554           ms/op
ClientGrpc.getUser                        sample  248477   3.865 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.134           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.104           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.227           ms/op
ClientGrpc.listUser                       sample  199781   4.806 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.255           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.733           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.883           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
