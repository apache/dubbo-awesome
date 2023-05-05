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
# Warmup Iteration   1: 2.704 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 9.418 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 9.912 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.012 ±(99.9%) 4.475 ops/ms [Average]
  (min, avg, max) = (9.832, 10.012, 10.291), stdev = 0.245
  CI (99.9%): [5.536, 14.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ops/ms
# Warmup Iteration   2: 8.965 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 10.292 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.328 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (10.292, 10.328, 10.394), stdev = 0.057
  CI (99.9%): [9.291, 11.366] (assumes normal distribution)


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
# Warmup Iteration   1: 3.367 ops/ms
# Warmup Iteration   2: 8.684 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.637 ±(99.9%) 5.247 ops/ms [Average]
  (min, avg, max) = (9.348, 9.637, 9.923), stdev = 0.288
  CI (99.9%): [4.390, 14.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.159 ops/ms
# Warmup Iteration   2: 7.679 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.459 ops/ms
Iteration   2: 8.446 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.423 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (8.363, 8.423, 8.459), stdev = 0.052
  CI (99.9%): [7.467, 9.378] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.740 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
Iteration   3: 3.236 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.218 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (3.127, 3.218, 3.292), stdev = 0.084
  CI (99.9%): [1.691, 4.746] (assumes normal distribution)


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
# Warmup Iteration   1: 7.158 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
Iteration   3: 2.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.010 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.996, 3.010, 3.028), stdev = 0.017
  CI (99.9%): [2.707, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 7.668 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.003 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
Iteration   2: 3.353 ±(99.9%) 0.008 ms/op
Iteration   3: 3.382 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.386 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.353, 3.386, 3.422), stdev = 0.035
  CI (99.9%): [2.752, 4.020] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.885 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
Iteration   1: 3.673 ±(99.9%) 0.011 ms/op
Iteration   2: 3.722 ±(99.9%) 0.009 ms/op
Iteration   3: 3.786 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (3.673, 3.727, 3.786), stdev = 0.056
  CI (99.9%): [2.698, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 7.271 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  17.984 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.303 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  17.795 ms/op
                 createUser·p0.9999: 22.784 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  15.761 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291111
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19191 
    [ 2.500,  5.000) = 263113 
    [ 5.000,  7.500) = 7532 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     16.298 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 7.685 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.610 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  14.272 ms/op
                 existUser·p0.9999: 24.389 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  12.683 ms/op
                 existUser·p0.9999: 21.709 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.044 ms/op
                 existUser·p0.9999: 22.005 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312263
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13604 
    [ 2.500,  5.000) = 293938 
    [ 5.000,  7.500) = 3953 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     22.828 ms/op
     p(99.9990) =     24.957 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 7.733 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.010 ms/op
Iteration   1: 3.320 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  18.077 ms/op
                 getUser·p0.9999: 22.774 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  11.092 ms/op
                 getUser·p0.9999: 21.101 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296415
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14223 
    [ 2.500,  5.000) = 272603 
    [ 5.000,  7.500) = 8427 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     15.202 ms/op
     p(99.9900) =     22.207 ms/op
     p(99.9990) =     23.300 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 9.208 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.012 ms/op
Iteration   1: 3.811 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 19.765 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.365 ms/op
                 listUser·p0.9999: 20.297 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255596
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 248438 
    [ 5.000,  7.500) = 5076 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.012 ± 4.475  ops/ms
ClientPb.existUser                       thrpt       3  10.328 ± 1.037  ops/ms
ClientPb.getUser                         thrpt       3   9.637 ± 5.247  ops/ms
ClientPb.listUser                        thrpt       3   8.423 ± 0.955  ops/ms
ClientPb.createUser                       avgt       3   3.218 ± 1.528   ms/op
ClientPb.existUser                        avgt       3   3.010 ± 0.303   ms/op
ClientPb.getUser                          avgt       3   3.386 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 1.029   ms/op
ClientPb.createUser                     sample  291111   3.296 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.834           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.774           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.068           ms/op
ClientPb.existUser                      sample  312263   3.072 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.828           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.100           ms/op
ClientPb.getUser                        sample  296415   3.236 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.202           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.207           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.527           ms/op
ClientPb.listUser                       sample  255596   3.756 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.928           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.349           ms/op
