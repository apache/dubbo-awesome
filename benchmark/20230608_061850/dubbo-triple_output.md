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
# Warmup Iteration   1: 1.963 ops/ms
# Warmup Iteration   2: 5.057 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 9.042 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 9.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.194 ±(99.9%) 5.566 ops/ms [Average]
  (min, avg, max) = (8.995, 9.194, 9.546), stdev = 0.305
  CI (99.9%): [3.628, 14.760] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.915 ops/ms
# Warmup Iteration   2: 8.647 ops/ms
# Warmup Iteration   3: 9.202 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.743 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.740 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (9.684, 9.740, 9.793), stdev = 0.055
  CI (99.9%): [8.745, 10.735] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 8.136 ops/ms
# Warmup Iteration   3: 8.913 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 9.423 ops/ms
Iteration   3: 9.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.250 ±(99.9%) 2.880 ops/ms [Average]
  (min, avg, max) = (9.113, 9.250, 9.423), stdev = 0.158
  CI (99.9%): [6.370, 12.130] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.069 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (8.012, 8.069, 8.183), stdev = 0.098
  CI (99.9%): [6.274, 9.865] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.919 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
Iteration   1: 3.418 ±(99.9%) 0.004 ms/op
Iteration   2: 3.419 ±(99.9%) 0.007 ms/op
Iteration   3: 3.352 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.352, 3.396, 3.419), stdev = 0.038
  CI (99.9%): [2.695, 4.097] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.649 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.010 ms/op
Iteration   1: 3.289 ±(99.9%) 0.004 ms/op
Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
Iteration   3: 3.314 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.289, 3.316, 3.346), stdev = 0.029
  CI (99.9%): [2.796, 3.837] (assumes normal distribution)


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
# Warmup Iteration   1: 9.948 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.004 ms/op
Iteration   1: 3.499 ±(99.9%) 0.004 ms/op
Iteration   2: 3.485 ±(99.9%) 0.011 ms/op
Iteration   3: 3.505 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.496 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (3.485, 3.496, 3.505), stdev = 0.010
  CI (99.9%): [3.306, 3.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.130 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.013 ms/op
Iteration   1: 4.027 ±(99.9%) 0.010 ms/op
Iteration   2: 4.044 ±(99.9%) 0.006 ms/op
Iteration   3: 3.985 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.019 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.985, 4.019, 4.044), stdev = 0.031
  CI (99.9%): [3.462, 4.575] (assumes normal distribution)


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
# Warmup Iteration   1: 9.061 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.009 ms/op
Iteration   1: 3.490 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  19.837 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.553 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.526 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 29.948 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272299
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7742 
    [ 2.500,  5.000) = 256521 
    [ 5.000,  7.500) = 7139 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     28.135 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  11.643 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  20.823 ms/op
                 existUser·p0.9999: 36.725 ms/op
                 existUser·p1.00:   38.339 ms/op

Iteration   3: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  18.547 ms/op
                 existUser·p0.9999: 25.748 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288513
  mean =      3.327 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11458 
    [ 2.500,  5.000) = 269409 
    [ 5.000,  7.500) = 6245 
    [ 7.500, 10.000) = 805 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     38.157 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 8.765 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.014 ms/op
Iteration   1: 3.445 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 25.728 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   2: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  21.923 ms/op
                 getUser·p0.9999: 24.789 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  17.256 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284163
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9168 
    [ 2.500,  5.000) = 268750 
    [ 5.000,  7.500) = 5297 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     20.273 ms/op
     p(99.9900) =     26.332 ms/op
     p(99.9990) =     27.959 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.421 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.015 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 29.134 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 3.894 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.965 ms/op
                 listUser·p0.999:  14.679 ms/op
                 listUser·p0.9999: 15.496 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   3: 3.849 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  13.466 ms/op
                 listUser·p0.9999: 15.371 ms/op
                 listUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244221
  mean =      3.929 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 238730 
    [ 5.000,  7.500) = 3494 
    [ 7.500, 10.000) = 1149 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.382 ms/op
     p(99.9900) =     27.123 ms/op
     p(99.9990) =     29.711 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.194 ± 5.566  ops/ms
ClientPb.existUser                       thrpt       3   9.740 ± 0.995  ops/ms
ClientPb.getUser                         thrpt       3   9.250 ± 2.880  ops/ms
ClientPb.listUser                        thrpt       3   8.069 ± 1.795  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 0.701   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.521   ms/op
ClientPb.getUser                          avgt       3   3.496 ± 0.190   ms/op
ClientPb.listUser                         avgt       3   4.019 ± 0.557   ms/op
ClientPb.createUser                     sample  272299   3.523 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.414           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.135           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  288513   3.327 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.227           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  284163   3.377 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.029           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.273           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.332           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  244221   3.929 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.382           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.123           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.917           ms/op
