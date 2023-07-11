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
# Warmup Iteration   1: 1.798 ops/ms
# Warmup Iteration   2: 4.044 ops/ms
# Warmup Iteration   3: 7.615 ops/ms
Iteration   1: 7.716 ops/ms
Iteration   2: 8.145 ops/ms
Iteration   3: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.049 ±(99.9%) 5.398 ops/ms [Average]
  (min, avg, max) = (7.716, 8.049, 8.284), stdev = 0.296
  CI (99.9%): [2.650, 13.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.588 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 8.579 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.417 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (8.328, 8.417, 8.579), stdev = 0.141
  CI (99.9%): [5.854, 10.980] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.327 ops/ms
# Warmup Iteration   2: 6.895 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.156 ±(99.9%) 7.007 ops/ms [Average]
  (min, avg, max) = (7.715, 8.156, 8.417), stdev = 0.384
  CI (99.9%): [1.149, 15.164] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.540 ops/ms
# Warmup Iteration   3: 6.755 ops/ms
Iteration   1: 6.865 ops/ms
Iteration   2: 6.776 ops/ms
Iteration   3: 6.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.837 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (6.776, 6.837, 6.870), stdev = 0.053
  CI (99.9%): [5.871, 7.803] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.478 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.637 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.007 ms/op
Iteration   1: 4.137 ±(99.9%) 0.003 ms/op
Iteration   2: 4.014 ±(99.9%) 0.005 ms/op
Iteration   3: 3.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.045 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (3.984, 4.045, 4.137), stdev = 0.081
  CI (99.9%): [2.561, 5.529] (assumes normal distribution)


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
# Warmup Iteration   1: 12.323 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.013 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
Iteration   2: 3.860 ±(99.9%) 0.006 ms/op
Iteration   3: 3.793 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.799 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.745, 3.799, 3.860), stdev = 0.058
  CI (99.9%): [2.738, 4.860] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.998 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.003 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
Iteration   2: 3.883 ±(99.9%) 0.012 ms/op
Iteration   3: 3.964 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.935 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.883, 3.935, 3.964), stdev = 0.045
  CI (99.9%): [3.109, 4.761] (assumes normal distribution)


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
# Warmup Iteration   1: 13.591 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.012 ms/op
Iteration   1: 4.581 ±(99.9%) 0.012 ms/op
Iteration   2: 4.712 ±(99.9%) 0.020 ms/op
Iteration   3: 4.688 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.661 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (4.581, 4.661, 4.712), stdev = 0.070
  CI (99.9%): [3.390, 5.931] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.882 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.751 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.017 ms/op
Iteration   1: 3.972 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  24.550 ms/op
                 createUser·p0.9999: 35.324 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   2: 4.178 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  26.995 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   35.258 ms/op

Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  23.102 ms/op
                 createUser·p0.9999: 33.112 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239819
  mean =      4.005 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 567 
    [ 2.500,  5.000) = 225464 
    [ 5.000,  7.500) = 11828 
    [ 7.500, 10.000) = 1207 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     24.999 ms/op
     p(99.9900) =     34.604 ms/op
     p(99.9990) =     35.560 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 11.093 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  22.420 ms/op
                 existUser·p0.9999: 26.152 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.708 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 31.679 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254403
  mean =      3.770 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1737 
    [ 2.500,  5.000) = 241973 
    [ 5.000,  7.500) = 9359 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     16.715 ms/op
     p(99.9900) =     31.115 ms/op
     p(99.9990) =     32.011 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 12.466 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
Iteration   1: 3.966 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.379 ms/op
                 getUser·p0.999:  22.032 ms/op
                 getUser·p0.9999: 24.934 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.908 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.831 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.548 ms/op
                 getUser·p0.999:  10.668 ms/op
                 getUser·p0.9999: 26.112 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.970 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.634 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  26.785 ms/op
                 getUser·p0.9999: 32.733 ms/op
                 getUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243075
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 247 
    [ 2.500,  5.000) = 230934 
    [ 5.000,  7.500) = 10176 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     21.985 ms/op
     p(99.9900) =     30.651 ms/op
     p(99.9990) =     33.035 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 14.740 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.890 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.017 ms/op
Iteration   1: 4.756 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 49.021 ms/op
                 listUser·p1.00:   54.723 ms/op

Iteration   2: 4.559 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  18.075 ms/op
                 listUser·p0.9999: 21.427 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.628 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.250 ms/op
                 listUser·p0.999:  17.200 ms/op
                 listUser·p0.9999: 19.667 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206561
  mean =      4.646 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 174966 
    [ 5.000, 10.000) = 30636 
    [10.000, 15.000) = 507 
    [15.000, 20.000) = 213 
    [20.000, 25.000) = 130 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 11 
    [45.000, 50.000) = 14 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     42.664 ms/op
     p(99.9990) =     51.724 ms/op
     p(99.9999) =     54.723 ms/op
    p(100.0000) =     54.723 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.049 ± 5.398  ops/ms
ClientPb.existUser                       thrpt       3   8.417 ± 2.563  ops/ms
ClientPb.getUser                         thrpt       3   8.156 ± 7.007  ops/ms
ClientPb.listUser                        thrpt       3   6.837 ± 0.966  ops/ms
ClientPb.createUser                       avgt       3   4.045 ± 1.484   ms/op
ClientPb.existUser                        avgt       3   3.799 ± 1.061   ms/op
ClientPb.getUser                          avgt       3   3.935 ± 0.826   ms/op
ClientPb.listUser                         avgt       3   4.661 ± 1.270   ms/op
ClientPb.createUser                     sample  239819   4.005 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.565           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.999           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.604           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  254403   3.770 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.115           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.080           ms/op
ClientPb.getUser                        sample  243075   3.947 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.634           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.985           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.651           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.817           ms/op
ClientPb.listUser                       sample  206561   4.646 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.323           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.070           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.664           ms/op
ClientPb.listUser:listUser·p1.00        sample          54.723           ms/op
