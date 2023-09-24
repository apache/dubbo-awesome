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
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 3.605 ops/ms
# Warmup Iteration   3: 7.389 ops/ms
Iteration   1: 7.007 ops/ms
Iteration   2: 7.439 ops/ms
Iteration   3: 7.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.240 ±(99.9%) 3.972 ops/ms [Average]
  (min, avg, max) = (7.007, 7.240, 7.439), stdev = 0.218
  CI (99.9%): [3.268, 11.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 6.033 ops/ms
# Warmup Iteration   3: 7.322 ops/ms
Iteration   1: 7.842 ops/ms
Iteration   2: 7.998 ops/ms
Iteration   3: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.864 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (7.751, 7.864, 7.998), stdev = 0.125
  CI (99.9%): [5.579, 10.148] (assumes normal distribution)


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
# Warmup Iteration   1: 1.880 ops/ms
# Warmup Iteration   2: 6.003 ops/ms
# Warmup Iteration   3: 7.087 ops/ms
Iteration   1: 7.073 ops/ms
Iteration   2: 7.371 ops/ms
Iteration   3: 7.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.218 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (7.073, 7.218, 7.371), stdev = 0.149
  CI (99.9%): [4.499, 9.937] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.927 ops/ms
# Warmup Iteration   2: 5.195 ops/ms
# Warmup Iteration   3: 6.275 ops/ms
Iteration   1: 6.239 ops/ms
Iteration   2: 6.079 ops/ms
Iteration   3: 6.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.245 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (6.079, 6.245, 6.417), stdev = 0.169
  CI (99.9%): [3.166, 9.324] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.102 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.358 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.443 ±(99.9%) 0.009 ms/op
Iteration   1: 4.490 ±(99.9%) 0.005 ms/op
Iteration   2: 4.333 ±(99.9%) 0.005 ms/op
Iteration   3: 4.189 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.337 ±(99.9%) 2.744 ms/op [Average]
  (min, avg, max) = (4.189, 4.337, 4.490), stdev = 0.150
  CI (99.9%): [1.593, 7.081] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.297 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.005 ms/op
Iteration   1: 4.039 ±(99.9%) 0.007 ms/op
Iteration   2: 4.130 ±(99.9%) 0.007 ms/op
Iteration   3: 4.112 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.093 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (4.039, 4.093, 4.130), stdev = 0.048
  CI (99.9%): [3.211, 4.976] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.523 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.341 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.006 ms/op
Iteration   1: 4.467 ±(99.9%) 0.007 ms/op
Iteration   2: 4.381 ±(99.9%) 0.008 ms/op
Iteration   3: 4.334 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.394 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (4.334, 4.394, 4.467), stdev = 0.067
  CI (99.9%): [3.164, 5.624] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.768 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.006 ms/op
Iteration   1: 4.886 ±(99.9%) 0.011 ms/op
Iteration   2: 5.012 ±(99.9%) 0.005 ms/op
Iteration   3: 5.275 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.058 ±(99.9%) 3.615 ms/op [Average]
  (min, avg, max) = (4.886, 5.058, 5.275), stdev = 0.198
  CI (99.9%): [1.442, 8.673] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.675 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.147 ±(99.9%) 0.028 ms/op
Iteration   1: 4.325 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   9.115 ms/op
                 createUser·p0.999:  25.131 ms/op
                 createUser·p0.9999: 27.662 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 4.417 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  18.599 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 4.242 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  31.049 ms/op
                 createUser·p0.9999: 33.650 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 221917
  mean =      4.327 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 297 
    [ 2.500,  5.000) = 194410 
    [ 5.000,  7.500) = 22332 
    [ 7.500, 10.000) = 3461 
    [10.000, 12.500) = 758 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     26.119 ms/op
     p(99.9900) =     33.097 ms/op
     p(99.9990) =     35.703 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.890 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.313 ±(99.9%) 0.016 ms/op
Iteration   1: 4.364 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  17.587 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.712 ms/op
                 existUser·p0.999:  13.919 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   3: 4.214 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  31.687 ms/op
                 existUser·p0.9999: 34.985 ms/op
                 existUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 227618
  mean =      4.215 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 204819 
    [ 5.000,  7.500) = 17795 
    [ 7.500, 10.000) = 3413 
    [10.000, 12.500) = 774 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     17.941 ms/op
     p(99.9900) =     33.963 ms/op
     p(99.9990) =     36.122 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.633 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.018 ms/op
Iteration   1: 4.458 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  25.389 ms/op
                 getUser·p0.9999: 35.968 ms/op
                 getUser·p1.00:   37.487 ms/op

Iteration   2: 4.308 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.152 ms/op
                 getUser·p0.99:   8.542 ms/op
                 getUser·p0.999:  14.327 ms/op
                 getUser·p0.9999: 28.335 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   3: 4.350 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.447 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  30.409 ms/op
                 getUser·p0.9999: 33.620 ms/op
                 getUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 219494
  mean =      4.371 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 190695 
    [ 5.000,  7.500) = 22871 
    [ 7.500, 10.000) = 4175 
    [10.000, 12.500) = 862 
    [12.500, 15.000) = 392 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     25.641 ms/op
     p(99.9900) =     35.393 ms/op
     p(99.9990) =     36.361 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.459 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.951 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.274 ±(99.9%) 0.023 ms/op
Iteration   1: 5.130 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  27.143 ms/op
                 listUser·p0.9999: 29.476 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   2: 5.050 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   10.384 ms/op
                 listUser·p0.999:  23.451 ms/op
                 listUser·p0.9999: 25.844 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   3: 5.066 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.916 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  18.838 ms/op
                 listUser·p0.9999: 24.096 ms/op
                 listUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 188739
  mean =      5.082 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 129453 
    [ 5.000,  7.500) = 50549 
    [ 7.500, 10.000) = 6275 
    [10.000, 12.500) = 1412 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     23.676 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.667 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.240 ± 3.972  ops/ms
ClientPb.existUser                       thrpt       3   7.864 ± 2.284  ops/ms
ClientPb.getUser                         thrpt       3   7.218 ± 2.719  ops/ms
ClientPb.listUser                        thrpt       3   6.245 ± 3.079  ops/ms
ClientPb.createUser                       avgt       3   4.337 ± 2.744   ms/op
ClientPb.existUser                        avgt       3   4.093 ± 0.882   ms/op
ClientPb.getUser                          avgt       3   4.394 ± 1.230   ms/op
ClientPb.listUser                         avgt       3   5.058 ± 3.615   ms/op
ClientPb.createUser                     sample  221917   4.327 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.077           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.119           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.717           ms/op
ClientPb.existUser                      sample  227618   4.215 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.618           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.941           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.963           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.028           ms/op
ClientPb.getUser                        sample  219494   4.371 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.447           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.257           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.641           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.393           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.487           ms/op
ClientPb.listUser                       sample  188739   5.082 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.013           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.676           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.164           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.015           ms/op
