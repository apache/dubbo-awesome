# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.724 ops/ms
# Warmup Iteration   2: 6.424 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 10.070 ops/ms
Iteration   3: 9.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.935 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (9.853, 9.935, 10.070), stdev = 0.118
  CI (99.9%): [7.788, 12.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ops/ms
# Warmup Iteration   2: 9.306 ops/ms
# Warmup Iteration   3: 9.879 ops/ms
Iteration   1: 10.391 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.540 ±(99.9%) 2.958 ops/ms [Average]
  (min, avg, max) = (10.391, 10.540, 10.712), stdev = 0.162
  CI (99.9%): [7.582, 13.498] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 9.978 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.159 ±(99.9%) 3.201 ops/ms [Average]
  (min, avg, max) = (10.030, 10.159, 10.359), stdev = 0.175
  CI (99.9%): [6.959, 13.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 8.473 ops/ms
Iteration   1: 8.627 ops/ms
Iteration   2: 8.505 ops/ms
Iteration   3: 8.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.612 ±(99.9%) 1.816 ops/ms [Average]
  (min, avg, max) = (8.505, 8.612, 8.703), stdev = 0.100
  CI (99.9%): [6.795, 10.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.003 ms/op
Iteration   2: 3.277 ±(99.9%) 0.004 ms/op
Iteration   3: 3.117 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.117, 3.205, 3.277), stdev = 0.081
  CI (99.9%): [1.727, 4.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.457 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.008 ms/op
Iteration   2: 3.255 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.147 ±(99.9%) 2.546 ms/op [Average]
  (min, avg, max) = (2.989, 3.147, 3.255), stdev = 0.140
  CI (99.9%): [0.600, 5.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.207 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.002 ms/op
Iteration   1: 3.317 ±(99.9%) 0.005 ms/op
Iteration   2: 3.107 ±(99.9%) 0.005 ms/op
Iteration   3: 3.168 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.198 ±(99.9%) 1.972 ms/op [Average]
  (min, avg, max) = (3.107, 3.198, 3.317), stdev = 0.108
  CI (99.9%): [1.226, 5.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.160 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.005 ms/op
Iteration   1: 3.744 ±(99.9%) 0.008 ms/op
Iteration   2: 3.783 ±(99.9%) 0.005 ms/op
Iteration   3: 3.789 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.744, 3.772, 3.789), stdev = 0.024
  CI (99.9%): [3.327, 4.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.244 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
Iteration   1: 3.197 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  17.627 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 20.159 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 22.773 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298361
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11809 
    [ 2.500,  5.000) = 281271 
    [ 5.000,  7.500) = 4445 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.263 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 20.972 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.528 ms/op
                 existUser·p0.9999: 21.809 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  8.260 ms/op
                 existUser·p0.9999: 28.925 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315044
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18667 
    [ 2.500,  5.000) = 291142 
    [ 5.000,  7.500) = 4598 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =      8.568 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     30.043 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.553 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.010 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.011 ms/op
                 getUser·p0.9999: 30.631 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.800 ms/op
                 getUser·p0.99:   5.592 ms/op
                 getUser·p0.999:  10.066 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 308017
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8479 
    [ 2.500,  5.000) = 294825 
    [ 5.000,  7.500) = 3943 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     28.868 ms/op
     p(99.9990) =     31.545 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.729 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.011 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 19.617 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.767 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.964 ms/op
                 listUser·p0.9999: 15.232 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 3.694 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 16.417 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257350
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 250431 
    [ 5.000,  7.500) = 5302 
    [ 7.500, 10.000) = 934 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     17.570 ms/op
     p(99.9990) =     20.437 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.935 ± 2.147  ops/ms
ClientPb.existUser                       thrpt       3  10.540 ± 2.958  ops/ms
ClientPb.getUser                         thrpt       3  10.159 ± 3.201  ops/ms
ClientPb.listUser                        thrpt       3   8.612 ± 1.816  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.477   ms/op
ClientPb.existUser                        avgt       3   3.147 ± 2.546   ms/op
ClientPb.getUser                          avgt       3   3.198 ± 1.972   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 0.445   ms/op
ClientPb.createUser                     sample  298361   3.216 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.862           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.302           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.757           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.149           ms/op
ClientPb.existUser                      sample  315044   3.047 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.568           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  308017   3.116 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.912           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.868           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.588           ms/op
ClientPb.listUser                       sample  257350   3.727 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.337           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.570           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.496           ms/op
