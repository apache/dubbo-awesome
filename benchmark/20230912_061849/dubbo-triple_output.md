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
# Warmup Iteration   1: 2.025 ops/ms
# Warmup Iteration   2: 5.139 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 8.775 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.863 ±(99.9%) 11.049 ops/ms [Average]
  (min, avg, max) = (8.306, 8.863, 9.508), stdev = 0.606
  CI (99.9%): [≈ 0, 19.912] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 8.622 ops/ms
# Warmup Iteration   3: 9.272 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.594 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.431 ±(99.9%) 2.657 ops/ms [Average]
  (min, avg, max) = (9.313, 9.431, 9.594), stdev = 0.146
  CI (99.9%): [6.775, 12.088] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 8.851 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.496 ops/ms
Iteration   3: 8.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.247 ±(99.9%) 5.316 ops/ms [Average]
  (min, avg, max) = (8.926, 9.247, 9.496), stdev = 0.291
  CI (99.9%): [3.931, 14.563] (assumes normal distribution)


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
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 6.993 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.821 ±(99.9%) 0.815 ops/ms [Average]
  (min, avg, max) = (7.777, 7.821, 7.866), stdev = 0.045
  CI (99.9%): [7.006, 8.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.289 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.008 ms/op
Iteration   1: 3.600 ±(99.9%) 0.003 ms/op
Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
Iteration   3: 3.304 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.444 ±(99.9%) 2.706 ms/op [Average]
  (min, avg, max) = (3.304, 3.444, 3.600), stdev = 0.148
  CI (99.9%): [0.738, 6.150] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.666 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.332 ±(99.9%) 0.008 ms/op
Iteration   2: 3.307 ±(99.9%) 0.005 ms/op
Iteration   3: 3.202 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.202, 3.280, 3.332), stdev = 0.069
  CI (99.9%): [2.018, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 8.844 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.005 ms/op
Iteration   1: 3.600 ±(99.9%) 0.003 ms/op
Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
Iteration   3: 3.485 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 1.599 ms/op [Average]
  (min, avg, max) = (3.428, 3.504, 3.600), stdev = 0.088
  CI (99.9%): [1.905, 5.104] (assumes normal distribution)


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
# Warmup Iteration   1: 11.508 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.007 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
Iteration   2: 4.117 ±(99.9%) 0.009 ms/op
Iteration   3: 4.053 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.077 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (4.053, 4.077, 4.117), stdev = 0.035
  CI (99.9%): [3.445, 4.710] (assumes normal distribution)


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
# Warmup Iteration   1: 8.441 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.463 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  22.093 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  22.394 ms/op
                 createUser·p0.9999: 26.956 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.788 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  19.199 ms/op
                 createUser·p0.9999: 24.039 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280196
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10570 
    [ 2.500,  5.000) = 262563 
    [ 5.000,  7.500) = 5673 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     19.359 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.495 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.072 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
Iteration   1: 3.382 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  21.050 ms/op
                 existUser·p0.9999: 27.152 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.122 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 29.029 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 3.382 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.516 ms/op
                 existUser·p0.999:  25.129 ms/op
                 existUser·p0.9999: 30.248 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280146
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8763 
    [ 2.500,  5.000) = 263600 
    [ 5.000,  7.500) = 6402 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     13.332 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     31.057 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 8.665 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 24.009 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.549 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  22.078 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 25.916 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272262
  mean =      3.522 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2810 
    [ 2.500,  5.000) = 257486 
    [ 5.000,  7.500) = 9901 
    [ 7.500, 10.000) = 1404 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     19.128 ms/op
     p(99.9900) =     25.847 ms/op
     p(99.9990) =     27.458 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 10.572 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.228 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.058 ms/op
                 listUser·p0.999:  22.163 ms/op
                 listUser·p0.9999: 30.933 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 4.185 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  15.967 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 25.199 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230868
  mean =      4.156 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 219398 
    [ 5.000,  7.500) = 8831 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     28.208 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.863 ± 11.049  ops/ms
ClientPb.existUser                       thrpt       3   9.431 ±  2.657  ops/ms
ClientPb.getUser                         thrpt       3   9.247 ±  5.316  ops/ms
ClientPb.listUser                        thrpt       3   7.821 ±  0.815  ops/ms
ClientPb.createUser                       avgt       3   3.444 ±  2.706   ms/op
ClientPb.existUser                        avgt       3   3.280 ±  1.263   ms/op
ClientPb.getUser                          avgt       3   3.504 ±  1.599   ms/op
ClientPb.listUser                         avgt       3   4.077 ±  0.633   ms/op
ClientPb.createUser                     sample  280196   3.425 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.359            ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.001            ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098            ms/op
ClientPb.existUser                      sample  280146   3.425 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.225            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.332            ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.164            ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425            ms/op
ClientPb.getUser                        sample  272262   3.522 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.002            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.021            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.128            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.847            ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689            ms/op
ClientPb.listUser                       sample  230868   4.156 ±  0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.967            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750            ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.208            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014            ms/op
