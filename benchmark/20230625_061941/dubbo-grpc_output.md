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
# Warmup Iteration   1: 3.217 ops/ms
# Warmup Iteration   2: 7.382 ops/ms
# Warmup Iteration   3: 8.485 ops/ms
Iteration   1: 8.911 ops/ms
Iteration   2: 8.993 ops/ms
Iteration   3: 9.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.999 ±(99.9%) 1.654 ops/ms [Average]
  (min, avg, max) = (8.911, 8.999, 9.092), stdev = 0.091
  CI (99.9%): [7.345, 10.653] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.085 ops/ms
# Warmup Iteration   2: 8.941 ops/ms
# Warmup Iteration   3: 9.420 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.663 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.561 ±(99.9%) 1.679 ops/ms [Average]
  (min, avg, max) = (9.483, 9.561, 9.663), stdev = 0.092
  CI (99.9%): [7.882, 11.241] (assumes normal distribution)


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
# Warmup Iteration   1: 5.665 ops/ms
# Warmup Iteration   2: 8.624 ops/ms
# Warmup Iteration   3: 8.840 ops/ms
Iteration   1: 8.940 ops/ms
Iteration   2: 9.145 ops/ms
Iteration   3: 9.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.072 ±(99.9%) 2.092 ops/ms [Average]
  (min, avg, max) = (8.940, 9.072, 9.145), stdev = 0.115
  CI (99.9%): [6.980, 11.165] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ops/ms
# Warmup Iteration   2: 6.184 ops/ms
# Warmup Iteration   3: 6.891 ops/ms
Iteration   1: 6.896 ops/ms
Iteration   2: 6.895 ops/ms
Iteration   3: 6.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.915 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (6.895, 6.915, 6.954), stdev = 0.034
  CI (99.9%): [6.296, 7.535] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.181 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.003 ms/op
Iteration   1: 3.508 ±(99.9%) 0.004 ms/op
Iteration   2: 3.469 ±(99.9%) 0.003 ms/op
Iteration   3: 3.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.494 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (3.469, 3.494, 3.508), stdev = 0.022
  CI (99.9%): [3.099, 3.888] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.299 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.003 ms/op
Iteration   1: 3.385 ±(99.9%) 0.003 ms/op
Iteration   2: 3.316 ±(99.9%) 0.002 ms/op
Iteration   3: 3.317 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.339 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.316, 3.339, 3.385), stdev = 0.040
  CI (99.9%): [2.617, 4.062] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.124 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.004 ms/op
Iteration   1: 3.493 ±(99.9%) 0.003 ms/op
Iteration   2: 3.451 ±(99.9%) 0.003 ms/op
Iteration   3: 3.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.472 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.451, 3.472, 3.493), stdev = 0.021
  CI (99.9%): [3.093, 3.852] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.833 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.026 ms/op
Iteration   1: 4.558 ±(99.9%) 0.014 ms/op
Iteration   2: 4.508 ±(99.9%) 0.032 ms/op
Iteration   3: 4.496 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.521 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (4.496, 4.521, 4.558), stdev = 0.033
  CI (99.9%): [3.925, 5.117] (assumes normal distribution)


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.007 ms/op
Iteration   1: 3.472 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.829 ms/op
                 createUser·p0.9999: 15.247 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 3.407 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  7.013 ms/op
                 createUser·p0.9999: 15.172 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  7.685 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 277924
  mean =      3.453 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5877 
    [ 2.500,  5.000) = 269755 
    [ 5.000,  7.500) = 1997 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     30.979 ms/op
     p(99.9990) =     31.759 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.007 ms/op
Iteration   1: 3.283 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.846 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 15.835 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 3.301 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  7.430 ms/op
                 existUser·p0.9999: 17.368 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 3.300 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 25.218 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291501
  mean =      3.295 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14143 
    [ 2.500,  5.000) = 275218 
    [ 5.000,  7.500) = 1871 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     24.637 ms/op
     p(99.9990) =     27.170 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.008 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 15.793 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 3.408 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  7.810 ms/op
                 getUser·p0.9999: 15.585 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 3.425 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 20.151 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 277389
  mean =      3.461 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8692 
    [ 2.500,  5.000) = 265561 
    [ 5.000,  7.500) = 2639 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     20.921 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 6.575 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.012 ms/op
Iteration   1: 4.502 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  14.040 ms/op
                 listUser·p0.9999: 16.277 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 4.434 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  15.691 ms/op
                 listUser·p0.9999: 19.298 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.571 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.731 ms/op
                 listUser·p0.999:  18.352 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213123
  mean =      4.501 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 179073 
    [ 5.000,  7.500) = 30282 
    [ 7.500, 10.000) = 2865 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.429 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     28.006 ms/op
     p(99.9990) =     30.241 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.999 ± 1.654  ops/ms
ClientGrpc.existUser                       thrpt       3   9.561 ± 1.679  ops/ms
ClientGrpc.getUser                         thrpt       3   9.072 ± 2.092  ops/ms
ClientGrpc.listUser                        thrpt       3   6.915 ± 0.619  ops/ms
ClientGrpc.createUser                       avgt       3   3.494 ± 0.394   ms/op
ClientGrpc.existUser                        avgt       3   3.339 ± 0.722   ms/op
ClientGrpc.getUser                          avgt       3   3.472 ± 0.380   ms/op
ClientGrpc.listUser                         avgt       3   4.521 ± 0.596   ms/op
ClientGrpc.createUser                     sample  277924   3.453 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.627           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.979           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.818           ms/op
ClientGrpc.existUser                      sample  291501   3.295 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.332           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.637           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.296           ms/op
ClientGrpc.getUser                        sample  277389   3.461 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.778           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.499           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  213123   4.501 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.937           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.429           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.401           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.006           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.769           ms/op
