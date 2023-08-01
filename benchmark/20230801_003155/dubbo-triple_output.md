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
# Warmup Iteration   1: 2.260 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 9.220 ops/ms
Iteration   1: 9.985 ops/ms
Iteration   2: 10.193 ops/ms
Iteration   3: 10.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.076 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (9.985, 10.076, 10.193), stdev = 0.107
  CI (99.9%): [8.133, 12.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 8.784 ops/ms
# Warmup Iteration   3: 9.848 ops/ms
Iteration   1: 10.121 ops/ms
Iteration   2: 10.586 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.451 ±(99.9%) 5.245 ops/ms [Average]
  (min, avg, max) = (10.121, 10.451, 10.646), stdev = 0.287
  CI (99.9%): [5.206, 15.695] (assumes normal distribution)


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
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 9.439 ops/ms
# Warmup Iteration   3: 9.395 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 9.906 ops/ms
Iteration   3: 9.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.958 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (9.906, 9.958, 10.016), stdev = 0.055
  CI (99.9%): [8.948, 10.969] (assumes normal distribution)


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
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 7.722 ops/ms
# Warmup Iteration   3: 8.053 ops/ms
Iteration   1: 8.524 ops/ms
Iteration   2: 8.283 ops/ms
Iteration   3: 8.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.417 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (8.283, 8.417, 8.524), stdev = 0.123
  CI (99.9%): [6.178, 10.657] (assumes normal distribution)


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
# Warmup Iteration   1: 8.022 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.002 ms/op
Iteration   1: 3.146 ±(99.9%) 0.008 ms/op
Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
Iteration   3: 3.211 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.162 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.130, 3.162, 3.211), stdev = 0.043
  CI (99.9%): [2.378, 3.946] (assumes normal distribution)


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
# Warmup Iteration   1: 7.540 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.004 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.096 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.092 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.022, 3.092, 3.158), stdev = 0.068
  CI (99.9%): [1.852, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 8.397 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.004 ms/op
Iteration   1: 3.424 ±(99.9%) 0.005 ms/op
Iteration   2: 3.277 ±(99.9%) 0.002 ms/op
Iteration   3: 3.288 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.330 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (3.277, 3.330, 3.424), stdev = 0.082
  CI (99.9%): [1.834, 4.826] (assumes normal distribution)


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
# Warmup Iteration   1: 9.074 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
Iteration   1: 3.973 ±(99.9%) 0.006 ms/op
Iteration   2: 3.766 ±(99.9%) 0.009 ms/op
Iteration   3: 3.825 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.855 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (3.766, 3.855, 3.973), stdev = 0.107
  CI (99.9%): [1.904, 5.805] (assumes normal distribution)


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
# Warmup Iteration   1: 8.301 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  14.922 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  20.476 ms/op
                 createUser·p0.9999: 23.306 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  16.580 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299345
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18642 
    [ 2.500,  5.000) = 274172 
    [ 5.000,  7.500) = 5494 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     18.109 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 7.254 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.008 ms/op
Iteration   1: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.745 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  15.494 ms/op
                 existUser·p0.9999: 23.131 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.802 ms/op
                 existUser·p0.9999: 21.691 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300678
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14691 
    [ 2.500,  5.000) = 279556 
    [ 5.000,  7.500) = 5384 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.045 ms/op
     p(99.9900) =     22.182 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 7.844 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  14.223 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  13.736 ms/op
                 getUser·p0.9999: 21.981 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   5.539 ms/op
                 getUser·p0.999:  9.402 ms/op
                 getUser·p0.9999: 23.594 ms/op
                 getUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301559
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15411 
    [ 2.500,  5.000) = 281418 
    [ 5.000,  7.500) = 3862 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     14.105 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.508 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 9.684 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.012 ms/op
Iteration   1: 3.844 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  17.385 ms/op
                 listUser·p0.9999: 22.043 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.396 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.946 ms/op
                 listUser·p0.9999: 18.835 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.816 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.803 ms/op
                 listUser·p0.999:  12.962 ms/op
                 listUser·p0.9999: 15.763 ms/op
                 listUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248155
  mean =      3.869 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 238101 
    [ 5.000,  7.500) = 8009 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.172 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     20.367 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.076 ± 1.943  ops/ms
ClientPb.existUser                       thrpt       3  10.451 ± 5.245  ops/ms
ClientPb.getUser                         thrpt       3   9.958 ± 1.011  ops/ms
ClientPb.listUser                        thrpt       3   8.417 ± 2.240  ops/ms
ClientPb.createUser                       avgt       3   3.162 ± 0.784   ms/op
ClientPb.existUser                        avgt       3   3.092 ± 1.240   ms/op
ClientPb.getUser                          avgt       3   3.330 ± 1.496   ms/op
ClientPb.listUser                         avgt       3   3.855 ± 1.950   ms/op
ClientPb.createUser                     sample  299345   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.016           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.109           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.231           ms/op
ClientPb.existUser                      sample  300678   3.192 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.045           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  301559   3.182 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.740           ms/op
ClientPb.listUser                       sample  248155   3.869 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.172           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.367           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970           ms/op
