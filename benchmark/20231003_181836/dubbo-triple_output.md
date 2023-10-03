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
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 6.328 ops/ms
# Warmup Iteration   3: 9.241 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.630 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (9.534, 9.630, 9.679), stdev = 0.084
  CI (99.9%): [8.106, 11.155] (assumes normal distribution)


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
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 8.927 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 10.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.023 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (9.936, 10.023, 10.126), stdev = 0.096
  CI (99.9%): [8.276, 11.770] (assumes normal distribution)


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
# Warmup Iteration   1: 3.326 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 9.377 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.728 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (9.661, 9.728, 9.777), stdev = 0.060
  CI (99.9%): [8.637, 10.820] (assumes normal distribution)


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
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 7.363 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.190 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.202 ±(99.9%) 0.310 ops/ms [Average]
  (min, avg, max) = (8.190, 8.202, 8.221), stdev = 0.017
  CI (99.9%): [7.892, 8.511] (assumes normal distribution)


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
# Warmup Iteration   1: 8.543 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.005 ms/op
Iteration   1: 3.348 ±(99.9%) 0.004 ms/op
Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
Iteration   3: 3.251 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.309 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.251, 3.309, 3.348), stdev = 0.051
  CI (99.9%): [2.374, 4.245] (assumes normal distribution)


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
# Warmup Iteration   1: 9.362 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.282 ±(99.9%) 0.004 ms/op
Iteration   3: 3.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.223 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.158, 3.223, 3.282), stdev = 0.062
  CI (99.9%): [2.090, 4.355] (assumes normal distribution)


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
# Warmup Iteration   1: 8.601 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.005 ms/op
Iteration   1: 3.335 ±(99.9%) 0.004 ms/op
Iteration   2: 3.280 ±(99.9%) 0.003 ms/op
Iteration   3: 3.289 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.301 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.280, 3.301, 3.335), stdev = 0.030
  CI (99.9%): [2.762, 3.841] (assumes normal distribution)


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
# Warmup Iteration   1: 9.642 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.939 ±(99.9%) 0.004 ms/op
Iteration   2: 3.887 ±(99.9%) 0.006 ms/op
Iteration   3: 3.869 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.898 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.869, 3.898, 3.939), stdev = 0.036
  CI (99.9%): [3.241, 4.555] (assumes normal distribution)


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
# Warmup Iteration   1: 7.634 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.012 ms/op
Iteration   1: 3.465 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.061 ms/op
                 createUser·p0.999:  19.651 ms/op
                 createUser·p0.9999: 25.556 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  20.354 ms/op
                 createUser·p0.9999: 23.502 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282269
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10313 
    [ 2.500,  5.000) = 261189 
    [ 5.000,  7.500) = 9171 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     18.308 ms/op
     p(99.9900) =     23.422 ms/op
     p(99.9990) =     26.837 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.271 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  19.414 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.248 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  15.980 ms/op
                 existUser·p0.9999: 25.000 ms/op
                 existUser·p1.00:   35.193 ms/op

Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.274 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 23.729 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294772
  mean =      3.258 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7311 
    [ 2.500,  5.000) = 277750 
    [ 5.000,  7.500) = 8430 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     24.495 ms/op
     p(99.9990) =     27.667 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 8.033 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.010 ms/op
Iteration   1: 3.424 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  17.125 ms/op
                 getUser·p0.9999: 19.376 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  18.322 ms/op
                 getUser·p0.9999: 30.769 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  15.409 ms/op
                 getUser·p0.9999: 21.364 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286792
  mean =      3.345 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6717 
    [ 2.500,  5.000) = 269516 
    [ 5.000,  7.500) = 9136 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     21.965 ms/op
     p(99.9990) =     31.274 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 9.610 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 21.733 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  14.086 ms/op
                 listUser·p0.9999: 19.532 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 3.873 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  15.007 ms/op
                 listUser·p0.9999: 25.887 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242613
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 232208 
    [ 5.000,  7.500) = 7619 
    [ 7.500, 10.000) = 1729 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     15.555 ms/op
     p(99.9900) =     23.158 ms/op
     p(99.9990) =     26.399 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.630 ± 1.524  ops/ms
ClientPb.existUser                       thrpt       3  10.023 ± 1.747  ops/ms
ClientPb.getUser                         thrpt       3   9.728 ± 1.092  ops/ms
ClientPb.listUser                        thrpt       3   8.202 ± 0.310  ops/ms
ClientPb.createUser                       avgt       3   3.309 ± 0.935   ms/op
ClientPb.existUser                        avgt       3   3.223 ± 1.132   ms/op
ClientPb.getUser                          avgt       3   3.301 ± 0.540   ms/op
ClientPb.listUser                         avgt       3   3.898 ± 0.657   ms/op
ClientPb.createUser                     sample  282269   3.399 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.308           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.422           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.230           ms/op
ClientPb.existUser                      sample  294772   3.258 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.274           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.137           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.495           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  286792   3.345 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.965           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  242613   3.955 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.555           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
