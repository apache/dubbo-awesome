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
# Warmup Iteration   1: 5.163 ops/ms
# Warmup Iteration   2: 12.503 ops/ms
# Warmup Iteration   3: 12.504 ops/ms
Iteration   1: 12.935 ops/ms
Iteration   2: 13.028 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.979 ±(99.9%) 0.851 ops/ms [Average]
  (min, avg, max) = (12.935, 12.979, 13.028), stdev = 0.047
  CI (99.9%): [12.128, 13.829] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.542 ops/ms
# Warmup Iteration   2: 13.275 ops/ms
# Warmup Iteration   3: 13.371 ops/ms
Iteration   1: 13.395 ops/ms
Iteration   2: 13.378 ops/ms
Iteration   3: 13.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.297 ±(99.9%) 2.815 ops/ms [Average]
  (min, avg, max) = (13.119, 13.297, 13.395), stdev = 0.154
  CI (99.9%): [10.482, 16.113] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.367 ops/ms
# Warmup Iteration   2: 13.011 ops/ms
# Warmup Iteration   3: 13.136 ops/ms
Iteration   1: 13.084 ops/ms
Iteration   2: 13.195 ops/ms
Iteration   3: 13.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.120 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (13.081, 13.120, 13.195), stdev = 0.065
  CI (99.9%): [11.935, 14.305] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ops/ms
# Warmup Iteration   2: 10.774 ops/ms
# Warmup Iteration   3: 10.837 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 10.919 ops/ms
Iteration   3: 10.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.914 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (10.891, 10.914, 10.931), stdev = 0.021
  CI (99.9%): [10.537, 11.291] (assumes normal distribution)


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.490 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.477, 2.490, 2.505), stdev = 0.014
  CI (99.9%): [2.238, 2.741] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.411 ±(99.9%) 0.002 ms/op
Iteration   3: 2.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.411, 2.421, 2.427), stdev = 0.009
  CI (99.9%): [2.262, 2.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.455, 2.465, 2.480), stdev = 0.013
  CI (99.9%): [2.226, 2.703] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
Iteration   3: 2.983 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.958, 2.968, 2.983), stdev = 0.013
  CI (99.9%): [2.734, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 13.764 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  7.817 ms/op
                 createUser·p0.9999: 10.940 ms/op
                 createUser·p1.00:   11.796 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387336
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 189881 
    [ 2.500,  3.750) = 194168 
    [ 3.750,  5.000) = 2470 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =     13.308 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  5.666 ms/op
                 existUser·p0.9999: 13.711 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  6.559 ms/op
                 existUser·p0.9999: 12.694 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.968 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393644
  mean =      2.437 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 196150 
    [ 2.500,  3.750) = 194644 
    [ 3.750,  5.000) = 2043 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      6.021 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.814 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  7.901 ms/op
                 getUser·p0.9999: 13.567 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 13.659 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  6.356 ms/op
                 getUser·p0.9999: 12.484 ms/op
                 getUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387899
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 194147 
    [ 2.500,  3.750) = 188779 
    [ 3.750,  5.000) = 3625 
    [ 5.000,  6.250) = 762 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 146 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      7.827 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     13.963 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.593 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.502 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.941 ms/op
                 listUser·p0.9999: 12.845 ms/op
                 listUser·p1.00:   14.090 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.371 ms/op
                 listUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320667
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 95798 
    [ 2.500,  3.750) = 187014 
    [ 3.750,  5.000) = 30899 
    [ 5.000,  6.250) = 5589 
    [ 6.250,  7.500) = 554 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.197 ms/op
     p(99.9900) =     11.304 ms/op
     p(99.9990) =     13.235 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.979 ± 0.851  ops/ms
ClientPb.existUser                       thrpt       3  13.297 ± 2.815  ops/ms
ClientPb.getUser                         thrpt       3  13.120 ± 1.185  ops/ms
ClientPb.listUser                        thrpt       3  10.914 ± 0.377  ops/ms
ClientPb.createUser                       avgt       3   2.490 ± 0.251   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.239   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.234   ms/op
ClientPb.createUser                     sample  387336   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.296           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.308           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  393644   2.437 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  387899   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.881           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.827           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  320667   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.197           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.304           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.090           ms/op
