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
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 5.596 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.672 ops/ms
Iteration   2: 9.804 ops/ms
Iteration   3: 9.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.751 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (9.672, 9.751, 9.804), stdev = 0.070
  CI (99.9%): [8.479, 11.024] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.135 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.072 ±(99.9%) 0.641 ops/ms [Average]
  (min, avg, max) = (10.039, 10.072, 10.109), stdev = 0.035
  CI (99.9%): [9.431, 10.712] (assumes normal distribution)


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
# Warmup Iteration   1: 3.458 ops/ms
# Warmup Iteration   2: 9.216 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.966 ±(99.9%) 4.524 ops/ms [Average]
  (min, avg, max) = (9.680, 9.966, 10.123), stdev = 0.248
  CI (99.9%): [5.441, 14.490] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.703 ops/ms
# Warmup Iteration   3: 8.432 ops/ms
Iteration   1: 8.467 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.422 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (8.339, 8.422, 8.467), stdev = 0.072
  CI (99.9%): [7.116, 9.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.772 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.004 ms/op
Iteration   1: 3.338 ±(99.9%) 0.003 ms/op
Iteration   2: 3.247 ±(99.9%) 0.005 ms/op
Iteration   3: 3.292 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.292 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.247, 3.292, 3.338), stdev = 0.045
  CI (99.9%): [2.466, 4.119] (assumes normal distribution)


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
# Warmup Iteration   1: 8.158 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.003 ms/op
Iteration   1: 3.111 ±(99.9%) 0.004 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.109 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.079, 3.109, 3.135), stdev = 0.028
  CI (99.9%): [2.598, 3.620] (assumes normal distribution)


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
# Warmup Iteration   1: 8.358 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.003 ms/op
Iteration   1: 3.244 ±(99.9%) 0.002 ms/op
Iteration   2: 3.252 ±(99.9%) 0.004 ms/op
Iteration   3: 3.219 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.219, 3.238, 3.252), stdev = 0.017
  CI (99.9%): [2.921, 3.555] (assumes normal distribution)


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
# Warmup Iteration   1: 9.303 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.006 ms/op
Iteration   1: 3.785 ±(99.9%) 0.008 ms/op
Iteration   2: 3.823 ±(99.9%) 0.009 ms/op
Iteration   3: 3.755 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.788 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (3.755, 3.788, 3.823), stdev = 0.034
  CI (99.9%): [3.175, 4.401] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  16.105 ms/op
                 createUser·p0.9999: 20.483 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   6.155 ms/op
                 createUser·p0.999:  15.483 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296345
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16100 
    [ 2.500,  5.000) = 275833 
    [ 5.000,  7.500) = 3582 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     16.831 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 7.172 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.066 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 20.053 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  12.387 ms/op
                 existUser·p0.9999: 24.773 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  10.538 ms/op
                 existUser·p0.9999: 18.413 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304617
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14490 
    [ 2.500,  5.000) = 286126 
    [ 5.000,  7.500) = 3089 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.968 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 7.618 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  17.382 ms/op
                 getUser·p0.9999: 20.291 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 20.392 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.327 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  14.147 ms/op
                 getUser·p0.9999: 18.670 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292105
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14412 
    [ 2.500,  5.000) = 271820 
    [ 5.000,  7.500) = 4761 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 219 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     20.211 ms/op
     p(99.9990) =     21.400 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 9.142 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.012 ms/op
Iteration   1: 3.824 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.358 ms/op
                 listUser·p0.9999: 24.538 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 3.868 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.180 ms/op
                 listUser·p0.999:  13.441 ms/op
                 listUser·p0.9999: 14.402 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   3: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 16.790 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248727
  mean =      3.857 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 241315 
    [ 5.000,  7.500) = 5249 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     25.969 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.751 ± 1.272  ops/ms
ClientPb.existUser                       thrpt       3  10.072 ± 0.641  ops/ms
ClientPb.getUser                         thrpt       3   9.966 ± 4.524  ops/ms
ClientPb.listUser                        thrpt       3   8.422 ± 1.306  ops/ms
ClientPb.createUser                       avgt       3   3.292 ± 0.826   ms/op
ClientPb.existUser                        avgt       3   3.109 ± 0.511   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 0.317   ms/op
ClientPb.listUser                         avgt       3   3.788 ± 0.613   ms/op
ClientPb.createUser                     sample  296345   3.236 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.556           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  304617   3.149 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.019           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.527           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.297           ms/op
ClientPb.getUser                        sample  292105   3.285 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.969           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.211           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.529           ms/op
ClientPb.listUser                       sample  248727   3.857 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.120           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.681           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.856           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.018           ms/op
