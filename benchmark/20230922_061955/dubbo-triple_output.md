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
# Warmup Iteration   1: 2.386 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 9.285 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.703 ±(99.9%) 1.969 ops/ms [Average]
  (min, avg, max) = (9.606, 9.703, 9.819), stdev = 0.108
  CI (99.9%): [7.734, 11.672] (assumes normal distribution)


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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.537 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.061 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (9.953, 10.061, 10.174), stdev = 0.111
  CI (99.9%): [8.039, 12.084] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.258 ops/ms
# Warmup Iteration   2: 9.094 ops/ms
# Warmup Iteration   3: 9.444 ops/ms
Iteration   1: 9.659 ops/ms
Iteration   2: 9.862 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.720 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (9.639, 9.720, 9.862), stdev = 0.123
  CI (99.9%): [7.467, 11.973] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 7.415 ops/ms
# Warmup Iteration   3: 8.125 ops/ms
Iteration   1: 8.297 ops/ms
Iteration   2: 8.438 ops/ms
Iteration   3: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.301 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (8.169, 8.301, 8.438), stdev = 0.134
  CI (99.9%): [5.851, 10.751] (assumes normal distribution)


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
# Warmup Iteration   1: 7.928 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.002 ms/op
Iteration   1: 3.239 ±(99.9%) 0.005 ms/op
Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
Iteration   3: 3.200 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.239 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.200, 3.239, 3.278), stdev = 0.039
  CI (99.9%): [2.530, 3.948] (assumes normal distribution)


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
# Warmup Iteration   1: 7.052 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.165 ±(99.9%) 0.004 ms/op
Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
Iteration   3: 3.112 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.124 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.094, 3.124, 3.165), stdev = 0.037
  CI (99.9%): [2.458, 3.790] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.611 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.002 ms/op
Iteration   1: 3.306 ±(99.9%) 0.002 ms/op
Iteration   2: 3.243 ±(99.9%) 0.004 ms/op
Iteration   3: 3.213 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.254 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.213, 3.254, 3.306), stdev = 0.047
  CI (99.9%): [2.390, 4.119] (assumes normal distribution)


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
# Warmup Iteration   1: 8.703 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.003 ms/op
Iteration   1: 3.751 ±(99.9%) 0.007 ms/op
Iteration   2: 3.750 ±(99.9%) 0.005 ms/op
Iteration   3: 3.849 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.783 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.750, 3.783, 3.849), stdev = 0.057
  CI (99.9%): [2.740, 4.826] (assumes normal distribution)


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
# Warmup Iteration   1: 8.245 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  12.922 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.354 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.619 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288413
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18130 
    [ 2.500,  5.000) = 265759 
    [ 5.000,  7.500) = 3664 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     21.337 ms/op
     p(99.9990) =     23.105 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.905 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.140 ms/op
                 existUser·p0.999:  16.548 ms/op
                 existUser·p0.9999: 20.813 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  12.360 ms/op
                 existUser·p0.9999: 22.103 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 23.563 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294846
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10977 
    [ 2.500,  5.000) = 278745 
    [ 5.000,  7.500) = 4252 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.695 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.760 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  18.362 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  18.473 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  16.604 ms/op
                 getUser·p0.9999: 22.451 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290067
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10746 
    [ 2.500,  5.000) = 270175 
    [ 5.000,  7.500) = 7774 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     17.430 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 10.555 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 3.848 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 15.746 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.855 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248668
  mean =      3.859 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 242668 
    [ 5.000,  7.500) = 4295 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     21.050 ms/op
     p(99.9990) =     22.103 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.703 ± 1.969  ops/ms
ClientPb.existUser                       thrpt       3  10.061 ± 2.022  ops/ms
ClientPb.getUser                         thrpt       3   9.720 ± 2.253  ops/ms
ClientPb.listUser                        thrpt       3   8.301 ± 2.450  ops/ms
ClientPb.createUser                       avgt       3   3.239 ± 0.709   ms/op
ClientPb.existUser                        avgt       3   3.124 ± 0.666   ms/op
ClientPb.getUser                          avgt       3   3.254 ± 0.865   ms/op
ClientPb.listUser                         avgt       3   3.783 ± 1.043   ms/op
ClientPb.createUser                     sample  288413   3.325 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.200           ms/op
ClientPb.existUser                      sample  294846   3.253 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.227           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.117           ms/op
ClientPb.getUser                        sample  290067   3.309 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.249           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  248668   3.859 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.050           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.184           ms/op
