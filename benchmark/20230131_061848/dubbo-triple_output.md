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
# Warmup Iteration   1: 2.536 ops/ms
# Warmup Iteration   2: 6.118 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 9.767 ops/ms
Iteration   2: 9.404 ops/ms
Iteration   3: 9.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.586 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (9.404, 9.586, 9.767), stdev = 0.181
  CI (99.9%): [6.280, 12.892] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 9.419 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 10.296 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.499 ±(99.9%) 4.087 ops/ms [Average]
  (min, avg, max) = (10.296, 10.499, 10.739), stdev = 0.224
  CI (99.9%): [6.411, 14.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 9.393 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.209 ±(99.9%) 2.907 ops/ms [Average]
  (min, avg, max) = (10.027, 10.209, 10.320), stdev = 0.159
  CI (99.9%): [7.303, 13.116] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 6.933 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 8.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.330 ±(99.9%) 5.125 ops/ms [Average]
  (min, avg, max) = (8.118, 8.330, 8.649), stdev = 0.281
  CI (99.9%): [3.205, 13.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.004 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.121, 3.137, 3.161), stdev = 0.021
  CI (99.9%): [2.749, 3.525] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.577 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.004 ms/op
Iteration   1: 3.100 ±(99.9%) 0.005 ms/op
Iteration   2: 3.138 ±(99.9%) 0.009 ms/op
Iteration   3: 3.139 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.126 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.100, 3.126, 3.139), stdev = 0.023
  CI (99.9%): [2.714, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 8.527 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.002 ms/op
Iteration   1: 3.228 ±(99.9%) 0.003 ms/op
Iteration   2: 3.240 ±(99.9%) 0.004 ms/op
Iteration   3: 3.181 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (3.181, 3.216, 3.240), stdev = 0.031
  CI (99.9%): [2.652, 3.781] (assumes normal distribution)


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
# Warmup Iteration   1: 9.351 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
Iteration   1: 3.682 ±(99.9%) 0.008 ms/op
Iteration   2: 3.634 ±(99.9%) 0.009 ms/op
Iteration   3: 3.628 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.648 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.628, 3.648, 3.682), stdev = 0.030
  CI (99.9%): [3.105, 4.191] (assumes normal distribution)


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
# Warmup Iteration   1: 7.162 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.885 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  14.467 ms/op
                 createUser·p0.9999: 20.774 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  10.179 ms/op
                 createUser·p0.9999: 23.287 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.690 ms/op
                 createUser·p0.999:  17.038 ms/op
                 createUser·p0.9999: 22.390 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301097
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21969 
    [ 2.500,  5.000) = 272641 
    [ 5.000,  7.500) = 5420 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     16.835 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.572 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 6.729 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.008 ms/op
Iteration   1: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  14.243 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 20.036 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.225 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311229
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14271 
    [ 2.500,  5.000) = 291739 
    [ 5.000,  7.500) = 4490 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.071 ms/op
     p(99.9900) =     21.672 ms/op
     p(99.9990) =     23.935 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.734 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.011 ms/op
Iteration   1: 3.247 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  15.418 ms/op
                 getUser·p0.9999: 22.975 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.298 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  9.128 ms/op
                 getUser·p0.9999: 26.382 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  9.758 ms/op
                 getUser·p0.9999: 21.694 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297290
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15706 
    [ 2.500,  5.000) = 275527 
    [ 5.000,  7.500) = 5277 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     11.298 ms/op
     p(99.9900) =     25.184 ms/op
     p(99.9990) =     27.143 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 8.978 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
Iteration   1: 3.791 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 20.553 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255800
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 247532 
    [ 5.000,  7.500) = 6196 
    [ 7.500, 10.000) = 1267 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.962 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     21.251 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.586 ± 3.306  ops/ms
ClientPb.existUser                       thrpt       3  10.499 ± 4.087  ops/ms
ClientPb.getUser                         thrpt       3  10.209 ± 2.907  ops/ms
ClientPb.listUser                        thrpt       3   8.330 ± 5.125  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   3.126 ± 0.411   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 0.565   ms/op
ClientPb.listUser                         avgt       3   3.648 ± 0.543   ms/op
ClientPb.createUser                     sample  301097   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.835           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.315           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.264           ms/op
ClientPb.existUser                      sample  311229   3.082 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.071           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.672           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  297290   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.115           ms/op
ClientPb.listUser                       sample  255800   3.755 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.122           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.496           ms/op
