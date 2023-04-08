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
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.441 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.856 ops/ms
Iteration   2: 8.830 ops/ms
Iteration   3: 9.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.992 ±(99.9%) 4.721 ops/ms [Average]
  (min, avg, max) = (8.830, 8.992, 9.291), stdev = 0.259
  CI (99.9%): [4.271, 13.713] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.105 ops/ms
# Warmup Iteration   2: 8.814 ops/ms
# Warmup Iteration   3: 9.535 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.733 ±(99.9%) 2.717 ops/ms [Average]
  (min, avg, max) = (9.588, 9.733, 9.886), stdev = 0.149
  CI (99.9%): [7.016, 12.450] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.516 ops/ms
# Warmup Iteration   2: 8.065 ops/ms
# Warmup Iteration   3: 9.174 ops/ms
Iteration   1: 9.240 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.408 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (9.240, 9.408, 9.720), stdev = 0.271
  CI (99.9%): [4.472, 14.344] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 6.918 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 7.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.881 ±(99.9%) 1.260 ops/ms [Average]
  (min, avg, max) = (7.814, 7.881, 7.952), stdev = 0.069
  CI (99.9%): [6.621, 9.141] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.524 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.003 ms/op
Iteration   1: 3.503 ±(99.9%) 0.006 ms/op
Iteration   2: 3.469 ±(99.9%) 0.007 ms/op
Iteration   3: 3.374 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.449 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.374, 3.449, 3.503), stdev = 0.067
  CI (99.9%): [2.229, 4.669] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.398 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.008 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
Iteration   3: 3.333 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.311 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (3.297, 3.311, 3.333), stdev = 0.019
  CI (99.9%): [2.958, 3.664] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.595 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.003 ms/op
Iteration   1: 3.433 ±(99.9%) 0.006 ms/op
Iteration   2: 3.439 ±(99.9%) 0.006 ms/op
Iteration   3: 3.368 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.368, 3.413, 3.439), stdev = 0.039
  CI (99.9%): [2.697, 4.130] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.449 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.006 ms/op
Iteration   1: 4.198 ±(99.9%) 0.009 ms/op
Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
Iteration   3: 4.004 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (4.004, 4.086, 4.198), stdev = 0.100
  CI (99.9%): [2.258, 5.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.242 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.012 ms/op
Iteration   1: 3.584 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  20.615 ms/op
                 createUser·p0.9999: 27.593 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 3.501 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.966 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 27.780 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.393 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  24.987 ms/op
                 createUser·p0.9999: 31.312 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275042
  mean =      3.491 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7522 
    [ 2.500,  5.000) = 254278 
    [ 5.000,  7.500) = 12173 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 8.040 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  9.626 ms/op
                 existUser·p0.9999: 23.770 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  15.220 ms/op
                 existUser·p0.9999: 24.287 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.367 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.211 ms/op
                 existUser·p0.999:  18.905 ms/op
                 existUser·p0.9999: 33.619 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289078
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12045 
    [ 2.500,  5.000) = 270928 
    [ 5.000,  7.500) = 5003 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.280 ms/op
     p(99.9900) =     31.264 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 9.015 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.012 ms/op
Iteration   1: 3.499 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  21.119 ms/op
                 getUser·p0.9999: 24.080 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  23.944 ms/op
                 getUser·p0.9999: 28.102 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  25.159 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279779
  mean =      3.432 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1972 
    [ 2.500,  5.000) = 270223 
    [ 5.000,  7.500) = 6522 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     21.445 ms/op
     p(99.9900) =     28.116 ms/op
     p(99.9990) =     29.563 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.382 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.013 ms/op
Iteration   1: 4.207 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 26.660 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.025 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 17.009 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 17.104 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235471
  mean =      4.073 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 226808 
    [ 5.000,  7.500) = 6136 
    [ 7.500, 10.000) = 1488 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     25.639 ms/op
     p(99.9990) =     27.448 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.992 ± 4.721  ops/ms
ClientPb.existUser                       thrpt       3   9.733 ± 2.717  ops/ms
ClientPb.getUser                         thrpt       3   9.408 ± 4.936  ops/ms
ClientPb.listUser                        thrpt       3   7.881 ± 1.260  ops/ms
ClientPb.createUser                       avgt       3   3.449 ± 1.220   ms/op
ClientPb.existUser                        avgt       3   3.311 ± 0.353   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 0.717   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 1.828   ms/op
ClientPb.createUser                     sample  275042   3.491 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.884           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  289078   3.321 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.149           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.280           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  279779   3.432 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.006           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.116           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  235471   4.073 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.130           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.040           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.639           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
