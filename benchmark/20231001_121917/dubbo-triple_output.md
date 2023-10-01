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
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 5.690 ops/ms
# Warmup Iteration   3: 9.073 ops/ms
Iteration   1: 9.566 ops/ms
Iteration   2: 9.713 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.625 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (9.566, 9.625, 9.713), stdev = 0.077
  CI (99.9%): [8.212, 11.038] (assumes normal distribution)


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
# Warmup Iteration   1: 3.170 ops/ms
# Warmup Iteration   2: 8.668 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.133 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.047 ±(99.9%) 1.525 ops/ms [Average]
  (min, avg, max) = (9.966, 10.047, 10.133), stdev = 0.084
  CI (99.9%): [8.522, 11.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 8.843 ops/ms
# Warmup Iteration   3: 9.618 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 10.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.850 ±(99.9%) 2.396 ops/ms [Average]
  (min, avg, max) = (9.771, 9.850, 10.001), stdev = 0.131
  CI (99.9%): [7.453, 12.246] (assumes normal distribution)


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
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 7.774 ops/ms
# Warmup Iteration   3: 8.307 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.338 ±(99.9%) 0.300 ops/ms [Average]
  (min, avg, max) = (8.321, 8.338, 8.354), stdev = 0.016
  CI (99.9%): [8.037, 8.638] (assumes normal distribution)


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
# Warmup Iteration   1: 8.727 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.002 ms/op
Iteration   1: 3.235 ±(99.9%) 0.002 ms/op
Iteration   2: 3.328 ±(99.9%) 0.001 ms/op
Iteration   3: 3.203 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.256 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (3.203, 3.256, 3.328), stdev = 0.065
  CI (99.9%): [2.074, 4.437] (assumes normal distribution)


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
# Warmup Iteration   1: 8.803 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.256 ±(99.9%) 0.004 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.193 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.157, 3.193, 3.256), stdev = 0.055
  CI (99.9%): [2.194, 4.193] (assumes normal distribution)


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
# Warmup Iteration   1: 7.724 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.002 ms/op
Iteration   1: 3.300 ±(99.9%) 0.005 ms/op
Iteration   2: 3.248 ±(99.9%) 0.003 ms/op
Iteration   3: 3.261 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.270 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.248, 3.270, 3.300), stdev = 0.027
  CI (99.9%): [2.774, 3.766] (assumes normal distribution)


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
# Warmup Iteration   1: 9.053 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.004 ms/op
Iteration   1: 3.907 ±(99.9%) 0.006 ms/op
Iteration   2: 3.870 ±(99.9%) 0.005 ms/op
Iteration   3: 3.832 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.870 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.832, 3.870, 3.907), stdev = 0.037
  CI (99.9%): [3.191, 4.548] (assumes normal distribution)


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
# Warmup Iteration   1: 8.123 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  15.363 ms/op
                 createUser·p0.9999: 20.285 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.289 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  13.644 ms/op
                 createUser·p0.9999: 18.830 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294493
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17800 
    [ 2.500,  5.000) = 272863 
    [ 5.000,  7.500) = 2995 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.506 ms/op
     p(99.9000) =     15.295 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.712 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 6.761 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.216 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  12.775 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  15.142 ms/op
                 existUser·p0.9999: 24.363 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.555 ms/op
                 existUser·p0.999:  13.627 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299343
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25350 
    [ 2.500,  5.000) = 268594 
    [ 5.000,  7.500) = 4339 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     23.497 ms/op
     p(99.9990) =     25.134 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 9.298 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
Iteration   1: 3.241 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  15.716 ms/op
                 getUser·p0.9999: 20.746 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.693 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  15.106 ms/op
                 getUser·p0.9999: 20.269 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294363
  mean =      3.260 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8084 
    [ 2.500,  5.000) = 281827 
    [ 5.000,  7.500) = 3770 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.116 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.545 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 9.498 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.154 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 23.816 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   8.206 ms/op
                 listUser·p0.999:  14.730 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247373
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 239042 
    [ 5.000,  7.500) = 5816 
    [ 7.500, 10.000) = 1732 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     22.243 ms/op
     p(99.9990) =     24.233 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.625 ± 1.413  ops/ms
ClientPb.existUser                       thrpt       3  10.047 ± 1.525  ops/ms
ClientPb.getUser                         thrpt       3   9.850 ± 2.396  ops/ms
ClientPb.listUser                        thrpt       3   8.338 ± 0.300  ops/ms
ClientPb.createUser                       avgt       3   3.256 ± 1.182   ms/op
ClientPb.existUser                        avgt       3   3.193 ± 0.999   ms/op
ClientPb.getUser                          avgt       3   3.270 ± 0.496   ms/op
ClientPb.listUser                         avgt       3   3.870 ± 0.679   ms/op
ClientPb.createUser                     sample  294493   3.258 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.506           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.295           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.905           ms/op
ClientPb.existUser                      sample  299343   3.205 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.497           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.428           ms/op
ClientPb.getUser                        sample  294363   3.260 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.030           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.116           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.362           ms/op
ClientPb.listUser                       sample  247373   3.877 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.975           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.243           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
