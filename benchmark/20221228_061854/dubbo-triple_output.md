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
# Warmup Iteration   1: 2.460 ops/ms
# Warmup Iteration   2: 5.637 ops/ms
# Warmup Iteration   3: 8.901 ops/ms
Iteration   1: 9.749 ops/ms
Iteration   2: 9.985 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.933 ±(99.9%) 3.002 ops/ms [Average]
  (min, avg, max) = (9.749, 9.933, 10.065), stdev = 0.165
  CI (99.9%): [6.931, 12.934] (assumes normal distribution)


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
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 9.650 ops/ms
# Warmup Iteration   3: 10.165 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 10.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.227 ±(99.9%) 3.287 ops/ms [Average]
  (min, avg, max) = (10.037, 10.227, 10.395), stdev = 0.180
  CI (99.9%): [6.940, 13.514] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 8.710 ops/ms
# Warmup Iteration   3: 9.490 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.082 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (10.027, 10.082, 10.111), stdev = 0.048
  CI (99.9%): [9.207, 10.958] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 8.447 ops/ms
Iteration   3: 8.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.237 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (7.976, 8.237, 8.447), stdev = 0.240
  CI (99.9%): [3.860, 12.615] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.338 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.005 ms/op
Iteration   1: 3.384 ±(99.9%) 0.008 ms/op
Iteration   2: 3.318 ±(99.9%) 0.003 ms/op
Iteration   3: 3.173 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.292 ±(99.9%) 1.968 ms/op [Average]
  (min, avg, max) = (3.173, 3.292, 3.384), stdev = 0.108
  CI (99.9%): [1.324, 5.260] (assumes normal distribution)


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
# Warmup Iteration   1: 7.204 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.002 ms/op
Iteration   1: 3.227 ±(99.9%) 0.006 ms/op
Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
Iteration   3: 3.239 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.221 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.199, 3.221, 3.239), stdev = 0.021
  CI (99.9%): [2.843, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 9.308 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.004 ms/op
Iteration   1: 3.268 ±(99.9%) 0.009 ms/op
Iteration   2: 3.182 ±(99.9%) 0.005 ms/op
Iteration   3: 3.147 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.199 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.147, 3.199, 3.268), stdev = 0.062
  CI (99.9%): [2.063, 4.336] (assumes normal distribution)


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
# Warmup Iteration   1: 9.045 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.004 ms/op
Iteration   1: 3.846 ±(99.9%) 0.007 ms/op
Iteration   2: 3.903 ±(99.9%) 0.004 ms/op
Iteration   3: 3.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.879 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.846, 3.879, 3.903), stdev = 0.029
  CI (99.9%): [3.348, 4.409] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.153 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.265 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  9.553 ms/op
                 createUser·p0.9999: 21.516 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.257 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  14.975 ms/op
                 createUser·p0.9999: 23.040 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 22.144 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298759
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17143 
    [ 2.500,  5.000) = 276711 
    [ 5.000,  7.500) = 3995 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.637 ms/op
     p(99.9900) =     22.614 ms/op
     p(99.9990) =     23.561 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.828 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  10.196 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  15.480 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.162 ms/op
                 existUser·p0.9999: 23.204 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301397
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22196 
    [ 2.500,  5.000) = 273072 
    [ 5.000,  7.500) = 5139 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     21.688 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 9.493 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
Iteration   1: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  17.762 ms/op
                 getUser·p0.9999: 22.774 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.698 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  12.904 ms/op
                 getUser·p0.9999: 24.004 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  15.241 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287913
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15724 
    [ 2.500,  5.000) = 263887 
    [ 5.000,  7.500) = 7339 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     15.878 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.285 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 9.423 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.310 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.019 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.802 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.308 ms/op
                 listUser·p0.999:  14.758 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 3.848 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 17.314 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247780
  mean =      3.875 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 240512 
    [ 5.000,  7.500) = 5419 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.766 ms/op
     p(99.9900) =     21.012 ms/op
     p(99.9990) =     22.600 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.933 ± 3.002  ops/ms
ClientPb.existUser                       thrpt       3  10.227 ± 3.287  ops/ms
ClientPb.getUser                         thrpt       3  10.082 ± 0.875  ops/ms
ClientPb.listUser                        thrpt       3   8.237 ± 4.378  ops/ms
ClientPb.createUser                       avgt       3   3.292 ± 1.968   ms/op
ClientPb.existUser                        avgt       3   3.221 ± 0.379   ms/op
ClientPb.getUser                          avgt       3   3.199 ± 1.137   ms/op
ClientPb.listUser                         avgt       3   3.879 ± 0.531   ms/op
ClientPb.createUser                     sample  298759   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.637           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.614           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.117           ms/op
ClientPb.existUser                      sample  301397   3.183 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.772           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.688           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.757           ms/op
ClientPb.getUser                        sample  287913   3.330 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.576           ms/op
ClientPb.listUser                       sample  247780   3.875 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.407           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.766           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.012           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
