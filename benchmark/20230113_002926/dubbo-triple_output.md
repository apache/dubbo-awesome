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
# Warmup Iteration   1: 1.934 ops/ms
# Warmup Iteration   2: 4.597 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.159 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.344 ±(99.9%) 2.924 ops/ms [Average]
  (min, avg, max) = (9.159, 9.344, 9.437), stdev = 0.160
  CI (99.9%): [6.420, 12.268] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.829 ops/ms
# Warmup Iteration   2: 8.600 ops/ms
# Warmup Iteration   3: 9.941 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.503 ops/ms
Iteration   3: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.329 ±(99.9%) 12.685 ops/ms [Average]
  (min, avg, max) = (8.563, 9.329, 9.921), stdev = 0.695
  CI (99.9%): [≈ 0, 22.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.744 ops/ms
# Warmup Iteration   2: 6.768 ops/ms
# Warmup Iteration   3: 8.699 ops/ms
Iteration   1: 9.268 ops/ms
Iteration   2: 9.069 ops/ms
Iteration   3: 9.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.300 ±(99.9%) 4.536 ops/ms [Average]
  (min, avg, max) = (9.069, 9.300, 9.563), stdev = 0.249
  CI (99.9%): [4.764, 13.837] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.752 ops/ms
# Warmup Iteration   2: 6.990 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 7.958 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.928 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (7.849, 7.928, 7.977), stdev = 0.069
  CI (99.9%): [6.661, 9.195] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.605 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.007 ms/op
Iteration   1: 3.613 ±(99.9%) 0.005 ms/op
Iteration   2: 3.377 ±(99.9%) 0.006 ms/op
Iteration   3: 3.455 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.482 ±(99.9%) 2.189 ms/op [Average]
  (min, avg, max) = (3.377, 3.482, 3.613), stdev = 0.120
  CI (99.9%): [1.292, 5.671] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.117 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.003 ms/op
Iteration   1: 3.487 ±(99.9%) 0.007 ms/op
Iteration   2: 3.443 ±(99.9%) 0.004 ms/op
Iteration   3: 3.293 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.407 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (3.293, 3.407, 3.487), stdev = 0.101
  CI (99.9%): [1.557, 5.258] (assumes normal distribution)


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
# Warmup Iteration   1: 10.131 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.004 ms/op
Iteration   1: 3.485 ±(99.9%) 0.007 ms/op
Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
Iteration   3: 3.398 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.408 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.341, 3.408, 3.485), stdev = 0.073
  CI (99.9%): [2.084, 4.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.887 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.009 ms/op
Iteration   1: 3.941 ±(99.9%) 0.013 ms/op
Iteration   2: 3.924 ±(99.9%) 0.013 ms/op
Iteration   3: 3.979 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.948 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.924, 3.948, 3.979), stdev = 0.028
  CI (99.9%): [3.433, 4.463] (assumes normal distribution)


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
# Warmup Iteration   1: 10.489 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.014 ms/op
Iteration   1: 3.378 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.704 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 21.677 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.030 ms/op
                 createUser·p0.999:  20.847 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.388 ms/op
                 createUser·p0.9999: 26.908 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282497
  mean =      3.397 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11755 
    [ 2.500,  5.000) = 264520 
    [ 5.000,  7.500) = 5024 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     19.186 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     30.387 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.158 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
Iteration   1: 3.363 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  11.319 ms/op
                 existUser·p0.9999: 26.001 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.469 ms/op
                 existUser·p0.999:  13.021 ms/op
                 existUser·p0.9999: 24.617 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  17.236 ms/op
                 existUser·p0.9999: 27.789 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289097
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5740 
    [ 2.500,  5.000) = 278217 
    [ 5.000,  7.500) = 3954 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     11.353 ms/op
     p(99.9900) =     26.840 ms/op
     p(99.9990) =     27.987 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 9.712 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.010 ms/op
Iteration   1: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  19.274 ms/op
                 getUser·p0.9999: 23.223 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.555 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  11.650 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  22.469 ms/op
                 getUser·p0.9999: 27.283 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276009
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7776 
    [ 2.500,  5.000) = 258244 
    [ 5.000,  7.500) = 7734 
    [ 7.500, 10.000) = 1734 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     25.460 ms/op
     p(99.9990) =     28.025 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.138 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.014 ms/op
Iteration   1: 4.139 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  21.552 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.609 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.241 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 21.002 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229999
  mean =      4.171 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 215751 
    [ 5.000,  7.500) = 10763 
    [ 7.500, 10.000) = 2380 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.451 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.344 ±  2.924  ops/ms
ClientPb.existUser                       thrpt       3   9.329 ± 12.685  ops/ms
ClientPb.getUser                         thrpt       3   9.300 ±  4.536  ops/ms
ClientPb.listUser                        thrpt       3   7.928 ±  1.267  ops/ms
ClientPb.createUser                       avgt       3   3.482 ±  2.189   ms/op
ClientPb.existUser                        avgt       3   3.407 ±  1.851   ms/op
ClientPb.getUser                          avgt       3   3.408 ±  1.324   ms/op
ClientPb.listUser                         avgt       3   3.948 ±  0.515   ms/op
ClientPb.createUser                     sample  282497   3.397 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.186            ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.132            ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999            ms/op
ClientPb.existUser                      sample  289097   3.317 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865            ms/op
ClientPb.existUser:existUser·p0.999     sample          11.353            ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.840            ms/op
ClientPb.existUser:existUser·p1.00      sample          28.213            ms/op
ClientPb.getUser                        sample  276009   3.476 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.299            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.550            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.460            ms/op
ClientPb.getUser:getUser·p1.00          sample          28.148            ms/op
ClientPb.listUser                       sample  229999   4.171 ±  0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.989            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.292            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.192            ms/op
ClientPb.listUser:listUser·p0.999       sample          17.695            ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.805            ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526            ms/op
