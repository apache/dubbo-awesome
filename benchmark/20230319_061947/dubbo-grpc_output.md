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
# Warmup Iteration   1: 3.918 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.473 ±(99.9%) 3.392 ops/ms [Average]
  (min, avg, max) = (10.259, 10.473, 10.584), stdev = 0.186
  CI (99.9%): [7.082, 13.865] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.820 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.913 ops/ms
Iteration   2: 10.952 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.905 ±(99.9%) 0.924 ops/ms [Average]
  (min, avg, max) = (10.851, 10.905, 10.952), stdev = 0.051
  CI (99.9%): [9.981, 11.829] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.479 ops/ms
# Warmup Iteration   2: 9.870 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.286 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.315 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (10.286, 10.315, 10.358), stdev = 0.038
  CI (99.9%): [9.623, 11.008] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.924 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 7.380 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 8.029 ops/ms
Iteration   3: 7.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.854 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (7.704, 7.854, 8.029), stdev = 0.164
  CI (99.9%): [4.867, 10.841] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.030, 3.048, 3.082), stdev = 0.030
  CI (99.9%): [2.508, 3.588] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.003 ms/op
Iteration   1: 2.895 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.915 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (2.895, 2.929, 2.977), stdev = 0.043
  CI (99.9%): [2.145, 3.713] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.043, 3.074, 3.106), stdev = 0.032
  CI (99.9%): [2.496, 3.653] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.838 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.006 ms/op
Iteration   1: 4.236 ±(99.9%) 0.010 ms/op
Iteration   2: 4.056 ±(99.9%) 0.011 ms/op
Iteration   3: 4.092 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.128 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (4.056, 4.128, 4.236), stdev = 0.096
  CI (99.9%): [2.384, 5.871] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.369 ms/op
                 createUser·p0.9999: 23.210 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  10.579 ms/op
                 createUser·p0.9999: 15.097 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  14.101 ms/op
                 createUser·p0.9999: 24.764 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309451
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14707 
    [ 2.500,  5.000) = 293024 
    [ 5.000,  7.500) = 1142 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.094 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.279 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  11.181 ms/op
                 existUser·p0.9999: 20.332 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.428 ms/op
                 existUser·p0.999:  7.430 ms/op
                 existUser·p0.9999: 20.016 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  11.790 ms/op
                 existUser·p0.9999: 24.857 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307800
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10615 
    [ 2.500,  5.000) = 295043 
    [ 5.000,  7.500) = 1562 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     25.355 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.887 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.398 ms/op
                 getUser·p0.9999: 13.708 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  7.791 ms/op
                 getUser·p0.9999: 19.917 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 3.218 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.495 ms/op
                 getUser·p0.9999: 18.845 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301611
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10292 
    [ 2.500,  5.000) = 289371 
    [ 5.000,  7.500) = 1575 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.851 ms/op
     p(99.9900) =     19.060 ms/op
     p(99.9990) =     20.250 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 6.019 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.474 ±(99.9%) 0.014 ms/op
Iteration   1: 4.326 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 29.879 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 4.235 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.656 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 4.179 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.409 ms/op
                 listUser·p0.999:  17.763 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225915
  mean =      4.246 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1700 
    [ 2.500,  5.000) = 194118 
    [ 5.000,  7.500) = 27258 
    [ 7.500, 10.000) = 2250 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.731 ms/op
     p(99.9900) =     28.816 ms/op
     p(99.9990) =     30.130 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.473 ± 3.392  ops/ms
ClientGrpc.existUser                       thrpt       3  10.905 ± 0.924  ops/ms
ClientGrpc.getUser                         thrpt       3  10.315 ± 0.693  ops/ms
ClientGrpc.listUser                        thrpt       3   7.854 ± 2.987  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.540   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.784   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 0.579   ms/op
ClientGrpc.listUser                         avgt       3   4.128 ± 1.744   ms/op
ClientGrpc.createUser                     sample  309451   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  307800   3.117 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.371           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.233           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.657           ms/op
ClientGrpc.getUser                        sample  301611   3.181 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.851           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.060           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  225915   4.246 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.919           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.043           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.766           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.731           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.816           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.179           ms/op
