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
# Warmup Iteration   1: 1.846 ops/ms
# Warmup Iteration   2: 4.221 ops/ms
# Warmup Iteration   3: 7.463 ops/ms
Iteration   1: 7.815 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 8.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.030 ±(99.9%) 3.788 ops/ms [Average]
  (min, avg, max) = (7.815, 8.030, 8.230), stdev = 0.208
  CI (99.9%): [4.243, 11.818] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.342 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.482 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.278 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (8.031, 8.278, 8.482), stdev = 0.228
  CI (99.9%): [4.114, 12.442] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
# Warmup Iteration   2: 6.105 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 8.064 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 7.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.988 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (7.846, 7.988, 8.064), stdev = 0.123
  CI (99.9%): [5.740, 10.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.935 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 6.512 ops/ms
Iteration   1: 6.647 ops/ms
Iteration   2: 6.515 ops/ms
Iteration   3: 6.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.509 ±(99.9%) 2.579 ops/ms [Average]
  (min, avg, max) = (6.364, 6.509, 6.647), stdev = 0.141
  CI (99.9%): [3.929, 9.088] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.101 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.930 ±(99.9%) 0.008 ms/op
Iteration   2: 4.002 ±(99.9%) 0.005 ms/op
Iteration   3: 3.905 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.946 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (3.905, 3.946, 4.002), stdev = 0.051
  CI (99.9%): [3.021, 4.870] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.916 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.004 ms/op
Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
Iteration   3: 3.693 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.749 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.693, 3.749, 3.800), stdev = 0.054
  CI (99.9%): [2.769, 4.729] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.530 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.004 ms/op
Iteration   1: 4.022 ±(99.9%) 0.004 ms/op
Iteration   2: 4.001 ±(99.9%) 0.003 ms/op
Iteration   3: 3.975 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.999 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.975, 3.999, 4.022), stdev = 0.023
  CI (99.9%): [3.575, 4.424] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.522 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.539 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.848 ±(99.9%) 0.008 ms/op
Iteration   1: 4.796 ±(99.9%) 0.009 ms/op
Iteration   2: 4.855 ±(99.9%) 0.012 ms/op
Iteration   3: 4.569 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.740 ±(99.9%) 2.756 ms/op [Average]
  (min, avg, max) = (4.569, 4.740, 4.855), stdev = 0.151
  CI (99.9%): [1.985, 7.496] (assumes normal distribution)


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
# Warmup Iteration   1: 12.795 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.769 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.018 ms/op
Iteration   1: 3.953 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  23.912 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 3.864 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.236 ms/op
                 createUser·p0.999:  26.679 ms/op
                 createUser·p0.9999: 34.060 ms/op
                 createUser·p1.00:   39.059 ms/op

Iteration   3: 3.970 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  15.650 ms/op
                 createUser·p0.9999: 36.214 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244334
  mean =      3.928 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 665 
    [ 2.500,  5.000) = 230443 
    [ 5.000,  7.500) = 10380 
    [ 7.500, 10.000) = 1880 
    [10.000, 12.500) = 568 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     23.746 ms/op
     p(99.9900) =     34.518 ms/op
     p(99.9990) =     37.947 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.359 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
Iteration   1: 3.772 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  23.469 ms/op
                 existUser·p0.9999: 32.523 ms/op
                 existUser·p1.00:   33.358 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  11.439 ms/op
                 existUser·p0.9999: 25.442 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  12.354 ms/op
                 existUser·p0.9999: 34.045 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248868
  mean =      3.857 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 555 
    [ 2.500,  5.000) = 237502 
    [ 5.000,  7.500) = 8786 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     32.899 ms/op
     p(99.9990) =     34.867 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 12.658 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.015 ms/op
Iteration   1: 4.257 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   6.668 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  23.748 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.071 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 35.627 ms/op
                 getUser·p1.00:   36.569 ms/op

Iteration   3: 3.957 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   7.451 ms/op
                 getUser·p0.999:  30.265 ms/op
                 getUser·p0.9999: 32.762 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237852
  mean =      4.035 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 222295 
    [ 5.000,  7.500) = 11648 
    [ 7.500, 10.000) = 2862 
    [10.000, 12.500) = 493 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     33.676 ms/op
     p(99.9990) =     36.167 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 14.609 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.857 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.921 ±(99.9%) 0.019 ms/op
Iteration   1: 4.864 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.291 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  27.370 ms/op
                 listUser·p0.9999: 32.749 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   2: 4.874 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.805 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  19.373 ms/op
                 listUser·p0.9999: 24.900 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 4.859 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 22.788 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197151
  mean =      4.866 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 153340 
    [ 5.000,  7.500) = 36822 
    [ 7.500, 10.000) = 5149 
    [10.000, 12.500) = 1098 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     33.296 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.030 ± 3.788  ops/ms
ClientPb.existUser                       thrpt       3   8.278 ± 4.164  ops/ms
ClientPb.getUser                         thrpt       3   7.988 ± 2.248  ops/ms
ClientPb.listUser                        thrpt       3   6.509 ± 2.579  ops/ms
ClientPb.createUser                       avgt       3   3.946 ± 0.924   ms/op
ClientPb.existUser                        avgt       3   3.749 ± 0.980   ms/op
ClientPb.getUser                          avgt       3   3.999 ± 0.424   ms/op
ClientPb.listUser                         avgt       3   4.740 ± 2.756   ms/op
ClientPb.createUser                     sample  244334   3.928 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.620           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.746           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.518           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.059           ms/op
ClientPb.existUser                      sample  248868   3.857 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.943           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.899           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  237852   4.035 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.282           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.691           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.676           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569           ms/op
ClientPb.listUser                       sample  197151   4.866 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.365           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.577           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.162           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.423           ms/op
