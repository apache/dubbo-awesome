# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.252 ops/ms
# Warmup Iteration   2: 5.995 ops/ms
# Warmup Iteration   3: 8.771 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 9.328 ops/ms
Iteration   3: 9.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.239 ±(99.9%) 4.320 ops/ms [Average]
  (min, avg, max) = (8.970, 9.239, 9.418), stdev = 0.237
  CI (99.9%): [4.919, 13.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 9.073 ops/ms
# Warmup Iteration   3: 9.617 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 10.022 ops/ms
Iteration   3: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.948 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (9.879, 9.948, 10.022), stdev = 0.072
  CI (99.9%): [8.641, 11.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.162 ops/ms
Iteration   2: 9.699 ops/ms
Iteration   3: 9.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.388 ±(99.9%) 5.077 ops/ms [Average]
  (min, avg, max) = (9.162, 9.388, 9.699), stdev = 0.278
  CI (99.9%): [4.311, 14.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 7.228 ops/ms
# Warmup Iteration   3: 7.753 ops/ms
Iteration   1: 8.144 ops/ms
Iteration   2: 7.962 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.077 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (7.962, 8.077, 8.144), stdev = 0.100
  CI (99.9%): [6.258, 9.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.901 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.007 ms/op
Iteration   1: 3.410 ±(99.9%) 0.008 ms/op
Iteration   2: 3.446 ±(99.9%) 0.007 ms/op
Iteration   3: 3.242 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.366 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (3.242, 3.366, 3.446), stdev = 0.109
  CI (99.9%): [1.382, 5.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.144 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.003 ms/op
Iteration   1: 3.326 ±(99.9%) 0.004 ms/op
Iteration   2: 3.256 ±(99.9%) 0.006 ms/op
Iteration   3: 3.221 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.268 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.221, 3.268, 3.326), stdev = 0.054
  CI (99.9%): [2.289, 4.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.074 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
Iteration   1: 3.431 ±(99.9%) 0.008 ms/op
Iteration   2: 3.302 ±(99.9%) 0.006 ms/op
Iteration   3: 3.501 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.411 ±(99.9%) 1.845 ms/op [Average]
  (min, avg, max) = (3.302, 3.411, 3.501), stdev = 0.101
  CI (99.9%): [1.566, 5.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.007 ms/op
Iteration   1: 4.098 ±(99.9%) 0.009 ms/op
Iteration   2: 3.936 ±(99.9%) 0.013 ms/op
Iteration   3: 4.035 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.023 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.936, 4.023, 4.098), stdev = 0.082
  CI (99.9%): [2.534, 5.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.376 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.934 ms/op
                 createUser·p0.999:  20.068 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.420 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  20.366 ms/op
                 createUser·p0.9999: 25.130 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  20.764 ms/op
                 createUser·p0.9999: 24.836 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276375
  mean =      3.471 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3868 
    [ 2.500,  5.000) = 265713 
    [ 5.000,  7.500) = 5803 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     25.436 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.432 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
Iteration   1: 3.395 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  18.510 ms/op
                 existUser·p0.9999: 21.402 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.346 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  20.317 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  12.400 ms/op
                 existUser·p0.9999: 26.746 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283721
  mean =      3.382 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10801 
    [ 2.500,  5.000) = 267503 
    [ 5.000,  7.500) = 4455 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     25.436 ms/op
     p(99.9990) =     27.071 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.537 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.669 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.357 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.795 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 25.863 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.340 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  19.877 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.414 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 25.776 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276683
  mean =      3.469 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5218 
    [ 2.500,  5.000) = 260841 
    [ 5.000,  7.500) = 9577 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.847 ms/op
     p(99.9900) =     25.472 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.172 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.014 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  22.354 ms/op
                 listUser·p0.9999: 26.153 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.384 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.824 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236727
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 227326 
    [ 5.000,  7.500) = 7294 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     24.705 ms/op
     p(99.9990) =     26.568 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.239 ± 4.320  ops/ms
ClientPb.existUser                       thrpt       3   9.948 ± 1.307  ops/ms
ClientPb.getUser                         thrpt       3   9.388 ± 5.077  ops/ms
ClientPb.listUser                        thrpt       3   8.077 ± 1.818  ops/ms
ClientPb.createUser                       avgt       3   3.366 ± 1.984   ms/op
ClientPb.existUser                        avgt       3   3.268 ± 0.979   ms/op
ClientPb.getUser                          avgt       3   3.411 ± 1.845   ms/op
ClientPb.listUser                         avgt       3   4.023 ± 1.489   ms/op
ClientPb.createUser                     sample  276375   3.471 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.031           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.543           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  283721   3.382 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.436           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  276683   3.469 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.357           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.847           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.472           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  236727   4.054 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.705           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
