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
# Warmup Iteration   1: 1.029 ops/ms
# Warmup Iteration   2: 2.175 ops/ms
# Warmup Iteration   3: 4.927 ops/ms
Iteration   1: 5.341 ops/ms
Iteration   2: 5.661 ops/ms
Iteration   3: 5.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.597 ±(99.9%) 4.203 ops/ms [Average]
  (min, avg, max) = (5.341, 5.597, 5.788), stdev = 0.230
  CI (99.9%): [1.394, 9.800] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
# Warmup Iteration   2: 4.275 ops/ms
# Warmup Iteration   3: 5.888 ops/ms
Iteration   1: 5.931 ops/ms
Iteration   2: 6.203 ops/ms
Iteration   3: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.161 ±(99.9%) 3.868 ops/ms [Average]
  (min, avg, max) = (5.931, 6.161, 6.349), stdev = 0.212
  CI (99.9%): [2.293, 10.028] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 4.251 ops/ms
# Warmup Iteration   3: 5.802 ops/ms
Iteration   1: 5.629 ops/ms
Iteration   2: 5.494 ops/ms
Iteration   3: 5.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.614 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (5.494, 5.614, 5.720), stdev = 0.114
  CI (99.9%): [3.538, 7.691] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 3.783 ops/ms
# Warmup Iteration   3: 5.062 ops/ms
Iteration   1: 4.806 ops/ms
Iteration   2: 5.064 ops/ms
Iteration   3: 4.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.916 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (4.806, 4.916, 5.064), stdev = 0.133
  CI (99.9%): [2.487, 7.345] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.951 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.452 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.014 ms/op
Iteration   1: 5.933 ±(99.9%) 0.013 ms/op
Iteration   2: 5.585 ±(99.9%) 0.014 ms/op
Iteration   3: 5.374 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.630 ±(99.9%) 5.149 ms/op [Average]
  (min, avg, max) = (5.374, 5.630, 5.933), stdev = 0.282
  CI (99.9%): [0.482, 10.779] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.637 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.670 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.484 ±(99.9%) 0.012 ms/op
Iteration   1: 5.475 ±(99.9%) 0.010 ms/op
Iteration   2: 5.481 ±(99.9%) 0.009 ms/op
Iteration   3: 5.427 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.461 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (5.427, 5.461, 5.481), stdev = 0.029
  CI (99.9%): [4.925, 5.998] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 19.488 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.685 ±(99.9%) 0.024 ms/op
Iteration   1: 5.624 ±(99.9%) 0.013 ms/op
Iteration   2: 5.813 ±(99.9%) 0.010 ms/op
Iteration   3: 5.682 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.707 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (5.624, 5.707, 5.813), stdev = 0.097
  CI (99.9%): [3.939, 7.474] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 21.722 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 8.454 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.707 ±(99.9%) 0.013 ms/op
Iteration   1: 6.476 ±(99.9%) 0.013 ms/op
Iteration   2: 6.484 ±(99.9%) 0.012 ms/op
Iteration   3: 6.289 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.416 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (6.289, 6.416, 6.484), stdev = 0.110
  CI (99.9%): [4.402, 8.431] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.881 ±(99.9%) 0.396 ms/op
# Warmup Iteration   2: 8.858 ±(99.9%) 0.079 ms/op
# Warmup Iteration   3: 5.992 ±(99.9%) 0.028 ms/op
Iteration   1: 5.782 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.655 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  25.612 ms/op
                 createUser·p0.9999: 34.235 ms/op
                 createUser·p1.00:   34.734 ms/op

Iteration   2: 5.803 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.493 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  18.737 ms/op
                 createUser·p0.9999: 29.818 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   3: 5.480 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.649 ms/op
                 createUser·p0.999:  28.095 ms/op
                 createUser·p0.9999: 31.052 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168964
  mean =      5.684 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 53166 
    [ 5.000,  7.500) = 102054 
    [ 7.500, 10.000) = 10403 
    [10.000, 12.500) = 2357 
    [12.500, 15.000) = 700 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     31.002 ms/op
     p(99.9990) =     34.644 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.375 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.310 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.624 ±(99.9%) 0.022 ms/op
