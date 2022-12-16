# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.185 ops/ms
# Warmup Iteration   2: 5.105 ops/ms
# Warmup Iteration   3: 8.864 ops/ms
Iteration   1: 9.102 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 9.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.292 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (9.102, 9.292, 9.519), stdev = 0.211
  CI (99.9%): [5.437, 13.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 8.751 ops/ms
# Warmup Iteration   3: 9.163 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 9.562 ops/ms
Iteration   3: 9.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.668 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (9.562, 9.668, 9.810), stdev = 0.128
  CI (99.9%): [7.334, 12.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 8.509 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 9.494 ops/ms
Iteration   2: 9.359 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.355 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (9.212, 9.355, 9.494), stdev = 0.141
  CI (99.9%): [6.786, 11.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 7.811 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.137 ±(99.9%) 3.437 ops/ms [Average]
  (min, avg, max) = (7.926, 8.137, 8.289), stdev = 0.188
  CI (99.9%): [4.700, 11.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.692 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.004 ms/op
Iteration   1: 3.427 ±(99.9%) 0.007 ms/op
Iteration   2: 3.645 ±(99.9%) 0.009 ms/op
Iteration   3: 3.561 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.544 ±(99.9%) 2.000 ms/op [Average]
  (min, avg, max) = (3.427, 3.544, 3.645), stdev = 0.110
  CI (99.9%): [1.545, 5.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.115 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.006 ms/op
Iteration   1: 3.215 ±(99.9%) 0.004 ms/op
Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
Iteration   3: 3.264 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.218 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.176, 3.218, 3.264), stdev = 0.044
  CI (99.9%): [2.414, 4.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.746 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.004 ms/op
Iteration   1: 3.477 ±(99.9%) 0.004 ms/op
Iteration   2: 3.369 ±(99.9%) 0.006 ms/op
Iteration   3: 3.437 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.369, 3.428, 3.477), stdev = 0.055
  CI (99.9%): [2.428, 4.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.658 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.007 ms/op
Iteration   1: 4.003 ±(99.9%) 0.009 ms/op
Iteration   2: 3.905 ±(99.9%) 0.008 ms/op
Iteration   3: 4.018 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.975 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.905, 3.975, 4.018), stdev = 0.061
  CI (99.9%): [2.856, 5.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.136 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.011 ms/op
Iteration   1: 3.600 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  20.753 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  24.341 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 3.580 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  19.027 ms/op
                 createUser·p0.9999: 26.839 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270352
  mean =      3.549 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8477 
    [ 2.500,  5.000) = 251787 
    [ 5.000,  7.500) = 8442 
    [ 7.500, 10.000) = 955 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     19.256 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.236 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.136 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.016 ms/op
                 existUser·p0.999:  19.420 ms/op
                 existUser·p0.9999: 33.503 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  21.785 ms/op
                 existUser·p0.9999: 24.402 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 26.928 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281030
  mean =      3.412 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8801 
    [ 2.500,  5.000) = 264155 
    [ 5.000,  7.500) = 7076 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     18.643 ms/op
     p(99.9900) =     31.945 ms/op
     p(99.9990) =     34.157 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
Iteration   1: 3.555 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  21.139 ms/op
                 getUser·p0.9999: 28.869 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   2: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  10.379 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 28.219 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273935
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3271 
    [ 2.500,  5.000) = 261588 
    [ 5.000,  7.500) = 7510 
    [ 7.500, 10.000) = 1037 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     28.102 ms/op
     p(99.9990) =     29.681 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.735 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.013 ms/op
Iteration   1: 3.996 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  22.347 ms/op
                 listUser·p0.9999: 30.507 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 3.989 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 26.125 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238674
  mean =      4.022 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 229338 
    [ 5.000,  7.500) = 7183 
    [ 7.500, 10.000) = 1344 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     28.578 ms/op
     p(99.9990) =     31.450 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.292 ± 3.855  ops/ms
ClientPb.existUser                       thrpt       3   9.668 ± 2.335  ops/ms
ClientPb.getUser                         thrpt       3   9.355 ± 2.569  ops/ms
ClientPb.listUser                        thrpt       3   8.137 ± 3.437  ops/ms
ClientPb.createUser                       avgt       3   3.544 ± 2.000   ms/op
ClientPb.existUser                        avgt       3   3.218 ± 0.804   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 1.000   ms/op
ClientPb.listUser                         avgt       3   3.975 ± 1.119   ms/op
ClientPb.createUser                     sample  270352   3.549 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.241           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.256           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.361           ms/op
ClientPb.existUser                      sample  281030   3.412 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.468           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.643           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.945           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  273935   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.712           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.102           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  238674   4.022 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.578           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.850           ms/op
