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
# Warmup Iteration   1: 2.024 ops/ms
# Warmup Iteration   2: 5.596 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.960 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.140 ±(99.9%) 2.872 ops/ms [Average]
  (min, avg, max) = (8.960, 9.140, 9.255), stdev = 0.157
  CI (99.9%): [6.267, 12.012] (assumes normal distribution)


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
# Warmup Iteration   1: 3.227 ops/ms
# Warmup Iteration   2: 8.869 ops/ms
# Warmup Iteration   3: 9.068 ops/ms
Iteration   1: 9.467 ops/ms
Iteration   2: 9.714 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.547 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (9.460, 9.547, 9.714), stdev = 0.145
  CI (99.9%): [6.908, 12.187] (assumes normal distribution)


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
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 8.477 ops/ms
# Warmup Iteration   3: 8.849 ops/ms
Iteration   1: 9.112 ops/ms
Iteration   2: 9.055 ops/ms
Iteration   3: 8.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.975 ±(99.9%) 3.458 ops/ms [Average]
  (min, avg, max) = (8.759, 8.975, 9.112), stdev = 0.190
  CI (99.9%): [5.518, 12.433] (assumes normal distribution)


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
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 7.066 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.716 ops/ms
Iteration   2: 7.550 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.674 ±(99.9%) 2.005 ops/ms [Average]
  (min, avg, max) = (7.550, 7.674, 7.757), stdev = 0.110
  CI (99.9%): [5.669, 9.680] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.981 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.003 ms/op
Iteration   1: 3.623 ±(99.9%) 0.003 ms/op
Iteration   2: 3.474 ±(99.9%) 0.006 ms/op
Iteration   3: 3.579 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.559 ±(99.9%) 1.400 ms/op [Average]
  (min, avg, max) = (3.474, 3.559, 3.623), stdev = 0.077
  CI (99.9%): [2.159, 4.958] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.480 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.003 ms/op
Iteration   1: 3.329 ±(99.9%) 0.002 ms/op
Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
Iteration   3: 3.361 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.366 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.329, 3.366, 3.408), stdev = 0.040
  CI (99.9%): [2.640, 4.092] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.532 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.004 ms/op
Iteration   1: 3.473 ±(99.9%) 0.004 ms/op
Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
Iteration   3: 3.488 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (3.407, 3.456, 3.488), stdev = 0.043
  CI (99.9%): [2.671, 4.241] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.999 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.003 ms/op
Iteration   1: 4.129 ±(99.9%) 0.006 ms/op
Iteration   2: 4.221 ±(99.9%) 0.004 ms/op
Iteration   3: 4.176 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.175 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (4.129, 4.175, 4.221), stdev = 0.046
  CI (99.9%): [3.338, 5.012] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.079 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.011 ms/op
Iteration   1: 3.572 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.714 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 23.201 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.569 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.435 ms/op
                 createUser·p0.999:  21.928 ms/op
                 createUser·p0.9999: 26.150 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  21.685 ms/op
                 createUser·p0.9999: 25.683 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271303
  mean =      3.534 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4256 
    [ 2.500,  5.000) = 261100 
    [ 5.000,  7.500) = 4516 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     25.817 ms/op
     p(99.9990) =     26.561 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 7.953 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
Iteration   1: 3.333 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   6.208 ms/op
                 existUser·p0.999:  22.560 ms/op
                 existUser·p0.9999: 25.342 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  20.912 ms/op
                 existUser·p0.9999: 25.099 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.404 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.531 ms/op
                 existUser·p0.999:  23.498 ms/op
                 existUser·p0.9999: 26.660 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285168
  mean =      3.365 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8512 
    [ 2.500,  5.000) = 272084 
    [ 5.000,  7.500) = 3345 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 203 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     21.687 ms/op
     p(99.9900) =     26.213 ms/op
     p(99.9990) =     28.637 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.273 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.011 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  22.056 ms/op
                 getUser·p0.9999: 27.001 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.549 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  21.324 ms/op
                 getUser·p0.9999: 25.493 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.564 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  16.742 ms/op
                 getUser·p0.9999: 25.036 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269858
  mean =      3.559 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1709 
    [ 2.500,  5.000) = 262739 
    [ 5.000,  7.500) = 4378 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     21.206 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 11.361 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.015 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  21.734 ms/op
                 listUser·p0.9999: 23.794 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.135 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 4.166 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.846 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232897
  mean =      4.121 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 223058 
    [ 5.000,  7.500) = 7960 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     23.518 ms/op
     p(99.9990) =     24.227 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.140 ± 2.872  ops/ms
ClientPb.existUser                       thrpt       3   9.547 ± 2.640  ops/ms
ClientPb.getUser                         thrpt       3   8.975 ± 3.458  ops/ms
ClientPb.listUser                        thrpt       3   7.674 ± 2.005  ops/ms
ClientPb.createUser                       avgt       3   3.559 ± 1.400   ms/op
ClientPb.existUser                        avgt       3   3.366 ± 0.726   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 0.785   ms/op
ClientPb.listUser                         avgt       3   4.175 ± 0.837   ms/op
ClientPb.createUser                     sample  271303   3.534 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.135           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  285168   3.365 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.687           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  269858   3.559 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.206           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.001           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  232897   4.121 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.728           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
