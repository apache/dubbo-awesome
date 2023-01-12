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
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 5.775 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.533 ops/ms
Iteration   2: 7.978 ops/ms
Iteration   3: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.762 ±(99.9%) 4.066 ops/ms [Average]
  (min, avg, max) = (7.533, 7.762, 7.978), stdev = 0.223
  CI (99.9%): [3.696, 11.828] (assumes normal distribution)


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
# Warmup Iteration   1: 4.657 ops/ms
# Warmup Iteration   2: 7.534 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 7.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.798 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (7.686, 7.798, 7.872), stdev = 0.099
  CI (99.9%): [6.000, 9.597] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ops/ms
# Warmup Iteration   2: 6.879 ops/ms
# Warmup Iteration   3: 7.076 ops/ms
Iteration   1: 7.296 ops/ms
Iteration   2: 7.165 ops/ms
Iteration   3: 7.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.235 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (7.165, 7.235, 7.296), stdev = 0.066
  CI (99.9%): [6.026, 8.445] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 5.411 ops/ms
# Warmup Iteration   3: 6.049 ops/ms
Iteration   1: 5.744 ops/ms
Iteration   2: 6.010 ops/ms
Iteration   3: 6.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.990 ±(99.9%) 4.306 ops/ms [Average]
  (min, avg, max) = (5.744, 5.990, 6.215), stdev = 0.236
  CI (99.9%): [1.683, 10.296] (assumes normal distribution)


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
# Warmup Iteration   1: 7.049 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.004 ms/op
Iteration   1: 4.194 ±(99.9%) 0.003 ms/op
Iteration   2: 4.456 ±(99.9%) 0.003 ms/op
Iteration   3: 4.422 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.358 ±(99.9%) 2.602 ms/op [Average]
  (min, avg, max) = (4.194, 4.358, 4.456), stdev = 0.143
  CI (99.9%): [1.756, 6.959] (assumes normal distribution)


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
# Warmup Iteration   1: 5.989 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.003 ms/op
Iteration   1: 4.020 ±(99.9%) 0.003 ms/op
Iteration   2: 4.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.902 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.006 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (3.902, 4.006, 4.095), stdev = 0.097
  CI (99.9%): [2.239, 5.772] (assumes normal distribution)


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
# Warmup Iteration   1: 5.896 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.003 ms/op
Iteration   1: 4.216 ±(99.9%) 0.004 ms/op
Iteration   2: 4.240 ±(99.9%) 0.002 ms/op
Iteration   3: 4.296 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.251 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (4.216, 4.251, 4.296), stdev = 0.041
  CI (99.9%): [3.499, 5.003] (assumes normal distribution)


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
# Warmup Iteration   1: 7.461 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.472 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.135 ±(99.9%) 0.012 ms/op
Iteration   1: 4.998 ±(99.9%) 0.007 ms/op
Iteration   2: 5.210 ±(99.9%) 0.018 ms/op
Iteration   3: 5.133 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.114 ±(99.9%) 1.954 ms/op [Average]
  (min, avg, max) = (4.998, 5.114, 5.210), stdev = 0.107
  CI (99.9%): [3.160, 7.067] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.078 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.011 ms/op
Iteration   1: 4.278 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.166 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   6.843 ms/op
                 createUser·p0.999:  10.136 ms/op
                 createUser·p0.9999: 16.344 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 4.263 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  15.728 ms/op
                 createUser·p0.9999: 19.251 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 4.287 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  12.926 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224445
  mean =      4.276 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3612 
    [ 2.500,  5.000) = 176799 
    [ 5.000,  7.500) = 42606 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     12.592 ms/op
     p(99.9900) =     24.186 ms/op
     p(99.9990) =     27.018 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 5.675 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  10.270 ms/op
                 existUser·p0.9999: 16.868 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 4.023 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.901 ms/op
                 existUser·p0.999:  11.496 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240741
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11222 
    [ 2.500,  5.000) = 199935 
    [ 5.000,  7.500) = 28408 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     10.785 ms/op
     p(99.9900) =     20.049 ms/op
     p(99.9990) =     21.685 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 6.579 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.012 ms/op
Iteration   1: 4.329 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   6.964 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 20.691 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 4.289 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  9.690 ms/op
                 getUser·p0.9999: 17.048 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 4.322 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 20.795 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222416
  mean =      4.313 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4803 
    [ 2.500,  5.000) = 170735 
    [ 5.000,  7.500) = 45403 
    [ 7.500, 10.000) = 1263 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.638 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 7.647 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.064 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.337 ±(99.9%) 0.019 ms/op
Iteration   1: 5.137 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  19.488 ms/op
                 listUser·p0.9999: 29.935 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 5.359 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 27.462 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 5.224 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.570 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  22.406 ms/op
                 listUser·p0.9999: 26.341 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183168
  mean =      5.239 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 87487 
    [ 5.000,  7.500) = 87470 
    [ 7.500, 10.000) = 6920 
    [10.000, 12.500) = 632 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     29.241 ms/op
     p(99.9990) =     30.327 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.762 ± 4.066  ops/ms
ClientGrpc.existUser                       thrpt       3   7.798 ± 1.798  ops/ms
ClientGrpc.getUser                         thrpt       3   7.235 ± 1.210  ops/ms
ClientGrpc.listUser                        thrpt       3   5.990 ± 4.306  ops/ms
ClientGrpc.createUser                       avgt       3   4.358 ± 2.602   ms/op
ClientGrpc.existUser                        avgt       3   4.006 ± 1.766   ms/op
ClientGrpc.getUser                          avgt       3   4.251 ± 0.752   ms/op
ClientGrpc.listUser                         avgt       3   5.114 ± 1.954   ms/op
ClientGrpc.createUser                     sample  224445   4.276 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.029           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.873           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.592           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.186           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  240741   3.990 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.897           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.785           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.049           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.955           ms/op
ClientGrpc.getUser                        sample  222416   4.313 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.061           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.929           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.546           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.758           ms/op
ClientGrpc.listUser                       sample  183168   5.239 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.249           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.856           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.241           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.409           ms/op
