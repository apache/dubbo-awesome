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
# Warmup Iteration   1: 2.133 ops/ms
# Warmup Iteration   2: 5.369 ops/ms
# Warmup Iteration   3: 6.749 ops/ms
Iteration   1: 7.005 ops/ms
Iteration   2: 7.223 ops/ms
Iteration   3: 7.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.144 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (7.005, 7.144, 7.223), stdev = 0.121
  CI (99.9%): [4.937, 9.351] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ops/ms
# Warmup Iteration   2: 6.963 ops/ms
# Warmup Iteration   3: 7.391 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 7.647 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.628 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (7.490, 7.628, 7.747), stdev = 0.130
  CI (99.9%): [5.261, 9.995] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 6.546 ops/ms
# Warmup Iteration   3: 6.907 ops/ms
Iteration   1: 7.181 ops/ms
Iteration   2: 7.071 ops/ms
Iteration   3: 7.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.116 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (7.071, 7.116, 7.181), stdev = 0.058
  CI (99.9%): [6.067, 8.165] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ops/ms
# Warmup Iteration   2: 4.733 ops/ms
# Warmup Iteration   3: 5.262 ops/ms
Iteration   1: 5.480 ops/ms
Iteration   2: 5.722 ops/ms
Iteration   3: 5.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.607 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (5.480, 5.607, 5.722), stdev = 0.122
  CI (99.9%): [3.389, 7.826] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.008 ms/op
Iteration   1: 4.659 ±(99.9%) 0.002 ms/op
Iteration   2: 4.435 ±(99.9%) 0.004 ms/op
Iteration   3: 4.473 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.523 ±(99.9%) 2.185 ms/op [Average]
  (min, avg, max) = (4.435, 4.523, 4.659), stdev = 0.120
  CI (99.9%): [2.337, 6.708] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.417 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.006 ms/op
Iteration   1: 4.414 ±(99.9%) 0.002 ms/op
Iteration   2: 4.337 ±(99.9%) 0.004 ms/op
Iteration   3: 4.334 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.362 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (4.334, 4.362, 4.414), stdev = 0.045
  CI (99.9%): [3.533, 5.190] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.006 ms/op
Iteration   1: 4.562 ±(99.9%) 0.003 ms/op
Iteration   2: 4.585 ±(99.9%) 0.006 ms/op
Iteration   3: 4.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.539 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (4.470, 4.539, 4.585), stdev = 0.061
  CI (99.9%): [3.432, 5.646] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.616 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.656 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.865 ±(99.9%) 0.019 ms/op
Iteration   1: 5.680 ±(99.9%) 0.022 ms/op
Iteration   2: 5.490 ±(99.9%) 0.016 ms/op
Iteration   3: 5.822 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.664 ±(99.9%) 3.038 ms/op [Average]
  (min, avg, max) = (5.490, 5.664, 5.822), stdev = 0.167
  CI (99.9%): [2.626, 8.703] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.369 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.013 ms/op
Iteration   1: 4.475 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.543 ms/op
                 createUser·p0.999:  13.131 ms/op
                 createUser·p0.9999: 16.200 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 4.433 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 19.253 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 4.580 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.417 ms/op
                 createUser·p0.999:  21.087 ms/op
                 createUser·p0.9999: 40.371 ms/op
                 createUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213511
  mean =      4.495 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 169966 
    [ 5.000, 10.000) = 42919 
    [10.000, 15.000) = 405 
    [15.000, 20.000) = 110 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     15.196 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     40.728 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.056 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.351 ±(99.9%) 0.011 ms/op
Iteration   1: 4.221 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   6.779 ms/op
                 existUser·p0.999:  11.939 ms/op
                 existUser·p0.9999: 19.052 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 4.253 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  12.187 ms/op
                 existUser·p0.9999: 21.675 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 4.324 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  14.631 ms/op
                 existUser·p0.9999: 31.084 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225004
  mean =      4.266 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4689 
    [ 2.500,  5.000) = 190300 
    [ 5.000,  7.500) = 28702 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     32.104 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.273 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.000 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.017 ms/op
Iteration   1: 4.584 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  14.484 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 4.461 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  11.774 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 4.479 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.873 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  10.641 ms/op
                 getUser·p0.9999: 25.068 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212929
  mean =      4.507 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2159 
    [ 2.500,  5.000) = 165715 
    [ 5.000,  7.500) = 43087 
    [ 7.500, 10.000) = 1461 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     12.012 ms/op
     p(99.9900) =     24.908 ms/op
     p(99.9990) =     25.219 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.053 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.989 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.965 ±(99.9%) 0.022 ms/op
Iteration   1: 5.711 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 20.853 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 5.806 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  19.966 ms/op
                 listUser·p0.9999: 24.803 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   3: 5.749 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  19.814 ms/op
                 listUser·p0.9999: 38.068 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166920
  mean =      5.755 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 44471 
    [ 5.000,  7.500) = 108002 
    [ 7.500, 10.000) = 11840 
    [10.000, 12.500) = 1901 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     18.877 ms/op
     p(99.9900) =     37.441 ms/op
     p(99.9990) =     38.447 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.144 ± 2.207  ops/ms
ClientGrpc.existUser                       thrpt       3   7.628 ± 2.367  ops/ms
ClientGrpc.getUser                         thrpt       3   7.116 ± 1.049  ops/ms
ClientGrpc.listUser                        thrpt       3   5.607 ± 2.218  ops/ms
ClientGrpc.createUser                       avgt       3   4.523 ± 2.185   ms/op
ClientGrpc.existUser                        avgt       3   4.362 ± 0.829   ms/op
ClientGrpc.getUser                          avgt       3   4.539 ± 1.107   ms/op
ClientGrpc.listUser                         avgt       3   5.664 ± 3.038   ms/op
ClientGrpc.createUser                     sample  213511   4.495 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.098           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.561           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.196           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.715           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.829           ms/op
ClientGrpc.existUser                      sample  225004   4.266 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.944           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.894           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.295           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.244           ms/op
ClientGrpc.getUser                        sample  212929   4.507 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.017           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.908           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.330           ms/op
ClientGrpc.listUser                       sample  166920   5.755 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.589           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.258           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.441           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.535           ms/op
