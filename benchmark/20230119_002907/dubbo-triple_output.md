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
# Warmup Iteration   1: 1.143 ops/ms
# Warmup Iteration   2: 2.329 ops/ms
# Warmup Iteration   3: 5.632 ops/ms
Iteration   1: 5.997 ops/ms
Iteration   2: 6.118 ops/ms
Iteration   3: 6.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.109 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (5.997, 6.109, 6.213), stdev = 0.109
  CI (99.9%): [4.129, 8.090] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
# Warmup Iteration   2: 4.685 ops/ms
# Warmup Iteration   3: 6.084 ops/ms
Iteration   1: 6.388 ops/ms
Iteration   2: 6.293 ops/ms
Iteration   3: 6.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.379 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (6.293, 6.379, 6.456), stdev = 0.081
  CI (99.9%): [4.893, 7.865] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.707 ops/ms
# Warmup Iteration   2: 4.920 ops/ms
# Warmup Iteration   3: 5.979 ops/ms
Iteration   1: 5.753 ops/ms
Iteration   2: 5.691 ops/ms
Iteration   3: 5.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.786 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (5.691, 5.786, 5.914), stdev = 0.115
  CI (99.9%): [3.689, 7.883] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 4.400 ops/ms
# Warmup Iteration   3: 5.369 ops/ms
Iteration   1: 5.293 ops/ms
Iteration   2: 5.494 ops/ms
Iteration   3: 5.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.411 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (5.293, 5.411, 5.494), stdev = 0.105
  CI (99.9%): [3.499, 7.324] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.736 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.959 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.263 ±(99.9%) 0.011 ms/op
Iteration   1: 5.212 ±(99.9%) 0.013 ms/op
Iteration   2: 5.094 ±(99.9%) 0.011 ms/op
Iteration   3: 5.049 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.118 ±(99.9%) 1.536 ms/op [Average]
  (min, avg, max) = (5.049, 5.118, 5.212), stdev = 0.084
  CI (99.9%): [3.582, 6.654] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.344 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.561 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.286 ±(99.9%) 0.007 ms/op
Iteration   1: 4.968 ±(99.9%) 0.010 ms/op
Iteration   2: 4.890 ±(99.9%) 0.012 ms/op
Iteration   3: 5.037 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.965 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.890, 4.965, 5.037), stdev = 0.074
  CI (99.9%): [3.623, 6.307] (assumes normal distribution)


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
# Warmup Iteration   1: 16.578 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.261 ±(99.9%) 0.008 ms/op
Iteration   1: 5.188 ±(99.9%) 0.013 ms/op
Iteration   2: 5.189 ±(99.9%) 0.013 ms/op
Iteration   3: 5.244 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.207 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (5.188, 5.207, 5.244), stdev = 0.032
  CI (99.9%): [4.623, 5.792] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.367 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.805 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.819 ±(99.9%) 0.019 ms/op
Iteration   1: 5.841 ±(99.9%) 0.020 ms/op
Iteration   2: 5.938 ±(99.9%) 0.012 ms/op
Iteration   3: 5.855 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.878 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (5.841, 5.878, 5.938), stdev = 0.053
  CI (99.9%): [4.920, 6.836] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.082 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.585 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.027 ms/op
Iteration   1: 5.328 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   11.190 ms/op
                 createUser·p0.999:  24.805 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   2: 5.371 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  25.050 ms/op
                 createUser·p0.9999: 28.085 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 5.248 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  29.166 ms/op
                 createUser·p0.9999: 32.211 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180453
  mean =      5.315 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 94316 
    [ 5.000,  7.500) = 74352 
    [ 7.500, 10.000) = 8982 
    [10.000, 12.500) = 1790 
    [12.500, 15.000) = 506 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     24.936 ms/op
     p(99.9900) =     31.063 ms/op
     p(99.9990) =     32.912 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 17.935 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 5.664 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.129 ±(99.9%) 0.020 ms/op
Iteration   1: 5.142 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.005 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  24.763 ms/op
                 existUser·p0.9999: 28.198 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   2: 5.060 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.815 ms/op
                 existUser·p0.999:  24.724 ms/op
                 existUser·p0.9999: 31.054 ms/op
                 existUser·p1.00:   32.178 ms/op

Iteration   3: 4.926 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.083 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  17.638 ms/op
                 existUser·p0.9999: 31.590 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190367
  mean =      5.041 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 125456 
    [ 5.000,  7.500) = 55646 
    [ 7.500, 10.000) = 6663 
    [10.000, 12.500) = 1806 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     24.559 ms/op
     p(99.9900) =     31.259 ms/op
     p(99.9990) =     32.001 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 15.452 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.734 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.072 ±(99.9%) 0.019 ms/op
Iteration   1: 5.056 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  19.975 ms/op
                 getUser·p0.9999: 24.533 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 4.907 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 4.991 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   9.503 ms/op
                 getUser·p0.999:  23.477 ms/op
                 getUser·p0.9999: 27.086 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192429
  mean =      4.984 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 130534 
    [ 5.000,  7.500) = 52976 
    [ 7.500, 10.000) = 6290 
    [10.000, 12.500) = 1597 
    [12.500, 15.000) = 591 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     20.812 ms/op
     p(99.9900) =     26.854 ms/op
     p(99.9990) =     27.374 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.843 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.004 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.079 ±(99.9%) 0.025 ms/op
Iteration   1: 5.827 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  23.465 ms/op
                 listUser·p0.9999: 26.887 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 5.711 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  25.299 ms/op
                 listUser·p0.9999: 28.836 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   3: 5.842 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  17.375 ms/op
                 listUser·p0.9999: 19.748 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165600
  mean =      5.793 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 29021 
    [ 5.000,  7.500) = 125182 
    [ 7.500, 10.000) = 8652 
    [10.000, 12.500) = 1696 
    [12.500, 15.000) = 500 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      2.077 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     27.798 ms/op
     p(99.9990) =     29.270 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.109 ± 1.981  ops/ms
ClientPb.existUser                       thrpt       3   6.379 ± 1.486  ops/ms
ClientPb.getUser                         thrpt       3   5.786 ± 2.097  ops/ms
ClientPb.listUser                        thrpt       3   5.411 ± 1.912  ops/ms
ClientPb.createUser                       avgt       3   5.118 ± 1.536   ms/op
ClientPb.existUser                        avgt       3   4.965 ± 1.342   ms/op
ClientPb.getUser                          avgt       3   5.207 ± 0.584   ms/op
ClientPb.listUser                         avgt       3   5.878 ± 0.958   ms/op
ClientPb.createUser                     sample  180453   5.315 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.879           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.936           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  190367   5.041 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.833           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.535           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.559           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.259           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  192429   4.984 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.356           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.854           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  165600   5.793 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.077           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.043           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.298           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.786           ms/op
