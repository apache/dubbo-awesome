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
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 5.750 ops/ms
# Warmup Iteration   3: 9.012 ops/ms
Iteration   1: 9.958 ops/ms
Iteration   2: 10.208 ops/ms
Iteration   3: 10.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.084 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (9.958, 10.084, 10.208), stdev = 0.125
  CI (99.9%): [7.811, 12.357] (assumes normal distribution)


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
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 9.505 ops/ms
# Warmup Iteration   3: 10.014 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.173 ops/ms
Iteration   3: 10.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.275 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (10.173, 10.275, 10.350), stdev = 0.091
  CI (99.9%): [8.606, 11.944] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 9.469 ops/ms
Iteration   1: 9.654 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.857 ±(99.9%) 8.281 ops/ms [Average]
  (min, avg, max) = (9.541, 9.857, 10.377), stdev = 0.454
  CI (99.9%): [1.576, 18.138] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.492 ops/ms
# Warmup Iteration   2: 8.029 ops/ms
# Warmup Iteration   3: 8.531 ops/ms
Iteration   1: 8.711 ops/ms
Iteration   2: 8.423 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.579 ±(99.9%) 2.661 ops/ms [Average]
  (min, avg, max) = (8.423, 8.579, 8.711), stdev = 0.146
  CI (99.9%): [5.918, 11.240] (assumes normal distribution)


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
# Warmup Iteration   1: 7.977 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.004 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
Iteration   2: 3.279 ±(99.9%) 0.007 ms/op
Iteration   3: 3.298 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 1.393 ms/op [Average]
  (min, avg, max) = (3.157, 3.245, 3.298), stdev = 0.076
  CI (99.9%): [1.852, 4.638] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.992 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.011 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (2.971, 3.011, 3.035), stdev = 0.034
  CI (99.9%): [2.383, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 8.326 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.005 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.310 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.229 ±(99.9%) 2.331 ms/op [Average]
  (min, avg, max) = (3.082, 3.229, 3.310), stdev = 0.128
  CI (99.9%): [0.898, 5.560] (assumes normal distribution)


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
# Warmup Iteration   1: 8.126 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.008 ms/op
Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
Iteration   2: 3.805 ±(99.9%) 0.005 ms/op
Iteration   3: 3.697 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.729 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (3.684, 3.729, 3.805), stdev = 0.067
  CI (99.9%): [2.513, 4.945] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.010 ms/op
Iteration   1: 3.174 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  19.015 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 22.082 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.233 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.657 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 28.020 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300566
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25470 
    [ 2.500,  5.000) = 269010 
    [ 5.000,  7.500) = 5154 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     18.102 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 7.454 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  9.609 ms/op
                 existUser·p0.9999: 22.435 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  13.098 ms/op
                 existUser·p0.9999: 19.466 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308073
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22590 
    [ 2.500,  5.000) = 280894 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.959 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.151 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.490 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.177 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.886 ms/op
                 getUser·p0.999:  9.740 ms/op
                 getUser·p0.9999: 23.213 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  16.329 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.939 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 23.262 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301969
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9815 
    [ 2.500,  5.000) = 286480 
    [ 5.000,  7.500) = 4926 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     10.342 ms/op
     p(99.9900) =     22.630 ms/op
     p(99.9990) =     24.018 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 9.438 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.012 ms/op
Iteration   1: 3.987 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 23.789 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.813 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  14.627 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.700 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 19.207 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250660
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 239765 
    [ 5.000,  7.500) = 8401 
    [ 7.500, 10.000) = 1757 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     15.936 ms/op
     p(99.9900) =     23.230 ms/op
     p(99.9990) =     24.051 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.084 ± 2.273  ops/ms
ClientPb.existUser                       thrpt       3  10.275 ± 1.669  ops/ms
ClientPb.getUser                         thrpt       3   9.857 ± 8.281  ops/ms
ClientPb.listUser                        thrpt       3   8.579 ± 2.661  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 1.393   ms/op
ClientPb.existUser                        avgt       3   3.011 ± 0.628   ms/op
ClientPb.getUser                          avgt       3   3.229 ± 2.331   ms/op
ClientPb.listUser                         avgt       3   3.729 ± 1.216   ms/op
ClientPb.createUser                     sample  300566   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  308073   3.116 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.094           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  301969   3.178 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.342           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.630           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  250660   3.830 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.936           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
