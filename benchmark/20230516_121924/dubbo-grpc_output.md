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
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 6.399 ops/ms
# Warmup Iteration   3: 7.062 ops/ms
Iteration   1: 7.694 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.876 ±(99.9%) 3.848 ops/ms [Average]
  (min, avg, max) = (7.694, 7.876, 8.107), stdev = 0.211
  CI (99.9%): [4.029, 11.724] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.185 ops/ms
# Warmup Iteration   2: 7.590 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.586 ops/ms
Iteration   3: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.446 ±(99.9%) 4.447 ops/ms [Average]
  (min, avg, max) = (8.164, 8.446, 8.587), stdev = 0.244
  CI (99.9%): [3.998, 12.893] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.376 ops/ms
# Warmup Iteration   2: 7.423 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.873 ops/ms
Iteration   2: 7.692 ops/ms
Iteration   3: 8.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.973 ±(99.9%) 6.227 ops/ms [Average]
  (min, avg, max) = (7.692, 7.973, 8.353), stdev = 0.341
  CI (99.9%): [1.746, 14.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ops/ms
# Warmup Iteration   2: 5.507 ops/ms
# Warmup Iteration   3: 5.499 ops/ms
Iteration   1: 5.721 ops/ms
Iteration   2: 6.020 ops/ms
Iteration   3: 6.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.930 ±(99.9%) 3.308 ops/ms [Average]
  (min, avg, max) = (5.721, 5.930, 6.048), stdev = 0.181
  CI (99.9%): [2.622, 9.238] (assumes normal distribution)


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
# Warmup Iteration   1: 6.486 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.011 ms/op
Iteration   1: 4.240 ±(99.9%) 0.004 ms/op
Iteration   2: 4.084 ±(99.9%) 0.003 ms/op
Iteration   3: 4.181 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.168 ±(99.9%) 1.443 ms/op [Average]
  (min, avg, max) = (4.084, 4.168, 4.240), stdev = 0.079
  CI (99.9%): [2.726, 5.611] (assumes normal distribution)


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
# Warmup Iteration   1: 5.574 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.004 ms/op
Iteration   1: 3.672 ±(99.9%) 0.004 ms/op
Iteration   2: 3.775 ±(99.9%) 0.003 ms/op
Iteration   3: 3.673 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.706 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.672, 3.706, 3.775), stdev = 0.059
  CI (99.9%): [2.628, 4.785] (assumes normal distribution)


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
# Warmup Iteration   1: 5.616 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.004 ms/op
Iteration   1: 3.830 ±(99.9%) 0.004 ms/op
Iteration   2: 3.972 ±(99.9%) 0.003 ms/op
Iteration   3: 3.859 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.887 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.830, 3.887, 3.972), stdev = 0.075
  CI (99.9%): [2.516, 5.258] (assumes normal distribution)


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
# Warmup Iteration   1: 7.718 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.403 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.128 ±(99.9%) 0.012 ms/op
Iteration   1: 4.913 ±(99.9%) 0.026 ms/op
Iteration   2: 4.916 ±(99.9%) 0.012 ms/op
Iteration   3: 5.114 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.981 ±(99.9%) 2.105 ms/op [Average]
  (min, avg, max) = (4.913, 4.981, 5.114), stdev = 0.115
  CI (99.9%): [2.876, 7.086] (assumes normal distribution)


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
# Warmup Iteration   1: 5.748 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  13.550 ms/op
                 createUser·p0.9999: 16.415 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 3.959 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 24.082 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 241556
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9618 
    [ 2.500,  5.000) = 211331 
    [ 5.000,  7.500) = 18334 
    [ 7.500, 10.000) = 1702 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     23.676 ms/op
     p(99.9990) =     24.404 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 5.473 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  11.525 ms/op
                 existUser·p0.9999: 18.545 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 3.804 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 16.019 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   3: 3.846 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  10.614 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247874
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8548 
    [ 2.500,  5.000) = 221007 
    [ 5.000,  7.500) = 16119 
    [ 7.500, 10.000) = 1742 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     11.569 ms/op
     p(99.9900) =     22.074 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 5.715 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.372 ms/op
                 getUser·p0.999:  15.221 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 23.381 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 4.105 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  13.127 ms/op
                 getUser·p0.9999: 29.098 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235088
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5599 
    [ 2.500,  5.000) = 205775 
    [ 5.000,  7.500) = 21363 
    [ 7.500, 10.000) = 1766 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     13.252 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     29.850 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 7.240 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.021 ms/op
Iteration   1: 5.384 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  17.092 ms/op
                 listUser·p0.9999: 19.337 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 5.095 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  22.622 ms/op
                 listUser·p0.9999: 24.862 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   3: 5.236 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  30.540 ms/op
                 listUser·p0.9999: 40.691 ms/op
                 listUser·p1.00:   41.484 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183177
  mean =      5.236 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 104272 
    [ 5.000, 10.000) = 76235 
    [10.000, 15.000) = 2247 
    [15.000, 20.000) = 260 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     19.217 ms/op
     p(99.9900) =     40.066 ms/op
     p(99.9990) =     41.430 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.876 ± 3.848  ops/ms
ClientGrpc.existUser                       thrpt       3   8.446 ± 4.447  ops/ms
ClientGrpc.getUser                         thrpt       3   7.973 ± 6.227  ops/ms
ClientGrpc.listUser                        thrpt       3   5.930 ± 3.308  ops/ms
ClientGrpc.createUser                       avgt       3   4.168 ± 1.443   ms/op
ClientGrpc.existUser                        avgt       3   3.706 ± 1.078   ms/op
ClientGrpc.getUser                          avgt       3   3.887 ± 1.371   ms/op
ClientGrpc.listUser                         avgt       3   4.981 ± 2.105   ms/op
ClientGrpc.createUser                     sample  241556   3.973 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.621           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.676           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.543           ms/op
ClientGrpc.existUser                      sample  247874   3.872 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.818           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.074           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  235088   4.081 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.252           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.770           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.950           ms/op
ClientGrpc.listUser                       sample  183177   5.236 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.217           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          40.066           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          41.484           ms/op
