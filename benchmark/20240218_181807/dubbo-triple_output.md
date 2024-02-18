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
# Warmup Iteration   1: 5.114 ops/ms
# Warmup Iteration   2: 12.289 ops/ms
# Warmup Iteration   3: 12.428 ops/ms
Iteration   1: 12.472 ops/ms
Iteration   2: 12.504 ops/ms
Iteration   3: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.507 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (12.472, 12.507, 12.543), stdev = 0.036
  CI (99.9%): [11.858, 13.156] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.315 ops/ms
# Warmup Iteration   2: 12.964 ops/ms
# Warmup Iteration   3: 12.886 ops/ms
Iteration   1: 13.199 ops/ms
Iteration   2: 13.185 ops/ms
Iteration   3: 13.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.209 ±(99.9%) 0.539 ops/ms [Average]
  (min, avg, max) = (13.185, 13.209, 13.242), stdev = 0.030
  CI (99.9%): [12.670, 13.747] (assumes normal distribution)


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
# Warmup Iteration   1: 8.179 ops/ms
# Warmup Iteration   2: 12.445 ops/ms
# Warmup Iteration   3: 12.735 ops/ms
Iteration   1: 12.728 ops/ms
Iteration   2: 12.683 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.687 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (12.651, 12.687, 12.728), stdev = 0.038
  CI (99.9%): [11.988, 13.386] (assumes normal distribution)


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
# Warmup Iteration   1: 6.878 ops/ms
# Warmup Iteration   2: 10.428 ops/ms
# Warmup Iteration   3: 10.309 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.606 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (10.523, 10.606, 10.653), stdev = 0.072
  CI (99.9%): [9.290, 11.923] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.003 ms/op
Iteration   1: 2.531 ±(99.9%) 0.005 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.519, 2.524, 2.531), stdev = 0.006
  CI (99.9%): [2.406, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.003 ms/op
Iteration   1: 2.433 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.429, 2.438, 2.451), stdev = 0.011
  CI (99.9%): [2.229, 2.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.481, 2.485, 2.489), stdev = 0.004
  CI (99.9%): [2.411, 2.559] (assumes normal distribution)


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (2.986, 3.010, 3.033), stdev = 0.024
  CI (99.9%): [2.581, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  10.919 ms/op
                 createUser·p0.9999: 13.782 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 12.197 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.935 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 11.639 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379843
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183207 
    [ 2.500,  3.750) = 192500 
    [ 3.750,  5.000) = 3218 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.653 ms/op
     p(99.9900) =     13.142 ms/op
     p(99.9990) =     14.103 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  9.022 ms/op
                 existUser·p0.9999: 20.845 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.744 ms/op
                 existUser·p0.9999: 12.635 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  7.569 ms/op
                 existUser·p0.9999: 12.091 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386640
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188155 
    [ 2.500,  5.000) = 197675 
    [ 5.000,  7.500) = 425 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.243 ms/op
     p(99.9900) =     13.522 ms/op
     p(99.9990) =     21.111 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  11.041 ms/op
                 getUser·p0.9999: 13.242 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  9.455 ms/op
                 getUser·p0.9999: 19.251 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.596 ms/op
                 getUser·p0.9999: 10.469 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380470
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185858 
    [ 2.500,  5.000) = 193210 
    [ 5.000,  7.500) = 1050 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      6.509 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     19.602 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.598 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.525 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.458 ms/op
                 listUser·p0.9999: 12.461 ms/op
                 listUser·p1.00:   14.008 ms/op

Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 10.464 ms/op
                 listUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317740
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 91347 
    [ 2.500,  3.750) = 185838 
    [ 3.750,  5.000) = 32696 
    [ 5.000,  6.250) = 6226 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 381 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     10.735 ms/op
     p(99.9990) =     13.876 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.507 ± 0.649  ops/ms
ClientPb.existUser                       thrpt       3  13.209 ± 0.539  ops/ms
ClientPb.getUser                         thrpt       3  12.687 ± 0.699  ops/ms
ClientPb.listUser                        thrpt       3  10.606 ± 1.317  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.118   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.429   ms/op
ClientPb.createUser                     sample  379843   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.653           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.142           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.383           ms/op
ClientPb.existUser                      sample  386640   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.243           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.522           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.299           ms/op
ClientPb.getUser                        sample  380470   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.509           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.500           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.021           ms/op
ClientPb.listUser                       sample  317740   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.881           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.735           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.008           ms/op
