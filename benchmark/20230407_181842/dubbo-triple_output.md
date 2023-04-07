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
# Warmup Iteration   1: 2.141 ops/ms
# Warmup Iteration   2: 5.425 ops/ms
# Warmup Iteration   3: 8.886 ops/ms
Iteration   1: 9.149 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.131 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (9.036, 9.131, 9.207), stdev = 0.087
  CI (99.9%): [7.545, 10.717] (assumes normal distribution)


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
# Warmup Iteration   1: 3.574 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 9.486 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.777 ±(99.9%) 3.886 ops/ms [Average]
  (min, avg, max) = (9.536, 9.777, 9.938), stdev = 0.213
  CI (99.9%): [5.891, 13.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.762 ops/ms
# Warmup Iteration   2: 8.246 ops/ms
# Warmup Iteration   3: 8.927 ops/ms
Iteration   1: 8.929 ops/ms
Iteration   2: 9.224 ops/ms
Iteration   3: 9.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.248 ±(99.9%) 6.046 ops/ms [Average]
  (min, avg, max) = (8.929, 9.248, 9.591), stdev = 0.331
  CI (99.9%): [3.201, 15.294] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.038 ops/ms
# Warmup Iteration   2: 7.250 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 8.081 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.133 ±(99.9%) 3.446 ops/ms [Average]
  (min, avg, max) = (7.976, 8.133, 8.342), stdev = 0.189
  CI (99.9%): [4.687, 11.579] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.079 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.003 ms/op
Iteration   1: 3.484 ±(99.9%) 0.005 ms/op
Iteration   2: 3.479 ±(99.9%) 0.006 ms/op
Iteration   3: 3.308 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.424 ±(99.9%) 1.831 ms/op [Average]
  (min, avg, max) = (3.308, 3.424, 3.484), stdev = 0.100
  CI (99.9%): [1.593, 5.255] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.902 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.008 ms/op
Iteration   1: 3.506 ±(99.9%) 0.007 ms/op
Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
Iteration   3: 3.263 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 2.774 ms/op [Average]
  (min, avg, max) = (3.226, 3.332, 3.506), stdev = 0.152
  CI (99.9%): [0.557, 6.106] (assumes normal distribution)


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
# Warmup Iteration   1: 11.030 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.004 ms/op
Iteration   1: 3.690 ±(99.9%) 0.005 ms/op
Iteration   2: 3.463 ±(99.9%) 0.003 ms/op
Iteration   3: 3.547 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.567 ±(99.9%) 2.096 ms/op [Average]
  (min, avg, max) = (3.463, 3.567, 3.690), stdev = 0.115
  CI (99.9%): [1.470, 5.663] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.472 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.006 ms/op
Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
Iteration   2: 4.104 ±(99.9%) 0.008 ms/op
Iteration   3: 4.003 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.043 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (4.003, 4.043, 4.104), stdev = 0.053
  CI (99.9%): [3.067, 5.018] (assumes normal distribution)


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
# Warmup Iteration   1: 9.581 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.011 ms/op
Iteration   1: 3.570 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  20.166 ms/op
                 createUser·p0.9999: 29.198 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 3.535 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  22.118 ms/op
                 createUser·p0.9999: 28.900 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.462 ms/op
                 createUser·p0.9999: 31.752 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272698
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7892 
    [ 2.500,  5.000) = 258006 
    [ 5.000,  7.500) = 5789 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     17.311 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.190 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 8.043 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
Iteration   1: 3.333 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  15.012 ms/op
                 existUser·p0.9999: 19.051 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.321 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.466 ms/op
                 existUser·p0.999:  9.364 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 23.181 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285103
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17383 
    [ 2.500,  5.000) = 262075 
    [ 5.000,  7.500) = 4889 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.687 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 10.032 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.013 ms/op
Iteration   1: 3.505 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 24.777 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  20.727 ms/op
                 getUser·p0.9999: 24.509 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.059 ms/op
                 getUser·p0.999:  10.623 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277360
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8006 
    [ 2.500,  5.000) = 259897 
    [ 5.000,  7.500) = 8357 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     20.293 ms/op
     p(99.9900) =     27.199 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 10.558 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
Iteration   1: 4.041 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 31.702 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  16.643 ms/op
                 listUser·p0.9999: 20.682 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.998 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238462
  mean =      4.025 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 229974 
    [ 5.000,  7.500) = 6147 
    [ 7.500, 10.000) = 1347 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.123 ms/op
     p(99.9900) =     30.419 ms/op
     p(99.9990) =     32.133 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.131 ± 1.586  ops/ms
ClientPb.existUser                       thrpt       3   9.777 ± 3.886  ops/ms
ClientPb.getUser                         thrpt       3   9.248 ± 6.046  ops/ms
ClientPb.listUser                        thrpt       3   8.133 ± 3.446  ops/ms
ClientPb.createUser                       avgt       3   3.424 ± 1.831   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 2.774   ms/op
ClientPb.getUser                          avgt       3   3.567 ± 2.096   ms/op
ClientPb.listUser                         avgt       3   4.043 ± 0.975   ms/op
ClientPb.createUser                     sample  272698   3.517 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.311           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.802           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.375           ms/op
ClientPb.existUser                      sample  285103   3.366 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  277360   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.578           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.293           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.199           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  238462   4.025 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.419           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.375           ms/op
