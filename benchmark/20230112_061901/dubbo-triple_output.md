# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.805 ops/ms
# Warmup Iteration   2: 5.518 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.053 ±(99.9%) 6.809 ops/ms [Average]
  (min, avg, max) = (9.675, 10.053, 10.421), stdev = 0.373
  CI (99.9%): [3.245, 16.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 9.444 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.451 ±(99.9%) 4.660 ops/ms [Average]
  (min, avg, max) = (10.196, 10.451, 10.707), stdev = 0.255
  CI (99.9%): [5.790, 15.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ops/ms
# Warmup Iteration   2: 8.770 ops/ms
# Warmup Iteration   3: 10.034 ops/ms
Iteration   1: 10.241 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 10.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.209 ±(99.9%) 0.824 ops/ms [Average]
  (min, avg, max) = (10.158, 10.209, 10.241), stdev = 0.045
  CI (99.9%): [9.385, 11.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 8.440 ops/ms
Iteration   1: 8.630 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.510 ±(99.9%) 3.565 ops/ms [Average]
  (min, avg, max) = (8.284, 8.510, 8.630), stdev = 0.195
  CI (99.9%): [4.944, 12.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.645 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.006 ms/op
Iteration   1: 3.238 ±(99.9%) 0.005 ms/op
Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
Iteration   3: 3.207 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.199 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.154, 3.199, 3.238), stdev = 0.042
  CI (99.9%): [2.425, 3.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.096 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.243 ±(99.9%) 0.006 ms/op
Iteration   2: 3.247 ±(99.9%) 0.005 ms/op
Iteration   3: 3.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.194 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (3.091, 3.194, 3.247), stdev = 0.089
  CI (99.9%): [1.577, 4.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.201 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.003 ms/op
Iteration   1: 3.285 ±(99.9%) 0.005 ms/op
Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
Iteration   3: 3.238 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.229 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.165, 3.229, 3.285), stdev = 0.061
  CI (99.9%): [2.124, 4.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.004 ms/op
Iteration   1: 3.822 ±(99.9%) 0.006 ms/op
Iteration   2: 3.653 ±(99.9%) 0.010 ms/op
Iteration   3: 3.702 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.726 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (3.653, 3.726, 3.822), stdev = 0.087
  CI (99.9%): [2.137, 5.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.839 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 20.795 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  12.535 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 30.079 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305495
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17198 
    [ 2.500,  5.000) = 284200 
    [ 5.000,  7.500) = 3265 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     28.177 ms/op
     p(99.9990) =     30.472 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.822 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  14.908 ms/op
                 existUser·p0.9999: 22.616 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 21.569 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.249 ms/op
                 existUser·p0.999:  9.522 ms/op
                 existUser·p0.9999: 20.497 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313212
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26012 
    [ 2.500,  5.000) = 282540 
    [ 5.000,  7.500) = 3881 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.420 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.365 ms/op
     p(99.9900) =     21.911 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.557 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  15.539 ms/op
                 getUser·p0.9999: 20.485 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  11.402 ms/op
                 getUser·p0.9999: 21.524 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.175 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  13.406 ms/op
                 getUser·p0.9999: 26.507 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300816
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20590 
    [ 2.500,  5.000) = 273294 
    [ 5.000,  7.500) = 5746 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     24.825 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.176 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.011 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 19.986 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.219 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 16.043 ms/op
                 listUser·p1.00:   16.531 ms/op

Iteration   3: 3.631 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   3.817 ms/op
                 listUser·p0.99:   5.387 ms/op
                 listUser·p0.999:  12.026 ms/op
                 listUser·p0.9999: 13.173 ms/op
                 listUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255827
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 248113 
    [ 5.000,  7.500) = 5822 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     20.485 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.053 ± 6.809  ops/ms
ClientPb.existUser                       thrpt       3  10.451 ± 4.660  ops/ms
ClientPb.getUser                         thrpt       3  10.209 ± 0.824  ops/ms
ClientPb.listUser                        thrpt       3   8.510 ± 3.565  ops/ms
ClientPb.createUser                       avgt       3   3.199 ± 0.775   ms/op
ClientPb.existUser                        avgt       3   3.194 ± 1.616   ms/op
ClientPb.getUser                          avgt       3   3.229 ± 1.105   ms/op
ClientPb.listUser                         avgt       3   3.726 ± 1.588   ms/op
ClientPb.createUser                     sample  305495   3.142 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.953           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.631           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.177           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  313212   3.062 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.732           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.365           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.003           ms/op
ClientPb.getUser                        sample  300816   3.187 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.825           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  255827   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.763           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.711           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.037           ms/op
