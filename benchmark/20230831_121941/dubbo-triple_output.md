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
# Warmup Iteration   1: 1.784 ops/ms
# Warmup Iteration   2: 4.405 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 8.678 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 9.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.833 ±(99.9%) 4.983 ops/ms [Average]
  (min, avg, max) = (8.671, 8.833, 9.148), stdev = 0.273
  CI (99.9%): [3.849, 13.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.736 ops/ms
# Warmup Iteration   2: 8.230 ops/ms
# Warmup Iteration   3: 9.033 ops/ms
Iteration   1: 9.480 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.433 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (9.403, 9.433, 9.480), stdev = 0.041
  CI (99.9%): [8.684, 10.183] (assumes normal distribution)


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
# Warmup Iteration   1: 2.832 ops/ms
# Warmup Iteration   2: 8.031 ops/ms
# Warmup Iteration   3: 8.711 ops/ms
Iteration   1: 9.220 ops/ms
Iteration   2: 8.614 ops/ms
Iteration   3: 9.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.022 ±(99.9%) 6.451 ops/ms [Average]
  (min, avg, max) = (8.614, 9.022, 9.232), stdev = 0.354
  CI (99.9%): [2.571, 15.473] (assumes normal distribution)


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
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 6.650 ops/ms
# Warmup Iteration   3: 7.455 ops/ms
Iteration   1: 7.453 ops/ms
Iteration   2: 7.482 ops/ms
Iteration   3: 7.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.549 ±(99.9%) 2.599 ops/ms [Average]
  (min, avg, max) = (7.453, 7.549, 7.713), stdev = 0.142
  CI (99.9%): [4.950, 10.148] (assumes normal distribution)


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
# Warmup Iteration   1: 10.553 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.005 ms/op
Iteration   1: 3.639 ±(99.9%) 0.005 ms/op
Iteration   2: 3.544 ±(99.9%) 0.006 ms/op
Iteration   3: 3.543 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.575 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.543, 3.575, 3.639), stdev = 0.055
  CI (99.9%): [2.566, 4.584] (assumes normal distribution)


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
# Warmup Iteration   1: 10.383 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.005 ms/op
Iteration   1: 3.514 ±(99.9%) 0.005 ms/op
Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
Iteration   3: 3.399 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.429 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.374, 3.429, 3.514), stdev = 0.075
  CI (99.9%): [2.062, 4.796] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.492 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.006 ms/op
Iteration   1: 3.566 ±(99.9%) 0.006 ms/op
Iteration   2: 3.484 ±(99.9%) 0.008 ms/op
Iteration   3: 3.416 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.489 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.416, 3.489, 3.566), stdev = 0.075
  CI (99.9%): [2.115, 4.862] (assumes normal distribution)


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
# Warmup Iteration   1: 11.903 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.008 ms/op
Iteration   1: 4.235 ±(99.9%) 0.008 ms/op
Iteration   2: 4.061 ±(99.9%) 0.011 ms/op
Iteration   3: 4.248 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.181 ±(99.9%) 1.906 ms/op [Average]
  (min, avg, max) = (4.061, 4.181, 4.248), stdev = 0.104
  CI (99.9%): [2.275, 6.088] (assumes normal distribution)


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
# Warmup Iteration   1: 9.127 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.010 ms/op
Iteration   1: 3.514 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  23.625 ms/op
                 createUser·p0.9999: 25.785 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.626 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  23.665 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.618 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 30.971 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267730
  mean =      3.585 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2747 
    [ 2.500,  5.000) = 255576 
    [ 5.000,  7.500) = 7311 
    [ 7.500, 10.000) = 1318 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 166 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     23.357 ms/op
     p(99.9900) =     28.965 ms/op
     p(99.9990) =     32.451 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 10.109 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.011 ms/op
Iteration   1: 3.551 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 24.641 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  23.525 ms/op
                 existUser·p0.9999: 26.568 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.552 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  25.360 ms/op
                 existUser·p0.9999: 32.375 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271198
  mean =      3.538 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7957 
    [ 2.500,  5.000) = 253398 
    [ 5.000,  7.500) = 8023 
    [ 7.500, 10.000) = 1144 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     18.966 ms/op
     p(99.9900) =     31.552 ms/op
     p(99.9990) =     32.548 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 9.980 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.011 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 23.975 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.576 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.989 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   7.288 ms/op
                 getUser·p0.999:  12.244 ms/op
                 getUser·p0.9999: 30.506 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271473
  mean =      3.536 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4385 
    [ 2.500,  5.000) = 258139 
    [ 5.000,  7.500) = 7084 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.960 ms/op
     p(99.9900) =     28.503 ms/op
     p(99.9990) =     30.755 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 11.388 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.014 ms/op
Iteration   1: 4.200 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  22.243 ms/op
                 listUser·p0.9999: 25.084 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.170 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 20.032 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.159 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 18.573 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229737
  mean =      4.176 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 217764 
    [ 5.000,  7.500) = 8659 
    [ 7.500, 10.000) = 1988 
    [10.000, 12.500) = 694 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     17.277 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.104 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.833 ± 4.983  ops/ms
ClientPb.existUser                       thrpt       3   9.433 ± 0.749  ops/ms
ClientPb.getUser                         thrpt       3   9.022 ± 6.451  ops/ms
ClientPb.listUser                        thrpt       3   7.549 ± 2.599  ops/ms
ClientPb.createUser                       avgt       3   3.575 ± 1.009   ms/op
ClientPb.existUser                        avgt       3   3.429 ± 1.367   ms/op
ClientPb.getUser                          avgt       3   3.489 ± 1.374   ms/op
ClientPb.listUser                         avgt       3   4.181 ± 1.906   ms/op
ClientPb.createUser                     sample  267730   3.585 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.357           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.965           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  271198   3.538 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.174           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.966           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.552           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  271473   3.536 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.503           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.326           ms/op
ClientPb.listUser                       sample  229737   4.176 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.277           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.820           ms/op
