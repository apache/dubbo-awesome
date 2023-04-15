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
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 6.582 ops/ms
# Warmup Iteration   3: 9.171 ops/ms
Iteration   1: 9.680 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 9.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.712 ±(99.9%) 6.681 ops/ms [Average]
  (min, avg, max) = (9.362, 9.712, 10.093), stdev = 0.366
  CI (99.9%): [3.031, 16.393] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ops/ms
# Warmup Iteration   2: 9.716 ops/ms
# Warmup Iteration   3: 9.944 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 9.696 ops/ms
Iteration   3: 10.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.028 ±(99.9%) 6.510 ops/ms [Average]
  (min, avg, max) = (9.696, 10.028, 10.405), stdev = 0.357
  CI (99.9%): [3.518, 16.538] (assumes normal distribution)


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
# Warmup Iteration   1: 3.682 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 10.309 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 10.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.150 ±(99.9%) 5.733 ops/ms [Average]
  (min, avg, max) = (9.788, 10.150, 10.353), stdev = 0.314
  CI (99.9%): [4.417, 15.883] (assumes normal distribution)


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
# Warmup Iteration   1: 3.046 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 8.547 ops/ms
Iteration   1: 8.612 ops/ms
Iteration   2: 8.431 ops/ms
Iteration   3: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.391 ±(99.9%) 4.437 ops/ms [Average]
  (min, avg, max) = (8.130, 8.391, 8.612), stdev = 0.243
  CI (99.9%): [3.954, 12.828] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.006 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.005 ms/op
Iteration   1: 3.175 ±(99.9%) 0.010 ms/op
Iteration   2: 3.327 ±(99.9%) 0.004 ms/op
Iteration   3: 3.253 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.252 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.175, 3.252, 3.327), stdev = 0.076
  CI (99.9%): [1.857, 4.646] (assumes normal distribution)


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
# Warmup Iteration   1: 8.799 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.107 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (3.021, 3.107, 3.227), stdev = 0.107
  CI (99.9%): [1.152, 5.063] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.004 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
Iteration   3: 3.346 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 1.590 ms/op [Average]
  (min, avg, max) = (3.182, 3.248, 3.346), stdev = 0.087
  CI (99.9%): [1.658, 4.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.567 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.003 ms/op
Iteration   1: 3.644 ±(99.9%) 0.012 ms/op
Iteration   2: 3.608 ±(99.9%) 0.014 ms/op
Iteration   3: 3.571 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.608 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.571, 3.608, 3.644), stdev = 0.037
  CI (99.9%): [2.941, 4.275] (assumes normal distribution)


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
Iteration   1: 3.216 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.316 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  17.001 ms/op
                 createUser·p0.9999: 22.753 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.449 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 20.541 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297239
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25789 
    [ 2.500,  5.000) = 263967 
    [ 5.000,  7.500) = 6507 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     22.226 ms/op
     p(99.9990) =     24.085 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 7.271 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.132 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  14.615 ms/op
                 existUser·p0.9999: 22.524 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 24.793 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.872 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306080
  mean =      3.133 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29800 
    [ 2.500,  5.000) = 270009 
    [ 5.000,  7.500) = 5436 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     23.540 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 8.040 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
Iteration   1: 3.106 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 24.304 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 25.530 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  11.867 ms/op
                 getUser·p0.9999: 19.300 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302929
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12204 
    [ 2.500,  5.000) = 285004 
    [ 5.000,  7.500) = 4865 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.483 ms/op
     p(99.9900) =     23.455 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 9.119 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.666 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.316 ms/op
                 listUser·p0.999:  17.490 ms/op
                 listUser·p0.9999: 19.819 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.717 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.515 ms/op
                 listUser·p0.999:  17.594 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.707 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  12.594 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259631
  mean =      3.696 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 253293 
    [ 5.000,  7.500) = 4294 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     22.848 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.712 ± 6.681  ops/ms
ClientPb.existUser                       thrpt       3  10.028 ± 6.510  ops/ms
ClientPb.getUser                         thrpt       3  10.150 ± 5.733  ops/ms
ClientPb.listUser                        thrpt       3   8.391 ± 4.437  ops/ms
ClientPb.createUser                       avgt       3   3.252 ± 1.394   ms/op
ClientPb.existUser                        avgt       3   3.107 ± 1.956   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 1.590   ms/op
ClientPb.listUser                         avgt       3   3.608 ± 0.667   ms/op
ClientPb.createUser                     sample  297239   3.227 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.226           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.117           ms/op
ClientPb.existUser                      sample  306080   3.133 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.540           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.494           ms/op
ClientPb.getUser                        sample  302929   3.167 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.147           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.483           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.455           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  259631   3.696 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.412           ms/op
