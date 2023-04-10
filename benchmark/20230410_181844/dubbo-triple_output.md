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
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 3.484 ops/ms
# Warmup Iteration   3: 6.439 ops/ms
Iteration   1: 6.891 ops/ms
Iteration   2: 7.280 ops/ms
Iteration   3: 7.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.156 ±(99.9%) 4.184 ops/ms [Average]
  (min, avg, max) = (6.891, 7.156, 7.296), stdev = 0.229
  CI (99.9%): [2.972, 11.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.981 ops/ms
# Warmup Iteration   2: 5.406 ops/ms
# Warmup Iteration   3: 7.113 ops/ms
Iteration   1: 7.500 ops/ms
Iteration   2: 7.563 ops/ms
Iteration   3: 7.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.541 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (7.500, 7.541, 7.563), stdev = 0.036
  CI (99.9%): [6.892, 8.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.036 ops/ms
# Warmup Iteration   2: 5.988 ops/ms
# Warmup Iteration   3: 7.172 ops/ms
Iteration   1: 7.296 ops/ms
Iteration   2: 7.018 ops/ms
Iteration   3: 7.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.154 ±(99.9%) 2.535 ops/ms [Average]
  (min, avg, max) = (7.018, 7.154, 7.296), stdev = 0.139
  CI (99.9%): [4.619, 9.688] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.724 ops/ms
# Warmup Iteration   2: 4.989 ops/ms
# Warmup Iteration   3: 5.940 ops/ms
Iteration   1: 6.088 ops/ms
Iteration   2: 6.073 ops/ms
Iteration   3: 6.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.081 ±(99.9%) 0.139 ops/ms [Average]
  (min, avg, max) = (6.073, 6.081, 6.088), stdev = 0.008
  CI (99.9%): [5.942, 6.220] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.275 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.817 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.012 ms/op
Iteration   1: 4.516 ±(99.9%) 0.008 ms/op
Iteration   2: 4.661 ±(99.9%) 0.007 ms/op
Iteration   3: 4.550 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.576 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (4.516, 4.576, 4.661), stdev = 0.076
  CI (99.9%): [3.190, 5.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.110 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 5.510 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.006 ms/op
Iteration   1: 4.244 ±(99.9%) 0.007 ms/op
Iteration   2: 4.074 ±(99.9%) 0.008 ms/op
Iteration   3: 4.308 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.208 ±(99.9%) 2.205 ms/op [Average]
  (min, avg, max) = (4.074, 4.208, 4.308), stdev = 0.121
  CI (99.9%): [2.003, 6.413] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 14.475 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.947 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.446 ±(99.9%) 0.007 ms/op
Iteration   1: 4.446 ±(99.9%) 0.006 ms/op
Iteration   2: 4.667 ±(99.9%) 0.008 ms/op
Iteration   3: 4.506 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.540 ±(99.9%) 2.081 ms/op [Average]
  (min, avg, max) = (4.446, 4.540, 4.667), stdev = 0.114
  CI (99.9%): [2.458, 6.621] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.247 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.440 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.284 ±(99.9%) 0.007 ms/op
Iteration   1: 5.430 ±(99.9%) 0.006 ms/op
Iteration   2: 5.302 ±(99.9%) 0.008 ms/op
Iteration   3: 5.083 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.272 ±(99.9%) 3.205 ms/op [Average]
  (min, avg, max) = (5.083, 5.272, 5.430), stdev = 0.176
  CI (99.9%): [2.067, 8.477] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.445 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.947 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.028 ms/op
Iteration   1: 4.572 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   12.239 ms/op
                 createUser·p0.999:  21.772 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   2: 4.231 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  22.826 ms/op
                 createUser·p0.9999: 43.085 ms/op
                 createUser·p1.00:   43.581 ms/op

Iteration   3: 4.402 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   12.091 ms/op
                 createUser·p0.999:  33.058 ms/op
                 createUser·p0.9999: 44.253 ms/op
                 createUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218416
  mean =      4.397 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 188286 
    [ 5.000, 10.000) = 26792 
    [10.000, 15.000) = 2159 
    [15.000, 20.000) = 693 
    [20.000, 25.000) = 213 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 118 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     28.481 ms/op
     p(99.9900) =     43.057 ms/op
     p(99.9990) =     45.368 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.588 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.020 ms/op
Iteration   1: 4.326 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  17.151 ms/op
                 existUser·p0.9999: 25.808 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 4.322 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   6.562 ms/op
                 existUser·p0.99:   12.108 ms/op
                 existUser·p0.999:  23.626 ms/op
                 existUser·p0.9999: 33.443 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 4.302 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.394 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  19.443 ms/op
                 existUser·p0.9999: 31.352 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 222379
  mean =      4.317 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 432 
    [ 2.500,  5.000) = 193293 
    [ 5.000,  7.500) = 21828 
    [ 7.500, 10.000) = 3542 
    [10.000, 12.500) = 1867 
    [12.500, 15.000) = 751 
    [15.000, 17.500) = 365 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     32.768 ms/op
     p(99.9990) =     33.773 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.269 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.374 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.027 ms/op
Iteration   1: 4.406 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.988 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  20.655 ms/op
                 getUser·p0.9999: 27.549 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   2: 4.366 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   10.830 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 35.172 ms/op
                 getUser·p1.00:   36.700 ms/op

Iteration   3: 4.443 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.761 ms/op
                 getUser·p0.99:   11.096 ms/op
                 getUser·p0.999:  24.708 ms/op
                 getUser·p0.9999: 34.983 ms/op
                 getUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 217849
  mean =      4.405 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166 
    [ 2.500,  5.000) = 186055 
    [ 5.000,  7.500) = 24019 
    [ 7.500, 10.000) = 4450 
    [10.000, 12.500) = 1886 
    [12.500, 15.000) = 619 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     34.879 ms/op
     p(99.9990) =     35.670 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.669 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.718 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.213 ±(99.9%) 0.026 ms/op
Iteration   1: 5.170 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   8.224 ms/op
                 listUser·p0.99:   13.042 ms/op
                 listUser·p0.999:  25.727 ms/op
                 listUser·p0.9999: 28.043 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 5.026 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   12.112 ms/op
                 listUser·p0.999:  24.786 ms/op
                 listUser·p0.9999: 29.021 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   3: 5.169 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.481 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.570 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  23.004 ms/op
                 listUser·p0.9999: 25.684 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 187416
  mean =      5.121 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 132452 
    [ 5.000,  7.500) = 42814 
    [ 7.500, 10.000) = 7990 
    [10.000, 12.500) = 2206 
    [12.500, 15.000) = 943 
    [15.000, 17.500) = 333 
    [17.500, 20.000) = 213 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     12.547 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     28.328 ms/op
     p(99.9990) =     29.746 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.156 ± 4.184  ops/ms
ClientPb.existUser                       thrpt       3   7.541 ± 0.649  ops/ms
ClientPb.getUser                         thrpt       3   7.154 ± 2.535  ops/ms
ClientPb.listUser                        thrpt       3   6.081 ± 0.139  ops/ms
ClientPb.createUser                       avgt       3   4.576 ± 1.386   ms/op
ClientPb.existUser                        avgt       3   4.208 ± 2.205   ms/op
ClientPb.getUser                          avgt       3   4.540 ± 2.081   ms/op
ClientPb.listUser                         avgt       3   5.272 ± 3.205   ms/op
ClientPb.createUser                     sample  218416   4.397 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.422           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.698           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.481           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.057           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.941           ms/op
ClientPb.existUser                      sample  222379   4.317 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.394           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.513           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.338           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.768           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  217849   4.405 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.158           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.561           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.879           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.700           ms/op
ClientPb.listUser                       sample  187416   5.121 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.481           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.414           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.547           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.576           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.328           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.147           ms/op
