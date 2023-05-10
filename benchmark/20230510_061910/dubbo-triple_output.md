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
# Warmup Iteration   1: 1.132 ops/ms
# Warmup Iteration   2: 2.514 ops/ms
# Warmup Iteration   3: 5.229 ops/ms
Iteration   1: 5.565 ops/ms
Iteration   2: 5.840 ops/ms
Iteration   3: 5.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.722 ±(99.9%) 2.584 ops/ms [Average]
  (min, avg, max) = (5.565, 5.722, 5.840), stdev = 0.142
  CI (99.9%): [3.138, 8.306] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.795 ops/ms
# Warmup Iteration   2: 4.811 ops/ms
# Warmup Iteration   3: 5.852 ops/ms
Iteration   1: 6.279 ops/ms
Iteration   2: 5.984 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.036 ±(99.9%) 4.058 ops/ms [Average]
  (min, avg, max) = (5.844, 6.036, 6.279), stdev = 0.222
  CI (99.9%): [1.977, 10.094] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.531 ops/ms
# Warmup Iteration   2: 4.685 ops/ms
# Warmup Iteration   3: 5.617 ops/ms
Iteration   1: 5.807 ops/ms
Iteration   2: 5.960 ops/ms
Iteration   3: 5.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.866 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (5.807, 5.866, 5.960), stdev = 0.083
  CI (99.9%): [4.356, 7.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.644 ops/ms
# Warmup Iteration   2: 3.966 ops/ms
# Warmup Iteration   3: 5.116 ops/ms
Iteration   1: 5.042 ops/ms
Iteration   2: 4.978 ops/ms
Iteration   3: 4.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.939 ±(99.9%) 2.323 ops/ms [Average]
  (min, avg, max) = (4.797, 4.939, 5.042), stdev = 0.127
  CI (99.9%): [2.616, 7.262] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.281 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 6.621 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.567 ±(99.9%) 0.009 ms/op
Iteration   1: 5.369 ±(99.9%) 0.009 ms/op
Iteration   2: 5.387 ±(99.9%) 0.014 ms/op
Iteration   3: 5.183 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.313 ±(99.9%) 2.064 ms/op [Average]
  (min, avg, max) = (5.183, 5.313, 5.387), stdev = 0.113
  CI (99.9%): [3.249, 7.377] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.281 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.566 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.578 ±(99.9%) 0.006 ms/op
Iteration   1: 5.183 ±(99.9%) 0.016 ms/op
Iteration   2: 5.617 ±(99.9%) 0.007 ms/op
Iteration   3: 5.545 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.448 ±(99.9%) 4.249 ms/op [Average]
  (min, avg, max) = (5.183, 5.448, 5.617), stdev = 0.233
  CI (99.9%): [1.199, 9.698] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.775 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.349 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.754 ±(99.9%) 0.010 ms/op
Iteration   1: 5.640 ±(99.9%) 0.011 ms/op
Iteration   2: 5.855 ±(99.9%) 0.010 ms/op
Iteration   3: 5.686 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.727 ±(99.9%) 2.065 ms/op [Average]
  (min, avg, max) = (5.640, 5.727, 5.855), stdev = 0.113
  CI (99.9%): [3.662, 7.792] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.273 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 8.104 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.506 ±(99.9%) 0.014 ms/op
Iteration   1: 6.482 ±(99.9%) 0.010 ms/op
Iteration   2: 6.360 ±(99.9%) 0.016 ms/op
Iteration   3: 6.315 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.386 ±(99.9%) 1.577 ms/op [Average]
  (min, avg, max) = (6.315, 6.386, 6.482), stdev = 0.086
  CI (99.9%): [4.809, 7.963] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.785 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.621 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.682 ±(99.9%) 0.027 ms/op
Iteration   1: 5.177 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  23.658 ms/op
                 createUser·p0.9999: 33.640 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   2: 5.186 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.365 ms/op
                 createUser·p0.95:   7.102 ms/op
                 createUser·p0.99:   9.317 ms/op
                 createUser·p0.999:  23.956 ms/op
                 createUser·p0.9999: 28.065 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 5.478 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  25.601 ms/op
                 createUser·p0.9999: 31.337 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181842
  mean =      5.277 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 93246 
    [ 5.000,  7.500) = 79807 
    [ 7.500, 10.000) = 7098 
    [10.000, 12.500) = 1091 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.167 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     24.072 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.621 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.476 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.865 ±(99.9%) 0.017 ms/op
Iteration   1: 5.046 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  26.337 ms/op
                 existUser·p0.9999: 30.573 ms/op
                 existUser·p1.00:   31.195 ms/op

Iteration   2: 5.166 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  22.263 ms/op
                 existUser·p0.9999: 32.383 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 5.087 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  27.596 ms/op
                 existUser·p0.9999: 39.013 ms/op
                 existUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188234
  mean =      5.099 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 113497 
    [ 5.000,  7.500) = 67106 
    [ 7.500, 10.000) = 5958 
    [10.000, 12.500) = 1007 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     22.612 ms/op
     p(99.9900) =     35.204 ms/op
     p(99.9990) =     39.526 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.671 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.290 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.397 ±(99.9%) 0.021 ms/op
Iteration   1: 5.558 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  22.459 ms/op
                 getUser·p0.9999: 25.280 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 5.254 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.815 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  24.674 ms/op
                 getUser·p0.9999: 32.105 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 5.229 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  24.858 ms/op
                 getUser·p0.9999: 32.409 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179634
  mean =      5.343 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 91193 
    [ 5.000,  7.500) = 78127 
    [ 7.500, 10.000) = 7308 
    [10.000, 12.500) = 1921 
    [12.500, 15.000) = 610 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     31.230 ms/op
     p(99.9990) =     32.710 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 19.613 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 7.001 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.592 ±(99.9%) 0.026 ms/op
Iteration   1: 5.967 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.162 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  22.176 ms/op
                 listUser·p0.9999: 24.814 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 6.024 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.928 ms/op
                 listUser·p0.999:  26.666 ms/op
                 listUser·p0.9999: 32.256 ms/op
                 listUser·p1.00:   33.325 ms/op

Iteration   3: 5.999 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.277 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  19.578 ms/op
                 listUser·p0.9999: 28.218 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159953
  mean =      5.996 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 26249 
    [ 5.000,  7.500) = 119081 
    [ 7.500, 10.000) = 11065 
    [10.000, 12.500) = 2536 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.568 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.381 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     23.562 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     32.932 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.722 ± 2.584  ops/ms
ClientPb.existUser                       thrpt       3   6.036 ± 4.058  ops/ms
ClientPb.getUser                         thrpt       3   5.866 ± 1.510  ops/ms
ClientPb.listUser                        thrpt       3   4.939 ± 2.323  ops/ms
ClientPb.createUser                       avgt       3   5.313 ± 2.064   ms/op
ClientPb.existUser                        avgt       3   5.448 ± 4.249   ms/op
ClientPb.getUser                          avgt       3   5.727 ± 2.065   ms/op
ClientPb.listUser                         avgt       3   6.386 ± 1.577   ms/op
ClientPb.createUser                     sample  181842   5.277 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.072           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.702           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  188234   5.099 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.712           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.612           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.584           ms/op
ClientPb.getUser                        sample  179634   5.343 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.191           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.905           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.230           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.866           ms/op
ClientPb.listUser                       sample  159953   5.996 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.568           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.562           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.490           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.325           ms/op
