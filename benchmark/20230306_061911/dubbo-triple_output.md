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
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 6.424 ops/ms
# Warmup Iteration   3: 8.377 ops/ms
Iteration   1: 9.325 ops/ms
Iteration   2: 9.294 ops/ms
Iteration   3: 9.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.368 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (9.294, 9.368, 9.484), stdev = 0.102
  CI (99.9%): [7.509, 11.226] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.969 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.418 ops/ms
Iteration   1: 10.000 ops/ms
Iteration   2: 9.922 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.936 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (9.886, 9.936, 10.000), stdev = 0.058
  CI (99.9%): [8.869, 11.002] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.715 ops/ms
# Warmup Iteration   2: 7.677 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.258 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.285 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (9.246, 9.285, 9.352), stdev = 0.058
  CI (99.9%): [8.223, 10.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 7.399 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.101 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 7.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.162 ±(99.9%) 4.704 ops/ms [Average]
  (min, avg, max) = (7.940, 8.162, 8.445), stdev = 0.258
  CI (99.9%): [3.458, 12.866] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.069 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.008 ms/op
Iteration   1: 3.325 ±(99.9%) 0.008 ms/op
Iteration   2: 3.356 ±(99.9%) 0.006 ms/op
Iteration   3: 3.360 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.347 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (3.325, 3.347, 3.360), stdev = 0.019
  CI (99.9%): [3.000, 3.693] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.211 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.006 ms/op
Iteration   1: 3.288 ±(99.9%) 0.006 ms/op
Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
Iteration   3: 3.245 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.239 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (3.183, 3.239, 3.288), stdev = 0.053
  CI (99.9%): [2.274, 4.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.684 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.007 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
Iteration   2: 3.301 ±(99.9%) 0.006 ms/op
Iteration   3: 3.395 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.370 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.301, 3.370, 3.416), stdev = 0.061
  CI (99.9%): [2.251, 4.490] (assumes normal distribution)


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
# Warmup Iteration   1: 9.604 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.007 ms/op
Iteration   1: 4.064 ±(99.9%) 0.007 ms/op
Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.980 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.909, 3.980, 4.064), stdev = 0.078
  CI (99.9%): [2.550, 5.411] (assumes normal distribution)


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
# Warmup Iteration   1: 8.494 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  19.653 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  21.944 ms/op
                 createUser·p0.9999: 33.510 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 3.457 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 28.827 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276398
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6042 
    [ 2.500,  5.000) = 263549 
    [ 5.000,  7.500) = 5669 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.847 ms/op
     p(99.9900) =     32.017 ms/op
     p(99.9990) =     33.763 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 7.613 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
Iteration   1: 3.242 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.545 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.930 ms/op
                 existUser·p0.9999: 29.598 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 24.846 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295466
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4648 
    [ 2.500,  5.000) = 285996 
    [ 5.000,  7.500) = 4217 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     11.593 ms/op
     p(99.9900) =     28.255 ms/op
     p(99.9990) =     30.148 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.940 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.012 ms/op
Iteration   1: 3.447 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 24.141 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.419 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 25.220 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  12.748 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284481
  mean =      3.373 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1258 
    [ 2.500,  5.000) = 276756 
    [ 5.000,  7.500) = 5644 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.234 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 11.425 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.988 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.089 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.863 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.551 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241826
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 233905 
    [ 5.000,  7.500) = 5269 
    [ 7.500, 10.000) = 1926 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     22.899 ms/op
     p(99.9990) =     24.925 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.368 ± 1.859  ops/ms
ClientPb.existUser                       thrpt       3   9.936 ± 1.066  ops/ms
ClientPb.getUser                         thrpt       3   9.285 ± 1.062  ops/ms
ClientPb.listUser                        thrpt       3   8.162 ± 4.704  ops/ms
ClientPb.createUser                       avgt       3   3.347 ± 0.346   ms/op
ClientPb.existUser                        avgt       3   3.239 ± 0.965   ms/op
ClientPb.getUser                          avgt       3   3.370 ± 1.119   ms/op
ClientPb.listUser                         avgt       3   3.980 ± 1.430   ms/op
ClientPb.createUser                     sample  276398   3.472 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.313           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.847           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  295466   3.247 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.572           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.593           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.278           ms/op
ClientPb.getUser                        sample  284481   3.373 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.094           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.223           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.951           ms/op
ClientPb.listUser                       sample  241826   3.965 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.532           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.899           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
