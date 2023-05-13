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
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 5.465 ops/ms
# Warmup Iteration   3: 6.686 ops/ms
Iteration   1: 7.183 ops/ms
Iteration   2: 7.264 ops/ms
Iteration   3: 7.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.296 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (7.183, 7.296, 7.441), stdev = 0.132
  CI (99.9%): [4.891, 9.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.491 ops/ms
# Warmup Iteration   2: 7.151 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 7.562 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.650 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (7.562, 7.650, 7.739), stdev = 0.088
  CI (99.9%): [6.036, 9.264] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 6.394 ops/ms
# Warmup Iteration   3: 6.902 ops/ms
Iteration   1: 7.117 ops/ms
Iteration   2: 7.104 ops/ms
Iteration   3: 7.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.202 ±(99.9%) 2.891 ops/ms [Average]
  (min, avg, max) = (7.104, 7.202, 7.385), stdev = 0.158
  CI (99.9%): [4.310, 10.093] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 5.290 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.811 ops/ms
Iteration   2: 5.576 ops/ms
Iteration   3: 5.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.775 ±(99.9%) 3.368 ops/ms [Average]
  (min, avg, max) = (5.576, 5.775, 5.940), stdev = 0.185
  CI (99.9%): [2.407, 9.143] (assumes normal distribution)


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
# Warmup Iteration   1: 7.362 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.775 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.490 ±(99.9%) 0.011 ms/op
Iteration   1: 4.424 ±(99.9%) 0.004 ms/op
Iteration   2: 4.492 ±(99.9%) 0.005 ms/op
Iteration   3: 4.373 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.430 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (4.373, 4.430, 4.492), stdev = 0.059
  CI (99.9%): [3.345, 5.514] (assumes normal distribution)


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
# Warmup Iteration   1: 6.057 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.010 ms/op
Iteration   1: 3.944 ±(99.9%) 0.003 ms/op
Iteration   2: 3.988 ±(99.9%) 0.002 ms/op
Iteration   3: 3.863 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.932 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.863, 3.932, 3.988), stdev = 0.063
  CI (99.9%): [2.774, 5.089] (assumes normal distribution)


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
# Warmup Iteration   1: 6.779 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.003 ms/op
Iteration   1: 4.405 ±(99.9%) 0.004 ms/op
Iteration   2: 4.334 ±(99.9%) 0.004 ms/op
Iteration   3: 4.411 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.383 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (4.334, 4.383, 4.411), stdev = 0.043
  CI (99.9%): [3.598, 5.168] (assumes normal distribution)


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
# Warmup Iteration   1: 7.578 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.012 ms/op
Iteration   1: 5.505 ±(99.9%) 0.014 ms/op
Iteration   2: 5.616 ±(99.9%) 0.018 ms/op
Iteration   3: 5.630 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.583 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (5.505, 5.583, 5.630), stdev = 0.068
  CI (99.9%): [4.336, 6.830] (assumes normal distribution)


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
# Warmup Iteration   1: 7.031 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.012 ms/op
Iteration   1: 4.401 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   8.227 ms/op
                 createUser·p0.999:  13.538 ms/op
                 createUser·p0.9999: 17.771 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 4.564 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  11.561 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 4.539 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  13.037 ms/op
                 createUser·p0.9999: 55.375 ms/op
                 createUser·p1.00:   55.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213296
  mean =      4.500 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 165935 
    [ 5.000, 10.000) = 46646 
    [10.000, 15.000) = 580 
    [15.000, 20.000) = 77 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     54.832 ms/op
     p(99.9990) =     55.575 ms/op
     p(99.9999) =     55.575 ms/op
    p(100.0000) =     55.575 ms/op


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
# Warmup Iteration   1: 6.661 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.011 ms/op
Iteration   1: 4.098 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 16.646 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 4.098 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.043 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  9.780 ms/op
                 existUser·p0.9999: 15.961 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   3: 3.973 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.555 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236528
  mean =      4.055 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6997 
    [ 2.500,  5.000) = 206742 
    [ 5.000,  7.500) = 21701 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =      9.904 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     23.712 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 6.994 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.012 ms/op
Iteration   1: 4.516 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.140 ms/op
                 getUser·p0.99:   8.282 ms/op
                 getUser·p0.999:  13.897 ms/op
                 getUser·p0.9999: 31.008 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   2: 4.455 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  11.612 ms/op
                 getUser·p0.9999: 18.633 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 4.260 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 21.102 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217791
  mean =      4.408 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2780 
    [ 2.500,  5.000) = 175118 
    [ 5.000,  7.500) = 38049 
    [ 7.500, 10.000) = 1425 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     28.424 ms/op
     p(99.9990) =     31.473 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 8.313 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.769 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.017 ms/op
Iteration   1: 5.668 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 25.853 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 5.615 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  18.278 ms/op
                 listUser·p0.9999: 20.846 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 5.536 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  21.217 ms/op
                 listUser·p0.9999: 24.696 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171356
  mean =      5.606 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133 
    [ 2.500,  5.000) = 53362 
    [ 5.000,  7.500) = 105370 
    [ 7.500, 10.000) = 10499 
    [10.000, 12.500) = 1511 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.247 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     24.801 ms/op
     p(99.9990) =     26.701 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.296 ± 2.405  ops/ms
ClientGrpc.existUser                       thrpt       3   7.650 ± 1.614  ops/ms
ClientGrpc.getUser                         thrpt       3   7.202 ± 2.891  ops/ms
ClientGrpc.listUser                        thrpt       3   5.775 ± 3.368  ops/ms
ClientGrpc.createUser                       avgt       3   4.430 ± 1.085   ms/op
ClientGrpc.existUser                        avgt       3   3.932 ± 1.157   ms/op
ClientGrpc.getUser                          avgt       3   4.383 ± 0.785   ms/op
ClientGrpc.listUser                         avgt       3   5.583 ± 1.247   ms/op
ClientGrpc.createUser                     sample  213296   4.500 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.008           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.725           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.140           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          54.832           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          55.575           ms/op
ClientGrpc.existUser                      sample  236528   4.055 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.049           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.981           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.904           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.316           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.757           ms/op
ClientGrpc.getUser                        sample  217791   4.408 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.949           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.407           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.288           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.424           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.490           ms/op
ClientGrpc.listUser                       sample  171356   5.606 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.612           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.247           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.612           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.801           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
