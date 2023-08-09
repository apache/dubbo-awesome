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
# Warmup Iteration   1: 2.414 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 8.967 ops/ms
Iteration   1: 9.297 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.529 ±(99.9%) 5.012 ops/ms [Average]
  (min, avg, max) = (9.297, 9.529, 9.832), stdev = 0.275
  CI (99.9%): [4.517, 14.542] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 9.491 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 9.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.025 ±(99.9%) 10.194 ops/ms [Average]
  (min, avg, max) = (9.405, 10.025, 10.490), stdev = 0.559
  CI (99.9%): [≈ 0, 20.220] (assumes normal distribution)


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
# Warmup Iteration   1: 3.222 ops/ms
# Warmup Iteration   2: 8.106 ops/ms
# Warmup Iteration   3: 9.157 ops/ms
Iteration   1: 10.004 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 9.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.952 ±(99.9%) 1.009 ops/ms [Average]
  (min, avg, max) = (9.894, 9.952, 10.004), stdev = 0.055
  CI (99.9%): [8.943, 10.960] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.939 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.018 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.089 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (8.018, 8.089, 8.170), stdev = 0.076
  CI (99.9%): [6.697, 9.481] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.838 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.003 ms/op
Iteration   1: 3.428 ±(99.9%) 0.007 ms/op
Iteration   2: 3.400 ±(99.9%) 0.005 ms/op
Iteration   3: 3.362 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.362, 3.397, 3.428), stdev = 0.033
  CI (99.9%): [2.791, 4.002] (assumes normal distribution)


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
# Warmup Iteration   1: 8.724 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.005 ms/op
Iteration   1: 3.242 ±(99.9%) 0.004 ms/op
Iteration   2: 3.188 ±(99.9%) 0.009 ms/op
Iteration   3: 3.138 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.189 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.138, 3.189, 3.242), stdev = 0.052
  CI (99.9%): [2.241, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 8.620 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.002 ms/op
Iteration   2: 3.232 ±(99.9%) 0.003 ms/op
Iteration   3: 3.276 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.226, 3.245, 3.276), stdev = 0.027
  CI (99.9%): [2.748, 3.741] (assumes normal distribution)


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.003 ms/op
Iteration   1: 3.756 ±(99.9%) 0.004 ms/op
Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
Iteration   3: 3.789 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.756, 3.778, 3.789), stdev = 0.019
  CI (99.9%): [3.431, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 7.959 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
Iteration   1: 3.232 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.513 ms/op
                 createUser·p0.9999: 25.074 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 24.556 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  15.671 ms/op
                 createUser·p0.9999: 20.981 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293572
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14897 
    [ 2.500,  5.000) = 271354 
    [ 5.000,  7.500) = 5773 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     24.302 ms/op
     p(99.9990) =     25.602 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 8.080 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.009 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 20.474 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.614 ms/op
                 existUser·p0.9999: 21.589 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  10.163 ms/op
                 existUser·p0.9999: 21.778 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305462
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24408 
    [ 2.500,  5.000) = 273612 
    [ 5.000,  7.500) = 6359 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     21.445 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 8.020 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  14.557 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.165 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  13.668 ms/op
                 getUser·p0.9999: 27.581 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.104 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298474
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12608 
    [ 2.500,  5.000) = 276052 
    [ 5.000,  7.500) = 8278 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     25.761 ms/op
     p(99.9990) =     28.153 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 8.597 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.011 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.603 ms/op
                 listUser·p0.9999: 21.940 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.394 ms/op
                 listUser·p0.999:  13.460 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   16.286 ms/op

Iteration   3: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  13.425 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251458
  mean =      3.819 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 241493 
    [ 5.000,  7.500) = 7351 
    [ 7.500, 10.000) = 1838 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     20.737 ms/op
     p(99.9990) =     22.412 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.529 ±  5.012  ops/ms
ClientPb.existUser                       thrpt       3  10.025 ± 10.194  ops/ms
ClientPb.getUser                         thrpt       3   9.952 ±  1.009  ops/ms
ClientPb.listUser                        thrpt       3   8.089 ±  1.392  ops/ms
ClientPb.createUser                       avgt       3   3.397 ±  0.605   ms/op
ClientPb.existUser                        avgt       3   3.189 ±  0.948   ms/op
ClientPb.getUser                          avgt       3   3.245 ±  0.497   ms/op
ClientPb.listUser                         avgt       3   3.778 ±  0.347   ms/op
ClientPb.createUser                     sample  293572   3.268 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964            ms/op
ClientPb.createUser:createUser·p0.999   sample          16.286            ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.302            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575            ms/op
ClientPb.existUser                      sample  305462   3.142 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.200            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505            ms/op
ClientPb.existUser:existUser·p0.999     sample          10.371            ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.445            ms/op
ClientPb.existUser:existUser·p1.00      sample          22.086            ms/op
ClientPb.getUser                        sample  298474   3.213 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.779            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.761            ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803            ms/op
ClientPb.listUser                       sample  251458   3.819 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.122            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528            ms/op
ClientPb.listUser:listUser·p0.999       sample          13.484            ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.737            ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970            ms/op
