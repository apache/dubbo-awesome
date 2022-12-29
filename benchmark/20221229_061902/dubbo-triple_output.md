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
# Warmup Iteration   1: 1.083 ops/ms
# Warmup Iteration   2: 2.534 ops/ms
# Warmup Iteration   3: 5.436 ops/ms
Iteration   1: 5.767 ops/ms
Iteration   2: 6.104 ops/ms
Iteration   3: 6.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.019 ±(99.9%) 4.061 ops/ms [Average]
  (min, avg, max) = (5.767, 6.019, 6.187), stdev = 0.223
  CI (99.9%): [1.958, 10.080] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 5.209 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.399 ops/ms
Iteration   2: 6.578 ops/ms
Iteration   3: 6.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.407 ±(99.9%) 3.072 ops/ms [Average]
  (min, avg, max) = (6.242, 6.407, 6.578), stdev = 0.168
  CI (99.9%): [3.335, 9.478] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.558 ops/ms
# Warmup Iteration   3: 6.061 ops/ms
Iteration   1: 6.140 ops/ms
Iteration   2: 5.712 ops/ms
Iteration   3: 6.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.979 ±(99.9%) 4.251 ops/ms [Average]
  (min, avg, max) = (5.712, 5.979, 6.140), stdev = 0.233
  CI (99.9%): [1.728, 10.231] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.729 ops/ms
# Warmup Iteration   2: 3.925 ops/ms
# Warmup Iteration   3: 5.074 ops/ms
Iteration   1: 5.223 ops/ms
Iteration   2: 5.353 ops/ms
Iteration   3: 5.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.305 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (5.223, 5.305, 5.353), stdev = 0.071
  CI (99.9%): [4.005, 6.604] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.730 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.337 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.471 ±(99.9%) 0.012 ms/op
Iteration   1: 5.344 ±(99.9%) 0.013 ms/op
Iteration   2: 5.101 ±(99.9%) 0.011 ms/op
Iteration   3: 5.276 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.240 ±(99.9%) 2.287 ms/op [Average]
  (min, avg, max) = (5.101, 5.240, 5.344), stdev = 0.125
  CI (99.9%): [2.953, 7.528] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.822 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.759 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.010 ms/op
Iteration   1: 4.966 ±(99.9%) 0.011 ms/op
Iteration   2: 5.000 ±(99.9%) 0.011 ms/op
Iteration   3: 4.957 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.974 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (4.957, 4.974, 5.000), stdev = 0.022
  CI (99.9%): [4.566, 5.383] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 16.832 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.288 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.011 ms/op
