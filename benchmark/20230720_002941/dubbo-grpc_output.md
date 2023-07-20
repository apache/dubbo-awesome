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
# Warmup Iteration   1: 4.463 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 10.173 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.675 ±(99.9%) 2.416 ops/ms [Average]
  (min, avg, max) = (10.524, 10.675, 10.772), stdev = 0.132
  CI (99.9%): [8.260, 13.091] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ops/ms
# Warmup Iteration   2: 10.718 ops/ms
# Warmup Iteration   3: 11.482 ops/ms
Iteration   1: 11.221 ops/ms
Iteration   2: 11.315 ops/ms
Iteration   3: 11.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.311 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (11.221, 11.311, 11.398), stdev = 0.088
  CI (99.9%): [9.698, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 7.663 ops/ms
# Warmup Iteration   2: 10.421 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.688 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (10.627, 10.688, 10.792), stdev = 0.090
  CI (99.9%): [9.040, 12.336] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.825 ops/ms
# Warmup Iteration   2: 8.143 ops/ms
# Warmup Iteration   3: 8.170 ops/ms
Iteration   1: 8.414 ops/ms
Iteration   2: 8.377 ops/ms
Iteration   3: 8.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.370 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (8.318, 8.370, 8.414), stdev = 0.048
  CI (99.9%): [7.492, 9.247] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.004 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.974, 2.986, 3.001), stdev = 0.014
  CI (99.9%): [2.732, 3.241] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.003 ms/op
Iteration   1: 2.792 ±(99.9%) 0.004 ms/op
Iteration   2: 2.812 ±(99.9%) 0.003 ms/op
Iteration   3: 2.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.837 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (2.792, 2.837, 2.908), stdev = 0.062
  CI (99.9%): [1.708, 3.966] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 2.947 ±(99.9%) 0.003 ms/op
Iteration   2: 2.921 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.938 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.921, 2.938, 2.947), stdev = 0.014
  CI (99.9%): [2.674, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.019 ms/op
Iteration   1: 3.860 ±(99.9%) 0.014 ms/op
Iteration   2: 3.787 ±(99.9%) 0.019 ms/op
Iteration   3: 3.835 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.827 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.787, 3.827, 3.860), stdev = 0.037
  CI (99.9%): [3.151, 4.504] (assumes normal distribution)


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  8.270 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.942 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.768 ms/op
                 createUser·p0.9999: 15.948 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320241
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 704 
    [ 1.250,  2.500) = 21109 
    [ 2.500,  3.750) = 286330 
    [ 3.750,  5.000) = 10768 
    [ 5.000,  6.250) = 774 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.191 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.589 ms/op
                 existUser·p0.9999: 17.007 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 12.879 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 2.847 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.060 ms/op
                 existUser·p0.9999: 13.742 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333413
  mean =      2.876 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3211 
    [ 1.250,  2.500) = 43496 
    [ 2.500,  3.750) = 277361 
    [ 3.750,  5.000) = 8252 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     16.292 ms/op
     p(99.9990) =     17.258 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.404 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 2.935 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.169 ms/op
                 getUser·p0.9999: 29.134 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.859 ms/op
                 getUser·p0.9999: 20.942 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326691
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32070 
    [ 2.500,  5.000) = 293377 
    [ 5.000,  7.500) = 945 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     23.980 ms/op
     p(99.9990) =     29.408 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.008 ms/op
Iteration   1: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 17.502 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.083 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.781 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  15.815 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252210
  mean =      3.810 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6102 
    [ 2.500,  5.000) = 228518 
    [ 5.000,  7.500) = 16747 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     13.317 ms/op
     p(99.9900) =     19.359 ms/op
     p(99.9990) =     21.607 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.675 ± 2.416  ops/ms
ClientGrpc.existUser                       thrpt       3  11.311 ± 1.613  ops/ms
ClientGrpc.getUser                         thrpt       3  10.688 ± 1.648  ops/ms
ClientGrpc.listUser                        thrpt       3   8.370 ± 0.877  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.254   ms/op
ClientGrpc.existUser                        avgt       3   2.837 ± 1.129   ms/op
ClientGrpc.getUser                          avgt       3   2.938 ± 0.264   ms/op
ClientGrpc.listUser                         avgt       3   3.827 ± 0.677   ms/op
ClientGrpc.createUser                     sample  320241   2.997 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.760           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  333413   2.876 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.600           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.292           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  326691   2.939 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.143           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.980           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.491           ms/op
ClientGrpc.listUser                       sample  252210   3.810 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.905           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.317           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.359           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
