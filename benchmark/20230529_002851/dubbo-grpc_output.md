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
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 7.015 ops/ms
# Warmup Iteration   3: 8.571 ops/ms
Iteration   1: 9.027 ops/ms
Iteration   2: 9.125 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.127 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (9.027, 9.127, 9.230), stdev = 0.101
  CI (99.9%): [7.277, 10.977] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.145 ops/ms
# Warmup Iteration   2: 9.007 ops/ms
# Warmup Iteration   3: 9.435 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.622 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.407 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (9.229, 9.407, 9.622), stdev = 0.199
  CI (99.9%): [5.784, 13.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.741 ops/ms
# Warmup Iteration   2: 8.457 ops/ms
# Warmup Iteration   3: 8.844 ops/ms
Iteration   1: 9.019 ops/ms
Iteration   2: 8.896 ops/ms
Iteration   3: 9.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.986 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (8.896, 8.986, 9.042), stdev = 0.078
  CI (99.9%): [7.558, 10.413] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ops/ms
# Warmup Iteration   2: 6.755 ops/ms
# Warmup Iteration   3: 6.924 ops/ms
Iteration   1: 7.244 ops/ms
Iteration   2: 6.969 ops/ms
Iteration   3: 6.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.043 ±(99.9%) 3.201 ops/ms [Average]
  (min, avg, max) = (6.918, 7.043, 7.244), stdev = 0.175
  CI (99.9%): [3.842, 10.245] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.004 ms/op
Iteration   1: 3.546 ±(99.9%) 0.005 ms/op
Iteration   2: 3.542 ±(99.9%) 0.004 ms/op
Iteration   3: 3.579 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.556 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.542, 3.556, 3.579), stdev = 0.020
  CI (99.9%): [3.191, 3.920] (assumes normal distribution)


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
# Warmup Iteration   1: 4.908 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.007 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
Iteration   3: 3.409 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.383 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.342, 3.383, 3.409), stdev = 0.036
  CI (99.9%): [2.734, 4.031] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.977 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.009 ms/op
Iteration   1: 3.561 ±(99.9%) 0.004 ms/op
Iteration   2: 3.448 ±(99.9%) 0.005 ms/op
Iteration   3: 3.529 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.512 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.448, 3.512, 3.561), stdev = 0.058
  CI (99.9%): [2.449, 4.575] (assumes normal distribution)


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
# Warmup Iteration   1: 6.580 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.018 ms/op
Iteration   1: 4.668 ±(99.9%) 0.013 ms/op
Iteration   2: 4.585 ±(99.9%) 0.009 ms/op
Iteration   3: 4.763 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.672 ±(99.9%) 1.626 ms/op [Average]
  (min, avg, max) = (4.585, 4.672, 4.763), stdev = 0.089
  CI (99.9%): [3.045, 6.298] (assumes normal distribution)


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
# Warmup Iteration   1: 5.308 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.010 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  8.950 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  8.639 ms/op
                 createUser·p0.9999: 17.008 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   3: 3.597 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  17.431 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264465
  mean =      3.632 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6671 
    [ 2.500,  5.000) = 252589 
    [ 5.000,  7.500) = 4545 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.052 ms/op
     p(99.9900) =     24.332 ms/op
     p(99.9990) =     24.948 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.006 ms/op
Iteration   1: 3.522 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.031 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.411 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.969 ms/op
                 existUser·p0.9999: 16.230 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 3.477 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 17.623 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276708
  mean =      3.469 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11632 
    [ 2.500,  5.000) = 260475 
    [ 5.000,  7.500) = 3969 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.791 ms/op
     p(99.9900) =     17.792 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.179 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.009 ms/op
Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  11.954 ms/op
                 getUser·p0.9999: 22.560 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  7.360 ms/op
                 getUser·p0.9999: 18.515 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.618 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.483 ms/op
                 getUser·p0.9999: 19.732 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263132
  mean =      3.646 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8001 
    [ 2.500,  5.000) = 248035 
    [ 5.000,  7.500) = 6342 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.927 ms/op
     p(99.9900) =     22.010 ms/op
     p(99.9990) =     22.739 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 7.218 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.687 ±(99.9%) 0.013 ms/op
Iteration   1: 4.668 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.934 ms/op
                 listUser·p0.9999: 17.306 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.651 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  18.522 ms/op
                 listUser·p0.9999: 26.100 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.701 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.666 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 23.147 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205254
  mean =      4.674 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 260 
    [ 2.500,  5.000) = 167368 
    [ 5.000,  7.500) = 33458 
    [ 7.500, 10.000) = 3577 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.476 ms/op
     p(99.9990) =     26.470 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.127 ± 1.850  ops/ms
ClientGrpc.existUser                       thrpt       3   9.407 ± 3.624  ops/ms
ClientGrpc.getUser                         thrpt       3   8.986 ± 1.427  ops/ms
ClientGrpc.listUser                        thrpt       3   7.043 ± 3.201  ops/ms
ClientGrpc.createUser                       avgt       3   3.556 ± 0.364   ms/op
ClientGrpc.existUser                        avgt       3   3.383 ± 0.648   ms/op
ClientGrpc.getUser                          avgt       3   3.512 ± 1.063   ms/op
ClientGrpc.listUser                         avgt       3   4.672 ± 1.626   ms/op
ClientGrpc.createUser                     sample  264465   3.632 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.909           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.052           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.035           ms/op
ClientGrpc.existUser                      sample  276708   3.469 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  263132   3.646 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.817           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.010           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.265           ms/op
ClientGrpc.listUser                       sample  205254   4.674 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.476           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
