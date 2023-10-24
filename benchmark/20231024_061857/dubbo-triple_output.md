# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 5.392 ops/ms
# Warmup Iteration   3: 8.456 ops/ms
Iteration   1: 9.123 ops/ms
Iteration   2: 9.031 ops/ms
Iteration   3: 9.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.176 ±(99.9%) 3.235 ops/ms [Average]
  (min, avg, max) = (9.031, 9.176, 9.374), stdev = 0.177
  CI (99.9%): [5.941, 12.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.910 ops/ms
# Warmup Iteration   2: 8.875 ops/ms
# Warmup Iteration   3: 9.516 ops/ms
Iteration   1: 9.623 ops/ms
Iteration   2: 9.925 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.735 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (9.623, 9.735, 9.925), stdev = 0.165
  CI (99.9%): [6.725, 12.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.420 ops/ms
Iteration   3: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.364 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (9.249, 9.364, 9.424), stdev = 0.100
  CI (99.9%): [7.545, 11.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.000 ops/ms
# Warmup Iteration   2: 7.396 ops/ms
# Warmup Iteration   3: 7.757 ops/ms
Iteration   1: 7.756 ops/ms
Iteration   2: 7.861 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.856 ±(99.9%) 1.778 ops/ms [Average]
  (min, avg, max) = (7.756, 7.856, 7.951), stdev = 0.097
  CI (99.9%): [6.078, 9.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.566 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.006 ms/op
Iteration   1: 3.424 ±(99.9%) 0.009 ms/op
Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
Iteration   3: 3.428 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.535 ms/op [Average]
  (min, avg, max) = (3.424, 3.474, 3.571), stdev = 0.084
  CI (99.9%): [1.940, 5.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.357 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.007 ms/op
Iteration   1: 3.314 ±(99.9%) 0.006 ms/op
Iteration   2: 3.301 ±(99.9%) 0.004 ms/op
Iteration   3: 3.272 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.296 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.272, 3.296, 3.314), stdev = 0.022
  CI (99.9%): [2.900, 3.691] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.003 ms/op
Iteration   1: 3.464 ±(99.9%) 0.003 ms/op
Iteration   2: 3.470 ±(99.9%) 0.002 ms/op
Iteration   3: 3.414 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (3.414, 3.450, 3.470), stdev = 0.031
  CI (99.9%): [2.886, 4.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.355 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.007 ms/op
Iteration   1: 4.099 ±(99.9%) 0.005 ms/op
Iteration   2: 4.068 ±(99.9%) 0.005 ms/op
Iteration   3: 4.125 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.097 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (4.068, 4.097, 4.125), stdev = 0.029
  CI (99.9%): [3.576, 4.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.820 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.010 ms/op
Iteration   1: 3.454 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 22.503 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 25.255 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  20.189 ms/op
                 createUser·p0.9999: 25.488 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277298
  mean =      3.462 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4956 
    [ 2.500,  5.000) = 268303 
    [ 5.000,  7.500) = 3068 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     25.946 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.792 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.008 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.121 ms/op
                 existUser·p0.999:  20.560 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  13.152 ms/op
                 existUser·p0.9999: 26.797 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  23.486 ms/op
                 existUser·p0.9999: 26.273 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278824
  mean =      3.444 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9802 
    [ 2.500,  5.000) = 263131 
    [ 5.000,  7.500) = 4755 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.044 ms/op
     p(99.9000) =     13.479 ms/op
     p(99.9900) =     26.218 ms/op
     p(99.9990) =     27.513 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.402 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.904 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.845 ms/op
                 getUser·p0.999:  22.138 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   35.783 ms/op

Iteration   2: 3.474 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  12.876 ms/op
                 getUser·p0.9999: 25.021 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.647 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  17.782 ms/op
                 getUser·p0.9999: 27.434 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272121
  mean =      3.527 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6350 
    [ 2.500,  5.000) = 258430 
    [ 5.000,  7.500) = 5862 
    [ 7.500, 10.000) = 828 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     20.952 ms/op
     p(99.9900) =     32.859 ms/op
     p(99.9990) =     35.604 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.581 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.013 ms/op
Iteration   1: 4.135 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.417 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 23.708 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 4.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.711 ms/op
                 listUser·p0.999:  14.191 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.123 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 15.254 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233958
  mean =      4.100 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 226899 
    [ 5.000,  7.500) = 5218 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.993 ms/op
     p(99.9900) =     22.669 ms/op
     p(99.9990) =     24.552 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.176 ± 3.235  ops/ms
ClientPb.existUser                       thrpt       3   9.735 ± 3.011  ops/ms
ClientPb.getUser                         thrpt       3   9.364 ± 1.819  ops/ms
ClientPb.listUser                        thrpt       3   7.856 ± 1.778  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.535   ms/op
ClientPb.existUser                        avgt       3   3.296 ± 0.396   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 0.564   ms/op
ClientPb.listUser                         avgt       3   4.097 ± 0.521   ms/op
ClientPb.createUser                     sample  277298   3.462 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.838           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  278824   3.444 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.044           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.479           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.218           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  272121   3.527 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.788           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.952           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.859           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  233958   4.100 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.993           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.669           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.362           ms/op
