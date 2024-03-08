# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.620 ops/ms
# Warmup Iteration   2: 12.549 ops/ms
# Warmup Iteration   3: 12.985 ops/ms
Iteration   1: 13.041 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.116 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (13.041, 13.116, 13.175), stdev = 0.068
  CI (99.9%): [11.871, 14.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.214 ops/ms
# Warmup Iteration   2: 13.533 ops/ms
# Warmup Iteration   3: 13.799 ops/ms
Iteration   1: 13.619 ops/ms
Iteration   2: 13.834 ops/ms
Iteration   3: 13.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.713 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (13.619, 13.713, 13.834), stdev = 0.110
  CI (99.9%): [11.708, 15.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.218 ops/ms
# Warmup Iteration   2: 12.939 ops/ms
# Warmup Iteration   3: 13.133 ops/ms
Iteration   1: 13.185 ops/ms
Iteration   2: 13.227 ops/ms
Iteration   3: 13.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.211 ±(99.9%) 0.409 ops/ms [Average]
  (min, avg, max) = (13.185, 13.211, 13.227), stdev = 0.022
  CI (99.9%): [12.801, 13.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.149 ops/ms
# Warmup Iteration   2: 10.851 ops/ms
# Warmup Iteration   3: 10.876 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.030 ops/ms
Iteration   3: 11.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.029 ±(99.9%) 0.024 ops/ms [Average]
  (min, avg, max) = (11.027, 11.029, 11.030), stdev = 0.001
  CI (99.9%): [11.004, 11.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.003 ms/op
Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.430 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.414, 2.430, 2.441), stdev = 0.014
  CI (99.9%): [2.175, 2.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.357 ±(99.9%) 0.004 ms/op
Iteration   1: 2.356 ±(99.9%) 0.004 ms/op
Iteration   2: 2.358 ±(99.9%) 0.004 ms/op
Iteration   3: 2.374 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.363 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.356, 2.363, 2.374), stdev = 0.010
  CI (99.9%): [2.181, 2.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.591 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.386 ±(99.9%) 0.003 ms/op
Iteration   1: 2.381 ±(99.9%) 0.004 ms/op
Iteration   2: 2.378 ±(99.9%) 0.002 ms/op
Iteration   3: 2.372 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.377 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.372, 2.377, 2.381), stdev = 0.005
  CI (99.9%): [2.294, 2.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.513 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.006 ms/op
Iteration   2: 2.947 ±(99.9%) 0.006 ms/op
Iteration   3: 2.956 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.949 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.946, 2.949, 2.956), stdev = 0.005
  CI (99.9%): [2.854, 3.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.850 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.006 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  7.240 ms/op
                 createUser·p0.9999: 14.166 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  10.254 ms/op
                 createUser·p0.9999: 11.941 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  7.881 ms/op
                 createUser·p0.9999: 10.109 ms/op
                 createUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 395621
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 197681 
    [ 2.500,  3.750) = 194951 
    [ 3.750,  5.000) = 2234 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     12.803 ms/op
     p(99.9990) =     14.813 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.384 ±(99.9%) 0.005 ms/op
Iteration   1: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.809 ms/op
                 existUser·p0.9999: 14.502 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   2: 2.364 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 13.459 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 11.134 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403920
  mean =      2.374 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 209248 
    [ 2.500,  3.750) = 191868 
    [ 3.750,  5.000) = 2084 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     13.530 ms/op
     p(99.9990) =     14.827 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  5.922 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.357 ms/op
                 getUser·p0.9999: 12.386 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  6.506 ms/op
                 getUser·p0.9999: 10.581 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393964
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 201045 
    [ 2.500,  3.750) = 188885 
    [ 3.750,  5.000) = 2734 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.054 ms/op
     p(99.9900) =     12.816 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.009 ms/op
Iteration   1: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.306 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 2.924 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  9.377 ms/op
                 listUser·p0.9999: 13.085 ms/op
                 listUser·p1.00:   13.943 ms/op

Iteration   3: 2.913 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.852 ms/op
                 listUser·p0.9999: 11.028 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327286
  mean =      2.930 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 108338 
    [ 2.500,  3.750) = 183689 
    [ 3.750,  5.000) = 28558 
    [ 5.000,  6.250) = 5392 
    [ 6.250,  7.500) = 457 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.124 ms/op
     p(99.9990) =     13.871 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.116 ± 1.245  ops/ms
ClientPb.existUser                       thrpt       3  13.713 ± 2.006  ops/ms
ClientPb.getUser                         thrpt       3  13.211 ± 0.409  ops/ms
ClientPb.listUser                        thrpt       3  11.029 ± 0.024  ops/ms
ClientPb.createUser                       avgt       3   2.430 ± 0.255   ms/op
ClientPb.existUser                        avgt       3   2.363 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.377 ± 0.083   ms/op
ClientPb.listUser                         avgt       3   2.949 ± 0.096   ms/op
ClientPb.createUser                     sample  395621   2.424 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.503           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.937           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.647           ms/op
ClientPb.existUser                      sample  403920   2.374 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.530           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.368           ms/op
ClientPb.getUser                        sample  393964   2.435 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.901           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.816           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  327286   2.930 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.730           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.124           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.943           ms/op
