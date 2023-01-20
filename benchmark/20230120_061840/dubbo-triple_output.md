# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.541 ops/ms
# Warmup Iteration   2: 6.227 ops/ms
# Warmup Iteration   3: 9.306 ops/ms
Iteration   1: 9.791 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 9.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.913 ±(99.9%) 5.880 ops/ms [Average]
  (min, avg, max) = (9.669, 9.913, 10.278), stdev = 0.322
  CI (99.9%): [4.033, 15.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ops/ms
# Warmup Iteration   2: 9.730 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.626 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (10.561, 10.626, 10.682), stdev = 0.061
  CI (99.9%): [9.518, 11.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ops/ms
# Warmup Iteration   2: 9.094 ops/ms
# Warmup Iteration   3: 9.911 ops/ms
Iteration   1: 10.268 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.149 ±(99.9%) 5.665 ops/ms [Average]
  (min, avg, max) = (9.796, 10.149, 10.382), stdev = 0.311
  CI (99.9%): [4.484, 15.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.337 ops/ms
# Warmup Iteration   2: 7.338 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.253 ops/ms
Iteration   3: 8.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.296 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (8.253, 8.296, 8.354), stdev = 0.052
  CI (99.9%): [7.344, 9.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.495 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.005 ms/op
Iteration   1: 3.131 ±(99.9%) 0.010 ms/op
Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
Iteration   3: 3.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.118 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.089, 3.118, 3.133), stdev = 0.024
  CI (99.9%): [2.671, 3.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.059, 3.082, 3.094), stdev = 0.020
  CI (99.9%): [2.716, 3.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.002 ms/op
Iteration   1: 3.223 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.005 ms/op
Iteration   3: 3.262 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.223, 3.238, 3.262), stdev = 0.021
  CI (99.9%): [2.855, 3.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.793 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.007 ms/op
Iteration   1: 3.785 ±(99.9%) 0.005 ms/op
Iteration   2: 3.711 ±(99.9%) 0.005 ms/op
Iteration   3: 3.745 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.747 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.711, 3.747, 3.785), stdev = 0.037
  CI (99.9%): [3.073, 4.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.450 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  9.898 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.685 ms/op
                 createUser·p0.95:   4.627 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  16.680 ms/op
                 createUser·p0.9999: 19.636 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 19.517 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304046
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24207 
    [ 2.500,  5.000) = 272609 
    [ 5.000,  7.500) = 6345 
    [ 7.500, 10.000) = 421 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 205 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.132 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.853 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.997 ms/op
                 existUser·p0.9999: 23.273 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 21.790 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  13.297 ms/op
                 existUser·p0.9999: 22.012 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309177
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18992 
    [ 2.500,  5.000) = 282565 
    [ 5.000,  7.500) = 6846 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     22.252 ms/op
     p(99.9990) =     23.721 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.382 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.251 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  13.024 ms/op
                 getUser·p0.9999: 22.320 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 22.118 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   5.258 ms/op
                 getUser·p0.999:  10.282 ms/op
                 getUser·p0.9999: 24.545 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304402
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20309 
    [ 2.500,  5.000) = 276840 
    [ 5.000,  7.500) = 6450 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     12.635 ms/op
     p(99.9900) =     23.550 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.563 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 3.690 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.540 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 16.080 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.622 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.386 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256194
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 248146 
    [ 5.000,  7.500) = 5629 
    [ 7.500, 10.000) = 1703 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     24.152 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.913 ± 5.880  ops/ms
ClientPb.existUser                       thrpt       3  10.626 ± 1.108  ops/ms
ClientPb.getUser                         thrpt       3  10.149 ± 5.665  ops/ms
ClientPb.listUser                        thrpt       3   8.296 ± 0.952  ops/ms
ClientPb.createUser                       avgt       3   3.118 ± 0.447   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 0.366   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 0.383   ms/op
ClientPb.listUser                         avgt       3   3.747 ± 0.674   ms/op
ClientPb.createUser                     sample  304046   3.153 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.466           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.366           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  309177   3.105 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.895           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.252           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.921           ms/op
ClientPb.getUser                        sample  304402   3.153 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.635           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.723           ms/op
ClientPb.listUser                       sample  256194   3.743 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.572           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
