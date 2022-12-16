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
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 5.468 ops/ms
# Warmup Iteration   3: 9.390 ops/ms
Iteration   1: 9.419 ops/ms
Iteration   2: 9.855 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.879 ±(99.9%) 8.611 ops/ms [Average]
  (min, avg, max) = (9.419, 9.879, 10.363), stdev = 0.472
  CI (99.9%): [1.268, 18.490] (assumes normal distribution)


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
# Warmup Iteration   1: 3.660 ops/ms
# Warmup Iteration   2: 9.578 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 9.919 ops/ms
Iteration   2: 10.317 ops/ms
Iteration   3: 9.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.064 ±(99.9%) 4.009 ops/ms [Average]
  (min, avg, max) = (9.919, 10.064, 10.317), stdev = 0.220
  CI (99.9%): [6.055, 14.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ops/ms
# Warmup Iteration   2: 8.908 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.118 ops/ms
Iteration   2: 10.143 ops/ms
Iteration   3: 9.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.037 ±(99.9%) 2.973 ops/ms [Average]
  (min, avg, max) = (9.849, 10.037, 10.143), stdev = 0.163
  CI (99.9%): [7.063, 13.010] (assumes normal distribution)


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
# Warmup Iteration   1: 3.195 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 8.649 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.663 ±(99.9%) 0.244 ops/ms [Average]
  (min, avg, max) = (8.649, 8.663, 8.675), stdev = 0.013
  CI (99.9%): [8.419, 8.907] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.879 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.007 ms/op
Iteration   1: 3.220 ±(99.9%) 0.005 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.142 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.072, 3.142, 3.220), stdev = 0.075
  CI (99.9%): [1.779, 4.505] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.039 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.047 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.033, 3.047, 3.070), stdev = 0.020
  CI (99.9%): [2.689, 3.405] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.613 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.002 ms/op
Iteration   1: 3.162 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
Iteration   3: 3.126 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.101 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.015, 3.101, 3.162), stdev = 0.077
  CI (99.9%): [1.700, 4.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.009 ms/op
Iteration   1: 3.715 ±(99.9%) 0.005 ms/op
Iteration   2: 3.715 ±(99.9%) 0.006 ms/op
Iteration   3: 3.653 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.694 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.653, 3.694, 3.715), stdev = 0.036
  CI (99.9%): [3.041, 4.348] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.175 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.009 ms/op
Iteration   1: 3.098 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  18.244 ms/op
                 createUser·p0.9999: 25.942 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  12.893 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  13.081 ms/op
                 createUser·p0.9999: 18.957 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302046
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22707 
    [ 2.500,  5.000) = 274735 
    [ 5.000,  7.500) = 3987 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     24.857 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  17.248 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.509 ms/op
                 existUser·p0.9999: 21.412 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.025 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315480
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22948 
    [ 2.500,  5.000) = 287466 
    [ 5.000,  7.500) = 4366 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.939 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.552 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.138 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  18.217 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 3.082 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  21.987 ms/op
                 getUser·p0.9999: 24.397 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  9.507 ms/op
                 getUser·p0.9999: 18.256 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304413
  mean =      3.152 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15051 
    [ 2.500,  5.000) = 284356 
    [ 5.000,  7.500) = 4236 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     24.219 ms/op
     p(99.9990) =     24.771 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.392 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.013 ms/op
Iteration   1: 3.650 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.936 ms/op
                 listUser·p0.9999: 18.857 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.730 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.417 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 15.424 ms/op
                 listUser·p1.00:   15.499 ms/op

Iteration   3: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258343
  mean =      3.716 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 250046 
    [ 5.000,  7.500) = 6826 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     20.518 ms/op
     p(99.9990) =     20.671 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.879 ± 8.611  ops/ms
ClientPb.existUser                       thrpt       3  10.064 ± 4.009  ops/ms
ClientPb.getUser                         thrpt       3  10.037 ± 2.973  ops/ms
ClientPb.listUser                        thrpt       3   8.663 ± 0.244  ops/ms
ClientPb.createUser                       avgt       3   3.142 ± 1.363   ms/op
ClientPb.existUser                        avgt       3   3.047 ± 0.358   ms/op
ClientPb.getUser                          avgt       3   3.101 ± 1.401   ms/op
ClientPb.listUser                         avgt       3   3.694 ± 0.653   ms/op
ClientPb.createUser                     sample  302046   3.174 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.059           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.857           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.411           ms/op
ClientPb.existUser                      sample  315480   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.025           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.037           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.577           ms/op
ClientPb.getUser                        sample  304413   3.152 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.646           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.219           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  258343   3.716 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.944           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
