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
# Warmup Iteration   1: 2.454 ops/ms
# Warmup Iteration   2: 5.996 ops/ms
# Warmup Iteration   3: 7.638 ops/ms
Iteration   1: 8.134 ops/ms
Iteration   2: 8.257 ops/ms
Iteration   3: 7.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.943 ±(99.9%) 8.054 ops/ms [Average]
  (min, avg, max) = (7.438, 7.943, 8.257), stdev = 0.441
  CI (99.9%): [≈ 0, 15.997] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.766 ops/ms
# Warmup Iteration   2: 6.993 ops/ms
# Warmup Iteration   3: 7.470 ops/ms
Iteration   1: 7.767 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.261 ±(99.9%) 7.884 ops/ms [Average]
  (min, avg, max) = (7.767, 8.261, 8.567), stdev = 0.432
  CI (99.9%): [0.377, 16.145] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.961 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 7.972 ops/ms
Iteration   3: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.095 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (7.972, 8.095, 8.184), stdev = 0.110
  CI (99.9%): [6.085, 10.106] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ops/ms
# Warmup Iteration   2: 5.372 ops/ms
# Warmup Iteration   3: 5.995 ops/ms
Iteration   1: 5.800 ops/ms
Iteration   2: 5.611 ops/ms
Iteration   3: 5.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.728 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (5.611, 5.728, 5.800), stdev = 0.103
  CI (99.9%): [3.855, 7.601] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.546 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.004 ms/op
Iteration   1: 4.284 ±(99.9%) 0.003 ms/op
Iteration   2: 4.322 ±(99.9%) 0.003 ms/op
Iteration   3: 4.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.288 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (4.258, 4.288, 4.322), stdev = 0.032
  CI (99.9%): [3.696, 4.879] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.230 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.004 ms/op
Iteration   1: 3.738 ±(99.9%) 0.003 ms/op
Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
Iteration   3: 3.604 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.704 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (3.604, 3.704, 3.771), stdev = 0.089
  CI (99.9%): [2.089, 5.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.925 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.004 ms/op
Iteration   1: 3.855 ±(99.9%) 0.003 ms/op
Iteration   2: 4.161 ±(99.9%) 0.005 ms/op
Iteration   3: 4.244 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.087 ±(99.9%) 3.741 ms/op [Average]
  (min, avg, max) = (3.855, 4.087, 4.244), stdev = 0.205
  CI (99.9%): [0.346, 7.828] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.711 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.864 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.098 ±(99.9%) 0.009 ms/op
Iteration   1: 4.976 ±(99.9%) 0.032 ms/op
Iteration   2: 5.079 ±(99.9%) 0.012 ms/op
Iteration   3: 5.188 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.081 ±(99.9%) 1.939 ms/op [Average]
  (min, avg, max) = (4.976, 5.081, 5.188), stdev = 0.106
  CI (99.9%): [3.142, 7.020] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.132 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.315 ±(99.9%) 0.012 ms/op
Iteration   1: 4.345 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  12.361 ms/op
                 createUser·p0.9999: 21.713 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 4.310 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  12.216 ms/op
                 createUser·p0.9999: 24.764 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 4.434 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  13.951 ms/op
                 createUser·p0.9999: 27.379 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220036
  mean =      4.362 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4463 
    [ 2.500,  5.000) = 176646 
    [ 5.000,  7.500) = 36140 
    [ 7.500, 10.000) = 2188 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.728 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.012 ms/op
Iteration   1: 4.079 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  11.784 ms/op
                 existUser·p0.9999: 31.921 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   2: 3.898 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 15.796 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  10.493 ms/op
                 existUser·p0.9999: 17.493 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242111
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7859 
    [ 2.500,  5.000) = 214537 
    [ 5.000,  7.500) = 17974 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     23.684 ms/op
     p(99.9990) =     32.399 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.818 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.475 ±(99.9%) 0.015 ms/op
Iteration   1: 4.455 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.873 ms/op
                 getUser·p0.999:  13.628 ms/op
                 getUser·p0.9999: 17.462 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 4.330 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  13.484 ms/op
                 getUser·p0.9999: 26.123 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 4.472 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   7.987 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 26.958 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217268
  mean =      4.418 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8278 
    [ 2.500,  5.000) = 162383 
    [ 5.000,  7.500) = 43865 
    [ 7.500, 10.000) = 2005 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     12.979 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.976 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.311 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.971 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.643 ±(99.9%) 0.018 ms/op
Iteration   1: 5.671 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 5.178 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  17.375 ms/op
                 listUser·p0.9999: 23.882 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 4.988 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.954 ms/op
                 listUser·p0.9999: 24.058 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182461
  mean =      5.264 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187 
    [ 2.500,  5.000) = 88012 
    [ 5.000,  7.500) = 83871 
    [ 7.500, 10.000) = 8809 
    [10.000, 12.500) = 1084 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     22.971 ms/op
     p(99.9990) =     24.462 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.943 ± 8.054  ops/ms
ClientGrpc.existUser                       thrpt       3   8.261 ± 7.884  ops/ms
ClientGrpc.getUser                         thrpt       3   8.095 ± 2.011  ops/ms
ClientGrpc.listUser                        thrpt       3   5.728 ± 1.873  ops/ms
ClientGrpc.createUser                       avgt       3   4.288 ± 0.592   ms/op
ClientGrpc.existUser                        avgt       3   3.704 ± 1.616   ms/op
ClientGrpc.getUser                          avgt       3   4.087 ± 3.741   ms/op
ClientGrpc.listUser                         avgt       3   5.081 ± 1.939   ms/op
ClientGrpc.createUser                     sample  220036   4.362 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.978           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.808           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.987           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.976           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.182           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.820           ms/op
ClientGrpc.existUser                      sample  242111   3.964 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.898           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.684           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.539           ms/op
ClientGrpc.getUser                        sample  217268   4.418 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.946           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.905           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.952           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.246           ms/op
ClientGrpc.listUser                       sample  182461   5.264 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.569           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.765           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.971           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
