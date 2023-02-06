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
# Warmup Iteration   1: 2.185 ops/ms
# Warmup Iteration   2: 5.222 ops/ms
# Warmup Iteration   3: 8.550 ops/ms
Iteration   1: 9.031 ops/ms
Iteration   2: 9.354 ops/ms
Iteration   3: 9.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.227 ±(99.9%) 3.153 ops/ms [Average]
  (min, avg, max) = (9.031, 9.227, 9.354), stdev = 0.173
  CI (99.9%): [6.075, 12.380] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 8.718 ops/ms
# Warmup Iteration   3: 9.624 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 9.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.873 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (9.740, 9.873, 9.982), stdev = 0.123
  CI (99.9%): [7.638, 12.109] (assumes normal distribution)


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
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 7.883 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.634 ±(99.9%) 2.804 ops/ms [Average]
  (min, avg, max) = (9.472, 9.634, 9.778), stdev = 0.154
  CI (99.9%): [6.831, 12.438] (assumes normal distribution)


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
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.029 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (7.939, 8.029, 8.165), stdev = 0.120
  CI (99.9%): [5.847, 10.211] (assumes normal distribution)


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
# Warmup Iteration   1: 9.427 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.004 ms/op
Iteration   1: 3.392 ±(99.9%) 0.013 ms/op
Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
Iteration   3: 3.404 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.385 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.358, 3.385, 3.404), stdev = 0.024
  CI (99.9%): [2.953, 3.816] (assumes normal distribution)


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
# Warmup Iteration   1: 9.793 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.010 ms/op
Iteration   1: 3.222 ±(99.9%) 0.011 ms/op
Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
Iteration   3: 3.287 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.245 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.222, 3.245, 3.287), stdev = 0.036
  CI (99.9%): [2.582, 3.909] (assumes normal distribution)


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
# Warmup Iteration   1: 11.153 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.003 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
Iteration   3: 3.323 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (3.323, 3.410, 3.512), stdev = 0.096
  CI (99.9%): [1.664, 5.156] (assumes normal distribution)


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
# Warmup Iteration   1: 10.384 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.583 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
Iteration   1: 3.996 ±(99.9%) 0.017 ms/op
Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
Iteration   3: 3.926 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.926, 3.958, 3.996), stdev = 0.035
  CI (99.9%): [3.314, 4.602] (assumes normal distribution)


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
# Warmup Iteration   1: 10.448 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.013 ms/op
Iteration   1: 3.477 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  19.539 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  23.067 ms/op
                 createUser·p0.9999: 27.017 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.938 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  17.904 ms/op
                 createUser·p0.9999: 27.585 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282771
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7531 
    [ 2.500,  5.000) = 269602 
    [ 5.000,  7.500) = 4634 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     26.992 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.590 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  17.476 ms/op
                 existUser·p0.9999: 23.390 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.342 ms/op
                 existUser·p0.9999: 22.061 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  16.840 ms/op
                 existUser·p0.9999: 25.768 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289252
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13622 
    [ 2.500,  5.000) = 268019 
    [ 5.000,  7.500) = 6713 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     24.319 ms/op
     p(99.9990) =     26.334 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 8.826 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.548 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  16.477 ms/op
                 getUser·p0.9999: 21.397 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  21.447 ms/op
                 getUser·p0.9999: 25.016 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 3.451 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  20.779 ms/op
                 getUser·p0.9999: 31.219 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278353
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4662 
    [ 2.500,  5.000) = 266183 
    [ 5.000,  7.500) = 6167 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     16.612 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     31.301 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 11.115 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.013 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.065 ms/op
                 listUser·p0.9999: 23.728 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.486 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 18.136 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.017 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241963
  mean =      3.968 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 233978 
    [ 5.000,  7.500) = 5862 
    [ 7.500, 10.000) = 1121 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     22.197 ms/op
     p(99.9990) =     24.071 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.227 ± 3.153  ops/ms
ClientPb.existUser                       thrpt       3   9.873 ± 2.236  ops/ms
ClientPb.getUser                         thrpt       3   9.634 ± 2.804  ops/ms
ClientPb.listUser                        thrpt       3   8.029 ± 2.182  ops/ms
ClientPb.createUser                       avgt       3   3.385 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   3.245 ± 0.663   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 1.746   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 0.644   ms/op
ClientPb.createUser                     sample  282771   3.391 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.955           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  289252   3.319 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.319           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  278353   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.602           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  241963   3.968 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.197           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
