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
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 5.929 ops/ms
# Warmup Iteration   3: 8.854 ops/ms
Iteration   1: 9.592 ops/ms
Iteration   2: 9.471 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.553 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (9.471, 9.553, 9.597), stdev = 0.072
  CI (99.9%): [8.248, 10.859] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 9.385 ops/ms
# Warmup Iteration   3: 9.476 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.816 ±(99.9%) 5.752 ops/ms [Average]
  (min, avg, max) = (9.485, 9.816, 10.113), stdev = 0.315
  CI (99.9%): [4.064, 15.567] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.018 ops/ms
# Warmup Iteration   2: 8.685 ops/ms
# Warmup Iteration   3: 9.357 ops/ms
Iteration   1: 9.775 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.722 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (9.664, 9.722, 9.775), stdev = 0.056
  CI (99.9%): [8.708, 10.735] (assumes normal distribution)


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
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 7.008 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 8.027 ops/ms
Iteration   2: 7.876 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.989 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (7.876, 7.989, 8.065), stdev = 0.100
  CI (99.9%): [6.166, 9.813] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.537 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.003 ms/op
Iteration   1: 3.299 ±(99.9%) 0.003 ms/op
Iteration   2: 3.325 ±(99.9%) 0.007 ms/op
Iteration   3: 3.294 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.306 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.294, 3.306, 3.325), stdev = 0.017
  CI (99.9%): [2.999, 3.613] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.432 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.004 ms/op
Iteration   2: 3.244 ±(99.9%) 0.006 ms/op
Iteration   3: 3.168 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.199 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (3.168, 3.199, 3.244), stdev = 0.040
  CI (99.9%): [2.467, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.004 ms/op
Iteration   1: 3.336 ±(99.9%) 0.003 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.306 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.329 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.306, 3.329, 3.345), stdev = 0.021
  CI (99.9%): [2.953, 3.706] (assumes normal distribution)


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
# Warmup Iteration   1: 9.660 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.004 ms/op
Iteration   1: 3.957 ±(99.9%) 0.004 ms/op
Iteration   2: 3.977 ±(99.9%) 0.005 ms/op
Iteration   3: 3.958 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.964 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.957, 3.964, 3.977), stdev = 0.011
  CI (99.9%): [3.761, 4.167] (assumes normal distribution)


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
# Warmup Iteration   1: 9.718 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
Iteration   1: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.278 ms/op
                 createUser·p0.999:  17.008 ms/op
                 createUser·p0.9999: 19.635 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  18.721 ms/op
                 createUser·p0.9999: 21.084 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.379 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 20.843 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288270
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10168 
    [ 2.500,  5.000) = 270649 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 221 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     20.819 ms/op
     p(99.9990) =     24.595 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 7.434 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.010 ms/op
Iteration   1: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  11.884 ms/op
                 existUser·p0.9999: 20.906 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  16.068 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.268 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  17.402 ms/op
                 existUser·p0.9999: 23.902 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294308
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15608 
    [ 2.500,  5.000) = 270618 
    [ 5.000,  7.500) = 6891 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     15.363 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     24.485 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 7.747 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  16.149 ms/op
                 getUser·p0.9999: 20.925 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  15.942 ms/op
                 getUser·p0.9999: 18.261 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 28.433 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288981
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7676 
    [ 2.500,  5.000) = 271900 
    [ 5.000,  7.500) = 7656 
    [ 7.500, 10.000) = 1063 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     20.782 ms/op
     p(99.9990) =     29.404 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 10.532 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.875 ms/op
                 listUser·p0.999:  17.090 ms/op
                 listUser·p0.9999: 21.652 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  14.671 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.956 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237801
  mean =      4.033 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177 
    [ 2.500,  5.000) = 227717 
    [ 5.000,  7.500) = 7143 
    [ 7.500, 10.000) = 1822 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 370 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     15.093 ms/op
     p(99.9900) =     20.422 ms/op
     p(99.9990) =     22.434 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.553 ± 1.305  ops/ms
ClientPb.existUser                       thrpt       3   9.816 ± 5.752  ops/ms
ClientPb.getUser                         thrpt       3   9.722 ± 1.013  ops/ms
ClientPb.listUser                        thrpt       3   7.989 ± 1.823  ops/ms
ClientPb.createUser                       avgt       3   3.306 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   3.199 ± 0.732   ms/op
ClientPb.getUser                          avgt       3   3.329 ± 0.377   ms/op
ClientPb.listUser                         avgt       3   3.964 ± 0.203   ms/op
ClientPb.createUser                     sample  288270   3.329 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.819           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.773           ms/op
ClientPb.existUser                      sample  294308   3.260 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.363           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.774           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.674           ms/op
ClientPb.getUser                        sample  288981   3.319 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.292           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.782           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  237801   4.033 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.479           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.422           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.479           ms/op
