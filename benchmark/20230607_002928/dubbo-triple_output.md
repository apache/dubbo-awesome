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
# Warmup Iteration   1: 2.430 ops/ms
# Warmup Iteration   2: 5.589 ops/ms
# Warmup Iteration   3: 9.159 ops/ms
Iteration   1: 9.429 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.716 ±(99.9%) 5.794 ops/ms [Average]
  (min, avg, max) = (9.429, 9.716, 10.057), stdev = 0.318
  CI (99.9%): [3.922, 15.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 8.903 ops/ms
# Warmup Iteration   3: 10.091 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 9.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.204 ±(99.9%) 6.491 ops/ms [Average]
  (min, avg, max) = (9.826, 10.204, 10.533), stdev = 0.356
  CI (99.9%): [3.713, 16.695] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.612 ops/ms
Iteration   1: 9.581 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 10.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.906 ±(99.9%) 5.158 ops/ms [Average]
  (min, avg, max) = (9.581, 9.906, 10.094), stdev = 0.283
  CI (99.9%): [4.748, 15.064] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.274 ops/ms
# Warmup Iteration   2: 7.642 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.645 ops/ms
Iteration   2: 8.691 ops/ms
Iteration   3: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.615 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (8.508, 8.615, 8.691), stdev = 0.095
  CI (99.9%): [6.881, 10.349] (assumes normal distribution)


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
# Warmup Iteration   1: 9.416 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.005 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
Iteration   2: 3.287 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.177 ±(99.9%) 1.741 ms/op [Average]
  (min, avg, max) = (3.117, 3.177, 3.287), stdev = 0.095
  CI (99.9%): [1.436, 4.918] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.403 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.006 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (2.963, 3.006, 3.034), stdev = 0.038
  CI (99.9%): [2.321, 3.691] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.006 ms/op
Iteration   1: 3.217 ±(99.9%) 0.003 ms/op
Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
Iteration   3: 3.213 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.190 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.141, 3.190, 3.217), stdev = 0.043
  CI (99.9%): [2.408, 3.972] (assumes normal distribution)


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
# Warmup Iteration   1: 8.695 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.006 ms/op
Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
Iteration   2: 3.872 ±(99.9%) 0.005 ms/op
Iteration   3: 3.734 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.795 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (3.734, 3.795, 3.872), stdev = 0.070
  CI (99.9%): [2.514, 5.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.131 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.009 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 24.099 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.741 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  10.685 ms/op
                 createUser·p0.9999: 24.346 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  14.606 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298172
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26060 
    [ 2.500,  5.000) = 265476 
    [ 5.000,  7.500) = 5716 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.644 ms/op
     p(99.9900) =     23.965 ms/op
     p(99.9990) =     24.947 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 8.435 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.631 ms/op
                 existUser·p0.9999: 23.531 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 25.293 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.501 ms/op
                 existUser·p0.9999: 20.696 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308373
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31162 
    [ 2.500,  5.000) = 272460 
    [ 5.000,  7.500) = 3767 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     26.042 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 9.187 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.011 ms/op
Iteration   1: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  16.886 ms/op
                 getUser·p0.9999: 21.114 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  16.098 ms/op
                 getUser·p0.9999: 22.316 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297892
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13780 
    [ 2.500,  5.000) = 277315 
    [ 5.000,  7.500) = 5628 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     15.534 ms/op
     p(99.9900) =     26.359 ms/op
     p(99.9990) =     28.345 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 9.188 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.013 ms/op
Iteration   1: 3.655 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.115 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.050 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.605 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.372 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 14.414 ms/op
                 listUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255109
  mean =      3.760 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 247558 
    [ 5.000,  7.500) = 5699 
    [ 7.500, 10.000) = 1066 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     20.429 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.716 ± 5.794  ops/ms
ClientPb.existUser                       thrpt       3  10.204 ± 6.491  ops/ms
ClientPb.getUser                         thrpt       3   9.906 ± 5.158  ops/ms
ClientPb.listUser                        thrpt       3   8.615 ± 1.734  ops/ms
ClientPb.createUser                       avgt       3   3.177 ± 1.741   ms/op
ClientPb.existUser                        avgt       3   3.006 ± 0.685   ms/op
ClientPb.getUser                          avgt       3   3.190 ± 0.782   ms/op
ClientPb.listUser                         avgt       3   3.795 ± 1.281   ms/op
ClientPb.createUser                     sample  298172   3.217 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.965           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.756           ms/op
ClientPb.existUser                      sample  308373   3.111 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.041           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.483           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  297892   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.534           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  255109   3.760 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.605           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
