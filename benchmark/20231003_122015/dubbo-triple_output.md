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
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 4.483 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 8.893 ops/ms
Iteration   2: 8.698 ops/ms
Iteration   3: 9.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.917 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (8.698, 8.917, 9.159), stdev = 0.231
  CI (99.9%): [4.697, 13.136] (assumes normal distribution)


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
# Warmup Iteration   1: 2.436 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 9.337 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.494 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (9.328, 9.494, 9.645), stdev = 0.159
  CI (99.9%): [6.593, 12.394] (assumes normal distribution)


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
# Warmup Iteration   1: 2.764 ops/ms
# Warmup Iteration   2: 8.403 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 9.147 ops/ms
Iteration   3: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.081 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (9.008, 9.081, 9.147), stdev = 0.070
  CI (99.9%): [7.800, 10.363] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.637 ops/ms
# Warmup Iteration   2: 6.979 ops/ms
# Warmup Iteration   3: 7.184 ops/ms
Iteration   1: 7.409 ops/ms
Iteration   2: 7.619 ops/ms
Iteration   3: 7.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.520 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (7.409, 7.520, 7.619), stdev = 0.106
  CI (99.9%): [5.593, 9.447] (assumes normal distribution)


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
# Warmup Iteration   1: 12.580 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.006 ms/op
Iteration   1: 3.521 ±(99.9%) 0.006 ms/op
Iteration   2: 3.526 ±(99.9%) 0.005 ms/op
Iteration   3: 3.590 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.521, 3.546, 3.590), stdev = 0.039
  CI (99.9%): [2.837, 4.254] (assumes normal distribution)


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
# Warmup Iteration   1: 10.177 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.003 ms/op
Iteration   1: 3.433 ±(99.9%) 0.004 ms/op
Iteration   2: 3.349 ±(99.9%) 0.005 ms/op
Iteration   3: 3.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.388 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.349, 3.388, 3.433), stdev = 0.042
  CI (99.9%): [2.616, 4.159] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.545 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.003 ms/op
Iteration   1: 3.555 ±(99.9%) 0.005 ms/op
Iteration   2: 3.642 ±(99.9%) 0.006 ms/op
Iteration   3: 3.486 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.561 ±(99.9%) 1.423 ms/op [Average]
  (min, avg, max) = (3.486, 3.561, 3.642), stdev = 0.078
  CI (99.9%): [2.138, 4.984] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.158 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.007 ms/op
Iteration   1: 4.183 ±(99.9%) 0.006 ms/op
Iteration   2: 4.196 ±(99.9%) 0.006 ms/op
Iteration   3: 4.150 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.176 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (4.150, 4.176, 4.196), stdev = 0.024
  CI (99.9%): [3.741, 4.612] (assumes normal distribution)


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
# Warmup Iteration   1: 9.987 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.011 ms/op
Iteration   1: 3.557 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  15.845 ms/op
                 createUser·p0.9999: 26.248 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   2: 3.447 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   6.451 ms/op
                 createUser·p0.999:  23.069 ms/op
                 createUser·p0.9999: 26.235 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.533 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  15.459 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273182
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5135 
    [ 2.500,  5.000) = 259593 
    [ 5.000,  7.500) = 6824 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.855 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.942 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  18.755 ms/op
                 existUser·p0.9999: 21.173 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.514 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  21.725 ms/op
                 existUser·p0.9999: 23.849 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.400 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  16.300 ms/op
                 existUser·p0.9999: 27.190 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279266
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7367 
    [ 2.500,  5.000) = 263459 
    [ 5.000,  7.500) = 6447 
    [ 7.500, 10.000) = 1281 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     25.498 ms/op
     p(99.9990) =     27.382 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 9.550 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.012 ms/op
Iteration   1: 3.603 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  21.111 ms/op
                 getUser·p0.9999: 24.158 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  22.315 ms/op
                 getUser·p0.9999: 24.736 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  12.139 ms/op
                 getUser·p0.9999: 27.108 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268643
  mean =      3.573 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3535 
    [ 2.500,  5.000) = 254232 
    [ 5.000,  7.500) = 8569 
    [ 7.500, 10.000) = 1642 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     21.409 ms/op
     p(99.9900) =     25.858 ms/op
     p(99.9990) =     27.618 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 11.414 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.014 ms/op
Iteration   1: 4.222 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.908 ms/op
                 listUser·p0.999:  21.806 ms/op
                 listUser·p0.9999: 28.386 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 4.198 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  15.786 ms/op
                 listUser·p0.9999: 25.720 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 4.196 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  16.668 ms/op
                 listUser·p0.9999: 35.021 ms/op
                 listUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228227
  mean =      4.205 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 216953 
    [ 5.000,  7.500) = 7641 
    [ 7.500, 10.000) = 2452 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     17.854 ms/op
     p(99.9900) =     33.042 ms/op
     p(99.9990) =     35.877 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.917 ± 4.220  ops/ms
ClientPb.existUser                       thrpt       3   9.494 ± 2.901  ops/ms
ClientPb.getUser                         thrpt       3   9.081 ± 1.282  ops/ms
ClientPb.listUser                        thrpt       3   7.520 ± 1.927  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 0.708   ms/op
ClientPb.existUser                        avgt       3   3.388 ± 0.771   ms/op
ClientPb.getUser                          avgt       3   3.561 ± 1.423   ms/op
ClientPb.listUser                         avgt       3   4.176 ± 0.436   ms/op
ClientPb.createUser                     sample  273182   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.204           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.083           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  279266   3.436 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.986           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.498           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  268643   3.573 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.761           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.274           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.409           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.858           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  228227   4.205 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.073           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.854           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.042           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
