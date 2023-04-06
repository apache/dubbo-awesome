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
# Warmup Iteration   1: 4.779 ops/ms
# Warmup Iteration   2: 9.638 ops/ms
# Warmup Iteration   3: 10.337 ops/ms
Iteration   1: 10.883 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.876 ±(99.9%) 0.269 ops/ms [Average]
  (min, avg, max) = (10.859, 10.876, 10.885), stdev = 0.015
  CI (99.9%): [10.607, 11.145] (assumes normal distribution)


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
# Warmup Iteration   1: 8.244 ops/ms
# Warmup Iteration   2: 11.135 ops/ms
# Warmup Iteration   3: 11.272 ops/ms
Iteration   1: 11.498 ops/ms
Iteration   2: 11.456 ops/ms
Iteration   3: 11.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.488 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (11.456, 11.488, 11.510), stdev = 0.028
  CI (99.9%): [10.977, 11.999] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ops/ms
# Warmup Iteration   2: 10.536 ops/ms
# Warmup Iteration   3: 10.837 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.024 ops/ms
Iteration   3: 11.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  11.039 ±(99.9%) 0.432 ops/ms [Average]
  (min, avg, max) = (11.024, 11.039, 11.066), stdev = 0.024
  CI (99.9%): [10.607, 11.471] (assumes normal distribution)


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
# Warmup Iteration   1: 6.183 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.456 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.391 ±(99.9%) 1.485 ops/ms [Average]
  (min, avg, max) = (8.300, 8.391, 8.456), stdev = 0.081
  CI (99.9%): [6.905, 9.876] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.005 ms/op
Iteration   1: 2.926 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.926, 2.961, 2.979), stdev = 0.030
  CI (99.9%): [2.412, 3.509] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.803 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.807 ±(99.9%) 0.004 ms/op
Iteration   1: 2.822 ±(99.9%) 0.005 ms/op
Iteration   2: 2.806 ±(99.9%) 0.003 ms/op
Iteration   3: 2.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.820 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.806, 2.820, 2.832), stdev = 0.013
  CI (99.9%): [2.586, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.002 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.951 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (2.922, 2.951, 2.987), stdev = 0.033
  CI (99.9%): [2.353, 3.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.007 ms/op
Iteration   1: 3.752 ±(99.9%) 0.007 ms/op
Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
Iteration   3: 3.803 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.786 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.752, 3.786, 3.803), stdev = 0.030
  CI (99.9%): [3.242, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.481 ms/op
                 createUser·p0.9999: 12.301 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.228 ms/op
                 createUser·p0.9999: 13.452 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  8.046 ms/op
                 createUser·p0.9999: 16.646 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326525
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2423 
    [ 1.250,  2.500) = 35968 
    [ 2.500,  3.750) = 272482 
    [ 3.750,  5.000) = 14408 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 144 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.929 ms/op
     p(99.9900) =     15.931 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.006 ms/op
Iteration   1: 2.789 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  7.919 ms/op
                 existUser·p0.9999: 10.962 ms/op
                 existUser·p1.00:   11.174 ms/op

Iteration   2: 2.818 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.944 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.793 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.785 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 15.091 ms/op
                 existUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342595
  mean =      2.800 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3884 
    [ 1.250,  2.500) = 58014 
    [ 2.500,  3.750) = 271807 
    [ 3.750,  5.000) = 8123 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     14.180 ms/op
     p(99.9990) =     15.724 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.856 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.293 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.209 ms/op
                 getUser·p0.9999: 14.084 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.926 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  5.923 ms/op
                 getUser·p0.9999: 13.206 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.782 ms/op
                 getUser·p0.9999: 16.550 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 330770
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3171 
    [ 1.250,  2.500) = 36728 
    [ 2.500,  3.750) = 278966 
    [ 3.750,  5.000) = 10937 
    [ 5.000,  6.250) = 648 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.182 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     16.868 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.009 ms/op
Iteration   1: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.799 ms/op
                 listUser·p0.9999: 16.297 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   2: 3.810 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.526 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  18.744 ms/op
                 listUser·p0.9999: 21.345 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  13.587 ms/op
                 listUser·p0.9999: 19.781 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251144
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5565 
    [ 2.500,  5.000) = 226637 
    [ 5.000,  7.500) = 18000 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     13.594 ms/op
     p(99.9900) =     20.378 ms/op
     p(99.9990) =     21.839 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.876 ± 0.269  ops/ms
ClientGrpc.existUser                       thrpt       3  11.488 ± 0.511  ops/ms
ClientGrpc.getUser                         thrpt       3  11.039 ± 0.432  ops/ms
ClientGrpc.listUser                        thrpt       3   8.391 ± 1.485  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.549   ms/op
ClientGrpc.existUser                        avgt       3   2.820 ± 0.234   ms/op
ClientGrpc.getUser                          avgt       3   2.951 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   3.786 ± 0.544   ms/op
ClientGrpc.createUser                     sample  326525   2.940 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.931           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.170           ms/op
ClientGrpc.existUser                      sample  342595   2.800 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.810           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.709           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.180           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.958           ms/op
ClientGrpc.getUser                        sample  330770   2.903 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.182           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.336           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.022           ms/op
ClientGrpc.listUser                       sample  251144   3.820 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.594           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.378           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.889           ms/op
