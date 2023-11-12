# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.046 ops/ms
# Warmup Iteration   2: 4.667 ops/ms
# Warmup Iteration   3: 8.701 ops/ms
Iteration   1: 8.915 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.125 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (8.915, 9.125, 9.382), stdev = 0.237
  CI (99.9%): [4.804, 13.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 9.528 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.641 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.518 ±(99.9%) 3.409 ops/ms [Average]
  (min, avg, max) = (9.303, 9.518, 9.641), stdev = 0.187
  CI (99.9%): [6.108, 12.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.045 ops/ms
# Warmup Iteration   2: 8.381 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 9.156 ops/ms
Iteration   2: 9.308 ops/ms
Iteration   3: 9.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.250 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (9.156, 9.250, 9.308), stdev = 0.082
  CI (99.9%): [7.746, 10.754] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 7.141 ops/ms
# Warmup Iteration   3: 7.546 ops/ms
Iteration   1: 7.469 ops/ms
Iteration   2: 7.751 ops/ms
Iteration   3: 7.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.597 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (7.469, 7.597, 7.751), stdev = 0.143
  CI (99.9%): [4.988, 10.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.823 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.003 ms/op
Iteration   1: 3.427 ±(99.9%) 0.011 ms/op
Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
Iteration   3: 3.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (3.427, 3.481, 3.547), stdev = 0.061
  CI (99.9%): [2.370, 4.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.783 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.004 ms/op
Iteration   1: 3.462 ±(99.9%) 0.003 ms/op
Iteration   2: 3.295 ±(99.9%) 0.003 ms/op
Iteration   3: 3.378 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.378 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.295, 3.378, 3.462), stdev = 0.083
  CI (99.9%): [1.860, 4.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.095 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.004 ms/op
Iteration   1: 3.624 ±(99.9%) 0.004 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.460 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.529 ±(99.9%) 1.554 ms/op [Average]
  (min, avg, max) = (3.460, 3.529, 3.624), stdev = 0.085
  CI (99.9%): [1.975, 5.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.823 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.006 ms/op
Iteration   1: 4.218 ±(99.9%) 0.008 ms/op
Iteration   2: 4.307 ±(99.9%) 0.004 ms/op
Iteration   3: 4.152 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.226 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (4.152, 4.226, 4.307), stdev = 0.078
  CI (99.9%): [2.807, 5.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.244 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.011 ms/op
Iteration   1: 3.851 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  12.171 ms/op
                 createUser·p0.9999: 19.520 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   2: 3.534 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  18.760 ms/op
                 createUser·p0.9999: 21.983 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  20.883 ms/op
                 createUser·p0.9999: 27.293 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264388
  mean =      3.630 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3395 
    [ 2.500,  5.000) = 250658 
    [ 5.000,  7.500) = 8441 
    [ 7.500, 10.000) = 1344 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.618 ms/op
     p(99.9900) =     26.536 ms/op
     p(99.9990) =     27.551 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.064 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  16.448 ms/op
                 existUser·p0.9999: 20.766 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  19.326 ms/op
                 existUser·p0.9999: 21.486 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  12.637 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278652
  mean =      3.442 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6165 
    [ 2.500,  5.000) = 267290 
    [ 5.000,  7.500) = 4203 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     15.601 ms/op
     p(99.9900) =     24.257 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.332 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.012 ms/op
Iteration   1: 3.663 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.277 ms/op
                 getUser·p0.999:  20.170 ms/op
                 getUser·p0.9999: 36.969 ms/op
                 getUser·p1.00:   37.814 ms/op

Iteration   2: 3.564 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.207 ms/op
                 getUser·p0.999:  20.563 ms/op
                 getUser·p0.9999: 23.528 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  8.293 ms/op
                 getUser·p0.9999: 41.919 ms/op
                 getUser·p1.00:   47.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268907
  mean =      3.570 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 261485 
    [ 5.000, 10.000) = 6959 
    [10.000, 15.000) = 127 
    [15.000, 20.000) = 86 
    [20.000, 25.000) = 160 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 27 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     18.621 ms/op
     p(99.9900) =     37.900 ms/op
     p(99.9990) =     46.244 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.816 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.260 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  19.100 ms/op
                 listUser·p0.9999: 25.018 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 4.191 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.254 ms/op
                 listUser·p0.999:  16.081 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.212 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.700 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227242
  mean =      4.221 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 217953 
    [ 5.000,  7.500) = 7323 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     16.413 ms/op
     p(99.9900) =     24.284 ms/op
     p(99.9990) =     25.696 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.125 ± 4.321  ops/ms
ClientPb.existUser                       thrpt       3   9.518 ± 3.409  ops/ms
ClientPb.getUser                         thrpt       3   9.250 ± 1.504  ops/ms
ClientPb.listUser                        thrpt       3   7.597 ± 2.608  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 1.111   ms/op
ClientPb.existUser                        avgt       3   3.378 ± 1.519   ms/op
ClientPb.getUser                          avgt       3   3.529 ± 1.554   ms/op
ClientPb.listUser                         avgt       3   4.226 ± 1.419   ms/op
ClientPb.createUser                     sample  264388   3.630 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.536           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  278652   3.442 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.436           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.149           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.601           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.257           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.296           ms/op
ClientPb.getUser                        sample  268907   3.570 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.621           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.900           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.317           ms/op
ClientPb.listUser                       sample  227242   4.221 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.413           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.284           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
