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
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 6.243 ops/ms
# Warmup Iteration   3: 9.069 ops/ms
Iteration   1: 9.513 ops/ms
Iteration   2: 9.537 ops/ms
Iteration   3: 8.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.292 ±(99.9%) 7.373 ops/ms [Average]
  (min, avg, max) = (8.825, 9.292, 9.537), stdev = 0.404
  CI (99.9%): [1.918, 16.665] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ops/ms
# Warmup Iteration   2: 9.289 ops/ms
# Warmup Iteration   3: 10.418 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.188 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (10.148, 10.188, 10.224), stdev = 0.038
  CI (99.9%): [9.492, 10.884] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ops/ms
# Warmup Iteration   2: 9.269 ops/ms
# Warmup Iteration   3: 9.529 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.129 ±(99.9%) 3.258 ops/ms [Average]
  (min, avg, max) = (9.986, 10.129, 10.329), stdev = 0.179
  CI (99.9%): [6.871, 13.387] (assumes normal distribution)


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
# Warmup Iteration   1: 3.502 ops/ms
# Warmup Iteration   2: 8.140 ops/ms
# Warmup Iteration   3: 8.314 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.411 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (8.219, 8.411, 8.585), stdev = 0.184
  CI (99.9%): [5.058, 11.763] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.025 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.003 ms/op
Iteration   1: 3.208 ±(99.9%) 0.006 ms/op
Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
Iteration   3: 3.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.218 ±(99.9%) 1.819 ms/op [Average]
  (min, avg, max) = (3.124, 3.218, 3.322), stdev = 0.100
  CI (99.9%): [1.399, 5.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.755 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
Iteration   1: 3.084 ±(99.9%) 0.005 ms/op
Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
Iteration   3: 3.183 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.084, 3.131, 3.183), stdev = 0.050
  CI (99.9%): [2.222, 4.040] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.001 ms/op
Iteration   1: 3.342 ±(99.9%) 0.002 ms/op
Iteration   2: 3.261 ±(99.9%) 0.003 ms/op
Iteration   3: 3.253 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.285 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.253, 3.285, 3.342), stdev = 0.049
  CI (99.9%): [2.395, 4.176] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.104 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.008 ms/op
Iteration   1: 3.779 ±(99.9%) 0.009 ms/op
Iteration   2: 3.745 ±(99.9%) 0.004 ms/op
Iteration   3: 3.743 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.743, 3.756, 3.779), stdev = 0.020
  CI (99.9%): [3.394, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.231 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.010 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  11.523 ms/op
                 createUser·p0.9999: 18.358 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.293 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.548 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  16.412 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303300
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12889 
    [ 2.500,  5.000) = 285596 
    [ 5.000,  7.500) = 4156 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.379 ms/op
     p(99.9900) =     24.096 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  10.617 ms/op
                 existUser·p0.9999: 23.420 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 21.969 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 26.573 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307061
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23055 
    [ 2.500,  5.000) = 278738 
    [ 5.000,  7.500) = 4616 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     24.948 ms/op
     p(99.9990) =     27.719 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 9.027 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.196 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  15.676 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.473 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  10.131 ms/op
                 getUser·p0.9999: 26.174 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.977 ms/op
                 getUser·p0.9999: 20.088 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303980
  mean =      3.156 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14870 
    [ 2.500,  5.000) = 280941 
    [ 5.000,  7.500) = 7347 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     24.779 ms/op
     p(99.9990) =     27.065 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.962 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.013 ms/op
Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.693 ms/op
                 listUser·p0.999:  15.743 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 16.191 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.658 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 14.983 ms/op
                 listUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257549
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 250070 
    [ 5.000,  7.500) = 5445 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.836 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     26.785 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.292 ± 7.373  ops/ms
ClientPb.existUser                       thrpt       3  10.188 ± 0.696  ops/ms
ClientPb.getUser                         thrpt       3  10.129 ± 3.258  ops/ms
ClientPb.listUser                        thrpt       3   8.411 ± 3.353  ops/ms
ClientPb.createUser                       avgt       3   3.218 ± 1.819   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 0.909   ms/op
ClientPb.getUser                          avgt       3   3.285 ± 0.891   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 0.362   ms/op
ClientPb.createUser                     sample  303300   3.165 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.293           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.096           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  307061   3.126 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.529           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  303980   3.156 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.255           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.221           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  257549   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.516           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.836           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
