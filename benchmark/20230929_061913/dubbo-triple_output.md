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
# Warmup Iteration   1: 1.867 ops/ms
# Warmup Iteration   2: 4.838 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.942 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 9.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.997 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (8.942, 8.997, 9.054), stdev = 0.056
  CI (99.9%): [7.976, 10.018] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 9.367 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.756 ops/ms
Iteration   3: 9.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.579 ±(99.9%) 2.818 ops/ms [Average]
  (min, avg, max) = (9.475, 9.579, 9.756), stdev = 0.154
  CI (99.9%): [6.761, 12.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.496 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.891 ops/ms
Iteration   1: 9.072 ops/ms
Iteration   2: 9.010 ops/ms
Iteration   3: 9.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.121 ±(99.9%) 2.615 ops/ms [Average]
  (min, avg, max) = (9.010, 9.121, 9.283), stdev = 0.143
  CI (99.9%): [6.506, 11.736] (assumes normal distribution)


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
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 6.519 ops/ms
# Warmup Iteration   3: 7.633 ops/ms
Iteration   1: 7.668 ops/ms
Iteration   2: 7.437 ops/ms
Iteration   3: 7.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.518 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (7.437, 7.518, 7.668), stdev = 0.130
  CI (99.9%): [5.139, 9.897] (assumes normal distribution)


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
# Warmup Iteration   1: 11.323 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.006 ms/op
Iteration   1: 3.584 ±(99.9%) 0.005 ms/op
Iteration   2: 3.442 ±(99.9%) 0.004 ms/op
Iteration   3: 3.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 1.293 ms/op [Average]
  (min, avg, max) = (3.442, 3.514, 3.584), stdev = 0.071
  CI (99.9%): [2.221, 4.807] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.006 ms/op
Iteration   1: 3.342 ±(99.9%) 0.003 ms/op
Iteration   2: 3.359 ±(99.9%) 0.003 ms/op
Iteration   3: 3.348 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.349 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.342, 3.349, 3.359), stdev = 0.009
  CI (99.9%): [3.192, 3.507] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.861 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.003 ms/op
Iteration   1: 3.452 ±(99.9%) 0.005 ms/op
Iteration   2: 3.471 ±(99.9%) 0.005 ms/op
Iteration   3: 3.415 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.446 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.415, 3.446, 3.471), stdev = 0.028
  CI (99.9%): [2.927, 3.965] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.181 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.007 ms/op
Iteration   1: 4.112 ±(99.9%) 0.004 ms/op
Iteration   2: 4.074 ±(99.9%) 0.007 ms/op
Iteration   3: 4.133 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.106 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (4.074, 4.106, 4.133), stdev = 0.030
  CI (99.9%): [3.567, 4.646] (assumes normal distribution)


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
# Warmup Iteration   1: 9.425 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.011 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  18.599 ms/op
                 createUser·p0.9999: 21.202 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 25.647 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271153
  mean =      3.536 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4985 
    [ 2.500,  5.000) = 258112 
    [ 5.000,  7.500) = 6233 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     18.574 ms/op
     p(99.9900) =     23.708 ms/op
     p(99.9990) =     26.027 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 8.054 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  21.294 ms/op
                 existUser·p0.9999: 23.999 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  23.822 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.377 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.245 ms/op
                 existUser·p0.999:  23.634 ms/op
                 existUser·p0.9999: 28.427 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280940
  mean =      3.417 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7467 
    [ 2.500,  5.000) = 265018 
    [ 5.000,  7.500) = 6745 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 203 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     22.710 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     28.645 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 9.447 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.009 ms/op
Iteration   1: 3.567 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  20.687 ms/op
                 getUser·p0.9999: 26.707 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  21.955 ms/op
                 getUser·p0.9999: 24.478 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.521 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  20.015 ms/op
                 getUser·p0.9999: 26.671 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271482
  mean =      3.533 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6497 
    [ 2.500,  5.000) = 255445 
    [ 5.000,  7.500) = 7570 
    [ 7.500, 10.000) = 1192 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.193 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 11.564 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.016 ms/op
Iteration   1: 4.293 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.281 ms/op
                 listUser·p0.999:  23.493 ms/op
                 listUser·p0.9999: 41.890 ms/op
                 listUser·p1.00:   43.778 ms/op

Iteration   2: 4.114 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.100 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 20.034 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230348
  mean =      4.167 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 219079 
    [ 5.000, 10.000) = 10385 
    [10.000, 15.000) = 399 
    [15.000, 20.000) = 323 
    [20.000, 25.000) = 118 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     39.642 ms/op
     p(99.9990) =     43.713 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.997 ± 1.021  ops/ms
ClientPb.existUser                       thrpt       3   9.579 ± 2.818  ops/ms
ClientPb.getUser                         thrpt       3   9.121 ± 2.615  ops/ms
ClientPb.listUser                        thrpt       3   7.518 ± 2.379  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 1.293   ms/op
ClientPb.existUser                        avgt       3   3.349 ± 0.157   ms/op
ClientPb.getUser                          avgt       3   3.446 ± 0.519   ms/op
ClientPb.listUser                         avgt       3   4.106 ± 0.539   ms/op
ClientPb.createUser                     sample  271153   3.536 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.840           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.574           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.708           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.083           ms/op
ClientPb.existUser                      sample  280940   3.417 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.996           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.710           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  271482   3.533 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.025           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.135           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  230348   4.167 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.319           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.778           ms/op
