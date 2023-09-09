# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.481 ops/ms
# Warmup Iteration   2: 5.975 ops/ms
# Warmup Iteration   3: 9.189 ops/ms
Iteration   1: 9.358 ops/ms
Iteration   2: 9.671 ops/ms
Iteration   3: 9.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.625 ±(99.9%) 4.508 ops/ms [Average]
  (min, avg, max) = (9.358, 9.625, 9.845), stdev = 0.247
  CI (99.9%): [5.117, 14.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 8.967 ops/ms
# Warmup Iteration   3: 9.837 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.574 ops/ms
Iteration   3: 9.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.274 ±(99.9%) 6.304 ops/ms [Average]
  (min, avg, max) = (9.896, 10.274, 10.574), stdev = 0.346
  CI (99.9%): [3.970, 16.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ops/ms
# Warmup Iteration   2: 9.408 ops/ms
# Warmup Iteration   3: 9.829 ops/ms
Iteration   1: 9.530 ops/ms
Iteration   2: 9.793 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.650 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (9.530, 9.650, 9.793), stdev = 0.133
  CI (99.9%): [7.223, 12.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.491 ops/ms
# Warmup Iteration   2: 7.591 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.263 ops/ms
Iteration   2: 8.341 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.372 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (8.263, 8.372, 8.512), stdev = 0.127
  CI (99.9%): [6.051, 10.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.003 ms/op
Iteration   1: 3.262 ±(99.9%) 0.002 ms/op
Iteration   2: 3.254 ±(99.9%) 0.006 ms/op
Iteration   3: 3.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.243 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.214, 3.243, 3.262), stdev = 0.026
  CI (99.9%): [2.775, 3.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.208 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.006 ms/op
Iteration   1: 3.213 ±(99.9%) 0.006 ms/op
Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
Iteration   3: 3.184 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.191 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.174, 3.191, 3.213), stdev = 0.020
  CI (99.9%): [2.824, 3.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.419 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.002 ms/op
Iteration   1: 3.347 ±(99.9%) 0.004 ms/op
Iteration   2: 3.284 ±(99.9%) 0.004 ms/op
Iteration   3: 3.257 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.296 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.257, 3.296, 3.347), stdev = 0.046
  CI (99.9%): [2.451, 4.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.963 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.007 ms/op
Iteration   1: 3.929 ±(99.9%) 0.005 ms/op
Iteration   2: 3.799 ±(99.9%) 0.006 ms/op
Iteration   3: 3.754 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.827 ±(99.9%) 1.652 ms/op [Average]
  (min, avg, max) = (3.754, 3.827, 3.929), stdev = 0.091
  CI (99.9%): [2.176, 5.479] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.893 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.010 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.896 ms/op
                 createUser·p0.999:  12.364 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.381 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  15.401 ms/op
                 createUser·p0.9999: 34.079 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293284
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23816 
    [ 2.500,  5.000) = 263445 
    [ 5.000,  7.500) = 4616 
    [ 7.500, 10.000) = 960 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     33.085 ms/op
     p(99.9990) =     34.420 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.663 ms/op
                 existUser·p0.9999: 19.941 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.559 ms/op
                 existUser·p0.9999: 23.284 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299543
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21019 
    [ 2.500,  5.000) = 272023 
    [ 5.000,  7.500) = 5607 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.698 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     21.566 ms/op
     p(99.9990) =     23.659 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.372 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
Iteration   1: 3.305 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  14.540 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  11.289 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.550 ms/op
                 getUser·p0.999:  14.307 ms/op
                 getUser·p0.9999: 21.830 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290287
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10923 
    [ 2.500,  5.000) = 269507 
    [ 5.000,  7.500) = 8244 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     25.296 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.441 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.012 ms/op
Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  14.071 ms/op
                 listUser·p0.9999: 20.477 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 17.915 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.783 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  14.466 ms/op
                 listUser·p0.9999: 22.759 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250093
  mean =      3.835 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 239916 
    [ 5.000,  7.500) = 7258 
    [ 7.500, 10.000) = 1971 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     20.381 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.625 ± 4.508  ops/ms
ClientPb.existUser                       thrpt       3  10.274 ± 6.304  ops/ms
ClientPb.getUser                         thrpt       3   9.650 ± 2.427  ops/ms
ClientPb.listUser                        thrpt       3   8.372 ± 2.321  ops/ms
ClientPb.createUser                       avgt       3   3.243 ± 0.468   ms/op
ClientPb.existUser                        avgt       3   3.191 ± 0.367   ms/op
ClientPb.getUser                          avgt       3   3.296 ± 0.845   ms/op
ClientPb.listUser                         avgt       3   3.827 ± 1.652   ms/op
ClientPb.createUser                     sample  293284   3.273 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.464           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.085           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  299543   3.203 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.698           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.617           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.822           ms/op
ClientPb.getUser                        sample  290287   3.305 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.296           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.230           ms/op
ClientPb.listUser                       sample  250093   3.835 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.622           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.381           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
