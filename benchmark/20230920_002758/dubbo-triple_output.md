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
# Warmup Iteration   1: 2.268 ops/ms
# Warmup Iteration   2: 5.650 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 9.234 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 9.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.145 ±(99.9%) 2.834 ops/ms [Average]
  (min, avg, max) = (8.965, 9.145, 9.235), stdev = 0.155
  CI (99.9%): [6.311, 11.979] (assumes normal distribution)


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
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 8.921 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.595 ops/ms
Iteration   3: 9.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.597 ±(99.9%) 2.277 ops/ms [Average]
  (min, avg, max) = (9.473, 9.597, 9.723), stdev = 0.125
  CI (99.9%): [7.320, 11.874] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 8.732 ops/ms
# Warmup Iteration   3: 8.857 ops/ms
Iteration   1: 9.172 ops/ms
Iteration   2: 9.170 ops/ms
Iteration   3: 9.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.191 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (9.170, 9.191, 9.233), stdev = 0.036
  CI (99.9%): [8.540, 9.843] (assumes normal distribution)


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
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 6.812 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 7.483 ops/ms
Iteration   2: 7.774 ops/ms
Iteration   3: 7.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.620 ±(99.9%) 2.669 ops/ms [Average]
  (min, avg, max) = (7.483, 7.620, 7.774), stdev = 0.146
  CI (99.9%): [4.951, 10.289] (assumes normal distribution)


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.002 ms/op
Iteration   1: 3.488 ±(99.9%) 0.006 ms/op
Iteration   2: 3.421 ±(99.9%) 0.003 ms/op
Iteration   3: 3.476 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.462 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.421, 3.462, 3.488), stdev = 0.036
  CI (99.9%): [2.804, 4.119] (assumes normal distribution)


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
# Warmup Iteration   1: 9.709 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.002 ms/op
Iteration   1: 3.333 ±(99.9%) 0.004 ms/op
Iteration   2: 3.316 ±(99.9%) 0.005 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.316, 3.325, 3.333), stdev = 0.008
  CI (99.9%): [3.175, 3.475] (assumes normal distribution)


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
# Warmup Iteration   1: 9.023 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.004 ms/op
Iteration   1: 3.524 ±(99.9%) 0.004 ms/op
Iteration   2: 3.423 ±(99.9%) 0.003 ms/op
Iteration   3: 3.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.423, 3.463, 3.524), stdev = 0.054
  CI (99.9%): [2.474, 4.451] (assumes normal distribution)


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
# Warmup Iteration   1: 9.520 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.007 ms/op
Iteration   1: 4.164 ±(99.9%) 0.007 ms/op
Iteration   2: 4.189 ±(99.9%) 0.009 ms/op
Iteration   3: 4.121 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.158 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (4.121, 4.158, 4.189), stdev = 0.035
  CI (99.9%): [3.528, 4.788] (assumes normal distribution)


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
# Warmup Iteration   1: 8.870 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.008 ms/op
Iteration   1: 3.466 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.274 ms/op
                 createUser·p0.9999: 18.629 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.563 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  18.699 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.621 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 25.417 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275439
  mean =      3.485 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4428 
    [ 2.500,  5.000) = 265647 
    [ 5.000,  7.500) = 4198 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     24.394 ms/op
     p(99.9990) =     25.928 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  16.302 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.455 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  19.918 ms/op
                 existUser·p0.9999: 28.966 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281212
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10227 
    [ 2.500,  5.000) = 265562 
    [ 5.000,  7.500) = 4077 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     16.834 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.667 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 7.845 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.010 ms/op
Iteration   1: 3.640 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.539 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 24.459 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.569 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  23.047 ms/op
                 getUser·p0.9999: 25.531 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.527 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  10.883 ms/op
                 getUser·p0.9999: 25.870 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268226
  mean =      3.578 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5878 
    [ 2.500,  5.000) = 254372 
    [ 5.000,  7.500) = 6732 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 163 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     25.401 ms/op
     p(99.9990) =     26.813 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 9.418 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.013 ms/op
Iteration   1: 4.218 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  22.413 ms/op
                 listUser·p0.9999: 26.707 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.175 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.948 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 4.132 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.133 ms/op
                 listUser·p0.9999: 18.730 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229743
  mean =      4.175 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 220870 
    [ 5.000,  7.500) = 6703 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     24.086 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.145 ± 2.834  ops/ms
ClientPb.existUser                       thrpt       3   9.597 ± 2.277  ops/ms
ClientPb.getUser                         thrpt       3   9.191 ± 0.651  ops/ms
ClientPb.listUser                        thrpt       3   7.620 ± 2.669  ops/ms
ClientPb.createUser                       avgt       3   3.462 ± 0.657   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 0.989   ms/op
ClientPb.listUser                         avgt       3   4.158 ± 0.630   ms/op
ClientPb.createUser                     sample  275439   3.485 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.689           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.629           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.394           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.313           ms/op
ClientPb.existUser                      sample  281212   3.413 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.834           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  268226   3.578 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.925           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.401           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  229743   4.175 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.318           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
