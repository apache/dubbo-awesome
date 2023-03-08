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
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 5.658 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 9.320 ops/ms
Iteration   2: 9.704 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.508 ±(99.9%) 3.502 ops/ms [Average]
  (min, avg, max) = (9.320, 9.508, 9.704), stdev = 0.192
  CI (99.9%): [6.007, 13.010] (assumes normal distribution)


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
# Warmup Iteration   1: 2.774 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 9.513 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.720 ±(99.9%) 4.583 ops/ms [Average]
  (min, avg, max) = (9.522, 9.720, 10.003), stdev = 0.251
  CI (99.9%): [5.137, 14.304] (assumes normal distribution)


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
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 9.530 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.328 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (9.142, 9.328, 9.530), stdev = 0.195
  CI (99.9%): [5.774, 12.883] (assumes normal distribution)


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
# Warmup Iteration   1: 2.614 ops/ms
# Warmup Iteration   2: 6.990 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.074 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (7.993, 8.074, 8.159), stdev = 0.083
  CI (99.9%): [6.565, 9.584] (assumes normal distribution)


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
# Warmup Iteration   1: 10.691 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.006 ms/op
Iteration   1: 3.393 ±(99.9%) 0.007 ms/op
Iteration   2: 3.461 ±(99.9%) 0.009 ms/op
Iteration   3: 3.555 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.469 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.393, 3.469, 3.555), stdev = 0.082
  CI (99.9%): [1.982, 4.957] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.051 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
Iteration   2: 3.354 ±(99.9%) 0.007 ms/op
Iteration   3: 3.245 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.310 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.245, 3.310, 3.354), stdev = 0.058
  CI (99.9%): [2.261, 4.360] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.260 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.004 ms/op
Iteration   1: 3.548 ±(99.9%) 0.007 ms/op
Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
Iteration   3: 3.427 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.435 ±(99.9%) 2.001 ms/op [Average]
  (min, avg, max) = (3.329, 3.435, 3.548), stdev = 0.110
  CI (99.9%): [1.433, 5.436] (assumes normal distribution)


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
# Warmup Iteration   1: 10.083 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
Iteration   1: 3.907 ±(99.9%) 0.013 ms/op
Iteration   2: 3.922 ±(99.9%) 0.008 ms/op
Iteration   3: 3.915 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.915 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.907, 3.915, 3.922), stdev = 0.008
  CI (99.9%): [3.775, 4.054] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.004 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.010 ms/op
Iteration   1: 3.691 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  10.114 ms/op
                 createUser·p0.9999: 23.156 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.460 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  21.885 ms/op
                 createUser·p0.9999: 26.207 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 27.545 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272994
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7044 
    [ 2.500,  5.000) = 254713 
    [ 5.000,  7.500) = 9764 
    [ 7.500, 10.000) = 1032 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     27.188 ms/op
     p(99.9990) =     28.561 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 7.938 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 22.047 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 24.856 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 27.300 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286198
  mean =      3.354 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13014 
    [ 2.500,  5.000) = 267570 
    [ 5.000,  7.500) = 4737 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.292 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 9.833 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  20.500 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.237 ms/op
                 getUser·p0.999:  21.682 ms/op
                 getUser·p0.9999: 24.636 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  18.804 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282197
  mean =      3.399 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7388 
    [ 2.500,  5.000) = 269278 
    [ 5.000,  7.500) = 4410 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     19.641 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.596 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 10.928 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.958 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 16.216 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   3: 3.866 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.916 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 15.937 ms/op
                 listUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244918
  mean =      3.916 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 238717 
    [ 5.000,  7.500) = 4154 
    [ 7.500, 10.000) = 1181 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.158 ms/op
     p(99.9900) =     22.102 ms/op
     p(99.9990) =     23.493 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.508 ± 3.502  ops/ms
ClientPb.existUser                       thrpt       3   9.720 ± 4.583  ops/ms
ClientPb.getUser                         thrpt       3   9.328 ± 3.555  ops/ms
ClientPb.listUser                        thrpt       3   8.074 ± 1.509  ops/ms
ClientPb.createUser                       avgt       3   3.469 ± 1.487   ms/op
ClientPb.existUser                        avgt       3   3.310 ± 1.049   ms/op
ClientPb.getUser                          avgt       3   3.435 ± 2.001   ms/op
ClientPb.listUser                         avgt       3   3.915 ± 0.139   ms/op
ClientPb.createUser                     sample  272994   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.990           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.188           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  286198   3.354 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.640           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  282197   3.399 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.641           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.115           ms/op
ClientPb.listUser                       sample  244918   3.916 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.790           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.158           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.102           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
