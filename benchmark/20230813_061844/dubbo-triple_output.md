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
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 4.824 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 8.865 ops/ms
Iteration   2: 9.158 ops/ms
Iteration   3: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.065 ±(99.9%) 3.156 ops/ms [Average]
  (min, avg, max) = (8.865, 9.065, 9.172), stdev = 0.173
  CI (99.9%): [5.909, 12.221] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.909 ops/ms
# Warmup Iteration   2: 8.596 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.707 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.725 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (9.673, 9.725, 9.794), stdev = 0.063
  CI (99.9%): [8.580, 10.869] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 8.234 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 9.240 ops/ms
Iteration   2: 9.156 ops/ms
Iteration   3: 8.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.022 ±(99.9%) 5.618 ops/ms [Average]
  (min, avg, max) = (8.670, 9.022, 9.240), stdev = 0.308
  CI (99.9%): [3.404, 14.640] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 6.711 ops/ms
# Warmup Iteration   3: 7.441 ops/ms
Iteration   1: 7.493 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 4.618 ops/ms [Average]
  (min, avg, max) = (7.493, 7.780, 7.971), stdev = 0.253
  CI (99.9%): [3.162, 12.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.690 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.008 ms/op
Iteration   1: 3.530 ±(99.9%) 0.002 ms/op
Iteration   2: 3.465 ±(99.9%) 0.004 ms/op
Iteration   3: 3.440 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.440, 3.478, 3.530), stdev = 0.046
  CI (99.9%): [2.631, 4.326] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.006 ms/op
Iteration   1: 3.401 ±(99.9%) 0.006 ms/op
Iteration   2: 3.245 ±(99.9%) 0.006 ms/op
Iteration   3: 3.408 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 1.675 ms/op [Average]
  (min, avg, max) = (3.245, 3.351, 3.408), stdev = 0.092
  CI (99.9%): [1.676, 5.026] (assumes normal distribution)


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
# Warmup Iteration   1: 9.287 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.007 ms/op
Iteration   1: 3.525 ±(99.9%) 0.004 ms/op
Iteration   2: 3.451 ±(99.9%) 0.006 ms/op
Iteration   3: 3.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.451, 3.502, 3.529), stdev = 0.044
  CI (99.9%): [2.705, 4.298] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.544 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.989 ±(99.9%) 0.013 ms/op
Iteration   2: 4.048 ±(99.9%) 0.008 ms/op
Iteration   3: 4.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.029 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.989, 4.029, 4.049), stdev = 0.035
  CI (99.9%): [3.398, 4.659] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.986 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
Iteration   1: 3.465 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 24.870 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  22.919 ms/op
                 createUser·p0.9999: 26.625 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  21.987 ms/op
                 createUser·p0.9999: 27.495 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272558
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8104 
    [ 2.500,  5.000) = 256763 
    [ 5.000,  7.500) = 6009 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     26.124 ms/op
     p(99.9990) =     32.230 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.346 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.009 ms/op
Iteration   1: 3.460 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.790 ms/op
                 existUser·p0.999:  20.033 ms/op
                 existUser·p0.9999: 23.315 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.364 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  21.753 ms/op
                 existUser·p0.9999: 24.641 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  13.048 ms/op
                 existUser·p0.9999: 26.669 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283050
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12832 
    [ 2.500,  5.000) = 261397 
    [ 5.000,  7.500) = 6934 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     25.211 ms/op
     p(99.9990) =     27.367 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 10.085 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.012 ms/op
Iteration   1: 3.726 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.886 ms/op
                 getUser·p0.999:  21.596 ms/op
                 getUser·p0.9999: 25.652 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   2: 3.488 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  21.946 ms/op
                 getUser·p0.9999: 32.009 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.588 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.735 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  23.387 ms/op
                 getUser·p0.9999: 27.877 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266777
  mean =      3.598 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7487 
    [ 2.500,  5.000) = 245972 
    [ 5.000,  7.500) = 11144 
    [ 7.500, 10.000) = 1551 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     21.871 ms/op
     p(99.9900) =     31.599 ms/op
     p(99.9990) =     33.444 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 10.856 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.014 ms/op
Iteration   1: 4.220 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  20.046 ms/op
                 listUser·p0.9999: 23.457 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  19.368 ms/op
                 listUser·p0.9999: 24.554 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 4.187 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  14.751 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228870
  mean =      4.190 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 217731 
    [ 5.000,  7.500) = 7392 
    [ 7.500, 10.000) = 2380 
    [10.000, 12.500) = 681 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     17.601 ms/op
     p(99.9900) =     23.498 ms/op
     p(99.9990) =     24.599 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.065 ± 3.156  ops/ms
ClientPb.existUser                       thrpt       3   9.725 ± 1.144  ops/ms
ClientPb.getUser                         thrpt       3   9.022 ± 5.618  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 4.618  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 0.847   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 1.675   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 0.796   ms/op
ClientPb.listUser                         avgt       3   4.029 ± 0.630   ms/op
ClientPb.createUser                     sample  272558   3.517 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  283050   3.389 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  266777   3.598 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.871           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  228870   4.190 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.498           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
