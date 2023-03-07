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
# Warmup Iteration   1: 4.733 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.349 ops/ms
Iteration   2: 10.140 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.135 ±(99.9%) 3.962 ops/ms [Average]
  (min, avg, max) = (9.915, 10.135, 10.349), stdev = 0.217
  CI (99.9%): [6.172, 14.097] (assumes normal distribution)


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
# Warmup Iteration   1: 8.403 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.892 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.736 ±(99.9%) 2.710 ops/ms [Average]
  (min, avg, max) = (10.596, 10.736, 10.892), stdev = 0.149
  CI (99.9%): [8.026, 13.446] (assumes normal distribution)


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
# Warmup Iteration   1: 6.795 ops/ms
# Warmup Iteration   2: 10.075 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.131 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.168 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (10.131, 10.168, 10.233), stdev = 0.056
  CI (99.9%): [9.146, 11.191] (assumes normal distribution)


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
# Warmup Iteration   1: 5.915 ops/ms
# Warmup Iteration   2: 7.477 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.002 ops/ms
Iteration   3: 7.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.940 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (7.863, 7.940, 8.002), stdev = 0.071
  CI (99.9%): [6.649, 9.231] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.197 ±(99.9%) 0.001 ms/op
Iteration   2: 3.166 ±(99.9%) 0.001 ms/op
Iteration   3: 3.117 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.160 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.117, 3.160, 3.197), stdev = 0.040
  CI (99.9%): [2.422, 3.898] (assumes normal distribution)


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (2.960, 2.993, 3.019), stdev = 0.030
  CI (99.9%): [2.440, 3.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.001 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.001 ms/op
Iteration   3: 3.133 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.178 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.133, 3.178, 3.208), stdev = 0.040
  CI (99.9%): [2.457, 3.898] (assumes normal distribution)


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
# Warmup Iteration   1: 5.625 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.019 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
Iteration   2: 3.850 ±(99.9%) 0.007 ms/op
Iteration   3: 3.959 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (3.850, 3.930, 3.980), stdev = 0.070
  CI (99.9%): [2.653, 5.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
Iteration   1: 3.120 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.537 ms/op
                 createUser·p0.9999: 13.635 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  6.116 ms/op
                 createUser·p0.9999: 14.413 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.968 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.925 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310459
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 783 
    [ 1.250,  2.500) = 32411 
    [ 2.500,  3.750) = 246176 
    [ 3.750,  5.000) = 29716 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.833 ms/op
     p(99.9900) =     16.776 ms/op
     p(99.9990) =     18.186 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.849 ms/op
                 existUser·p0.9999: 12.669 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.204 ms/op
                 existUser·p0.9999: 14.998 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.946 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.169 ms/op
                 existUser·p0.999:  8.035 ms/op
                 existUser·p0.9999: 27.169 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320800
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44405 
    [ 2.500,  5.000) = 275569 
    [ 5.000,  7.500) = 530 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     24.741 ms/op
     p(99.9990) =     27.387 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.604 ms/op
                 getUser·p0.9999: 18.869 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.927 ms/op
                 getUser·p0.9999: 17.326 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.484 ms/op
                 getUser·p0.9999: 19.954 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304807
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24304 
    [ 2.500,  5.000) = 279424 
    [ 5.000,  7.500) = 777 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.482 ms/op
     p(99.9900) =     19.448 ms/op
     p(99.9990) =     20.249 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.984 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.049 ms/op
                 listUser·p0.9999: 16.847 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 27.134 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  21.766 ms/op
                 listUser·p0.9999: 26.900 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236965
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1914 
    [ 2.500,  5.000) = 208318 
    [ 5.000,  7.500) = 25137 
    [ 7.500, 10.000) = 1047 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     14.665 ms/op
     p(99.9900) =     26.660 ms/op
     p(99.9990) =     30.045 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.135 ± 3.962  ops/ms
ClientGrpc.existUser                       thrpt       3  10.736 ± 2.710  ops/ms
ClientGrpc.getUser                         thrpt       3  10.168 ± 1.023  ops/ms
ClientGrpc.listUser                        thrpt       3   7.940 ± 1.291  ops/ms
ClientGrpc.createUser                       avgt       3   3.160 ± 0.738   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.553   ms/op
ClientGrpc.getUser                          avgt       3   3.178 ± 0.721   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 1.277   ms/op
ClientGrpc.createUser                     sample  310459   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.833           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.186           ms/op
ClientGrpc.existUser                      sample  320800   2.992 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.741           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  304807   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.482           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.448           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  236965   4.050 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.770           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.665           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.769           ms/op
