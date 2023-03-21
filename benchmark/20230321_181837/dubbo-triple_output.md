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
# Warmup Iteration   1: 2.525 ops/ms
# Warmup Iteration   2: 6.350 ops/ms
# Warmup Iteration   3: 9.577 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.700 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.933 ±(99.9%) 3.992 ops/ms [Average]
  (min, avg, max) = (9.700, 9.933, 10.134), stdev = 0.219
  CI (99.9%): [5.940, 13.925] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 10.031 ops/ms
Iteration   1: 9.988 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.367 ±(99.9%) 6.141 ops/ms [Average]
  (min, avg, max) = (9.988, 10.367, 10.633), stdev = 0.337
  CI (99.9%): [4.226, 16.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 9.978 ops/ms
Iteration   1: 9.989 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 9.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.893 ±(99.9%) 2.394 ops/ms [Average]
  (min, avg, max) = (9.744, 9.893, 9.989), stdev = 0.131
  CI (99.9%): [7.499, 12.287] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ops/ms
# Warmup Iteration   2: 7.475 ops/ms
# Warmup Iteration   3: 8.324 ops/ms
Iteration   1: 8.518 ops/ms
Iteration   2: 8.584 ops/ms
Iteration   3: 8.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.557 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (8.518, 8.557, 8.584), stdev = 0.035
  CI (99.9%): [7.922, 9.192] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.841 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.198 ±(99.9%) 0.007 ms/op
Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
Iteration   3: 3.096 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.096, 3.153, 3.198), stdev = 0.052
  CI (99.9%): [2.207, 4.099] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.552 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
Iteration   3: 3.057 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (3.028, 3.097, 3.207), stdev = 0.096
  CI (99.9%): [1.351, 4.844] (assumes normal distribution)


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
# Warmup Iteration   1: 7.598 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.005 ms/op
Iteration   1: 3.236 ±(99.9%) 0.004 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.200 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.138, 3.200, 3.236), stdev = 0.053
  CI (99.9%): [2.225, 4.174] (assumes normal distribution)


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
# Warmup Iteration   1: 8.822 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.008 ms/op
Iteration   1: 3.835 ±(99.9%) 0.002 ms/op
Iteration   2: 3.602 ±(99.9%) 0.010 ms/op
Iteration   3: 3.806 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 2.317 ms/op [Average]
  (min, avg, max) = (3.602, 3.748, 3.835), stdev = 0.127
  CI (99.9%): [1.431, 6.065] (assumes normal distribution)


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
# Warmup Iteration   1: 8.418 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.009 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 22.453 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.449 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  19.283 ms/op
                 createUser·p0.9999: 22.751 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.129 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303673
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22776 
    [ 2.500,  5.000) = 274211 
    [ 5.000,  7.500) = 5769 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     15.625 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.292 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 7.930 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 24.427 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 18.726 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  11.421 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312078
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32819 
    [ 2.500,  5.000) = 274706 
    [ 5.000,  7.500) = 3843 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     24.602 ms/op
     p(99.9990) =     27.386 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 7.616 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.014 ms/op
Iteration   1: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  16.968 ms/op
                 getUser·p0.9999: 22.157 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 25.811 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.198 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  13.305 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300593
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13675 
    [ 2.500,  5.000) = 280086 
    [ 5.000,  7.500) = 5881 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     15.873 ms/op
     p(99.9900) =     25.950 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
Iteration   1: 3.777 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 17.537 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.733 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.337 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  14.309 ms/op
                 listUser·p0.9999: 16.644 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.010 ms/op
                 listUser·p0.9999: 16.138 ms/op
                 listUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254146
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 52 
    [ 2.500,  3.750) = 169349 
    [ 3.750,  5.000) = 74456 
    [ 5.000,  6.250) = 5125 
    [ 6.250,  7.500) = 3709 
    [ 7.500,  8.750) = 548 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 173 
    [15.000, 16.250) = 83 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     19.385 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.933 ± 3.992  ops/ms
ClientPb.existUser                       thrpt       3  10.367 ± 6.141  ops/ms
ClientPb.getUser                         thrpt       3   9.893 ± 2.394  ops/ms
ClientPb.listUser                        thrpt       3   8.557 ± 0.635  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 0.946   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 1.746   ms/op
ClientPb.getUser                          avgt       3   3.200 ± 0.974   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 2.317   ms/op
ClientPb.createUser                     sample  303673   3.158 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.625           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  312078   3.075 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.602           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  300593   3.191 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.549           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.873           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.950           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  254146   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.777           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.661           ms/op
