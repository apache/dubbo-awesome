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
# Warmup Iteration   1: 2.365 ops/ms
# Warmup Iteration   2: 6.000 ops/ms
# Warmup Iteration   3: 9.175 ops/ms
Iteration   1: 9.459 ops/ms
Iteration   2: 9.469 ops/ms
Iteration   3: 9.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.413 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (9.310, 9.413, 9.469), stdev = 0.089
  CI (99.9%): [7.785, 11.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ops/ms
# Warmup Iteration   2: 8.745 ops/ms
# Warmup Iteration   3: 9.205 ops/ms
Iteration   1: 9.465 ops/ms
Iteration   2: 9.778 ops/ms
Iteration   3: 9.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.613 ±(99.9%) 2.861 ops/ms [Average]
  (min, avg, max) = (9.465, 9.613, 9.778), stdev = 0.157
  CI (99.9%): [6.752, 12.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 9.266 ops/ms
Iteration   1: 9.435 ops/ms
Iteration   2: 9.632 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.530 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (9.435, 9.530, 9.632), stdev = 0.099
  CI (99.9%): [7.733, 11.327] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 7.431 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.285 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.279 ±(99.9%) 2.444 ops/ms [Average]
  (min, avg, max) = (8.142, 8.279, 8.410), stdev = 0.134
  CI (99.9%): [5.835, 10.723] (assumes normal distribution)


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
# Warmup Iteration   1: 8.992 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.006 ms/op
Iteration   1: 3.461 ±(99.9%) 0.004 ms/op
Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
Iteration   3: 3.346 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.400 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.346, 3.400, 3.461), stdev = 0.058
  CI (99.9%): [2.341, 4.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.634 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.006 ms/op
Iteration   1: 3.228 ±(99.9%) 0.005 ms/op
Iteration   2: 3.368 ±(99.9%) 0.007 ms/op
Iteration   3: 3.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.327 ±(99.9%) 1.580 ms/op [Average]
  (min, avg, max) = (3.228, 3.327, 3.387), stdev = 0.087
  CI (99.9%): [1.747, 4.908] (assumes normal distribution)


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
# Warmup Iteration   1: 8.214 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.005 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op
Iteration   2: 3.341 ±(99.9%) 0.006 ms/op
Iteration   3: 3.359 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.341, 3.378, 3.432), stdev = 0.048
  CI (99.9%): [2.496, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 10.210 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.005 ms/op
Iteration   1: 3.818 ±(99.9%) 0.014 ms/op
Iteration   2: 3.991 ±(99.9%) 0.010 ms/op
Iteration   3: 3.853 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.818, 3.887, 3.991), stdev = 0.091
  CI (99.9%): [2.222, 5.553] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.524 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.282 ms/op
                 createUser·p0.999:  18.977 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  22.299 ms/op
                 createUser·p0.9999: 24.355 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.378 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  14.287 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282296
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11918 
    [ 2.500,  5.000) = 265270 
    [ 5.000,  7.500) = 3939 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.593 ms/op
     p(99.9900) =     24.110 ms/op
     p(99.9990) =     25.034 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 8.003 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
Iteration   1: 3.315 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  18.381 ms/op
                 existUser·p0.9999: 27.725 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  17.629 ms/op
                 existUser·p0.9999: 24.356 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.624 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 27.721 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293680
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15618 
    [ 2.500,  5.000) = 273251 
    [ 5.000,  7.500) = 4108 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     27.087 ms/op
     p(99.9990) =     28.461 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 9.874 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
Iteration   1: 3.577 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  19.480 ms/op
                 getUser·p0.9999: 21.858 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 3.501 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  18.977 ms/op
                 getUser·p0.9999: 22.418 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.370 ms/op
                 getUser·p0.99:   6.083 ms/op
                 getUser·p0.999:  10.019 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272528
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10162 
    [ 2.500,  5.000) = 252924 
    [ 5.000,  7.500) = 8291 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     14.220 ms/op
     p(99.9900) =     23.814 ms/op
     p(99.9990) =     25.250 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 9.594 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.308 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 24.124 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 3.897 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.088 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.011 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240671
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 232327 
    [ 5.000,  7.500) = 6278 
    [ 7.500, 10.000) = 1320 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     24.874 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.413 ± 1.628  ops/ms
ClientPb.existUser                       thrpt       3   9.613 ± 2.861  ops/ms
ClientPb.getUser                         thrpt       3   9.530 ± 1.797  ops/ms
ClientPb.listUser                        thrpt       3   8.279 ± 2.444  ops/ms
ClientPb.createUser                       avgt       3   3.400 ± 1.059   ms/op
ClientPb.existUser                        avgt       3   3.327 ± 1.580   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 0.882   ms/op
ClientPb.listUser                         avgt       3   3.887 ± 1.665   ms/op
ClientPb.createUser                     sample  282296   3.396 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  293680   3.268 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.270           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.770           ms/op
ClientPb.getUser                        sample  272528   3.520 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.220           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.814           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.608           ms/op
ClientPb.listUser                       sample  240671   3.986 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
