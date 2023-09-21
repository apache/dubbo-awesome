# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ops/ms
# Warmup Iteration   2: 6.601 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.194 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.485 ±(99.9%) 6.892 ops/ms [Average]
  (min, avg, max) = (8.194, 8.485, 8.912), stdev = 0.378
  CI (99.9%): [1.594, 15.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.515 ops/ms
# Warmup Iteration   2: 8.403 ops/ms
# Warmup Iteration   3: 8.971 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.012 ops/ms
Iteration   3: 8.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.935 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (8.824, 8.935, 9.012), stdev = 0.098
  CI (99.9%): [7.140, 10.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.230 ops/ms
# Warmup Iteration   2: 8.119 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.721 ops/ms
Iteration   3: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.609 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (8.384, 8.609, 8.723), stdev = 0.195
  CI (99.9%): [5.044, 12.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ops/ms
# Warmup Iteration   2: 6.551 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 6.660 ops/ms
Iteration   2: 6.820 ops/ms
Iteration   3: 6.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.768 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (6.660, 6.768, 6.825), stdev = 0.094
  CI (99.9%): [5.062, 8.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.376 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.003 ms/op
Iteration   1: 3.764 ±(99.9%) 0.002 ms/op
Iteration   2: 3.883 ±(99.9%) 0.002 ms/op
Iteration   3: 3.781 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.809 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.764, 3.809, 3.883), stdev = 0.064
  CI (99.9%): [2.643, 4.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.095 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.005 ms/op
Iteration   1: 3.616 ±(99.9%) 0.003 ms/op
Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
Iteration   3: 3.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.523 ±(99.9%) 1.512 ms/op [Average]
  (min, avg, max) = (3.457, 3.523, 3.616), stdev = 0.083
  CI (99.9%): [2.011, 5.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.003 ms/op
Iteration   1: 3.779 ±(99.9%) 0.004 ms/op
Iteration   2: 3.715 ±(99.9%) 0.004 ms/op
Iteration   3: 3.712 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.735 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.712, 3.735, 3.779), stdev = 0.038
  CI (99.9%): [3.050, 4.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.660 ±(99.9%) 0.014 ms/op
Iteration   1: 4.660 ±(99.9%) 0.017 ms/op
Iteration   2: 4.733 ±(99.9%) 0.028 ms/op
Iteration   3: 4.654 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.683 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (4.654, 4.683, 4.733), stdev = 0.044
  CI (99.9%): [3.878, 5.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.009 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.776 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.845 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.515 ms/op
                 createUser·p0.999:  13.151 ms/op
                 createUser·p0.9999: 16.774 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 3.721 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.877 ms/op
                 createUser·p0.999:  9.143 ms/op
                 createUser·p0.9999: 25.376 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254114
  mean =      3.777 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5278 
    [ 2.500,  5.000) = 238629 
    [ 5.000,  7.500) = 8890 
    [ 7.500, 10.000) = 937 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.462 ms/op
     p(99.9000) =     12.841 ms/op
     p(99.9900) =     24.877 ms/op
     p(99.9990) =     25.491 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.007 ms/op
Iteration   1: 3.564 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.457 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  7.900 ms/op
                 existUser·p0.9999: 24.709 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.513 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.319 ms/op
                 existUser·p0.9999: 14.904 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  9.286 ms/op
                 existUser·p0.9999: 20.211 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273089
  mean =      3.516 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9848 
    [ 2.500,  5.000) = 257818 
    [ 5.000,  7.500) = 4780 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     21.541 ms/op
     p(99.9990) =     26.466 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.008 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  11.520 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 3.812 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.419 ms/op
                 getUser·p0.9999: 16.069 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250859
  mean =      3.827 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3090 
    [ 2.500,  5.000) = 238559 
    [ 5.000,  7.500) = 8194 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.225 ms/op
     p(99.9900) =     20.305 ms/op
     p(99.9990) =     21.905 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.664 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.056 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.012 ms/op
Iteration   1: 4.791 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  15.011 ms/op
                 listUser·p0.9999: 16.684 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.685 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 22.195 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 4.654 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  20.890 ms/op
                 listUser·p0.9999: 24.523 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203782
  mean =      4.709 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 221 
    [ 2.500,  5.000) = 159854 
    [ 5.000,  7.500) = 38886 
    [ 7.500, 10.000) = 3996 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     22.978 ms/op
     p(99.9990) =     27.837 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.485 ± 6.892  ops/ms
ClientGrpc.existUser                       thrpt       3   8.935 ± 1.795  ops/ms
ClientGrpc.getUser                         thrpt       3   8.609 ± 3.566  ops/ms
ClientGrpc.listUser                        thrpt       3   6.768 ± 1.706  ops/ms
ClientGrpc.createUser                       avgt       3   3.809 ± 1.167   ms/op
ClientGrpc.existUser                        avgt       3   3.523 ± 1.512   ms/op
ClientGrpc.getUser                          avgt       3   3.735 ± 0.685   ms/op
ClientGrpc.listUser                         avgt       3   4.683 ± 0.804   ms/op
ClientGrpc.createUser                     sample  254114   3.777 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.462           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.841           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.877           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  273089   3.516 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.457           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.962           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.541           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.903           ms/op
ClientGrpc.getUser                        sample  250859   3.827 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.867           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.054           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.305           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  203782   4.709 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.450           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.978           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
