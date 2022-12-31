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
# Warmup Iteration   1: 2.455 ops/ms
# Warmup Iteration   2: 5.846 ops/ms
# Warmup Iteration   3: 8.828 ops/ms
Iteration   1: 10.074 ops/ms
Iteration   2: 9.635 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.799 ±(99.9%) 4.369 ops/ms [Average]
  (min, avg, max) = (9.635, 9.799, 10.074), stdev = 0.239
  CI (99.9%): [5.430, 14.168] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 9.270 ops/ms
# Warmup Iteration   3: 10.207 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.343 ±(99.9%) 3.902 ops/ms [Average]
  (min, avg, max) = (10.111, 10.343, 10.532), stdev = 0.214
  CI (99.9%): [6.441, 14.244] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.247 ops/ms
# Warmup Iteration   2: 9.232 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 10.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.058 ±(99.9%) 2.841 ops/ms [Average]
  (min, avg, max) = (9.950, 10.058, 10.237), stdev = 0.156
  CI (99.9%): [7.217, 12.899] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 7.652 ops/ms
# Warmup Iteration   3: 8.349 ops/ms
Iteration   1: 8.381 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.306 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (8.170, 8.306, 8.381), stdev = 0.118
  CI (99.9%): [6.153, 10.459] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.006 ms/op
Iteration   1: 3.215 ±(99.9%) 0.006 ms/op
Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
Iteration   3: 3.320 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 1.711 ms/op [Average]
  (min, avg, max) = (3.133, 3.222, 3.320), stdev = 0.094
  CI (99.9%): [1.511, 4.934] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.683 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.005 ms/op
Iteration   1: 3.090 ±(99.9%) 0.005 ms/op
Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
Iteration   3: 3.158 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 1.317 ms/op [Average]
  (min, avg, max) = (3.014, 3.087, 3.158), stdev = 0.072
  CI (99.9%): [1.770, 4.404] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.273 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.003 ms/op
Iteration   1: 3.339 ±(99.9%) 0.004 ms/op
Iteration   2: 3.186 ±(99.9%) 0.005 ms/op
Iteration   3: 3.302 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.275 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (3.186, 3.275, 3.339), stdev = 0.080
  CI (99.9%): [1.819, 4.731] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.798 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.009 ms/op
Iteration   1: 3.874 ±(99.9%) 0.006 ms/op
Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
Iteration   3: 3.730 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.797 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.730, 3.797, 3.874), stdev = 0.072
  CI (99.9%): [2.475, 5.119] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.392 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.642 ms/op
                 createUser·p0.999:  19.226 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 22.837 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  16.685 ms/op
                 createUser·p0.9999: 22.730 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297269
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18060 
    [ 2.500,  5.000) = 272382 
    [ 5.000,  7.500) = 5628 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     22.652 ms/op
     p(99.9990) =     27.332 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.008 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  14.779 ms/op
                 existUser·p0.9999: 20.974 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 24.862 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  7.926 ms/op
                 existUser·p0.9999: 38.354 ms/op
                 existUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306676
  mean =      3.128 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 301039 
    [ 5.000, 10.000) = 5198 
    [10.000, 15.000) = 151 
    [15.000, 20.000) = 156 
    [20.000, 25.000) = 96 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     39.304 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.896 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.010 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  16.658 ms/op
                 getUser·p0.9999: 21.278 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  18.695 ms/op
                 getUser·p0.9999: 26.078 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.913 ms/op
                 getUser·p0.999:  11.376 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288825
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21500 
    [ 2.500,  5.000) = 258870 
    [ 5.000,  7.500) = 7655 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.630 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 10.070 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.012 ms/op
Iteration   1: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 27.284 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   2: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.087 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252484
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 245056 
    [ 5.000,  7.500) = 5577 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.030 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     26.362 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.799 ± 4.369  ops/ms
ClientPb.existUser                       thrpt       3  10.343 ± 3.902  ops/ms
ClientPb.getUser                         thrpt       3  10.058 ± 2.841  ops/ms
ClientPb.listUser                        thrpt       3   8.306 ± 2.153  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 1.711   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 1.317   ms/op
ClientPb.getUser                          avgt       3   3.275 ± 1.456   ms/op
ClientPb.listUser                         avgt       3   3.797 ± 1.322   ms/op
ClientPb.createUser                     sample  297269   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.993           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  306676   3.128 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.594           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.910           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.045           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.288           ms/op
ClientPb.getUser                        sample  288825   3.321 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  252484   3.801 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.030           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.362           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.886           ms/op