Iteration   1: 5.372 ±(99.9%) 0.011 ms/op
Iteration   2: 5.270 ±(99.9%) 0.006 ms/op
Iteration   3: 5.109 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.250 ±(99.9%) 2.425 ms/op [Average]
  (min, avg, max) = (5.109, 5.250, 5.372), stdev = 0.133
  CI (99.9%): [2.825, 7.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.997 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 7.408 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.209 ±(99.9%) 0.014 ms/op
Iteration   1: 6.219 ±(99.9%) 0.014 ms/op
Iteration   2: 6.584 ±(99.9%) 0.018 ms/op
Iteration   3: 6.061 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.288 ±(99.9%) 4.897 ms/op [Average]
  (min, avg, max) = (6.061, 6.288, 6.584), stdev = 0.268
  CI (99.9%): [1.391, 11.185] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.627 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.944 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.809 ±(99.9%) 0.029 ms/op
Iteration   1: 5.376 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   11.735 ms/op
                 createUser·p0.999:  24.281 ms/op
                 createUser·p0.9999: 27.953 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   2: 5.138 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   11.466 ms/op
                 createUser·p0.999:  23.499 ms/op
                 createUser·p0.9999: 32.067 ms/op
                 createUser·p1.00:   34.341 ms/op

Iteration   3: 5.287 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  31.737 ms/op
                 createUser·p0.9999: 38.732 ms/op
                 createUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182270
  mean =      5.265 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 102612 
    [ 5.000,  7.500) = 69767 
    [ 7.500, 10.000) = 6744 
    [10.000, 12.500) = 2015 
    [12.500, 15.000) = 540 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     24.141 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     39.045 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.770 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 6.245 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.220 ±(99.9%) 0.020 ms/op
Iteration   1: 5.143 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.607 ms/op
                 existUser·p0.999:  22.298 ms/op
                 existUser·p0.9999: 26.786 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 5.372 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   7.528 ms/op
                 existUser·p0.95:   8.749 ms/op
                 existUser·p0.99:   11.960 ms/op
                 existUser·p0.999:  21.496 ms/op
                 existUser·p0.9999: 29.924 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   3: 5.229 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   8.069 ms/op
                 existUser·p0.99:   11.611 ms/op
                 existUser·p0.999:  29.327 ms/op
                 existUser·p0.9999: 34.638 ms/op
                 existUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182736
  mean =      5.246 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 110382 
    [ 5.000,  7.500) = 58222 
    [ 7.500, 10.000) = 10472 
    [10.000, 12.500) = 2436 
    [12.500, 15.000) = 723 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     21.644 ms/op
     p(99.9900) =     33.224 ms/op
     p(99.9990) =     35.304 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.177 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.231 ±(99.9%) 0.020 ms/op
Iteration   1: 5.363 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   12.501 ms/op
                 getUser·p0.999:  24.817 ms/op
                 getUser·p0.9999: 33.047 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   2: 5.060 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.772 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.406 ms/op
                 getUser·p0.99:   10.265 ms/op
                 getUser·p0.999:  24.625 ms/op
                 getUser·p0.9999: 28.170 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 5.297 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   7.987 ms/op
                 getUser·p0.99:   11.305 ms/op
                 getUser·p0.999:  26.497 ms/op
                 getUser·p0.9999: 32.103 ms/op
                 getUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183243
  mean =      5.237 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 110110 
    [ 5.000,  7.500) = 60899 
    [ 7.500, 10.000) = 8947 
    [10.000, 12.500) = 2076 
    [12.500, 15.000) = 704 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     24.830 ms/op
     p(99.9900) =     31.829 ms/op
     p(99.9990) =     36.365 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 19.386 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.466 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.376 ±(99.9%) 0.029 ms/op
Iteration   1: 6.282 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.812 ms/op
                 listUser·p0.999:  25.955 ms/op
                 listUser·p0.9999: 41.871 ms/op
                 listUser·p1.00:   45.154 ms/op

Iteration   2: 6.204 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.856 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.959 ms/op
                 listUser·p0.999:  29.684 ms/op
                 listUser·p0.9999: 34.834 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   3: 6.218 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  23.776 ms/op
                 listUser·p0.9999: 27.077 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153883
  mean =      6.234 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13082 
    [ 5.000, 10.000) = 134370 
    [10.000, 15.000) = 5429 
    [15.000, 20.000) = 639 
    [20.000, 25.000) = 147 
    [25.000, 30.000) = 138 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.938 ms/op
     p(95.0000) =      9.667 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     26.640 ms/op
     p(99.9900) =     40.960 ms/op
     p(99.9990) =     44.060 ms/op
     p(99.9999) =     45.154 ms/op
    p(100.0000) =     45.154 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.019 ± 4.061  ops/ms
ClientPb.existUser                       thrpt       3   6.407 ± 3.072  ops/ms
ClientPb.getUser                         thrpt       3   5.979 ± 4.251  ops/ms
ClientPb.listUser                        thrpt       3   5.305 ± 1.299  ops/ms
ClientPb.createUser                       avgt       3   5.240 ± 2.287   ms/op
ClientPb.existUser                        avgt       3   4.974 ± 0.409   ms/op
ClientPb.getUser                          avgt       3   5.250 ± 2.425   ms/op
ClientPb.listUser                         avgt       3   6.288 ± 4.897   ms/op
ClientPb.createUser                     sample  182270   5.265 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.477           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.513           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.141           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.569           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.584           ms/op
ClientPb.existUser                      sample  182736   5.246 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.740           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.208           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.518           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.644           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.224           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  183243   5.237 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.565           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.036           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.321           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.830           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.829           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.256           ms/op
ClientPb.listUser                       sample  153883   6.234 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.141           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.667           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.640           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.154           ms/op
