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
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 6.153 ops/ms
# Warmup Iteration   3: 8.678 ops/ms
Iteration   1: 9.223 ops/ms
Iteration   2: 9.202 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.281 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (9.202, 9.281, 9.419), stdev = 0.120
  CI (99.9%): [7.094, 11.469] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.567 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (9.465, 9.567, 9.639), stdev = 0.091
  CI (99.9%): [7.909, 11.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.332 ops/ms
# Warmup Iteration   2: 8.297 ops/ms
# Warmup Iteration   3: 9.184 ops/ms
Iteration   1: 9.290 ops/ms
Iteration   2: 9.127 ops/ms
Iteration   3: 9.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.150 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (9.034, 9.150, 9.290), stdev = 0.130
  CI (99.9%): [6.781, 11.520] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 6.803 ops/ms
# Warmup Iteration   3: 7.394 ops/ms
Iteration   1: 7.617 ops/ms
Iteration   2: 7.760 ops/ms
Iteration   3: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.702 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (7.617, 7.702, 7.760), stdev = 0.076
  CI (99.9%): [6.323, 9.081] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.752 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.006 ms/op
Iteration   1: 3.534 ±(99.9%) 0.004 ms/op
Iteration   2: 3.539 ±(99.9%) 0.006 ms/op
Iteration   3: 3.337 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.470 ±(99.9%) 2.102 ms/op [Average]
  (min, avg, max) = (3.337, 3.470, 3.539), stdev = 0.115
  CI (99.9%): [1.368, 5.572] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.006 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op
Iteration   2: 3.327 ±(99.9%) 0.006 ms/op
Iteration   3: 3.308 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.304, 3.313, 3.327), stdev = 0.012
  CI (99.9%): [3.085, 3.541] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.016 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.006 ms/op
Iteration   1: 3.638 ±(99.9%) 0.006 ms/op
Iteration   2: 3.388 ±(99.9%) 0.004 ms/op
Iteration   3: 3.677 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.568 ±(99.9%) 2.859 ms/op [Average]
  (min, avg, max) = (3.388, 3.568, 3.677), stdev = 0.157
  CI (99.9%): [0.709, 6.426] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.296 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.009 ms/op
Iteration   1: 4.134 ±(99.9%) 0.006 ms/op
Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
Iteration   3: 4.013 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.079 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (4.013, 4.079, 4.134), stdev = 0.062
  CI (99.9%): [2.957, 5.202] (assumes normal distribution)


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
# Warmup Iteration   1: 8.922 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 22.179 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.432 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  20.967 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  19.614 ms/op
                 createUser·p0.9999: 29.964 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282254
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8714 
    [ 2.500,  5.000) = 268027 
    [ 5.000,  7.500) = 4024 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     19.685 ms/op
     p(99.9900) =     28.206 ms/op
     p(99.9990) =     30.962 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 10.425 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  19.399 ms/op
                 existUser·p0.9999: 25.139 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  21.325 ms/op
                 existUser·p0.9999: 24.839 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  12.129 ms/op
                 existUser·p0.9999: 27.024 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281632
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17399 
    [ 2.500,  5.000) = 255265 
    [ 5.000,  7.500) = 7561 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     26.303 ms/op
     p(99.9990) =     27.609 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 9.343 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.011 ms/op
Iteration   1: 3.541 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  14.466 ms/op
                 getUser·p0.9999: 18.840 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.472 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 21.083 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  18.583 ms/op
                 getUser·p0.9999: 23.299 ms/op
                 getUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274420
  mean =      3.497 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9298 
    [ 2.500,  5.000) = 257145 
    [ 5.000,  7.500) = 5998 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 171 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.724 ms/op
     p(99.9000) =     14.919 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     25.044 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 12.100 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.015 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  21.043 ms/op
                 listUser·p0.9999: 30.704 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.701 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.320 ms/op
                 listUser·p0.999:  14.936 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234543
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 223885 
    [ 5.000,  7.500) = 7947 
    [ 7.500, 10.000) = 1489 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.281 ± 2.187  ops/ms
ClientPb.existUser                       thrpt       3   9.567 ± 1.658  ops/ms
ClientPb.getUser                         thrpt       3   9.150 ± 2.370  ops/ms
ClientPb.listUser                        thrpt       3   7.702 ± 1.379  ops/ms
ClientPb.createUser                       avgt       3   3.470 ± 2.102   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 0.228   ms/op
ClientPb.getUser                          avgt       3   3.568 ± 2.859   ms/op
ClientPb.listUser                         avgt       3   4.079 ± 1.123   ms/op
ClientPb.createUser                     sample  282254   3.399 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.352           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.685           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.293           ms/op
ClientPb.existUser                      sample  281632   3.410 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.602           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.303           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  274420   3.497 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.724           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.919           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.643           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  234543   4.094 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.819           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
