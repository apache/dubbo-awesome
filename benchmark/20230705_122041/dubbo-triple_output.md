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
# Warmup Iteration   1: 1.848 ops/ms
# Warmup Iteration   2: 4.622 ops/ms
# Warmup Iteration   3: 8.237 ops/ms
Iteration   1: 8.605 ops/ms
Iteration   2: 8.926 ops/ms
Iteration   3: 9.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.947 ±(99.9%) 6.447 ops/ms [Average]
  (min, avg, max) = (8.605, 8.947, 9.311), stdev = 0.353
  CI (99.9%): [2.500, 15.393] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.569 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.556 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.538 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (9.381, 9.538, 9.678), stdev = 0.150
  CI (99.9%): [6.809, 12.267] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.977 ops/ms
# Warmup Iteration   2: 7.908 ops/ms
# Warmup Iteration   3: 8.583 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.862 ops/ms
Iteration   3: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.698 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (8.590, 8.698, 8.862), stdev = 0.144
  CI (99.9%): [6.067, 11.330] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.422 ops/ms
# Warmup Iteration   2: 6.629 ops/ms
# Warmup Iteration   3: 7.520 ops/ms
Iteration   1: 7.435 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 7.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.582 ±(99.9%) 4.094 ops/ms [Average]
  (min, avg, max) = (7.435, 7.582, 7.840), stdev = 0.224
  CI (99.9%): [3.488, 11.676] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.232 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.005 ms/op
Iteration   1: 3.612 ±(99.9%) 0.009 ms/op
Iteration   2: 3.457 ±(99.9%) 0.008 ms/op
Iteration   3: 3.697 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.588 ±(99.9%) 2.217 ms/op [Average]
  (min, avg, max) = (3.457, 3.588, 3.697), stdev = 0.122
  CI (99.9%): [1.371, 5.805] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.488 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.005 ms/op
Iteration   1: 3.447 ±(99.9%) 0.006 ms/op
Iteration   2: 3.348 ±(99.9%) 0.007 ms/op
Iteration   3: 3.477 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.424 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (3.348, 3.424, 3.477), stdev = 0.067
  CI (99.9%): [2.195, 4.653] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.329 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.005 ms/op
Iteration   1: 3.564 ±(99.9%) 0.007 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.607 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.556 ±(99.9%) 1.022 ms/op [Average]
  (min, avg, max) = (3.496, 3.556, 3.607), stdev = 0.056
  CI (99.9%): [2.533, 4.578] (assumes normal distribution)


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
# Warmup Iteration   1: 11.178 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.011 ms/op
Iteration   1: 4.201 ±(99.9%) 0.010 ms/op
Iteration   2: 4.155 ±(99.9%) 0.010 ms/op
Iteration   3: 4.242 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.200 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (4.155, 4.200, 4.242), stdev = 0.044
  CI (99.9%): [3.401, 4.998] (assumes normal distribution)


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
# Warmup Iteration   1: 11.266 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.016 ms/op
Iteration   1: 3.661 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  19.390 ms/op
                 createUser·p0.9999: 22.604 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.545 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  21.725 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.609 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  27.037 ms/op
                 createUser·p0.9999: 41.167 ms/op
                 createUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266039
  mean =      3.604 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 257239 
    [ 5.000, 10.000) = 8304 
    [10.000, 15.000) = 167 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 155 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     39.125 ms/op
     p(99.9990) =     41.353 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 8.699 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.009 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  19.332 ms/op
                 existUser·p0.9999: 23.449 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  12.067 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.467 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.317 ms/op
                 existUser·p0.999:  25.320 ms/op
                 existUser·p0.9999: 32.728 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282818
  mean =      3.393 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4334 
    [ 2.500,  5.000) = 270472 
    [ 5.000,  7.500) = 6786 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     33.047 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 10.072 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.011 ms/op
Iteration   1: 3.663 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   8.225 ms/op
                 getUser·p0.999:  22.842 ms/op
                 getUser·p0.9999: 28.853 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 3.649 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  27.963 ms/op
                 getUser·p0.9999: 30.613 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 3.619 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  23.183 ms/op
                 getUser·p0.9999: 32.576 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 263456
  mean =      3.643 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4088 
    [ 2.500,  5.000) = 248605 
    [ 5.000,  7.500) = 8838 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 117 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     23.349 ms/op
     p(99.9900) =     31.511 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 12.160 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.741 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.015 ms/op
Iteration   1: 4.316 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.433 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  23.642 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.264 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  17.505 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.276 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.735 ms/op
                 listUser·p0.9999: 20.172 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223899
  mean =      4.286 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 210271 
    [ 5.000,  7.500) = 10021 
    [ 7.500, 10.000) = 2281 
    [10.000, 12.500) = 601 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 185 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.124 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.947 ± 6.447  ops/ms
ClientPb.existUser                       thrpt       3   9.538 ± 2.729  ops/ms
ClientPb.getUser                         thrpt       3   8.698 ± 2.632  ops/ms
ClientPb.listUser                        thrpt       3   7.582 ± 4.094  ops/ms
ClientPb.createUser                       avgt       3   3.588 ± 2.217   ms/op
ClientPb.existUser                        avgt       3   3.424 ± 1.229   ms/op
ClientPb.getUser                          avgt       3   3.556 ± 1.022   ms/op
ClientPb.listUser                         avgt       3   4.200 ± 0.799   ms/op
ClientPb.createUser                     sample  266039   3.604 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.168           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.125           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.878           ms/op
ClientPb.existUser                      sample  282818   3.393 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194           ms/op
ClientPb.getUser                        sample  263456   3.643 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.349           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  223899   4.286 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.433           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.514           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.051           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
