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
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 5.377 ops/ms
# Warmup Iteration   3: 9.093 ops/ms
Iteration   1: 9.545 ops/ms
Iteration   2: 9.606 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.627 ±(99.9%) 1.708 ops/ms [Average]
  (min, avg, max) = (9.545, 9.627, 9.729), stdev = 0.094
  CI (99.9%): [7.919, 11.335] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ops/ms
# Warmup Iteration   2: 9.740 ops/ms
# Warmup Iteration   3: 9.696 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 10.051 ops/ms
Iteration   3: 10.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.093 ±(99.9%) 0.923 ops/ms [Average]
  (min, avg, max) = (10.051, 10.093, 10.149), stdev = 0.051
  CI (99.9%): [9.170, 11.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.497 ops/ms
# Warmup Iteration   2: 9.271 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 10.023 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 9.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.956 ±(99.9%) 3.045 ops/ms [Average]
  (min, avg, max) = (9.766, 9.956, 10.079), stdev = 0.167
  CI (99.9%): [6.911, 13.000] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.299 ops/ms
Iteration   2: 8.374 ops/ms
Iteration   3: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.347 ±(99.9%) 0.760 ops/ms [Average]
  (min, avg, max) = (8.299, 8.347, 8.374), stdev = 0.042
  CI (99.9%): [7.587, 9.106] (assumes normal distribution)


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
# Warmup Iteration   1: 8.598 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.004 ms/op
Iteration   1: 3.363 ±(99.9%) 0.002 ms/op
Iteration   2: 3.267 ±(99.9%) 0.002 ms/op
Iteration   3: 3.263 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.298 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.263, 3.298, 3.363), stdev = 0.057
  CI (99.9%): [2.267, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.002 ms/op
Iteration   1: 3.162 ±(99.9%) 0.003 ms/op
Iteration   2: 3.230 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.165 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.102, 3.165, 3.230), stdev = 0.064
  CI (99.9%): [1.996, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 7.588 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.001 ms/op
Iteration   1: 3.250 ±(99.9%) 0.003 ms/op
Iteration   2: 3.204 ±(99.9%) 0.003 ms/op
Iteration   3: 3.220 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.204, 3.224, 3.250), stdev = 0.023
  CI (99.9%): [2.797, 3.652] (assumes normal distribution)


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
# Warmup Iteration   1: 8.725 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.004 ms/op
Iteration   1: 3.827 ±(99.9%) 0.006 ms/op
Iteration   2: 3.771 ±(99.9%) 0.005 ms/op
Iteration   3: 3.796 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.798 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.771, 3.798, 3.827), stdev = 0.028
  CI (99.9%): [3.282, 4.314] (assumes normal distribution)


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
# Warmup Iteration   1: 8.122 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
Iteration   1: 3.288 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  18.276 ms/op
                 createUser·p0.9999: 20.128 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  19.557 ms/op
                 createUser·p0.9999: 23.933 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  16.159 ms/op
                 createUser·p0.9999: 22.342 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292290
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12815 
    [ 2.500,  5.000) = 275368 
    [ 5.000,  7.500) = 3153 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     17.849 ms/op
     p(99.9900) =     22.726 ms/op
     p(99.9990) =     25.398 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 7.292 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.177 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  15.696 ms/op
                 existUser·p0.9999: 19.396 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 20.998 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.356 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  11.687 ms/op
                 existUser·p0.9999: 20.666 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304341
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18180 
    [ 2.500,  5.000) = 281669 
    [ 5.000,  7.500) = 3694 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.485 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.683 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.370 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  18.350 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  17.845 ms/op
                 getUser·p0.9999: 21.483 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  14.857 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286648
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7887 
    [ 2.500,  5.000) = 269683 
    [ 5.000,  7.500) = 7868 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 190 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     17.280 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.363 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 8.870 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.010 ms/op
Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 25.362 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 3.853 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 15.199 ms/op
                 listUser·p1.00:   15.450 ms/op

Iteration   3: 3.805 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  14.319 ms/op
                 listUser·p0.9999: 16.849 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248872
  mean =      3.856 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 242519 
    [ 5.000,  7.500) = 4714 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.896 ms/op
     p(99.9900) =     22.904 ms/op
     p(99.9990) =     25.412 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.627 ± 1.708  ops/ms
ClientPb.existUser                       thrpt       3  10.093 ± 0.923  ops/ms
ClientPb.getUser                         thrpt       3   9.956 ± 3.045  ops/ms
ClientPb.listUser                        thrpt       3   8.347 ± 0.760  ops/ms
ClientPb.createUser                       avgt       3   3.298 ± 1.031   ms/op
ClientPb.existUser                        avgt       3   3.165 ± 1.169   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 0.427   ms/op
ClientPb.listUser                         avgt       3   3.798 ± 0.516   ms/op
ClientPb.createUser                     sample  292290   3.283 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.849           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.726           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.494           ms/op
ClientPb.existUser                      sample  304341   3.154 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.485           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.546           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.577           ms/op
ClientPb.getUser                        sample  286648   3.347 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.025           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.280           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.037           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.807           ms/op
ClientPb.listUser                       sample  248872   3.856 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.481           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.896           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.904           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
