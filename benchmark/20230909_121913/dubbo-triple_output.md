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
# Warmup Iteration   1: 2.023 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.745 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.912 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (8.745, 8.912, 9.034), stdev = 0.149
  CI (99.9%): [6.188, 11.636] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.761 ops/ms
# Warmup Iteration   2: 8.139 ops/ms
# Warmup Iteration   3: 9.344 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.562 ops/ms
Iteration   3: 9.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.685 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (9.562, 9.685, 9.777), stdev = 0.111
  CI (99.9%): [7.659, 11.710] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.755 ops/ms
# Warmup Iteration   2: 8.284 ops/ms
# Warmup Iteration   3: 9.053 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.224 ops/ms
Iteration   3: 9.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.264 ±(99.9%) 1.727 ops/ms [Average]
  (min, avg, max) = (9.195, 9.264, 9.372), stdev = 0.095
  CI (99.9%): [7.537, 10.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.714 ops/ms
# Warmup Iteration   2: 6.737 ops/ms
# Warmup Iteration   3: 7.537 ops/ms
Iteration   1: 7.733 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.797 ±(99.9%) 2.446 ops/ms [Average]
  (min, avg, max) = (7.708, 7.797, 7.952), stdev = 0.134
  CI (99.9%): [5.351, 10.244] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.557 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.008 ms/op
Iteration   1: 3.498 ±(99.9%) 0.003 ms/op
Iteration   2: 3.596 ±(99.9%) 0.004 ms/op
Iteration   3: 3.448 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.448, 3.514, 3.596), stdev = 0.075
  CI (99.9%): [2.139, 4.889] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.206 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.005 ms/op
Iteration   1: 3.389 ±(99.9%) 0.004 ms/op
Iteration   2: 3.460 ±(99.9%) 0.007 ms/op
Iteration   3: 3.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.453 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (3.389, 3.453, 3.511), stdev = 0.061
  CI (99.9%): [2.341, 4.566] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.813 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.006 ms/op
Iteration   1: 3.573 ±(99.9%) 0.006 ms/op
Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
Iteration   3: 3.516 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.536 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.516, 3.536, 3.573), stdev = 0.032
  CI (99.9%): [2.961, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 11.203 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.006 ms/op
Iteration   1: 4.306 ±(99.9%) 0.005 ms/op
Iteration   2: 4.078 ±(99.9%) 0.006 ms/op
Iteration   3: 4.019 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.135 ±(99.9%) 2.769 ms/op [Average]
  (min, avg, max) = (4.019, 4.135, 4.306), stdev = 0.152
  CI (99.9%): [1.365, 6.904] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.837 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.016 ms/op
Iteration   1: 3.414 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.016 ms/op
                 createUser·p0.999:  21.879 ms/op
                 createUser·p0.9999: 24.418 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   2: 3.509 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.340 ms/op
                 createUser·p0.999:  23.852 ms/op
                 createUser·p0.9999: 26.102 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.618 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.848 ms/op
                 createUser·p0.999:  19.437 ms/op
                 createUser·p0.9999: 29.070 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273175
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5465 
    [ 2.500,  5.000) = 260019 
    [ 5.000,  7.500) = 5927 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     27.744 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 9.219 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
Iteration   1: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  20.413 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  22.959 ms/op
                 existUser·p0.9999: 27.103 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  12.344 ms/op
                 existUser·p0.9999: 30.060 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278789
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12757 
    [ 2.500,  5.000) = 258455 
    [ 5.000,  7.500) = 5947 
    [ 7.500, 10.000) = 1001 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     31.141 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 8.650 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.013 ms/op
Iteration   1: 3.613 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.001 ms/op
                 getUser·p0.999:  11.311 ms/op
                 getUser·p0.9999: 26.566 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  23.018 ms/op
                 getUser·p0.9999: 26.971 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.620 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  20.215 ms/op
                 getUser·p0.9999: 29.262 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266546
  mean =      3.601 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2418 
    [ 2.500,  5.000) = 251820 
    [ 5.000,  7.500) = 10163 
    [ 7.500, 10.000) = 1466 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     12.851 ms/op
     p(99.9900) =     28.061 ms/op
     p(99.9990) =     29.404 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 11.547 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.015 ms/op
Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.476 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 27.471 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   8.436 ms/op
                 listUser·p0.999:  17.078 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  15.879 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232284
  mean =      4.132 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 221183 
    [ 5.000,  7.500) = 7767 
    [ 7.500, 10.000) = 2053 
    [10.000, 12.500) = 660 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.751 ms/op
     p(99.9900) =     25.817 ms/op
     p(99.9990) =     28.642 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.912 ± 2.724  ops/ms
ClientPb.existUser                       thrpt       3   9.685 ± 2.025  ops/ms
ClientPb.getUser                         thrpt       3   9.264 ± 1.727  ops/ms
ClientPb.listUser                        thrpt       3   7.797 ± 2.446  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 1.375   ms/op
ClientPb.existUser                        avgt       3   3.453 ± 1.113   ms/op
ClientPb.getUser                          avgt       3   3.536 ± 0.575   ms/op
ClientPb.listUser                         avgt       3   4.135 ± 2.769   ms/op
ClientPb.createUser                     sample  273175   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.744           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  278789   3.441 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.901           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  266546   3.601 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.559           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.851           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.061           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  232284   4.132 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.751           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.817           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
