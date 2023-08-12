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
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 5.810 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 9.026 ops/ms
Iteration   2: 9.005 ops/ms
Iteration   3: 9.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.088 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (9.005, 9.088, 9.234), stdev = 0.127
  CI (99.9%): [6.779, 11.397] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.187 ops/ms
Iteration   1: 9.320 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.511 ±(99.9%) 3.406 ops/ms [Average]
  (min, avg, max) = (9.320, 9.511, 9.693), stdev = 0.187
  CI (99.9%): [6.104, 12.917] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.354 ops/ms
# Warmup Iteration   2: 8.681 ops/ms
# Warmup Iteration   3: 8.817 ops/ms
Iteration   1: 9.300 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.307 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (9.239, 9.307, 9.381), stdev = 0.072
  CI (99.9%): [8.002, 10.612] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.973 ±(99.9%) 0.669 ops/ms [Average]
  (min, avg, max) = (7.934, 7.973, 8.006), stdev = 0.037
  CI (99.9%): [7.304, 8.643] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.568 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.452 ±(99.9%) 0.005 ms/op
Iteration   2: 3.485 ±(99.9%) 0.005 ms/op
Iteration   3: 3.427 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.454 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.427, 3.454, 3.485), stdev = 0.029
  CI (99.9%): [2.921, 3.988] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.837 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.004 ms/op
Iteration   1: 3.516 ±(99.9%) 0.005 ms/op
Iteration   2: 3.366 ±(99.9%) 0.006 ms/op
Iteration   3: 3.283 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.388 ±(99.9%) 2.154 ms/op [Average]
  (min, avg, max) = (3.283, 3.388, 3.516), stdev = 0.118
  CI (99.9%): [1.234, 5.542] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.101 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.004 ms/op
Iteration   1: 3.420 ±(99.9%) 0.006 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.392 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.345, 3.392, 3.420), stdev = 0.041
  CI (99.9%): [2.648, 4.135] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.606 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.007 ms/op
Iteration   1: 4.062 ±(99.9%) 0.010 ms/op
Iteration   2: 4.088 ±(99.9%) 0.010 ms/op
Iteration   3: 3.996 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.049 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.996, 4.049, 4.088), stdev = 0.047
  CI (99.9%): [3.187, 4.910] (assumes normal distribution)


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
# Warmup Iteration   1: 9.124 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.010 ms/op
Iteration   1: 3.485 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  21.052 ms/op
                 createUser·p0.9999: 25.094 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.387 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  21.333 ms/op
                 createUser·p0.9999: 26.495 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.341 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  16.994 ms/op
                 createUser·p0.9999: 25.573 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282062
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9243 
    [ 2.500,  5.000) = 265826 
    [ 5.000,  7.500) = 5483 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     26.783 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.482 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  20.407 ms/op
                 existUser·p0.9999: 29.284 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.228 ms/op
                 existUser·p0.9999: 28.769 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  21.578 ms/op
                 existUser·p0.9999: 32.064 ms/op
                 existUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284863
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11408 
    [ 2.500,  5.000) = 265232 
    [ 5.000,  7.500) = 7145 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     10.949 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     32.357 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 9.443 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.012 ms/op
Iteration   1: 3.540 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  18.558 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  19.674 ms/op
                 getUser·p0.9999: 23.347 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.455 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  18.913 ms/op
                 getUser·p0.9999: 27.158 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276864
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12735 
    [ 2.500,  5.000) = 253350 
    [ 5.000,  7.500) = 9027 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.440 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 10.528 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.015 ms/op
Iteration   1: 4.205 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  19.853 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.074 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.305 ms/op
                 listUser·p0.999:  16.394 ms/op
                 listUser·p0.9999: 19.075 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 3.899 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  14.584 ms/op
                 listUser·p0.9999: 16.073 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236505
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 224074 
    [ 5.000,  7.500) = 9117 
    [ 7.500, 10.000) = 2418 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     15.851 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     26.891 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.088 ± 2.309  ops/ms
ClientPb.existUser                       thrpt       3   9.511 ± 3.406  ops/ms
ClientPb.getUser                         thrpt       3   9.307 ± 1.305  ops/ms
ClientPb.listUser                        thrpt       3   7.973 ± 0.669  ops/ms
ClientPb.createUser                       avgt       3   3.454 ± 0.533   ms/op
ClientPb.existUser                        avgt       3   3.388 ± 2.154   ms/op
ClientPb.getUser                          avgt       3   3.392 ± 0.744   ms/op
ClientPb.listUser                         avgt       3   4.049 ± 0.862   ms/op
ClientPb.createUser                     sample  282062   3.404 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.043           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.690           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  284863   3.369 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.499           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.949           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.376           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.768           ms/op
ClientPb.getUser                        sample  276864   3.467 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.952           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  236505   4.056 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.409           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.851           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
