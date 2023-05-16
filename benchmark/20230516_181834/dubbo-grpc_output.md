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
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 4.890 ops/ms
# Warmup Iteration   3: 7.196 ops/ms
Iteration   1: 7.425 ops/ms
Iteration   2: 7.362 ops/ms
Iteration   3: 7.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.410 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (7.362, 7.410, 7.442), stdev = 0.042
  CI (99.9%): [6.639, 8.180] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.456 ops/ms
# Warmup Iteration   2: 7.062 ops/ms
# Warmup Iteration   3: 7.835 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.046 ±(99.9%) 2.883 ops/ms [Average]
  (min, avg, max) = (7.926, 8.046, 8.225), stdev = 0.158
  CI (99.9%): [5.162, 10.929] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.399 ops/ms
# Warmup Iteration   2: 6.890 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.512 ops/ms
Iteration   3: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.466 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (7.403, 7.466, 7.512), stdev = 0.057
  CI (99.9%): [6.429, 8.504] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 5.388 ops/ms
# Warmup Iteration   3: 5.735 ops/ms
Iteration   1: 5.801 ops/ms
Iteration   2: 5.655 ops/ms
Iteration   3: 5.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.774 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (5.655, 5.774, 5.866), stdev = 0.108
  CI (99.9%): [3.799, 7.749] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.457 ±(99.9%) 0.009 ms/op
Iteration   1: 4.457 ±(99.9%) 0.002 ms/op
Iteration   2: 4.291 ±(99.9%) 0.003 ms/op
Iteration   3: 4.563 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.437 ±(99.9%) 2.498 ms/op [Average]
  (min, avg, max) = (4.291, 4.437, 4.563), stdev = 0.137
  CI (99.9%): [1.939, 6.935] (assumes normal distribution)


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
# Warmup Iteration   1: 6.554 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.004 ms/op
Iteration   1: 4.023 ±(99.9%) 0.004 ms/op
Iteration   2: 4.041 ±(99.9%) 0.003 ms/op
Iteration   3: 3.824 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.963 ±(99.9%) 2.195 ms/op [Average]
  (min, avg, max) = (3.824, 3.963, 4.041), stdev = 0.120
  CI (99.9%): [1.768, 6.158] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.008 ms/op
Iteration   1: 4.253 ±(99.9%) 0.004 ms/op
Iteration   2: 4.228 ±(99.9%) 0.003 ms/op
Iteration   3: 4.088 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.190 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (4.088, 4.190, 4.253), stdev = 0.089
  CI (99.9%): [2.561, 5.819] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.422 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.999 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.020 ms/op
Iteration   1: 5.574 ±(99.9%) 0.024 ms/op
Iteration   2: 5.440 ±(99.9%) 0.021 ms/op
Iteration   3: 5.607 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.541 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (5.440, 5.541, 5.607), stdev = 0.088
  CI (99.9%): [3.930, 7.152] (assumes normal distribution)


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
# Warmup Iteration   1: 6.753 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.015 ms/op
Iteration   1: 4.271 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 20.481 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 4.384 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  14.587 ms/op
                 createUser·p0.9999: 22.683 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 4.154 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.417 ms/op
                 createUser·p0.999:  14.374 ms/op
                 createUser·p0.9999: 25.972 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224747
  mean =      4.268 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6974 
    [ 2.500,  5.000) = 176746 
    [ 5.000,  7.500) = 38912 
    [ 7.500, 10.000) = 1556 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     13.488 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.387 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 6.204 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.013 ms/op
Iteration   1: 4.196 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  11.939 ms/op
                 existUser·p0.9999: 16.261 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 4.060 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 16.583 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   3: 4.255 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.779 ms/op
                 existUser·p0.99:   7.643 ms/op
                 existUser·p0.999:  12.088 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230272
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5299 
    [ 2.500,  5.000) = 193776 
    [ 5.000,  7.500) = 29053 
    [ 7.500, 10.000) = 1588 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     11.432 ms/op
     p(99.9900) =     22.740 ms/op
     p(99.9990) =     23.223 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 6.917 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.015 ms/op
Iteration   1: 4.189 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  12.371 ms/op
                 getUser·p0.9999: 17.752 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 4.224 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  12.570 ms/op
                 getUser·p0.9999: 18.935 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 4.262 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   7.864 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227150
  mean =      4.225 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7792 
    [ 2.500,  5.000) = 186151 
    [ 5.000,  7.500) = 30919 
    [ 7.500, 10.000) = 1720 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     23.864 ms/op
     p(99.9990) =     27.323 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 9.510 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 5.866 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.022 ms/op
Iteration   1: 5.760 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.252 ms/op
                 listUser·p0.999:  15.924 ms/op
                 listUser·p0.9999: 17.883 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 5.843 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 24.169 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   3: 5.867 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 24.358 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164660
  mean =      5.823 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 162 
    [ 2.500,  5.000) = 55714 
    [ 5.000,  7.500) = 85710 
    [ 7.500, 10.000) = 18466 
    [10.000, 12.500) = 3556 
    [12.500, 15.000) = 570 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      8.102 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     19.180 ms/op
     p(99.9900) =     24.004 ms/op
     p(99.9990) =     26.461 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.410 ± 0.771  ops/ms
ClientGrpc.existUser                       thrpt       3   8.046 ± 2.883  ops/ms
ClientGrpc.getUser                         thrpt       3   7.466 ± 1.037  ops/ms
ClientGrpc.listUser                        thrpt       3   5.774 ± 1.975  ops/ms
ClientGrpc.createUser                       avgt       3   4.437 ± 2.498   ms/op
ClientGrpc.existUser                        avgt       3   3.963 ± 2.195   ms/op
ClientGrpc.getUser                          avgt       3   4.190 ± 1.629   ms/op
ClientGrpc.listUser                         avgt       3   5.541 ± 1.611   ms/op
ClientGrpc.createUser                     sample  224747   4.268 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.488           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.625           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.509           ms/op
ClientGrpc.existUser                      sample  230272   4.168 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.036           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.693           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.406           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.432           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.740           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  227150   4.225 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.920           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.767           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.337           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.864           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.525           ms/op
ClientGrpc.listUser                       sample  164660   5.823 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.710           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.180           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.004           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
