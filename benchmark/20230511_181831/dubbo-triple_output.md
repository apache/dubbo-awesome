# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.811 ops/ms
# Warmup Iteration   2: 4.198 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 8.378 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 8.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.770 ±(99.9%) 7.562 ops/ms [Average]
  (min, avg, max) = (8.378, 8.770, 9.204), stdev = 0.414
  CI (99.9%): [1.209, 16.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 9.025 ops/ms
Iteration   1: 9.307 ops/ms
Iteration   2: 9.631 ops/ms
Iteration   3: 9.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.583 ±(99.9%) 4.650 ops/ms [Average]
  (min, avg, max) = (9.307, 9.583, 9.810), stdev = 0.255
  CI (99.9%): [4.933, 14.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.970 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.794 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.951 ±(99.9%) 10.915 ops/ms [Average]
  (min, avg, max) = (8.262, 8.951, 9.341), stdev = 0.598
  CI (99.9%): [≈ 0, 19.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.327 ops/ms
# Warmup Iteration   2: 6.950 ops/ms
# Warmup Iteration   3: 7.414 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 7.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.887 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (7.824, 7.887, 7.995), stdev = 0.094
  CI (99.9%): [6.171, 9.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.261 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.008 ms/op
Iteration   1: 3.685 ±(99.9%) 0.003 ms/op
Iteration   2: 3.514 ±(99.9%) 0.008 ms/op
Iteration   3: 3.516 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.572 ±(99.9%) 1.790 ms/op [Average]
  (min, avg, max) = (3.514, 3.572, 3.685), stdev = 0.098
  CI (99.9%): [1.782, 5.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.271 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.003 ms/op
Iteration   1: 3.427 ±(99.9%) 0.007 ms/op
Iteration   2: 3.468 ±(99.9%) 0.008 ms/op
Iteration   3: 3.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.422 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.372, 3.422, 3.468), stdev = 0.048
  CI (99.9%): [2.540, 4.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.614 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.005 ms/op
Iteration   1: 3.499 ±(99.9%) 0.004 ms/op
Iteration   2: 3.567 ±(99.9%) 0.005 ms/op
Iteration   3: 3.394 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.487 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (3.394, 3.487, 3.567), stdev = 0.087
  CI (99.9%): [1.902, 5.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.070 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.005 ms/op
Iteration   1: 4.139 ±(99.9%) 0.009 ms/op
Iteration   2: 4.066 ±(99.9%) 0.011 ms/op
Iteration   3: 4.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.101 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.066, 4.101, 4.139), stdev = 0.037
  CI (99.9%): [3.433, 4.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.802 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.014 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  21.793 ms/op
                 createUser·p0.9999: 26.041 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.625 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  21.574 ms/op
                 createUser·p0.9999: 24.549 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.544 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.418 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  19.539 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271449
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7040 
    [ 2.500,  5.000) = 253875 
    [ 5.000,  7.500) = 9045 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     19.992 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     31.794 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.135 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.011 ms/op
Iteration   1: 3.279 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.361 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  23.316 ms/op
                 existUser·p0.9999: 26.312 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  20.235 ms/op
                 existUser·p0.9999: 25.104 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287106
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9092 
    [ 2.500,  5.000) = 272699 
    [ 5.000,  7.500) = 4092 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     26.682 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.110 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.015 ms/op
Iteration   1: 3.708 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  21.124 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   2: 3.412 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 24.917 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.625 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  24.181 ms/op
                 getUser·p0.9999: 28.612 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268422
  mean =      3.577 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5027 
    [ 2.500,  5.000) = 254619 
    [ 5.000,  7.500) = 6900 
    [ 7.500, 10.000) = 1170 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     29.300 ms/op
     p(99.9990) =     31.207 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.587 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.015 ms/op
Iteration   1: 4.235 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  22.365 ms/op
                 listUser·p0.9999: 26.917 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.145 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.986 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  16.330 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229833
  mean =      4.175 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 216898 
    [ 5.000,  7.500) = 9755 
    [ 7.500, 10.000) = 2087 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     25.595 ms/op
     p(99.9990) =     28.030 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.770 ±  7.562  ops/ms
ClientPb.existUser                       thrpt       3   9.583 ±  4.650  ops/ms
ClientPb.getUser                         thrpt       3   8.951 ± 10.915  ops/ms
ClientPb.listUser                        thrpt       3   7.887 ±  1.716  ops/ms
ClientPb.createUser                       avgt       3   3.572 ±  1.790   ms/op
ClientPb.existUser                        avgt       3   3.422 ±  0.882   ms/op
ClientPb.getUser                          avgt       3   3.487 ±  1.584   ms/op
ClientPb.listUser                         avgt       3   4.101 ±  0.668   ms/op
ClientPb.createUser                     sample  271449   3.535 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.397            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.644            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.992            ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.196            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982            ms/op
ClientPb.existUser                      sample  287106   3.341 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.542            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759            ms/op
ClientPb.existUser:existUser·p0.999     sample          16.564            ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.494            ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197            ms/op
ClientPb.getUser                        sample  268422   3.577 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.333            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.300            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670            ms/op
ClientPb.listUser                       sample  229833   4.175 ±  0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.186            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.128            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.167            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.055            ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.595            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312            ms/op
