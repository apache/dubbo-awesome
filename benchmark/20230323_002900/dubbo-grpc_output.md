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
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 6.607 ops/ms
# Warmup Iteration   3: 7.692 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.999 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (7.918, 7.999, 8.124), stdev = 0.110
  CI (99.9%): [5.987, 10.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ops/ms
# Warmup Iteration   2: 7.807 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 8.709 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 8.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.869 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (8.709, 8.869, 9.034), stdev = 0.163
  CI (99.9%): [5.904, 11.833] (assumes normal distribution)


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
# Warmup Iteration   1: 5.394 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 7.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.069 ±(99.9%) 3.565 ops/ms [Average]
  (min, avg, max) = (7.844, 8.069, 8.197), stdev = 0.195
  CI (99.9%): [4.504, 11.635] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 5.746 ops/ms
# Warmup Iteration   3: 6.329 ops/ms
Iteration   1: 6.307 ops/ms
Iteration   2: 6.340 ops/ms
Iteration   3: 6.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.286 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (6.213, 6.286, 6.340), stdev = 0.066
  CI (99.9%): [5.087, 7.485] (assumes normal distribution)


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
# Warmup Iteration   1: 6.082 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.003 ms/op
Iteration   1: 3.968 ±(99.9%) 0.003 ms/op
Iteration   2: 3.997 ±(99.9%) 0.003 ms/op
Iteration   3: 3.833 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.933 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.833, 3.933, 3.997), stdev = 0.087
  CI (99.9%): [2.340, 5.525] (assumes normal distribution)


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.002 ms/op
Iteration   1: 3.678 ±(99.9%) 0.003 ms/op
Iteration   2: 3.522 ±(99.9%) 0.003 ms/op
Iteration   3: 3.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.579 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.522, 3.579, 3.678), stdev = 0.087
  CI (99.9%): [2.000, 5.157] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.859 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.926 ±(99.9%) 0.002 ms/op
Iteration   2: 3.863 ±(99.9%) 0.004 ms/op
Iteration   3: 3.812 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.867 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.812, 3.867, 3.926), stdev = 0.057
  CI (99.9%): [2.826, 4.908] (assumes normal distribution)


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
# Warmup Iteration   1: 6.414 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.033 ±(99.9%) 0.020 ms/op
Iteration   1: 4.833 ±(99.9%) 0.013 ms/op
Iteration   2: 4.813 ±(99.9%) 0.010 ms/op
Iteration   3: 4.891 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.845 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (4.813, 4.845, 4.891), stdev = 0.040
  CI (99.9%): [4.108, 5.583] (assumes normal distribution)


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
# Warmup Iteration   1: 6.124 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
Iteration   1: 3.973 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 18.905 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  17.543 ms/op
                 createUser·p0.9999: 24.568 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 24.371 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242270
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3214 
    [ 2.500,  5.000) = 217861 
    [ 5.000,  7.500) = 19916 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     14.807 ms/op
     p(99.9900) =     24.077 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.711 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.010 ms/op
Iteration   1: 3.686 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  11.865 ms/op
                 existUser·p0.9999: 13.784 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 3.710 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  12.219 ms/op
                 existUser·p0.9999: 17.379 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 3.713 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 18.970 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259250
  mean =      3.703 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7473 
    [ 2.500,  5.000) = 238439 
    [ 5.000,  7.500) = 12055 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     19.832 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 5.955 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
Iteration   1: 3.871 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  13.125 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 3.779 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.181 ms/op
                 getUser·p0.9999: 18.433 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.975 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  12.913 ms/op
                 getUser·p0.9999: 20.771 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247684
  mean =      3.873 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5046 
    [ 2.500,  5.000) = 224879 
    [ 5.000,  7.500) = 16798 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     25.115 ms/op
     p(99.9990) =     26.478 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 6.871 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.490 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.979 ±(99.9%) 0.016 ms/op
Iteration   1: 5.293 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 17.364 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 5.015 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.234 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 19.509 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 4.971 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  17.978 ms/op
                 listUser·p0.9999: 21.345 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188549
  mean =      5.089 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 290 
    [ 2.500,  5.000) = 106151 
    [ 5.000,  7.500) = 72639 
    [ 7.500, 10.000) = 8179 
    [10.000, 12.500) = 802 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     22.223 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.999 ± 2.012  ops/ms
ClientGrpc.existUser                       thrpt       3   8.869 ± 2.965  ops/ms
ClientGrpc.getUser                         thrpt       3   8.069 ± 3.565  ops/ms
ClientGrpc.listUser                        thrpt       3   6.286 ± 1.199  ops/ms
ClientGrpc.createUser                       avgt       3   3.933 ± 1.593   ms/op
ClientGrpc.existUser                        avgt       3   3.579 ± 1.578   ms/op
ClientGrpc.getUser                          avgt       3   3.867 ± 1.041   ms/op
ClientGrpc.listUser                         avgt       3   4.845 ± 0.738   ms/op
ClientGrpc.createUser                     sample  242270   3.965 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.973           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.077           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  259250   3.703 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.866           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.026           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.302           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.309           ms/op
ClientGrpc.getUser                        sample  247684   3.873 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.722           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.218           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.928           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.115           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.608           ms/op
ClientGrpc.listUser                       sample  188549   5.089 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.015           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.504           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.349           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
