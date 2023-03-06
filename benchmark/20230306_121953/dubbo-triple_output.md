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
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 5.091 ops/ms
# Warmup Iteration   3: 8.353 ops/ms
Iteration   1: 9.128 ops/ms
Iteration   2: 9.189 ops/ms
Iteration   3: 9.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.206 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (9.128, 9.206, 9.300), stdev = 0.088
  CI (99.9%): [7.606, 10.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 9.120 ops/ms
# Warmup Iteration   3: 9.676 ops/ms
Iteration   1: 9.570 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.843 ±(99.9%) 4.447 ops/ms [Average]
  (min, avg, max) = (9.570, 9.843, 10.037), stdev = 0.244
  CI (99.9%): [5.396, 14.291] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.848 ops/ms
# Warmup Iteration   2: 8.181 ops/ms
# Warmup Iteration   3: 8.939 ops/ms
Iteration   1: 9.476 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.346 ±(99.9%) 3.287 ops/ms [Average]
  (min, avg, max) = (9.140, 9.346, 9.476), stdev = 0.180
  CI (99.9%): [6.058, 12.633] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 6.928 ops/ms
# Warmup Iteration   3: 7.634 ops/ms
Iteration   1: 7.834 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 8.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 4.319 ops/ms [Average]
  (min, avg, max) = (7.834, 8.072, 8.307), stdev = 0.237
  CI (99.9%): [3.752, 12.391] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
Iteration   1: 3.476 ±(99.9%) 0.007 ms/op
Iteration   2: 3.385 ±(99.9%) 0.010 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.448 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.385, 3.448, 3.481), stdev = 0.054
  CI (99.9%): [2.465, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 8.949 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.003 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
Iteration   3: 3.303 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (3.154, 3.251, 3.303), stdev = 0.085
  CI (99.9%): [1.708, 4.795] (assumes normal distribution)


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
# Warmup Iteration   1: 9.420 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.008 ms/op
Iteration   1: 3.425 ±(99.9%) 0.005 ms/op
Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
Iteration   3: 3.423 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.425 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (3.423, 3.425, 3.428), stdev = 0.002
  CI (99.9%): [3.383, 3.467] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.640 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
Iteration   2: 3.965 ±(99.9%) 0.007 ms/op
Iteration   3: 4.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.986 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.965, 3.986, 4.018), stdev = 0.028
  CI (99.9%): [3.472, 4.500] (assumes normal distribution)


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
# Warmup Iteration   1: 9.317 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
Iteration   1: 3.477 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  20.784 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  21.866 ms/op
                 createUser·p0.9999: 24.994 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.559 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.161 ms/op
                 createUser·p0.999:  20.159 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273862
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8973 
    [ 2.500,  5.000) = 256920 
    [ 5.000,  7.500) = 6867 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     20.747 ms/op
     p(99.9900) =     27.349 ms/op
     p(99.9990) =     28.768 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.185 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.454 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  20.382 ms/op
                 existUser·p0.9999: 30.400 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  12.984 ms/op
                 existUser·p0.9999: 27.668 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  23.251 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284483
  mean =      3.372 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12545 
    [ 2.500,  5.000) = 264872 
    [ 5.000,  7.500) = 6216 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     32.786 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 9.828 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.011 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  10.780 ms/op
                 getUser·p0.9999: 23.128 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 27.836 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  17.744 ms/op
                 getUser·p0.9999: 29.540 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277065
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4867 
    [ 2.500,  5.000) = 261331 
    [ 5.000,  7.500) = 9619 
    [ 7.500, 10.000) = 894 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     27.895 ms/op
     p(99.9990) =     29.970 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 10.765 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.014 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.752 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  19.261 ms/op
                 listUser·p0.9999: 24.561 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   2: 3.994 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.170 ms/op
                 listUser·p0.9999: 18.774 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.947 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.243 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 16.481 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239368
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 230864 
    [ 5.000,  7.500) = 6122 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     23.955 ms/op
     p(99.9990) =     25.016 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.206 ± 1.599  ops/ms
ClientPb.existUser                       thrpt       3   9.843 ± 4.447  ops/ms
ClientPb.getUser                         thrpt       3   9.346 ± 3.287  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 4.319  ops/ms
ClientPb.createUser                       avgt       3   3.448 ± 0.982   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 1.543   ms/op
ClientPb.getUser                          avgt       3   3.425 ± 0.042   ms/op
ClientPb.listUser                         avgt       3   3.986 ± 0.514   ms/op
ClientPb.createUser                     sample  273862   3.500 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.747           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  284483   3.372 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.786           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.372           ms/op
ClientPb.getUser                        sample  277065   3.463 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.026           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.895           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  239368   4.011 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.955           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.395           ms/op
