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
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 6.556 ops/ms
# Warmup Iteration   3: 9.065 ops/ms
Iteration   1: 9.726 ops/ms
Iteration   2: 9.890 ops/ms
Iteration   3: 10.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.879 ±(99.9%) 2.692 ops/ms [Average]
  (min, avg, max) = (9.726, 9.879, 10.021), stdev = 0.148
  CI (99.9%): [7.187, 12.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 8.869 ops/ms
# Warmup Iteration   3: 9.423 ops/ms
Iteration   1: 9.843 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.198 ±(99.9%) 6.214 ops/ms [Average]
  (min, avg, max) = (9.843, 10.198, 10.522), stdev = 0.341
  CI (99.9%): [3.984, 16.411] (assumes normal distribution)


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
# Warmup Iteration   1: 3.187 ops/ms
# Warmup Iteration   2: 9.081 ops/ms
# Warmup Iteration   3: 9.667 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 10.253 ops/ms
Iteration   3: 10.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.978 ±(99.9%) 5.600 ops/ms [Average]
  (min, avg, max) = (9.647, 9.978, 10.253), stdev = 0.307
  CI (99.9%): [4.378, 15.578] (assumes normal distribution)


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
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 7.981 ops/ms
# Warmup Iteration   3: 8.441 ops/ms
Iteration   1: 8.563 ops/ms
Iteration   2: 8.442 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.532 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (8.442, 8.532, 8.591), stdev = 0.079
  CI (99.9%): [7.091, 9.973] (assumes normal distribution)


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
# Warmup Iteration   1: 8.995 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.007 ms/op
Iteration   1: 3.300 ±(99.9%) 0.008 ms/op
Iteration   2: 3.291 ±(99.9%) 0.005 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.244 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (3.141, 3.244, 3.300), stdev = 0.089
  CI (99.9%): [1.615, 4.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
Iteration   3: 3.213 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.110 ±(99.9%) 1.642 ms/op [Average]
  (min, avg, max) = (3.045, 3.110, 3.213), stdev = 0.090
  CI (99.9%): [1.468, 4.753] (assumes normal distribution)


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
# Warmup Iteration   1: 9.040 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.004 ms/op
Iteration   1: 3.222 ±(99.9%) 0.007 ms/op
Iteration   2: 3.377 ±(99.9%) 0.005 ms/op
Iteration   3: 3.133 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.244 ±(99.9%) 2.256 ms/op [Average]
  (min, avg, max) = (3.133, 3.244, 3.377), stdev = 0.124
  CI (99.9%): [0.988, 5.500] (assumes normal distribution)


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
# Warmup Iteration   1: 9.213 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.008 ms/op
Iteration   1: 3.771 ±(99.9%) 0.008 ms/op
Iteration   2: 3.699 ±(99.9%) 0.006 ms/op
Iteration   3: 3.720 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.730 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.699, 3.730, 3.771), stdev = 0.037
  CI (99.9%): [3.054, 4.407] (assumes normal distribution)


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
# Warmup Iteration   1: 7.352 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
Iteration   1: 3.220 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 25.916 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  16.937 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295766
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32563 
    [ 2.500,  5.000) = 258205 
    [ 5.000,  7.500) = 4311 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     16.048 ms/op
     p(99.9900) =     24.355 ms/op
     p(99.9990) =     26.380 ms/op
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
# Warmup Iteration   1: 7.144 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.371 ms/op
                 existUser·p0.999:  17.812 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 23.356 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.558 ms/op
                 existUser·p0.999:  11.558 ms/op
                 existUser·p0.9999: 22.567 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300076
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31307 
    [ 2.500,  5.000) = 263766 
    [ 5.000,  7.500) = 4280 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     11.386 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 8.045 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.010 ms/op
Iteration   1: 3.165 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   6.224 ms/op
                 getUser·p0.999:  17.464 ms/op
                 getUser·p0.9999: 21.357 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  9.834 ms/op
                 getUser·p0.9999: 23.421 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  16.810 ms/op
                 getUser·p0.9999: 25.926 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299506
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12504 
    [ 2.500,  5.000) = 282285 
    [ 5.000,  7.500) = 3944 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     24.479 ms/op
     p(99.9990) =     26.379 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 9.966 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.011 ms/op
Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   5.931 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 28.049 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 3.733 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 16.293 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   3: 3.725 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 18.242 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258574
  mean =      3.710 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 252672 
    [ 5.000,  7.500) = 4425 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.879 ± 2.692  ops/ms
ClientPb.existUser                       thrpt       3  10.198 ± 6.214  ops/ms
ClientPb.getUser                         thrpt       3   9.978 ± 5.600  ops/ms
ClientPb.listUser                        thrpt       3   8.532 ± 1.441  ops/ms
ClientPb.createUser                       avgt       3   3.244 ± 1.629   ms/op
ClientPb.existUser                        avgt       3   3.110 ± 1.642   ms/op
ClientPb.getUser                          avgt       3   3.244 ± 2.256   ms/op
ClientPb.listUser                         avgt       3   3.730 ± 0.676   ms/op
ClientPb.createUser                     sample  295766   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.048           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.355           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  300076   3.199 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.428           ms/op
ClientPb.getUser                        sample  299506   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  258574   3.710 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.147           ms/op
