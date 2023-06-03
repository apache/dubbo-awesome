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
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 5.882 ops/ms
# Warmup Iteration   3: 8.798 ops/ms
Iteration   1: 9.047 ops/ms
Iteration   2: 9.172 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.256 ±(99.9%) 4.755 ops/ms [Average]
  (min, avg, max) = (9.047, 9.256, 9.548), stdev = 0.261
  CI (99.9%): [4.500, 14.011] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ops/ms
# Warmup Iteration   2: 8.995 ops/ms
# Warmup Iteration   3: 9.622 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.822 ±(99.9%) 10.265 ops/ms [Average]
  (min, avg, max) = (9.180, 9.822, 10.232), stdev = 0.563
  CI (99.9%): [≈ 0, 20.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 8.182 ops/ms
# Warmup Iteration   3: 8.895 ops/ms
Iteration   1: 9.059 ops/ms
Iteration   2: 9.096 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.092 ±(99.9%) 0.578 ops/ms [Average]
  (min, avg, max) = (9.059, 9.092, 9.122), stdev = 0.032
  CI (99.9%): [8.514, 9.671] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.783 ops/ms
Iteration   3: 7.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.792 ±(99.9%) 0.154 ops/ms [Average]
  (min, avg, max) = (7.783, 7.792, 7.798), stdev = 0.008
  CI (99.9%): [7.638, 7.946] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.743 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.003 ms/op
Iteration   1: 3.405 ±(99.9%) 0.005 ms/op
Iteration   2: 3.461 ±(99.9%) 0.005 ms/op
Iteration   3: 3.420 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.429 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.405, 3.429, 3.461), stdev = 0.029
  CI (99.9%): [2.894, 3.963] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.288 ±(99.9%) 0.005 ms/op
Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
Iteration   3: 3.507 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.345 ±(99.9%) 2.581 ms/op [Average]
  (min, avg, max) = (3.242, 3.345, 3.507), stdev = 0.141
  CI (99.9%): [0.765, 5.926] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.815 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.004 ms/op
Iteration   1: 3.424 ±(99.9%) 0.008 ms/op
Iteration   2: 3.413 ±(99.9%) 0.011 ms/op
Iteration   3: 3.392 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.392, 3.410, 3.424), stdev = 0.017
  CI (99.9%): [3.105, 3.715] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.187 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.007 ms/op
Iteration   1: 4.020 ±(99.9%) 0.008 ms/op
Iteration   2: 3.991 ±(99.9%) 0.010 ms/op
Iteration   3: 3.994 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.001 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.991, 4.001, 4.020), stdev = 0.016
  CI (99.9%): [3.709, 4.294] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
Iteration   1: 3.304 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  13.935 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  24.500 ms/op
                 createUser·p0.9999: 30.495 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   3: 3.572 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  20.150 ms/op
                 createUser·p0.9999: 28.444 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280182
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9442 
    [ 2.500,  5.000) = 264786 
    [ 5.000,  7.500) = 5175 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     20.212 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     34.223 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.754 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.010 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 30.312 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   2: 3.374 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  22.348 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   3: 3.274 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 46.531 ms/op
                 existUser·p1.00:   47.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292045
  mean =      3.286 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 286548 
    [ 5.000, 10.000) = 5004 
    [10.000, 15.000) = 195 
    [15.000, 20.000) = 45 
    [20.000, 25.000) = 112 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 30 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     44.879 ms/op
     p(99.9990) =     46.989 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


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
# Warmup Iteration   1: 8.841 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.011 ms/op
Iteration   1: 3.594 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  17.892 ms/op
                 getUser·p0.9999: 20.123 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.451 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 24.829 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  19.489 ms/op
                 getUser·p0.9999: 25.232 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271439
  mean =      3.535 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7105 
    [ 2.500,  5.000) = 254525 
    [ 5.000,  7.500) = 8674 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     13.313 ms/op
     p(99.9900) =     24.698 ms/op
     p(99.9990) =     25.873 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 11.058 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.502 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.014 ms/op
Iteration   1: 4.106 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  19.790 ms/op
                 listUser·p0.9999: 27.715 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.122 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.173 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 16.335 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232188
  mean =      4.133 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 219815 
    [ 5.000,  7.500) = 9761 
    [ 7.500, 10.000) = 1795 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     28.247 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.256 ±  4.755  ops/ms
ClientPb.existUser                       thrpt       3   9.822 ± 10.265  ops/ms
ClientPb.getUser                         thrpt       3   9.092 ±  0.578  ops/ms
ClientPb.listUser                        thrpt       3   7.792 ±  0.154  ops/ms
ClientPb.createUser                       avgt       3   3.429 ±  0.535   ms/op
ClientPb.existUser                        avgt       3   3.345 ±  2.581   ms/op
ClientPb.getUser                          avgt       3   3.410 ±  0.305   ms/op
ClientPb.listUser                         avgt       3   4.001 ±  0.292   ms/op
ClientPb.createUser                     sample  280182   3.425 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710            ms/op
ClientPb.createUser:createUser·p0.999   sample          20.212            ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.984            ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275            ms/op
ClientPb.existUser                      sample  292045   3.286 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.317            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.286            ms/op
ClientPb.existUser:existUser·p0.9999    sample          44.879            ms/op
ClientPb.existUser:existUser·p1.00      sample          47.120            ms/op
ClientPb.getUser                        sample  271439   3.535 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.551            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.096            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.571            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.313            ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.698            ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968            ms/op
ClientPb.listUser                       sample  232188   4.133 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.676            ms/op
ClientPb.listUser:listUser·p0.999       sample          16.007            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.477            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475            ms/op
