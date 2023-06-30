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
# Warmup Iteration   1: 4.053 ops/ms
# Warmup Iteration   2: 8.402 ops/ms
# Warmup Iteration   3: 9.858 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.314 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.375 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (10.314, 10.375, 10.422), stdev = 0.055
  CI (99.9%): [9.373, 11.376] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.656 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.819 ops/ms
Iteration   1: 10.995 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.827 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (10.709, 10.827, 10.995), stdev = 0.150
  CI (99.9%): [8.098, 13.556] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.368 ops/ms
# Warmup Iteration   2: 9.783 ops/ms
# Warmup Iteration   3: 10.203 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.366 ±(99.9%) 0.101 ops/ms [Average]
  (min, avg, max) = (10.361, 10.366, 10.372), stdev = 0.006
  CI (99.9%): [10.265, 10.467] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.671 ops/ms
# Warmup Iteration   2: 7.938 ops/ms
# Warmup Iteration   3: 7.780 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 7.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.017 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (7.917, 8.017, 8.165), stdev = 0.131
  CI (99.9%): [5.630, 10.405] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.038, 3.062, 3.077), stdev = 0.021
  CI (99.9%): [2.676, 3.448] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (2.914, 2.954, 2.976), stdev = 0.034
  CI (99.9%): [2.328, 3.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.218 ±(99.9%) 0.002 ms/op
Iteration   2: 3.322 ±(99.9%) 0.004 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.221 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.123, 3.221, 3.322), stdev = 0.099
  CI (99.9%): [1.406, 5.036] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.022 ms/op
Iteration   1: 4.102 ±(99.9%) 0.026 ms/op
Iteration   2: 4.045 ±(99.9%) 0.041 ms/op
Iteration   3: 3.919 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (3.919, 4.022, 4.102), stdev = 0.094
  CI (99.9%): [2.315, 5.729] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.309 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.692 ms/op
                 createUser·p0.9999: 17.386 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.505 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.140 ms/op
                 createUser·p0.9999: 18.536 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.591 ms/op
                 createUser·p0.9999: 24.862 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309331
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13933 
    [ 2.500,  5.000) = 293985 
    [ 5.000,  7.500) = 987 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.309 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.809 ms/op
     p(99.9900) =     24.480 ms/op
     p(99.9990) =     25.261 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.380 ms/op
                 existUser·p0.9999: 16.957 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.943 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  5.456 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 16.663 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320344
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 682 
    [ 1.250,  2.500) = 23900 
    [ 2.500,  3.750) = 283377 
    [ 3.750,  5.000) = 11072 
    [ 5.000,  6.250) = 770 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     16.661 ms/op
     p(99.9990) =     18.180 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.769 ms/op
                 getUser·p0.9999: 15.951 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.478 ms/op
                 getUser·p0.9999: 14.778 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.559 ms/op
                 getUser·p0.9999: 16.475 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314470
  mean =      3.053 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 433 
    [ 1.250,  2.500) = 10148 
    [ 2.500,  3.750) = 291912 
    [ 3.750,  5.000) = 10950 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     16.082 ms/op
     p(99.9990) =     17.133 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.671 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   16.171 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 25.420 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241242
  mean =      3.982 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2292 
    [ 2.500,  5.000) = 215322 
    [ 5.000,  7.500) = 22198 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.134 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.761 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.375 ± 1.002  ops/ms
ClientGrpc.existUser                       thrpt       3  10.827 ± 2.729  ops/ms
ClientGrpc.getUser                         thrpt       3  10.366 ± 0.101  ops/ms
ClientGrpc.listUser                        thrpt       3   8.017 ± 2.387  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 0.386   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.625   ms/op
ClientGrpc.getUser                          avgt       3   3.221 ± 1.815   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 1.707   ms/op
ClientGrpc.createUser                     sample  309331   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.309           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.809           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.480           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  320344   2.994 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.111           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  314470   3.053 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.082           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  241242   3.982 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.134           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.002           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
