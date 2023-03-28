# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 6.569 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 8.200 ops/ms
Iteration   2: 8.353 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.222 ±(99.9%) 2.223 ops/ms [Average]
  (min, avg, max) = (8.112, 8.222, 8.353), stdev = 0.122
  CI (99.9%): [5.999, 10.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.529 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 8.680 ops/ms
Iteration   1: 8.722 ops/ms
Iteration   2: 8.683 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.682 ±(99.9%) 0.734 ops/ms [Average]
  (min, avg, max) = (8.641, 8.682, 8.722), stdev = 0.040
  CI (99.9%): [7.949, 9.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.162 ops/ms
# Warmup Iteration   2: 7.901 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.290 ops/ms
Iteration   3: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.208 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (8.164, 8.208, 8.290), stdev = 0.071
  CI (99.9%): [6.905, 9.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ops/ms
# Warmup Iteration   2: 6.051 ops/ms
# Warmup Iteration   3: 6.524 ops/ms
Iteration   1: 6.507 ops/ms
Iteration   2: 6.208 ops/ms
Iteration   3: 6.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.353 ±(99.9%) 2.731 ops/ms [Average]
  (min, avg, max) = (6.208, 6.353, 6.507), stdev = 0.150
  CI (99.9%): [3.623, 9.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.007 ms/op
Iteration   1: 3.932 ±(99.9%) 0.003 ms/op
Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
Iteration   3: 3.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.891 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.843, 3.891, 3.932), stdev = 0.045
  CI (99.9%): [3.075, 4.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.003 ms/op
Iteration   1: 3.624 ±(99.9%) 0.004 ms/op
Iteration   2: 3.644 ±(99.9%) 0.003 ms/op
Iteration   3: 3.728 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.665 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.624, 3.665, 3.728), stdev = 0.055
  CI (99.9%): [2.663, 4.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.004 ms/op
Iteration   1: 4.105 ±(99.9%) 0.005 ms/op
Iteration   2: 3.930 ±(99.9%) 0.003 ms/op
Iteration   3: 3.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.974 ±(99.9%) 2.096 ms/op [Average]
  (min, avg, max) = (3.888, 3.974, 4.105), stdev = 0.115
  CI (99.9%): [1.878, 6.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.137 ±(99.9%) 0.020 ms/op
Iteration   1: 5.054 ±(99.9%) 0.013 ms/op
Iteration   2: 5.098 ±(99.9%) 0.014 ms/op
Iteration   3: 4.955 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.036 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (4.955, 5.036, 5.098), stdev = 0.073
  CI (99.9%): [3.704, 6.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.863 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.013 ms/op
Iteration   1: 3.786 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.319 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 16.795 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  10.993 ms/op
                 createUser·p0.9999: 16.772 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.038 ms/op
                 createUser·p0.999:  9.630 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251975
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9403 
    [ 2.500,  5.000) = 224948 
    [ 5.000,  7.500) = 15536 
    [ 7.500, 10.000) = 1707 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     20.166 ms/op
     p(99.9990) =     21.789 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.442 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.011 ms/op
Iteration   1: 3.606 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   6.875 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 17.630 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.741 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  11.584 ms/op
                 existUser·p0.9999: 32.309 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 3.709 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  12.889 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260468
  mean =      3.684 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8958 
    [ 2.500,  5.000) = 236912 
    [ 5.000,  7.500) = 12687 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     11.772 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.876 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.012 ms/op
Iteration   1: 3.830 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  10.854 ms/op
                 getUser·p0.9999: 16.711 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.755 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 22.068 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.852 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  13.336 ms/op
                 getUser·p0.9999: 23.321 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251814
  mean =      3.812 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11189 
    [ 2.500,  5.000) = 221746 
    [ 5.000,  7.500) = 17000 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.625 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.279 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.434 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.211 ±(99.9%) 0.020 ms/op
Iteration   1: 5.098 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.913 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 25.799 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 5.405 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.425 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  23.482 ms/op
                 listUser·p0.9999: 32.440 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   3: 5.348 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.616 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  28.398 ms/op
                 listUser·p0.9999: 39.146 ms/op
                 listUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181761
  mean =      5.280 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 99752 
    [ 5.000, 10.000) = 79058 
    [10.000, 15.000) = 2585 
    [15.000, 20.000) = 87 
    [20.000, 25.000) = 153 
    [25.000, 30.000) = 70 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     32.861 ms/op
     p(99.9990) =     40.824 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.222 ± 2.223  ops/ms
ClientGrpc.existUser                       thrpt       3   8.682 ± 0.734  ops/ms
ClientGrpc.getUser                         thrpt       3   8.208 ± 1.303  ops/ms
ClientGrpc.listUser                        thrpt       3   6.353 ± 2.731  ops/ms
ClientGrpc.createUser                       avgt       3   3.891 ± 0.816   ms/op
ClientGrpc.existUser                        avgt       3   3.665 ± 1.002   ms/op
ClientGrpc.getUser                          avgt       3   3.974 ± 2.096   ms/op
ClientGrpc.listUser                         avgt       3   5.036 ± 1.332   ms/op
ClientGrpc.createUser                     sample  251975   3.811 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.403           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.166           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  260468   3.684 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.772           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.836           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.817           ms/op
ClientGrpc.getUser                        sample  251814   3.812 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.143           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.823           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.658           ms/op
ClientGrpc.listUser                       sample  181761   5.280 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.425           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.577           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.861           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          42.271           ms/op
