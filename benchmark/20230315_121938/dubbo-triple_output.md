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
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.491 ops/ms
# Warmup Iteration   3: 8.741 ops/ms
Iteration   1: 9.057 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.377 ±(99.9%) 5.227 ops/ms [Average]
  (min, avg, max) = (9.057, 9.377, 9.610), stdev = 0.287
  CI (99.9%): [4.150, 14.605] (assumes normal distribution)


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
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 8.798 ops/ms
# Warmup Iteration   3: 9.466 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 10.222 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.986 ±(99.9%) 4.184 ops/ms [Average]
  (min, avg, max) = (9.764, 9.986, 10.222), stdev = 0.229
  CI (99.9%): [5.802, 14.170] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 8.624 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.690 ops/ms
Iteration   2: 9.685 ops/ms
Iteration   3: 9.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.617 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (9.475, 9.617, 9.690), stdev = 0.123
  CI (99.9%): [7.376, 11.857] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 7.528 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.343 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 7.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.184 ±(99.9%) 4.629 ops/ms [Average]
  (min, avg, max) = (7.891, 8.184, 8.343), stdev = 0.254
  CI (99.9%): [3.555, 12.813] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.803 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.003 ms/op
Iteration   1: 3.279 ±(99.9%) 0.011 ms/op
Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
Iteration   3: 3.442 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.378 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (3.279, 3.378, 3.442), stdev = 0.087
  CI (99.9%): [1.789, 4.966] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.763 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.010 ms/op
Iteration   1: 3.341 ±(99.9%) 0.004 ms/op
Iteration   2: 3.185 ±(99.9%) 0.004 ms/op
Iteration   3: 3.156 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.227 ±(99.9%) 1.818 ms/op [Average]
  (min, avg, max) = (3.156, 3.227, 3.341), stdev = 0.100
  CI (99.9%): [1.409, 5.045] (assumes normal distribution)


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
# Warmup Iteration   1: 9.112 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.002 ms/op
Iteration   1: 3.480 ±(99.9%) 0.007 ms/op
Iteration   2: 3.345 ±(99.9%) 0.003 ms/op
Iteration   3: 3.436 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.420 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.345, 3.420, 3.480), stdev = 0.069
  CI (99.9%): [2.163, 4.677] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.789 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.008 ms/op
Iteration   1: 3.997 ±(99.9%) 0.007 ms/op
Iteration   2: 3.799 ±(99.9%) 0.011 ms/op
Iteration   3: 3.872 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 1.831 ms/op [Average]
  (min, avg, max) = (3.799, 3.889, 3.997), stdev = 0.100
  CI (99.9%): [2.059, 5.720] (assumes normal distribution)


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
# Warmup Iteration   1: 10.303 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.010 ms/op
Iteration   1: 3.605 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  20.616 ms/op
                 createUser·p0.9999: 23.666 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  21.782 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  18.769 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272135
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8471 
    [ 2.500,  5.000) = 252738 
    [ 5.000,  7.500) = 9860 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     19.959 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 8.754 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  20.087 ms/op
                 existUser·p0.9999: 23.425 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  21.591 ms/op
                 existUser·p0.9999: 30.173 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.003 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  8.254 ms/op
                 existUser·p0.9999: 23.536 ms/op
                 existUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289132
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15624 
    [ 2.500,  5.000) = 268597 
    [ 5.000,  7.500) = 4061 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     29.265 ms/op
     p(99.9990) =     32.006 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 9.265 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.012 ms/op
Iteration   1: 3.577 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  19.681 ms/op
                 getUser·p0.9999: 22.157 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.497 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 25.545 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  9.406 ms/op
                 getUser·p0.9999: 28.909 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274670
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11617 
    [ 2.500,  5.000) = 255162 
    [ 5.000,  7.500) = 6854 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     11.523 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.074 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.666 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.013 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  20.582 ms/op
                 listUser·p0.9999: 23.758 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 3.917 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.801 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.917 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.842 ms/op
                 listUser·p0.9999: 16.120 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243040
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 234627 
    [ 5.000,  7.500) = 6598 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.089 ms/op
     p(99.9900) =     23.419 ms/op
     p(99.9990) =     24.173 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.377 ± 5.227  ops/ms
ClientPb.existUser                       thrpt       3   9.986 ± 4.184  ops/ms
ClientPb.getUser                         thrpt       3   9.617 ± 2.240  ops/ms
ClientPb.listUser                        thrpt       3   8.184 ± 4.629  ops/ms
ClientPb.createUser                       avgt       3   3.378 ± 1.588   ms/op
ClientPb.existUser                        avgt       3   3.227 ± 1.818   ms/op
ClientPb.getUser                          avgt       3   3.420 ± 1.257   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 1.831   ms/op
ClientPb.createUser                     sample  272135   3.528 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.571           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.959           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  289132   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.094           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.265           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  274670   3.491 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.542           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.523           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.460           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  243040   3.950 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.089           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.419           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