Iteration   1: 5.434 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.385 ms/op
                 existUser·p0.99:   10.469 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 37.232 ms/op
                 existUser·p1.00:   37.487 ms/op

Iteration   2: 5.607 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   11.583 ms/op
                 existUser·p0.999:  26.509 ms/op
                 existUser·p0.9999: 30.320 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   3: 5.708 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.390 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   8.315 ms/op
                 existUser·p0.99:   11.796 ms/op
                 existUser·p0.999:  28.508 ms/op
                 existUser·p0.9999: 36.268 ms/op
                 existUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171980
  mean =      5.580 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 54221 
    [ 5.000,  7.500) = 105935 
    [ 7.500, 10.000) = 8746 
    [10.000, 12.500) = 1988 
    [12.500, 15.000) = 581 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     37.392 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.549 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 7.529 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.543 ±(99.9%) 0.020 ms/op
Iteration   1: 5.605 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   7.365 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   12.166 ms/op
                 getUser·p0.999:  26.482 ms/op
                 getUser·p0.9999: 30.559 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   2: 5.377 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.569 ms/op
                 getUser·p0.99:   10.863 ms/op
                 getUser·p0.999:  33.518 ms/op
                 getUser·p0.9999: 37.028 ms/op
                 getUser·p1.00:   38.928 ms/op

Iteration   3: 5.625 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.580 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.078 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   12.173 ms/op
                 getUser·p0.999:  28.683 ms/op
                 getUser·p0.9999: 35.612 ms/op
                 getUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173526
  mean =      5.533 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 71039 
    [ 5.000,  7.500) = 89295 
    [ 7.500, 10.000) = 9752 
    [10.000, 12.500) = 2109 
    [12.500, 15.000) = 734 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     29.196 ms/op
     p(99.9900) =     37.028 ms/op
     p(99.9990) =     39.150 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.090 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 8.118 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.823 ±(99.9%) 0.031 ms/op
Iteration   1: 6.834 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.886 ms/op
                 listUser·p0.999:  27.765 ms/op
                 listUser·p0.9999: 31.619 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   2: 6.603 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   13.013 ms/op
                 listUser·p0.999:  33.589 ms/op
                 listUser·p0.9999: 39.911 ms/op
                 listUser·p1.00:   40.698 ms/op

Iteration   3: 6.615 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   13.025 ms/op
                 listUser·p0.999:  25.559 ms/op
                 listUser·p0.9999: 31.561 ms/op
                 listUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143684
  mean =      6.682 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3253 
    [ 5.000, 10.000) = 133891 
    [10.000, 15.000) = 5594 
    [15.000, 20.000) = 609 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 135 
    [30.000, 35.000) = 83 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     13.763 ms/op
     p(99.9000) =     28.682 ms/op
     p(99.9900) =     38.670 ms/op
     p(99.9990) =     40.469 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.597 ± 4.203  ops/ms
ClientPb.existUser                       thrpt       3   6.161 ± 3.868  ops/ms
ClientPb.getUser                         thrpt       3   5.614 ± 2.077  ops/ms
ClientPb.listUser                        thrpt       3   4.916 ± 2.429  ops/ms
ClientPb.createUser                       avgt       3   5.630 ± 5.149   ms/op
ClientPb.existUser                        avgt       3   5.461 ± 0.536   ms/op
ClientPb.getUser                          avgt       3   5.707 ± 1.768   ms/op
ClientPb.listUser                         avgt       3   6.416 ± 2.014   ms/op
ClientPb.createUser                     sample  168964   5.684 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.493           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.405           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.370           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.002           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  171980   5.580 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.053           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.970           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487           ms/op
ClientPb.getUser                        sample  173526   5.533 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.348           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.731           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.196           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.584           ms/op
ClientPb.listUser                       sample  143684   6.682 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.763           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.682           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.670           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.698           ms/op
