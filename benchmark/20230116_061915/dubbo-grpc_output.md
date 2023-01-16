# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.421 ops/ms
# Warmup Iteration   2: 6.372 ops/ms
# Warmup Iteration   3: 7.179 ops/ms
Iteration   1: 7.217 ops/ms
Iteration   2: 7.202 ops/ms
Iteration   3: 7.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.237 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (7.202, 7.237, 7.293), stdev = 0.049
  CI (99.9%): [6.351, 8.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ops/ms
# Warmup Iteration   2: 7.335 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 7.750 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.749 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (7.693, 7.749, 7.802), stdev = 0.054
  CI (99.9%): [6.756, 8.742] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ops/ms
# Warmup Iteration   2: 7.007 ops/ms
# Warmup Iteration   3: 7.143 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 7.434 ops/ms
Iteration   3: 7.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.373 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (7.313, 7.373, 7.434), stdev = 0.061
  CI (99.9%): [6.261, 8.484] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ops/ms
# Warmup Iteration   2: 5.326 ops/ms
# Warmup Iteration   3: 5.455 ops/ms
Iteration   1: 5.614 ops/ms
Iteration   2: 5.491 ops/ms
Iteration   3: 5.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.574 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (5.491, 5.574, 5.616), stdev = 0.072
  CI (99.9%): [4.266, 6.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.455 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.004 ms/op
Iteration   1: 4.341 ±(99.9%) 0.003 ms/op
Iteration   2: 4.183 ±(99.9%) 0.004 ms/op
Iteration   3: 4.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.243 ±(99.9%) 1.557 ms/op [Average]
  (min, avg, max) = (4.183, 4.243, 4.341), stdev = 0.085
  CI (99.9%): [2.686, 5.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.885 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.005 ms/op
Iteration   1: 4.195 ±(99.9%) 0.003 ms/op
Iteration   2: 4.122 ±(99.9%) 0.004 ms/op
Iteration   3: 4.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.146 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (4.120, 4.146, 4.195), stdev = 0.043
  CI (99.9%): [3.363, 4.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.648 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.008 ms/op
Iteration   1: 4.239 ±(99.9%) 0.004 ms/op
Iteration   2: 4.344 ±(99.9%) 0.002 ms/op
Iteration   3: 4.314 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.299 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (4.239, 4.299, 4.344), stdev = 0.054
  CI (99.9%): [3.315, 5.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.039 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.594 ±(99.9%) 0.014 ms/op
Iteration   1: 5.434 ±(99.9%) 0.013 ms/op
Iteration   2: 5.492 ±(99.9%) 0.018 ms/op
Iteration   3: 5.473 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.466 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (5.434, 5.466, 5.492), stdev = 0.029
  CI (99.9%): [4.929, 6.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.885 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.014 ms/op
Iteration   1: 4.298 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  12.610 ms/op
                 createUser·p0.9999: 24.613 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 4.321 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 4.539 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 30.110 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219019
  mean =      4.383 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4553 
    [ 2.500,  5.000) = 163458 
    [ 5.000,  7.500) = 48894 
    [ 7.500, 10.000) = 1534 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     14.155 ms/op
     p(99.9900) =     28.774 ms/op
     p(99.9990) =     30.930 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.411 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.012 ms/op
Iteration   1: 4.228 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 18.673 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 4.165 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.734 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  10.669 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 4.195 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  14.559 ms/op
                 existUser·p0.9999: 21.271 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228744
  mean =      4.196 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7047 
    [ 2.500,  5.000) = 181756 
    [ 5.000,  7.500) = 38251 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     11.539 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     21.683 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.631 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.013 ms/op
Iteration   1: 4.412 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 14.999 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   2: 4.462 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  14.700 ms/op
                 getUser·p0.9999: 17.481 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 4.368 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  10.061 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217603
  mean =      4.414 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2661 
    [ 2.500,  5.000) = 163403 
    [ 5.000,  7.500) = 49592 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     11.298 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     20.436 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.714 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.860 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.489 ±(99.9%) 0.019 ms/op
Iteration   1: 5.602 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  15.463 ms/op
                 listUser·p0.9999: 19.361 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 5.758 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 19.741 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 5.534 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  26.123 ms/op
                 listUser·p0.9999: 31.366 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170451
  mean =      5.630 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 58163 
    [ 5.000,  7.500) = 97401 
    [ 7.500, 10.000) = 12510 
    [10.000, 12.500) = 1642 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     30.535 ms/op
     p(99.9990) =     32.028 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.237 ± 0.886  ops/ms
ClientGrpc.existUser                       thrpt       3   7.749 ± 0.993  ops/ms
ClientGrpc.getUser                         thrpt       3   7.373 ± 1.112  ops/ms
ClientGrpc.listUser                        thrpt       3   5.574 ± 1.308  ops/ms
ClientGrpc.createUser                       avgt       3   4.243 ± 1.557   ms/op
ClientGrpc.existUser                        avgt       3   4.146 ± 0.783   ms/op
ClientGrpc.getUser                          avgt       3   4.299 ± 0.984   ms/op
ClientGrpc.listUser                         avgt       3   5.466 ± 0.537   ms/op
ClientGrpc.createUser                     sample  219019   4.383 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.957           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.438           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.155           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.774           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.195           ms/op
ClientGrpc.existUser                      sample  228744   4.196 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.677           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.725           ms/op
ClientGrpc.getUser                        sample  217603   4.414 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.007           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.298           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.252           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  170451   5.630 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.257           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.241           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.662           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.535           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.375           ms/op
