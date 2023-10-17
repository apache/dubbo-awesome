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
# Warmup Iteration   1: 0.985 ops/ms
# Warmup Iteration   2: 2.273 ops/ms
# Warmup Iteration   3: 4.880 ops/ms
Iteration   1: 5.382 ops/ms
Iteration   2: 5.526 ops/ms
Iteration   3: 5.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.542 ±(99.9%) 3.060 ops/ms [Average]
  (min, avg, max) = (5.382, 5.542, 5.717), stdev = 0.168
  CI (99.9%): [2.482, 8.601] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.353 ops/ms
# Warmup Iteration   2: 4.262 ops/ms
# Warmup Iteration   3: 5.597 ops/ms
Iteration   1: 5.854 ops/ms
Iteration   2: 6.270 ops/ms
Iteration   3: 6.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.069 ±(99.9%) 3.802 ops/ms [Average]
  (min, avg, max) = (5.854, 6.069, 6.270), stdev = 0.208
  CI (99.9%): [2.267, 9.870] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.362 ops/ms
# Warmup Iteration   2: 4.068 ops/ms
# Warmup Iteration   3: 5.813 ops/ms
Iteration   1: 5.770 ops/ms
Iteration   2: 5.713 ops/ms
Iteration   3: 5.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.694 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (5.597, 5.694, 5.770), stdev = 0.088
  CI (99.9%): [4.086, 7.301] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.444 ops/ms
# Warmup Iteration   2: 3.844 ops/ms
# Warmup Iteration   3: 4.843 ops/ms
Iteration   1: 4.770 ops/ms
Iteration   2: 4.860 ops/ms
Iteration   3: 4.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.817 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (4.770, 4.817, 4.860), stdev = 0.045
  CI (99.9%): [3.990, 5.644] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 18.320 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.506 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.841 ±(99.9%) 0.008 ms/op
