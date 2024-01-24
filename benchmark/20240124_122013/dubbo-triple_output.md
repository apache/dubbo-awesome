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
# Warmup Iteration   1: 5.274 ops/ms
# Warmup Iteration   2: 12.478 ops/ms
# Warmup Iteration   3: 12.611 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.962 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.871 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (12.804, 12.871, 12.962), stdev = 0.082
  CI (99.9%): [11.379, 14.363] (assumes normal distribution)


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
# Warmup Iteration   1: 8.555 ops/ms
# Warmup Iteration   2: 13.373 ops/ms
# Warmup Iteration   3: 13.140 ops/ms
Iteration   1: 13.143 ops/ms
Iteration   2: 13.329 ops/ms
Iteration   3: 13.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.230 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (13.143, 13.230, 13.329), stdev = 0.094
  CI (99.9%): [11.523, 14.938] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ops/ms
# Warmup Iteration   2: 12.833 ops/ms
# Warmup Iteration   3: 13.074 ops/ms
Iteration   1: 13.200 ops/ms
Iteration   2: 13.040 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.045 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (12.895, 13.045, 13.200), stdev = 0.153
  CI (99.9%): [10.259, 15.831] (assumes normal distribution)


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
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.888 ops/ms
Iteration   2: 10.895 ops/ms
Iteration   3: 10.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.922 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (10.888, 10.922, 10.983), stdev = 0.053
  CI (99.9%): [9.952, 11.891] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.455 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (2.423, 2.455, 2.490), stdev = 0.033
  CI (99.9%): [1.848, 3.062] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.003 ms/op
Iteration   1: 2.424 ±(99.9%) 0.003 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.419, 2.427, 2.439), stdev = 0.010
  CI (99.9%): [2.245, 2.610] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.434 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.431, 2.434, 2.437), stdev = 0.003
  CI (99.9%): [2.374, 2.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
Iteration   3: 2.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.949 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.935, 2.949, 2.964), stdev = 0.014
  CI (99.9%): [2.685, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  6.789 ms/op
                 createUser·p0.9999: 13.224 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  6.394 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389353
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 193230 
    [ 2.500,  3.750) = 192252 
    [ 3.750,  5.000) = 2945 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.022 ms/op
     p(99.9900) =     12.734 ms/op
     p(99.9990) =     14.239 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.553 ms/op
                 existUser·p0.9999: 14.251 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  7.201 ms/op
                 existUser·p0.9999: 12.759 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.549 ms/op
                 existUser·p0.9999: 11.814 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393405
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 198454 
    [ 2.500,  3.750) = 192265 
    [ 3.750,  5.000) = 2076 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      5.922 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.013 ms/op
                 getUser·p0.9999: 13.224 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  6.243 ms/op
                 getUser·p0.9999: 12.162 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.702 ms/op
                 getUser·p0.999:  6.468 ms/op
                 getUser·p0.9999: 11.370 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386211
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 193475 
    [ 2.500,  3.750) = 185232 
    [ 3.750,  5.000) = 5404 
    [ 5.000,  6.250) = 1654 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     12.868 ms/op
     p(99.9990) =     13.800 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.505 ms/op
                 listUser·p0.9999: 11.551 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.146 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.501 ms/op
                 listUser·p0.9999: 11.222 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319075
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 91984 
    [ 2.500,  3.750) = 190172 
    [ 3.750,  5.000) = 30119 
    [ 5.000,  6.250) = 5488 
    [ 6.250,  7.500) = 561 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.323 ms/op
     p(99.9990) =     12.315 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.871 ± 1.492  ops/ms
ClientPb.existUser                       thrpt       3  13.230 ± 1.707  ops/ms
ClientPb.getUser                         thrpt       3  13.045 ± 2.786  ops/ms
ClientPb.listUser                        thrpt       3  10.922 ± 0.970  ops/ms
ClientPb.createUser                       avgt       3   2.455 ± 0.607   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.183   ms/op
ClientPb.getUser                          avgt       3   2.434 ± 0.059   ms/op
ClientPb.listUser                         avgt       3   2.949 ± 0.264   ms/op
ClientPb.createUser                     sample  389353   2.462 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.022           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.726           ms/op
ClientPb.existUser                      sample  393405   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.922           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  386211   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.144           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.868           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.894           ms/op
ClientPb.listUser                       sample  319075   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.323           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
