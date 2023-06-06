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
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 5.825 ops/ms
# Warmup Iteration   3: 7.242 ops/ms
Iteration   1: 7.419 ops/ms
Iteration   2: 7.287 ops/ms
Iteration   3: 7.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.392 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (7.287, 7.392, 7.470), stdev = 0.095
  CI (99.9%): [5.666, 9.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.934 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 8.170 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.043 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (8.029, 8.043, 8.061), stdev = 0.016
  CI (99.9%): [7.744, 8.342] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ops/ms
# Warmup Iteration   2: 6.789 ops/ms
# Warmup Iteration   3: 7.044 ops/ms
Iteration   1: 7.263 ops/ms
Iteration   2: 7.425 ops/ms
Iteration   3: 7.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.384 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (7.263, 7.384, 7.464), stdev = 0.107
  CI (99.9%): [5.436, 9.333] (assumes normal distribution)


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
# Warmup Iteration   1: 3.637 ops/ms
# Warmup Iteration   2: 5.547 ops/ms
# Warmup Iteration   3: 5.715 ops/ms
Iteration   1: 5.891 ops/ms
Iteration   2: 5.764 ops/ms
Iteration   3: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.765 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (5.641, 5.765, 5.891), stdev = 0.125
  CI (99.9%): [3.482, 8.049] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.004 ms/op
Iteration   1: 4.325 ±(99.9%) 0.003 ms/op
Iteration   2: 4.438 ±(99.9%) 0.003 ms/op
Iteration   3: 4.482 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.415 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (4.325, 4.415, 4.482), stdev = 0.081
  CI (99.9%): [2.937, 5.893] (assumes normal distribution)


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
# Warmup Iteration   1: 6.100 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.004 ms/op
Iteration   1: 3.967 ±(99.9%) 0.003 ms/op
Iteration   2: 4.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.020 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.967, 4.020, 4.103), stdev = 0.072
  CI (99.9%): [2.698, 5.342] (assumes normal distribution)


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
# Warmup Iteration   1: 6.638 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.003 ms/op
Iteration   1: 4.273 ±(99.9%) 0.003 ms/op
Iteration   2: 4.205 ±(99.9%) 0.004 ms/op
Iteration   3: 4.251 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.243 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (4.205, 4.243, 4.273), stdev = 0.035
  CI (99.9%): [3.611, 4.875] (assumes normal distribution)


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
# Warmup Iteration   1: 7.840 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.852 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.436 ±(99.9%) 0.018 ms/op
Iteration   1: 5.606 ±(99.9%) 0.013 ms/op
Iteration   2: 5.532 ±(99.9%) 0.019 ms/op
Iteration   3: 5.322 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.487 ±(99.9%) 2.687 ms/op [Average]
  (min, avg, max) = (5.322, 5.487, 5.606), stdev = 0.147
  CI (99.9%): [2.800, 8.174] (assumes normal distribution)


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
# Warmup Iteration   1: 6.480 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.812 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.014 ms/op
Iteration   1: 4.247 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   6.915 ms/op
                 createUser·p0.999:  12.339 ms/op
                 createUser·p0.9999: 22.296 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 4.178 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  10.732 ms/op
                 createUser·p0.9999: 17.509 ms/op
                 createUser·p1.00:   17.826 ms/op

Iteration   3: 4.399 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.371 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 23.141 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224461
  mean =      4.273 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1371 
    [ 2.500,  5.000) = 185474 
    [ 5.000,  7.500) = 36152 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.010 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.692 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 6.276 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  10.880 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.921 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 28.732 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 4.004 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  10.098 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241107
  mean =      3.979 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4347 
    [ 2.500,  5.000) = 215505 
    [ 5.000,  7.500) = 19908 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     11.121 ms/op
     p(99.9900) =     28.013 ms/op
     p(99.9990) =     30.002 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 5.992 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.012 ms/op
Iteration   1: 4.174 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   6.716 ms/op
                 getUser·p0.999:  8.821 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 4.257 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  12.559 ms/op
                 getUser·p0.9999: 24.131 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 4.292 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  14.235 ms/op
                 getUser·p0.9999: 21.546 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226437
  mean =      4.240 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2184 
    [ 2.500,  5.000) = 189440 
    [ 5.000,  7.500) = 33384 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     11.939 ms/op
     p(99.9900) =     21.802 ms/op
     p(99.9990) =     24.533 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 9.087 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 5.674 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.496 ±(99.9%) 0.018 ms/op
Iteration   1: 5.561 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.072 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  20.211 ms/op
                 listUser·p0.9999: 27.327 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 5.570 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  17.678 ms/op
                 listUser·p0.9999: 22.815 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 5.435 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  20.611 ms/op
                 listUser·p0.9999: 30.391 ms/op
                 listUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173952
  mean =      5.521 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 64839 
    [ 5.000,  7.500) = 96218 
    [ 7.500, 10.000) = 10598 
    [10.000, 12.500) = 1665 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     30.886 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.392 ± 1.726  ops/ms
ClientGrpc.existUser                       thrpt       3   8.043 ± 0.299  ops/ms
ClientGrpc.getUser                         thrpt       3   7.384 ± 1.949  ops/ms
ClientGrpc.listUser                        thrpt       3   5.765 ± 2.284  ops/ms
ClientGrpc.createUser                       avgt       3   4.415 ± 1.478   ms/op
ClientGrpc.existUser                        avgt       3   4.020 ± 1.322   ms/op
ClientGrpc.getUser                          avgt       3   4.243 ± 0.632   ms/op
ClientGrpc.listUser                         avgt       3   5.487 ± 2.687   ms/op
ClientGrpc.createUser                     sample  224461   4.273 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.104           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.308           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.881           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.010           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.822           ms/op
ClientGrpc.existUser                      sample  241107   3.979 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.711           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.619           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.121           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.013           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.081           ms/op
ClientGrpc.getUser                        sample  226437   4.240 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.149           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.939           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.802           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  173952   5.521 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.300           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.355           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.874           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.082           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.031           ms/op