Iteration   1: 5.882 ±(99.9%) 0.010 ms/op
Iteration   2: 5.942 ±(99.9%) 0.008 ms/op
Iteration   3: 5.667 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.830 ±(99.9%) 2.634 ms/op [Average]
  (min, avg, max) = (5.667, 5.830, 5.942), stdev = 0.144
  CI (99.9%): [3.196, 8.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.914 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.389 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.775 ±(99.9%) 0.009 ms/op
Iteration   1: 5.833 ±(99.9%) 0.006 ms/op
Iteration   2: 5.557 ±(99.9%) 0.010 ms/op
Iteration   3: 5.423 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.604 ±(99.9%) 3.818 ms/op [Average]
  (min, avg, max) = (5.423, 5.604, 5.833), stdev = 0.209
  CI (99.9%): [1.787, 9.422] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 19.544 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.263 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.755 ±(99.9%) 0.010 ms/op
Iteration   1: 5.759 ±(99.9%) 0.013 ms/op
Iteration   2: 5.772 ±(99.9%) 0.008 ms/op
Iteration   3: 5.511 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.681 ±(99.9%) 2.688 ms/op [Average]
  (min, avg, max) = (5.511, 5.681, 5.772), stdev = 0.147
  CI (99.9%): [2.993, 8.368] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 21.739 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 8.733 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.888 ±(99.9%) 0.013 ms/op
Iteration   1: 6.736 ±(99.9%) 0.007 ms/op
Iteration   2: 6.621 ±(99.9%) 0.010 ms/op
Iteration   3: 6.753 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.703 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (6.621, 6.703, 6.753), stdev = 0.072
  CI (99.9%): [5.391, 8.016] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 17.762 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 7.564 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.195 ±(99.9%) 0.028 ms/op
Iteration   1: 5.776 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.087 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   10.961 ms/op
                 createUser·p0.999:  28.800 ms/op
                 createUser·p0.9999: 35.672 ms/op
                 createUser·p1.00:   37.487 ms/op

Iteration   2: 5.818 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.531 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  20.811 ms/op
                 createUser·p0.9999: 35.127 ms/op
                 createUser·p1.00:   35.324 ms/op

Iteration   3: 5.907 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.578 ms/op
                 createUser·p0.999:  30.933 ms/op
                 createUser·p0.9999: 38.273 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164464
  mean =      5.833 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 36912 
    [ 5.000,  7.500) = 116344 
    [ 7.500, 10.000) = 8317 
    [10.000, 12.500) = 1977 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 61 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     26.667 ms/op
     p(99.9900) =     37.231 ms/op
     p(99.9990) =     38.586 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.387 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.489 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.025 ms/op
Iteration   1: 5.609 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   6.881 ms/op
                 existUser·p0.95:   7.823 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  16.335 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   2: 5.576 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.552 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  28.508 ms/op
                 existUser·p0.9999: 31.970 ms/op
                 existUser·p1.00:   33.128 ms/op

Iteration   3: 5.488 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.626 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   10.421 ms/op
                 existUser·p0.999:  29.876 ms/op
                 existUser·p0.9999: 34.024 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172658
  mean =      5.557 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 54631 
    [ 5.000,  7.500) = 109892 
    [ 7.500, 10.000) = 6201 
    [10.000, 12.500) = 1323 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.478 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     33.021 ms/op
     p(99.9990) =     36.212 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.304 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.898 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.925 ±(99.9%) 0.023 ms/op
Iteration   1: 5.679 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.843 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.660 ms/op
                 getUser·p0.99:   11.287 ms/op
                 getUser·p0.999:  25.342 ms/op
                 getUser·p0.9999: 28.729 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   2: 5.634 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 36.962 ms/op
                 getUser·p1.00:   39.846 ms/op

Iteration   3: 5.582 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   3.035 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.356 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  27.615 ms/op
                 getUser·p0.9999: 30.736 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170317
  mean =      5.632 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 44753 
    [ 5.000,  7.500) = 116422 
    [ 7.500, 10.000) = 6551 
    [10.000, 12.500) = 1674 
    [12.500, 15.000) = 444 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     24.107 ms/op
     p(99.9900) =     35.387 ms/op
     p(99.9990) =     39.109 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.633 ±(99.9%) 0.394 ms/op
# Warmup Iteration   2: 8.948 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 6.714 ±(99.9%) 0.029 ms/op
Iteration   1: 6.760 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   6.472 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.993 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 28.517 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 6.708 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.472 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  28.519 ms/op
                 listUser·p0.9999: 42.810 ms/op
                 listUser·p1.00:   42.992 ms/op

Iteration   3: 7.014 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   6.652 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   14.123 ms/op
                 listUser·p0.999:  26.052 ms/op
                 listUser·p0.9999: 30.226 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140684
  mean =      6.824 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1973 
    [ 5.000, 10.000) = 133357 
    [10.000, 15.000) = 4599 
    [15.000, 20.000) = 449 
    [20.000, 25.000) = 92 
    [25.000, 30.000) = 173 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      6.521 ms/op
     p(90.0000) =      8.012 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     26.847 ms/op
     p(99.9900) =     41.021 ms/op
     p(99.9990) =     42.965 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


# Run complete. Total time: 00:13:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.542 ± 3.060  ops/ms
ClientPb.existUser                       thrpt       3   6.069 ± 3.802  ops/ms
ClientPb.getUser                         thrpt       3   5.694 ± 1.607  ops/ms
ClientPb.listUser                        thrpt       3   4.817 ± 0.827  ops/ms
ClientPb.createUser                       avgt       3   5.830 ± 2.634   ms/op
ClientPb.existUser                        avgt       3   5.604 ± 3.818   ms/op
ClientPb.getUser                          avgt       3   5.681 ± 2.688   ms/op
ClientPb.listUser                         avgt       3   6.703 ± 1.313   ms/op
ClientPb.createUser                     sample  164464   5.833 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.004           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.667           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.231           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  172658   5.557 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.430           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.273           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.544           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.307           ms/op
ClientPb.getUser                        sample  170317   5.632 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.392           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.107           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.387           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.846           ms/op
ClientPb.listUser                       sample  140684   6.824 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.012           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.140           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.021           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.992           ms/op
