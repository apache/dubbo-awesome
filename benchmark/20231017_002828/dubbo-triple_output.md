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
# Warmup Iteration   1: 2.407 ops/ms
# Warmup Iteration   2: 5.620 ops/ms
# Warmup Iteration   3: 9.197 ops/ms
Iteration   1: 9.502 ops/ms
Iteration   2: 9.816 ops/ms
Iteration   3: 9.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.643 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (9.502, 9.643, 9.816), stdev = 0.160
  CI (99.9%): [6.730, 12.556] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 10.114 ops/ms
Iteration   1: 10.013 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.989 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (9.886, 9.989, 10.069), stdev = 0.094
  CI (99.9%): [8.280, 11.699] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.577 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.659 ±(99.9%) 3.628 ops/ms [Average]
  (min, avg, max) = (9.478, 9.659, 9.872), stdev = 0.199
  CI (99.9%): [6.031, 13.287] (assumes normal distribution)


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
# Warmup Iteration   1: 3.256 ops/ms
# Warmup Iteration   2: 7.547 ops/ms
# Warmup Iteration   3: 7.964 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.207 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (8.038, 8.207, 8.372), stdev = 0.167
  CI (99.9%): [5.153, 11.262] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.235 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.006 ms/op
Iteration   1: 3.340 ±(99.9%) 0.007 ms/op
Iteration   2: 3.316 ±(99.9%) 0.003 ms/op
Iteration   3: 3.295 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.317 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.295, 3.317, 3.340), stdev = 0.022
  CI (99.9%): [2.907, 3.727] (assumes normal distribution)


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
# Warmup Iteration   1: 7.711 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.005 ms/op
Iteration   1: 3.254 ±(99.9%) 0.005 ms/op
Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
Iteration   3: 3.174 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.210 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.174, 3.210, 3.254), stdev = 0.040
  CI (99.9%): [2.474, 3.947] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.713 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.003 ms/op
Iteration   1: 3.402 ±(99.9%) 0.002 ms/op
Iteration   2: 3.317 ±(99.9%) 0.002 ms/op
Iteration   3: 3.270 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.330 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.270, 3.330, 3.402), stdev = 0.067
  CI (99.9%): [2.109, 4.550] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.952 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.004 ms/op
Iteration   1: 3.864 ±(99.9%) 0.004 ms/op
Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
Iteration   3: 3.853 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.845 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (3.817, 3.845, 3.864), stdev = 0.024
  CI (99.9%): [3.402, 4.288] (assumes normal distribution)


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
# Warmup Iteration   1: 8.539 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  14.088 ms/op
                 createUser·p0.9999: 20.820 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  14.008 ms/op
                 createUser·p0.9999: 23.535 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 19.298 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292815
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10517 
    [ 2.500,  5.000) = 277790 
    [ 5.000,  7.500) = 3774 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.796 ms/op
     p(99.9900) =     22.076 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.580 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
Iteration   1: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.570 ms/op
                 existUser·p0.9999: 23.017 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  14.221 ms/op
                 existUser·p0.9999: 23.219 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  15.601 ms/op
                 existUser·p0.9999: 21.952 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300713
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17924 
    [ 2.500,  5.000) = 278241 
    [ 5.000,  7.500) = 3546 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     15.127 ms/op
     p(99.9900) =     22.706 ms/op
     p(99.9990) =     24.313 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 8.878 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
Iteration   1: 3.388 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  16.029 ms/op
                 getUser·p0.9999: 18.434 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 20.325 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 20.849 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289036
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11491 
    [ 2.500,  5.000) = 269465 
    [ 5.000,  7.500) = 6994 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     16.416 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.143 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.688 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.010 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  17.735 ms/op
                 listUser·p0.9999: 20.632 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.995 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.376 ms/op
                 listUser·p0.999:  14.184 ms/op
                 listUser·p0.9999: 16.907 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 3.893 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.551 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.634 ms/op
                 listUser·p0.999:  12.876 ms/op
                 listUser·p0.9999: 14.958 ms/op
                 listUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244137
  mean =      3.933 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 237413 
    [ 5.000,  7.500) = 4929 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 451 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.270 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.643 ± 2.913  ops/ms
ClientPb.existUser                       thrpt       3   9.989 ± 1.709  ops/ms
ClientPb.getUser                         thrpt       3   9.659 ± 3.628  ops/ms
ClientPb.listUser                        thrpt       3   8.207 ± 3.054  ops/ms
ClientPb.createUser                       avgt       3   3.317 ± 0.410   ms/op
ClientPb.existUser                        avgt       3   3.210 ± 0.736   ms/op
ClientPb.getUser                          avgt       3   3.330 ± 1.220   ms/op
ClientPb.listUser                         avgt       3   3.845 ± 0.443   ms/op
ClientPb.createUser                     sample  292815   3.276 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.796           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.773           ms/op
ClientPb.existUser                      sample  300713   3.192 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.127           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.706           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  289036   3.320 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.555           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.416           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.365           ms/op
ClientPb.listUser                       sample  244137   3.933 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.551           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.463           ms/op
